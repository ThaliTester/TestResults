#### Test 5065027857de7f1_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
--------- beginning of system
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 2006): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2006): Module APK com.google.android.play.games already loaded
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/ComposerPerformance( 5725): 1449832319553 ms / [DONE] Composer constructor
E/CII     ( 5725): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5725): ReservationManager()
I/Mms/ReservationManager( 5725): resetAfterConnected()
D/TP/MmsSmsProvider( 1458): query,matched:7, calling pid = 5725
D/TP/MmsSmsProvider( 1458): match 7:Elapsed time : 1.404 ms
I/Mms/ReservationManager( 5725): getReservedSendMessageCount(): retMessageCount=0
D/Mms/Conversation( 5725): [start]    init() consume time = 52.699323
D/TP/MmsSmsProvider( 1458): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1458): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1458): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1458): sUpgradeVersion = 0, db.getVersion() = 81
D/TP/MmsSmsProvider( 1458): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1458): need read changed broadcast:false
D/Mms/MmsApp( 5725): [end]    onCreate() consume time = 8.875572
D/Mms/Conversation( 5725): [end]    init consume time = 0.515782
D/Mms/MessagingNotification( 5725): [start]    init() consume time = 2.68776
D/Mms/MessagingNotification( 5725): [end]    init consume time = 2.548906
D/Mms/DownloadManager( 5725): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5725): roaming ------> false, mSimSlot = 0
D/Mms/SpamFilter( 5725): [start]    SpamFilter fill() begin consume time = 6.294688
D/Mms/MethodReflector( 5725): getSubId is called
D/Mms/TelephonyUtils( 5725): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5725): getTelephonyProperty is called
D/Mms/DownloadManager( 5725): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5725): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5725): auto download without roaming -> true
D/Mms/DownloadManager( 5725): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5725): mAutoDownload ------> true
D/TP/MmsSmsProvider( 1458): query,matched:400, calling pid = 5725
D/Mms/Synchronizer( 5725): [start]    doSync consume time = 2.966875
D/TP/MmsSmsProvider( 1458): query,matched:0, calling pid = 5725
V/TP/MmsSmsProvider( 1458): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1458): match 0:Elapsed time : 0.942 ms
D/TP/MmsSmsProvider( 1458): update, matched:300, calling pid = 5725
V/TP/MmsSmsProvider( 1458): syncDBData start
V/TP/MmsSmsProvider( 1458): syncDBData sms end
V/TP/MmsSmsProvider( 1458): syncDBData mms end
V/TP/MmsSmsProvider( 1458): syncDBData end
D/Mms/SpamFilter( 5725): [end]    SpamFilter fill() finished consume time = 5.84776
D/Mms/Synchronizer( 5725): [end]    doSync consume time = 0.204219
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
D/Mms/FreeMessageStatusReceiver( 5725): onReceive, action : android.intent.action.PACKAGE_ADDED
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5913): MountEmulatedStorage()
I/libpersona( 5913): KNOX_SDCARD checking this for 10072
E/Zygote  ( 5913): v2
I/libpersona( 5913): KNOX_SDCARD not a persona
I/SELinux ( 5913): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5913 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
I/SELinux ( 5913): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/SELinux ( 5913): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
D/ChimeraCfgMgr( 2006): Loading module com.google.android.gms.gass from APK com.google.android.gms
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 5913): TimaSignature is unavailable
D/ActivityThread( 5913): Added TimaKeyStore provider
I/art     (  303): Explicit concurrent mark sweep GC freed 8738(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 23.883ms
D/AsyncTaskServiceImpl( 2006): Submit a task: k
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 16.978ms
V/AlarmManager( 1014): waitForAlarm result :8
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 746us total 16.783ms
I/DBG_POLICYDM( 5796): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
E/Zygote  ( 5933): MountEmulatedStorage()
E/Zygote  ( 5933): v2
I/libpersona( 5933): KNOX_SDCARD checking this for 10047
I/libpersona( 5933): KNOX_SDCARD not a persona
I/SELinux ( 5933): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5933): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5933): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5796): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
I/ActivityManager( 1014): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5933 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5933): TimaSignature is unavailable
D/ActivityThread( 5933): Added TimaKeyStore provider
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 2006): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/FreeMessageReceiverService( 5725): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5725): onHandleIntent: ACTION_PACKAGE_ADDED
D/BadgeProvider( 5913): onCreate
I/ActivityManager( 1014): Killing 5032:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/BadgeProvider( 5913): DatabaseHelper
D/ChimeraCfgMgr( 2006): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MessagingNotification( 5725): checkBadgeCount unreadCount=0 badgeCount=0
W/ResourcesManager( 5933): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5933): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5933): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/TP/SmsProvider( 1458): query,matched:26, calling pid = 5725
D/TP/SmsProvider( 1458): match 26:Elapsed time : 1.270 ms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 2006): Using Auth Proxy for data requests.
D/k       ( 2006): Processing package: com.test.thalitest
W/BaseAppContext( 2006): Using Auth Proxy for data requests.
W/libprocessgroup( 1014): failed to open /acct/uid_10150/pid_5032/cgroup.procs: No such file or directory
I/ActivityManager( 1014): Killing 5271:com.android.providers.calendar/u0a42 (adj 15): empty #31
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1458): query,matched:6, calling pid = 5725
D/TP/MmsSmsProvider( 1458): match 6:Elapsed time : 2.917 ms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5956 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/Zygote  ( 5956): MountEmulatedStorage()
E/Zygote  ( 5956): v2
I/libpersona( 5956): KNOX_SDCARD checking this for 10025
I/libpersona( 5956): KNOX_SDCARD not a persona
I/SELinux ( 5956): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5956): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5956): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SL_DEBUG( 5880): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5880): isLoggable:: SL_DEBUG_EXIST = false
D/SSRM:n  ( 1014): SIOP:: AP = 320
W/libprocessgroup( 1014): failed to open /acct/uid_10042/pid_5271/cgroup.procs: No such file or directory
D/GassUtils( 2006): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 2006): Found info for package com.test.thalitest in db.
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 5956): TimaSignature is unavailable
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 5956): Added TimaKeyStore provider
D/MyFiles ( 5933): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     ( 1840): Explicit concurrent mark sweep GC freed 36196(2MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 12MB/21MB, paused 1.448ms total 81.063ms
I/ActivityManager( 1014): Killing 3907:com.google.android.talk/u0a104 (adj 15): empty #31
E/DataBuffer( 1840): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@210eb8f4)
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 5956): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/BaseAppContext( 2006): Using Auth Proxy for data requests.
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
E/installd(  284): system dir 0 : /system/app/
E/installd(  284): system dir 1 : /system/priv-app/
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
I/TactileAssist( 1014): enable value -1
I/TactileAssist( 1014): internal enable value -1
I/TactileAssist( 1014): intensity value -1
I/TactileAssist( 1014): saveAppList value true
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/TactileAssist( 1014): List of disabled apps :
D/PackageManager( 1014): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/AlarmManager( 1014): waitForAlarm result :8
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
W/libprocessgroup( 1014): failed to open /acct/uid_10104/pid_3907/cgroup.procs: No such file or directory
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5976): MountEmulatedStorage()
E/Zygote  ( 5976): v2
I/libpersona( 5976): KNOX_SDCARD checking this for 10053
I/libpersona( 5976): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5976 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 5976): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5976): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5976): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/BaseAppContext( 2006): Using Auth Proxy for data requests.
I/OMACP   ( 5956): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/TimaKeyStoreProvider( 5976): TimaSignature is unavailable
W/BaseAppContext( 2006): Using Auth Proxy for data requests.
W/BaseAppContext( 2006): Using Auth Proxy for data requests.
D/Mms/Omacp( 5725): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/PeopleDatabaseHelper( 2006): cleanUpNonGplusAccounts done.
D/ActivityThread( 5976): Added TimaKeyStore provider
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5880): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/BaseAppContext( 2006): Using Auth Proxy for data requests.
W/ResourcesManager( 5976): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/OMACP   ( 5956): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
I/OMACP   ( 5956): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
I/OMACP   ( 5956): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5956): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5956): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5956): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5956): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
I/OMACP   ( 5956): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5880): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/OMACP   ( 5956): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5956): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5956): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
D/Compatibility( 5976): onReceive() it will make start service
I/OMACP   ( 5956): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
I/OMACP   ( 5956): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/Compatibility( 5976): onHandleIntent()
D/Compatibility( 5976): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
D/Compatibility( 5976): found: 2
I/UpdateIcingCorporaServi( 5313): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 5976): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5976): skipping ResolveInfo{53f6d3 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5976): considering ResolveInfo{33269210 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5976): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5976): enabling receiver ResolveInfo{104d4109 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5976): enabling receiver ResolveInfo{10ab9f0e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5976): enabling receiver ResolveInfo{365d2d2f com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5976): enabling receiver ResolveInfo{2acabf3c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/Zygote  ( 5999): MountEmulatedStorage()
I/libpersona( 5999): KNOX_SDCARD checking this for 10041
E/Zygote  ( 5999): v2
I/libpersona( 5999): KNOX_SDCARD not a persona
I/SELinux ( 5999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5999): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5999 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/Compatibility( 5976): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 5999): TimaSignature is unavailable
D/ActivityThread( 5999): Added TimaKeyStore provider
I/UpdateIcingCorporaServi( 5313): UpdateCorporaTask done [took 103 ms] updated apps [took 103 ms] 
I/ActivityManager( 1014): Killing 5374:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/SA      ( 5999): [SSP] onCreated
I/ActivityManager( 1014): Killing 5405:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/SA      ( 5999): [TPM] There is no property file
I/SA      ( 5999): [SCU] isHaveSA() - false
I/SA      ( 5999): [TPM] getModelProperty : null
I/SA      ( 5999): [TPM] getCSCProperty : null
I/SA      ( 5999): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5999): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5999): [DM] TFT FEATURE: false
I/SA      ( 5999): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5999): [DM] init START
I/SA      ( 5999): [DM] This device is not a Vodafone
W/ResourceType( 5999): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 5999): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 5999): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5999): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 5999): [SCU] isHaveSA() - false
I/SA      ( 5999): support phone number id : false
I/SA      ( 5999): [DM] Supports Ref Jpn : true
I/SA      ( 5999): [DM] init END
I/SA      ( 5999): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
W/GAV2    ( 5811): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SA      ( 5999): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
I/ActivityManager( 1014): Killing 5422:com.google.android.apps.plus/u0a120 (adj 15): empty #31
W/libprocessgroup( 1014): failed to open /acct/uid_10069/pid_5374/cgroup.procs: No such file or directory
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5405/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10120/pid_5422/cgroup.procs: No such file or directory
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1014): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6030 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/Zygote  ( 6030): MountEmulatedStorage()
I/libpersona( 6030): KNOX_SDCARD checking this for 10100
E/Zygote  ( 6030): v2
I/libpersona( 6030): KNOX_SDCARD not a persona
I/SELinux ( 6030): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Killing 5576:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
I/SELinux ( 6030): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6030): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
W/GAV2    ( 5811): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/TimaKeyStoreProvider( 6030): TimaSignature is unavailable
D/ActivityThread( 6030): Added TimaKeyStore provider
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PackageIntentReceiver( 6030): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6030): Not GearManger package! 
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
W/libprocessgroup( 1014): failed to open /acct/uid_10040/pid_5576/cgroup.procs: No such file or directory
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6052): MountEmulatedStorage()
I/libpersona( 6052): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6052): v2
I/libpersona( 6052): KNOX_SDCARD not a persona
I/SELinux ( 6052): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6052): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6052): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6052 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/AccountFeatureHelper( 5811): Write apps_features disabled false
D/TimaKeyStoreProvider( 6052): TimaSignature is unavailable
D/ActivityThread( 6052): Added TimaKeyStore provider
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6068): MountEmulatedStorage()
I/ActivityManager( 1014): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6068 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 6068): v2
I/libpersona( 6068): KNOX_SDCARD checking this for 1000
I/libpersona( 6068): KNOX_SDCARD not a persona
I/SELinux ( 6068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6068): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6068): TimaSignature is unavailable
D/ActivityThread( 6068): Added TimaKeyStore provider
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/AcmsPackageEventListener( 6068): Received: android.intent.action.PACKAGE_ADDED
W/ContextImpl( 6068): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
I/art     ( 1014): Explicit concurrent mark sweep GC freed 224289(14MB) AllocSpace objects, 7(4MB) LOS objects, 33% free, 27MB/41MB, paused 2.866ms total 200.895ms
E/Zygote  ( 6084): MountEmulatedStorage()
E/Zygote  ( 6084): v2
I/libpersona( 6084): KNOX_SDCARD checking this for 10120
I/libpersona( 6084): KNOX_SDCARD not a persona
I/SELinux ( 6084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6084 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 5195:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/SELinux ( 6084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
E/SELinux ( 6084): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/AcmsService( 6068): Enter Oncreate
D/AcmsServiceMonitor( 6068): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6068): creating AcmsCore
D/AcmsCore( 6068): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6068): AcmsCore
D/AcmsCore( 6068): init
D/AcmsCore( 6068): Looper handler is not null
D/AcmsCore( 6068): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6068): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6068): Incrementing - Counter value: 1
D/AcmsCore( 6068): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6068): onStartCommand
D/AcmsService( 6068): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6068): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6068): Incrementing - Counter value: 2
D/AcmsService( 6068): Incremented Counter Value : onStartCommand
D/TimaKeyStoreProvider( 6084): TimaSignature is unavailable
D/AcmsCertificateMngr( 6068): AcmsCertificateMngr
D/ActivityThread( 6084): Added TimaKeyStore provider
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityThread( 6068): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
V/AlarmManager( 1014): waitForAlarm result :8
D/AcmsRevocationMngr( 6068): AcmsRevocationMngr
W/ResourcesManager( 6084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/GAV2    ( 5811): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1014): Killing 5211:com.android.calendar/u0a135 (adj 15): empty #31
D/AcmsService( 6068): Inside handle Intent
D/AcmsService( 6068): App added - package name: com.test.thalitest
D/AcmsCore( 6068): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6068): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6068): Incrementing - Counter value: 3
D/AcmsCore( 6068): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6068): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6068): Decrementing - Counter value: 2
E/SMD     (  288): DCD OFF
I/Icing   ( 2006): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
W/libprocessgroup( 1014): failed to open /acct/uid_10134/pid_5195/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10135/pid_5211/cgroup.procs: No such file or directory
D/ChimeraCfgMgr( 2006): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2006): Module APK com.google.android.play.games already loaded
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
I/Icing   ( 2006): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 1014): Killing 5065:com.google.android.gm/u0a101 (adj 15): empty #31
W/libprocessgroup( 1014): failed to open /acct/uid_10101/pid_5065/cgroup.procs: No such file or directory
D/AndroidRuntime( 6107): 
D/AndroidRuntime( 6107): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6107): CheckJNI is OFF
D/AndroidRuntime( 6107): readGMSProperty: start
D/AndroidRuntime( 6107): readGMSProperty: already setted!!
D/AndroidRuntime( 6107): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6107): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6107): readGMSProperty: end
D/AndroidRuntime( 6107): addProductProperty: start
I/Mms/MmsApp( 5725):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5725): [start]    fillCache consume time = 1973.657395
D/Mms/ComposeMessageFragment( 5725): fillCache, easy = false
E/AffinityControl( 6107): AffinityControl: registerfunction enter
D/AndroidRuntime( 6107): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/AbsListView( 5725): Get MotionRecognitionManager
D/MotionRecognitionService( 1014):  ssp status : false
D/Mms/ComposeMessageFragment( 5725): [end]    fillCache consume time = 88.48
W/ActivityManager( 1014): mDVFSHelper.acquire()
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1014): *FMB* installDecor flags : 25362712
E/Zygote  ( 6123): MountEmulatedStorage()
E/Zygote  ( 6123): v2
I/libpersona( 6123): KNOX_SDCARD checking this for 10175
I/libpersona( 6123): KNOX_SDCARD not a persona
I/SELinux ( 6123): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6123 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 3134
D/AndroidRuntime( 6107): Shutting down VM
I/SELinux ( 6123): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6123): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
I/ActivityManager( 1014): Killing 5500:com.google.android.music:main/u0a111 (adj 15): empty #31
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 6123): TimaSignature is unavailable
D/ActivityThread( 6123): Added TimaKeyStore provider
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
V/ActivityManager( 1014): Display changed displayId=0
E/JavaBinder( 1014): !!! FAILED BINDER TRANSACTION !!!
W/DisplayManagerService( 1014): Failed to notify process 5500 that displays changed, assuming it died.
W/DisplayManagerService( 1014): android.os.TransactionTooLargeException
W/DisplayManagerService( 1014): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService( 1014): 	at android.os.BinderProxy.transact(Binder.java:511)
W/DisplayManagerService( 1014): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService( 1014): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
W/DisplayManagerService( 1014): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
W/DisplayManagerService( 1014): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
W/DisplayManagerService( 1014): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
W/DisplayManagerService( 1014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService( 1014): 	at android.os.Looper.loop(Looper.java:145)
W/DisplayManagerService( 1014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService( 1014): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1014): isKioskContainerExistOnDevice
W/libprocessgroup( 1014): failed to open /acct/uid_10111/pid_5500/cgroup.procs: No such file or directory
I/SurfaceFlinger(  257): id=10 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  257): id=10 Removed YUIInstallC (-2/9)
V/ActivityThread( 3134): updateVisibility : ActivityRecord{32efa580 token=android.os.BinderProxy@1960afd7 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/Mms/BubbleViewCache( 5725): fillCache bubble = 1
I/WebViewFactory( 6123): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
W/art     ( 6107): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/LibraryLoader( 6123): Time to load native libraries: 1 ms (timestamps 9485-9486)
I/LibraryLoader( 6123): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6123): Binding Chromium to main looper Looper (main, tid 1) {104d4109}
,I/LibraryLoader( 6123): Expected native library version number "",actual native library version number ""
,I/chromium( 6123): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6123): Initializing chromium process, singleProcess=true
W/art     ( 6123): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6123): ApplicationContext is null in ApplicationStatus
W/chromium( 6123): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 6123): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 6123): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 6123): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6123): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6123): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6123): Local Branch: 
I/Adreno-EGL( 6123): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6123): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6123):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/chromium( 6123): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/art     ( 6123): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6123): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6123): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6123): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6123): CordovaWebView is running on device made by: samsung
,W/art     ( 6123): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6123): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6123): Render dirty regions requested: true
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/PhoneWindow( 6123): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6123): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1014): Focus entered window: 6123
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6123): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6123): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6123): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6123): Enabling debug mode 0
,V/ActivityThread( 6123): updateVisibility : ActivityRecord{3e7c8935 token=android.os.BinderProxy@2df9c01f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1175): There is/are notification(s) 
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1785): getCurrentCandidateView
,W/IInputConnectionWrapper( 6123): showStatusIcon on inactive InputConnection
,I/Timeline( 6123): Timeline: Activity_idle id: android.os.BinderProxy@2df9c01f time:89938
,I/ActivityManager( 1014): Displayed Component not be shown by security: +600ms (total +695ms)
,W/ActivityManager( 1014): mDVFSHelper.release()
I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{1453195 u0 com.test.thalitest/.MainActivity t3} time:89940
,I/SurfaceFlinger(  257): id=13 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=13 Removed uhalitest (-2/9)
,W/BindingManager( 6123): Cannot call determinedVisibility() - never saw a connection for the pid: 6123
,D/SamsungIME( 1785): Dismiss ExpandCandiate
,I/DBG_POLICYDM( 5796): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5796): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
I/DBG_POLICYDM( 5796): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
I/DBG_POLICYDM( 5796): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
I/DBG_POLICYDM( 5796): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
I/DBG_POLICYDM( 5796): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
I/DBG_POLICYDM( 5796): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/JsMessageQueue( 6123): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1785): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1785): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1785): KeybaordView init() : load resources
,V/AlarmManager( 1014): waitForAlarm result :8
,D/jxcore_app_log( 6123): JniHelper::setJavaVM(0xb7639450), pthread_self() = -1212613152
,D/JX-Cordova( 6123): jxcore cordova android initializing
,I/SamsungIME( 1785): getCurrentKeyboard
I/SamsungIME( 1785): getTextKeyboard
,D/SamsungIME( 1785): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/SamsungIME( 1785): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AcmsKeyStoreHelper( 6068):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6068): Key Store exist
I/AcmsKeyStoreHelper( 6068): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6068):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 6068): getKeyStoreForApplication success 
D/AcmsCore( 6068): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6068): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6068): Decrementing - Counter value: 1
D/AcmsCore( 6068): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6068): This is NOT a valid MirrorLink app
D/AcmsCore( 6068): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6068): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6068): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6068): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6068): getSvcCounter - Counter value: 0
,D/AcmsService( 6068): Enter onDestroy
,I/AcmsService( 6068): cleanUp(): inside service clean up
,D/AcmsCore( 6068): AcmsCore: inside DeInit
D/AcmsCore( 6068): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6068): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6068): AcmsRevocationMngr: inside cleanup
,D/AcmsKeyStoreHelper( 6068): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6068): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6068): getSvcCounter - Counter value: 0
,D/AcmsService( 6068): killing acms process
I/Process ( 6068): Sending signal. PID: 6068 SIG: 9
,I/ActivityManager( 1014): Process ACMS.Process (pid 6068)(adj 0) has died(36,1170)
,E/SMD     (  288): DCD OFF
,W/jxcore-log( 6123): Initializing JXcore engine
,W/jxcore-log( 6123): JXcore engine is ready
,W/jxcore-log( 6123): Starting JXcore engine
,E/audit   ( 1913): type=1400 msg=audit(1449832324.267:205): avc:  denied  { ioctl } for  pid=6123 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1913):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1913): type=1300 msg=audit(1449832324.267:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=be9d6d58 items=0 ppid=303 ppcomm=main pid=6123 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1913): type=1320 msg=audit(1449832324.267:205): 
,W/jxcore-log( 6123): Platform android
W/jxcore-log( 6123): 
W/jxcore-log( 6123): Process ARCH arm
W/jxcore-log( 6123): 
,I/PowerManagerService( 1014): [PWL] Off : 15s ago
,I/jxcore-log( 6123): JXcore Cordova bridge is ready!
I/jxcore-log( 6123): 
,W/jxcore-log( 6123): JXcore engine is started
I/Choreographer( 6123): Skipped 147 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6123): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 6123): Toggling radios to true,
I/jxcore-log( 6123): 
,D/BluetoothAdapter( 6123): enable()
,D/BluetoothAdapter( 6123): enable(): BT is already enabled..!,
,D/SecContentProvider( 1014): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1014): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1014): mCursor = null
,D/WifiService( 1014): setWifiEnabled: true pid=6123, uid=10175,
,W/ActivityManager( 1014): Permission Denial: getCurrentUser() from pid=6123, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1014): Failed getting userId using ActivityManagerNative
W/WifiService( 1014): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6123, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1014): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1014): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213),
W/WifiService( 1014): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1014): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1014): ,	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1014): name = wifi_on
,I/WifiService( 1014): disconnect: pid=6123, uid=10175
,I/wpa_supplicant( 2075): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6123): Radios toggled
I/jxcore-log( 6123): 
,I/jxcore-log( 6123): Got Device Bluetooth address: 7C:F9:0E:37:96:AB
I/jxcore-log( 6123): 
,I/jxcore-log( 6123): Perf Test app loaded loaded
I/jxcore-log( 6123): 
,I/jxcore-log( 6123): check test folder
I/jxcore-log( 6123): 
,I/jxcore-log( 6123): found test : ./testFindPeers.js
I/jxcore-log( 6123): 
,I/wpa_supplicant( 2075): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 2075): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 2075): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 2075): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030,
,I/wpa_supplicant( 2075): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/wpa_supplicant( 2075): Cmd 35605 not handled
,E/WifiStateMachine( 1014): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 2075): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 2075): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 2075): P2P: Current p2p state = IDLE
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2075): wlan0: State: DISCONNECTED -> SCANNING
,I/wpa_supplicant( 2075): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 2075): First Scan Start
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2075): Scan requested (ret=0) - scan timeout 30 seconds
,D/Tethering( 1014): InitialState.processMessage what=4,
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,E/Tethering( 1014): No numeric data
,D/Tethering( 1014): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1014): clearTetheredNotification()
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false,
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,E/WifiNative-wlan0( 1014): do suspend true
D/WifiP2pService( 1014): InactiveState{ what=143375 }
D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 1000
,I/jxcore-log( 6123): found test : ./testSendData.js
I/jxcore-log( 6123): 
D/CommandListener(  278): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1840): Read error: ssl=0xb7b62f20: I/O error during system call, Connection timed out,
D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
V/NativeCrypto( 1840): SSL shutdown failed: ssl=0xb7b62f20: I/O error during system call, Broken pipe
D/HotspotTile( 1175): updateTetherState():false, false
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 1000
,D/NtpTrustedTime( 1014): forceRefresh Fail.
,D/ConnectivityService( 1014): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
,E/ConnectivityService( 1014): updateNetworkInfo()
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/qtaguid ( 1014): Tagging socket 360 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
E/ConnectivityService( 1014): updateNetworkInfo()
V/NetworkStats( 1014): performPollLocked(flags=0x1)
E/WifiStateMachine( 1014): Start Disconnecting Watchdog 1
I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,I/wpa_supplicant( 2075): wlan0: Setting scan request: 0 sec 0 usec
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,I/qtaguid ( 1014): Untagging socket 360
,I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiNative-wlan0( 1014): do suspend true
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/WifiP2pService( 1014): InactiveState{ what=143375 }
D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3608): Starting #8
,I/Hs20UtilService( 3608): Message received 5007
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/EnterpriseController(  278): uids 1000
,D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
,D/ConnectivityService( 1014): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/ConnectivityService( 1014): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
V/NetworkStats( 1014): performPollLocked() took 53ms
D/EntConnectivity( 1014): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityService( 1014): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI_P2P( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Validated
D/ConnectivityManager.CallbackHandler( 2006): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory( 1458): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1458): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524292
,I/NearbySettings( 1314): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1314): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
D/CSLegacyTypeTracker( 1014): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1014): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 1014): nai.networkMonitor.doQuit(),
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): doQuit - quitNow()
,D/EntConnectivity( 1014): Not allowed due to - mEnabled false - primarySimSlot false
,D/Tethering( 1014): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1014): MasterInitialState.processMessage what=3
,D/NtpTrustedTime( 1014): forceRefresh Fail.
,V/NetworkStats( 1014): updateIfacesLocked()
V/NetworkStats( 1014): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---,
D/NtpTrustedTime( 1014): forceRefresh() from cache miss
D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1014): forceRefresh Fail.
,V/NetworkStats( 1014): performPollLocked() took 7ms
D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NetworkStats( 1014): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1014): forceRefresh Fail.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
D/WifiNetworkAgent( 1014): NetworkAgent: NetworkAgent channel lost
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/WIFI    ( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,E/Zygote  ( 6188): MountEmulatedStorage()
I/libpersona( 6188): KNOX_SDCARD checking this for 10104
E/Zygote  ( 6188): v2
I/libpersona( 6188): KNOX_SDCARD not a persona
I/SELinux ( 6188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6188 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 6188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6188): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,I/Choreographer( 6123): Skipped 107 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6123): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TimaKeyStoreProvider( 6188): TimaSignature is unavailable
,D/ActivityThread( 6188): Added TimaKeyStore provider
,E/SMD     (  288): DCD OFF
,W/ResourcesManager( 6188): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3,
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,I/Babel   ( 6188): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6188): MmsConfig.loadMmsSettings
,I/Babel   ( 6188): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel   ( 6188): MmsConfig.loadFromDatabase
,E/Babel   ( 6188): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6188): MmsConfig.loadFromResources
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
E/Babel   ( 6188): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6188): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/Settings( 6188): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 6188): App launched.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3608): Starting #9
,I/Hs20UtilService( 3608): Message received 5007
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1314): MountReceiver.onReceive - Set preference state off
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  283): getCameraInfo: X
,V/NearbySettings( 1314): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6188): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6188): Unsupported mime audio/evrc
W/AudioCapabilities( 6188): Unsupported mime audio/qcelp,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6188): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6188): Unsupported mime audio/mpeg-L2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6188): Unsupported mime audio/x-ms-wma
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6188): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6188): Unsupported mime audio/qcelp
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6188): Unsupported mime audio/evrc
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6188): Unsupported mime video/wvc1
,W/VideoCapabilities( 6188): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6188): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6188): Unsupported mime video/wvc1
,W/VideoCapabilities( 6188): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6188): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6188): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6188): Unsupported mime video/mp43
,W/VideoCapabilities( 6188): Unsupported mime video/sorenson
,W/VideoCapabilities( 6188): Unsupported mime video/mp4v-esdp
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/VideoCapabilities( 6188): Unsupported profile 4 for video/mp4v-es
,I/ApplicationPolicy( 1014): updateDataUsageMap
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5747): SPPPushClient is installed : true
I/DBG_DM  ( 3134): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
I/PCWCLIENTTRACE_PushUtil( 5747): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5747): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5747): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1014): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,I/splitIntent( 1014): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5747): noConnectivity : true
,I/DBG_DM  ( 3134): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,E/Zygote  ( 6231): MountEmulatedStorage(),
E/Zygote  ( 6231): v2
I/libpersona( 6231): KNOX_SDCARD checking this for 10111
I/libpersona( 6231): KNOX_SDCARD not a persona
,I/SELinux ( 6231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6231): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6231 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/art     (  303): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 26.415ms,
,D/TimaKeyStoreProvider( 6231): TimaSignature is unavailable,
D/ActivityThread( 6231): Added TimaKeyStore provider,
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 599us total 20.816ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 600us total 16.824ms
,E/Zygote  ( 6246): MountEmulatedStorage(),
E/Zygote  ( 6246): v2
I/ActivityManager( 1014): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6246 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6246): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6246): KNOX_SDCARD checking this for 10009
D/accuweather( 1702): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/libpersona( 6246): KNOX_SDCARD not a persona
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,I/SELinux ( 6246): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6246): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6258): MountEmulatedStorage(),
I/ActivityManager( 1014): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6258 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/Zygote  ( 6258): v2
I/libpersona( 6258): KNOX_SDCARD checking this for 10145
I/libpersona( 6258): KNOX_SDCARD not a persona
,I/SELinux ( 6258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/SELinux ( 6258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/TimaKeyStoreProvider( 6246): TimaSignature is unavailable
E/SELinux ( 6258): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 6246): Added TimaKeyStore provider
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 1702): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1702): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1702): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1702): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 6258): TimaSignature is unavailable
,D/ActivityThread( 6258): Added TimaKeyStore provider
,D/accuweather( 1702): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1702): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/ActivityManager( 1014): Killing 5663:com.google.android.gms:car/u0a12 (adj 15): empty #31
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6277): MountEmulatedStorage(),
E/Zygote  ( 6277): v2
I/libpersona( 6277): KNOX_SDCARD checking this for 10081
,I/libpersona( 6277): KNOX_SDCARD not a persona
,I/SELinux ( 6277): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6277): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6277): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6277 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6258): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6258): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6258): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6258): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6258): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6277): TimaSignature is unavailable
,D/ActivityThread( 6277): Added TimaKeyStore provider
,I/MusicStore( 6231): Database version: 108
,I/ActivityManager( 1014): Killing 5298:com.samsung.aasaservice/1000 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3671): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Dec 11 12:12:07 GMT+01:00 2015
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,I/wpa_supplicant( 2075): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 2075): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 2075): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 2075): Trying to associate with  'G700'
I/wpa_supplicant( 2075): Re-associate with C0.AA.48
I/wpa_supplicant( 2075): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 2075): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1014): didn't find BSSID Trying to associate with SSID 'NG700'
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3671): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,I/KLMS-2.5.183: ( 3671): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3671): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/KLMS-2.5.183: ( 3671): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,I/KLMS-2.5.183: ( 3671): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1014): failed to open /acct/uid_10012/pid_5663/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5298/cgroup.procs: No such file or directory
,I/KLMS-2.5.183: ( 3671): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/ActivityManager( 1014): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6301 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a,
,I/KLMS-2.5.183: ( 3671): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false,
I/KLMS-2.5.183: ( 3671): StateImplV2(): networkChangeListener().END
,E/Zygote  ( 6301): MountEmulatedStorage()
I/libpersona( 6301): KNOX_SDCARD checking this for 10034
E/Zygote  ( 6301): v2
I/libpersona( 6301): KNOX_SDCARD not a persona
I/SELinux ( 6301): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6301): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6301): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3671): KLMSIntentService(): onDestroy()
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 2075): Cmd 35605 not handled
D/Tethering( 1014): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2075): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 2075): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 2075): Associated with C0.AA.48
I/wpa_supplicant( 2075): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2075): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2075): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceStatusChanged wlan0, false
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled,
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/SecContentProvider2( 1014): mCursor = null
I/wpa_supplicant( 2075): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2075): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 2075): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 2075): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,D/TimaKeyStoreProvider( 6301): TimaSignature is unavailable
I/wpa_supplicant( 2075): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 2075): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2075): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/ActivityThread( 6301): Added TimaKeyStore provider
,I/wpa_supplicant( 2075): Blacklist: Clear (temp) 
I/wpa_supplicant( 2075): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
D/Tethering( 1014): interfaceLinkStateChanged wlan0, true
D/Tethering( 1014): interfaceStatusChanged wlan0, true
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, true
,E/Tethering( 1014): No numeric data
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, true
D/Tethering( 1014): interfaceStatusChanged wlan0, true
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, true
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/Tethering( 1014): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1014): clearTetheredNotification()
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,D/NtpTrustedTime( 1014): forceRefresh Fail.
,V/NetworkStats( 1014): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,V/NetworkStats( 1014): performPollLocked() took 4ms
,D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1175): updateTetherState():false, false
,D/WifiNative-wlan0( 1014): callSECApiVoid - ID [50]
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,D/NtpTrustedTime( 1014): forceRefresh Fail.
,E/WifiConfigStore( 1014): setLastSelectedConfiguration -1
,D/ConnectivityService( 1014): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1014): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1014): updateNetworkInfo()
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  278): Setting iface cfg
,E/WifiStateMachine( 1014): Start Dhcp Watchdog 2
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1014): mCursor = null
,W/ResourcesManager( 6231): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6231): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/WifiNative-wlan0( 1014): do suspend false
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,I/SO_AGENT( 6301): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6322): MountEmulatedStorage(),
E/Zygote  ( 6322): v2
I/libpersona( 6322): KNOX_SDCARD checking this for 10113
I/libpersona( 6322): KNOX_SDCARD not a persona
I/SELinux ( 6322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6322 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6322): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/JNIHelp ( 6231): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/DBG_POLICYDM( 5796): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false,
,I/DBG_POLICYDM( 5796): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5796): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5796): [com.policydm.XDMApplication(477/isNetworkChanged)] network not changed.... 
,D/TimaKeyStoreProvider( 6322): TimaSignature is unavailable
,D/ActivityThread( 6322): Added TimaKeyStore provider
,E/SPPClientService( 5855): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 5999): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5999): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5999): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5999): [SLFUCHKMGR] constructor called
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/ActivityManager( 1014): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SA      ( 5999): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5999): [OR] == isSIMCardReady false ==
,I/SA      ( 5999): [SCU] == networkStateCheck == false
I/SA      ( 5999): [OR] onReceive END
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/BadgeProvider( 5913): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/DownloadManager( 1222): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,E/SPPClientService( 5855): [[SystemStateMonitorService]] No Active Internet
,W/ActivityThread( 6231): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6231): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e44ced0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6231): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6231): GMSCore installation verified
,D/Launcher.Model( 1479): reloadBadges entered.
,D/BadgeProvider( 5913): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5913): sendNotify, [notify] : null
D/BadgeProvider( 5913): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5913): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5913): update, [UpdateCount] : 1
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6345): MountEmulatedStorage()
,E/Zygote  ( 6345): v2
I/libpersona( 6345): KNOX_SDCARD checking this for 1000
,I/libpersona( 6345): KNOX_SDCARD not a persona
,I/SELinux ( 6345): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6345 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6345): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1014): Killing 4874:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,E/SELinux ( 6345): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/ActivityManager( 1014): Killing 5711:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ConfigStore( 6231): Config Database version: 1
,D/TimaKeyStoreProvider( 6345): TimaSignature is unavailable
,D/ActivityThread( 6345): Added TimaKeyStore provider
,E/dhcpcd  ( 6360): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6360): version 5.5.6 starting
E/dhcpcd  ( 6360): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,D/SecurityLogAgent( 6345): KnoxConfiguration : Current State = 1,
D/SecurityLogAgent( 6345): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6345): StateMachine : Current State = 1
,D/SecurityLogAgent( 6345): StateMachine : Changed Current State = 1
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6369): MountEmulatedStorage()
I/libpersona( 6369): KNOX_SDCARD checking this for 10159
E/Zygote  ( 6369): v2
I/libpersona( 6369): KNOX_SDCARD not a persona
I/SELinux ( 6369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6369 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 5233:com.samsung.android.sm/1000 (adj 15): empty #31
,I/SELinux ( 6369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6369): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1014): failed to open /acct/uid_10152/pid_5711/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10044/pid_4874/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6360): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6360): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6360): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6360): bssid match
,I/dhcpcd  ( 6360): wlan0: rebinding lease of 192.168.1.129
,D/TimaKeyStoreProvider( 6369): TimaSignature is unavailable
,D/ActivityThread( 6369): Added TimaKeyStore provider
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6231): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6231): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6231): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5233/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/iu.Environment( 2006): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2006): num queued entries: 0
,I/iu.UploadsManager( 2006): num updated entries: 0
,I/iu.SyncManager( 2006): NEXT; no task
,I/ActivityManager( 1014): Killing 5331:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4312, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,W/libprocessgroup( 1014): failed to open /acct/uid_10015/pid_5331/cgroup.procs: No such file or directory
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 55484(2MB) AllocSpace objects, 3(96KB) LOS objects, 33% free, 27MB/41MB, paused 2.637ms total 149.780ms
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1014): getStreamVolume 3 index 0
,I/MediaRouter( 6231): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6231): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6322): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6322): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,W/ContextImpl( 6322): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6322): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1014): Killing 5016:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6396): MountEmulatedStorage(),
I/libpersona( 6396): KNOX_SDCARD checking this for 10002
E/Zygote  ( 6396): v2
I/libpersona( 6396): KNOX_SDCARD not a persona
,I/SELinux ( 6396): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6396): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6396): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6396 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 6396): TimaSignature is unavailable
,D/ActivityThread( 6396): Added TimaKeyStore provider
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GHttpClientFactory( 6231): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5016/cgroup.procs: No such file or directory
,I/ActivityManager( 1014): Killing 5772:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6428): MountEmulatedStorage()
I/libpersona( 6428): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6428): v2
I/libpersona( 6428): KNOX_SDCARD not a persona
,I/SELinux ( 6428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6428): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6428 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6428): TimaSignature is unavailable
,D/ActivityThread( 6428): Added TimaKeyStore provider
I/WebViewFactory( 6322): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/LibraryLoader( 6322): Time to load native libraries: 1 ms (timestamps 6288-6289)
,I/LibraryLoader( 6322): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6322): Binding Chromium to main looper Looper (main, tid 1) {8175e01}
,I/LibraryLoader( 6322): Expected native library version number "",actual native library version number ""
,I/chromium( 6322): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6322): Initializing chromium process, singleProcess=true
I/DIAGMON_AGENT( 6428): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/art     ( 6322): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6322): ApplicationContext is null in ApplicationStatus
,W/chromium( 6322): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6322): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,I/chromium( 6322): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5772/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6322): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6322): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6322): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6322): Local Branch: 
I/Adreno-EGL( 6322): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6322): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6322):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6322): Requires BLUETOOTH permission
,I/NSApplication( 6322): Starting up...
,I/ActivityManager( 1014): Killing 5762:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,I/DIAGMON_AGENT( 6428): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6428): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6428): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6428): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6428): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6428): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,I/ActivityManager( 1014): Killing 5356:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6462): MountEmulatedStorage()
,E/Zygote  ( 6462): v2
I/libpersona( 6462): KNOX_SDCARD checking this for 10125
I/libpersona( 6462): KNOX_SDCARD not a persona
,I/SELinux ( 6462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6462 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,I/ActivityManager( 1014): Killing 5389:com.sec.knox.bridge/1000 (adj 15): empty #31
,I/SELinux ( 6462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6462): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1014): failed to open /acct/uid_10156/pid_5762/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6462): TimaSignature is unavailable
,D/ActivityThread( 6462): Added TimaKeyStore provider
,W/ResourcesManager( 6462): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6462): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6462): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6462): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6462): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6462): PeriphStartReceiver.onReceive - no need to start
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1014): Killing 5443:com.android.vending/u0a28 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 3608): Starting #10
I/Hs20UtilService( 3608): Message received 5007
,V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1314): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1314): MountReceiver.mPrefHandler - 7002
,W/libprocessgroup( 1014): failed to open /acct/uid_10032/pid_5356/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5389/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10028/pid_5443/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6360): wlan0: acknowledged 192.168.1.129 from 192.168.1.1,
,I/dhcpcd  ( 6360): wlan0: leased 192.168.1.129 for 86400 seconds
,E/WifiNative-wlan0( 1014): do suspend true
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1014): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1014): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1014): callSECApiInt - ID [210]
,E/ConnectivityService( 1014): updateNetworkInfo()
,D/ConnectivityService( 1014): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1014): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1014): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/WifiStateMachine( 1014): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
I/Hs20UtilService( 3608): Starting #11
,I/Hs20UtilService( 3608): Message received 5007,
,D/ConnectivityService( 1014): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
D/ConnectivityService( 1014): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1014): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1014): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1014): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1014): LTETest block dns file not exists
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 1014): updateNetworkInfo()
,E/WifiStateMachine( 1014): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiStateMachine( 1014): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService( 1014): updateNetworkInfo()
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1014): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1014): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 1000
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,D/WIFI    ( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true,
D/ConnectivityService( 1014):    accepting network in place of null,
D/WIFI_P2P( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1014): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/TelephonyNetworkFactory( 1458): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true,
D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/CSLegacyTypeTracker( 1014): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/TelephonyNetworkFactory( 1458): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1014): mBoosterFLAG : 0
I/WifiTrafficPoller( 1014): current booster mode : FullMode
,D/WifiNative-wlan0( 1014): callSECApiVoid - ID [212],
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1014): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/EntConnectivity( 1014): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityService( 1014): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/Tethering( 1014): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1014): MasterInitialState.processMessage what=3
,V/NetworkStats( 1014): updateIfacesLocked()
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
V/NetworkStats( 1014): performPollLocked(flags=0x1)
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 1000
D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
V/NetworkStats( 1014): performPollLocked() took 5ms
,D/ConnectivityManager.CallbackHandler( 2006): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
I/Hs20UtilService( 3608): Starting #12
,I/Hs20UtilService( 3608): Message received 5007
D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3608): Starting #13
,I/Hs20UtilService( 3608): Message received 5007
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1014): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1014): mCursor = null
I/System.out( 1014): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1014): mCursor = null
,D/NtpTrustedTime( 1014): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449832329663 mCachedNtpElapsedRealtime : 97291 mCachedNtpCertainty : 10
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 11 Dec 2015 11:12:09 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449832329742], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449832329722]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Validated
D/ConnectivityService( 1014): Validated NetworkAgentInfo [WIFI () - 503]
I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=4, Uoast
D/ConnectivityService( 1014): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1014): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1014): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 2006): CM callback handler got msg 524290
,D/PowerManagerService( 1014): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,D/SRIB_DCS( 1175): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
,D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
,D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SSRM:n  ( 1014): SIOP:: AP = 330
,E/SMD     (  288): DCD OFF
,D/PackageManager( 1014): [MSG] MCS_UNBIND
,I/ActivityManager( 1014): Killing 5725:com.android.mms/u0a46 (adj 15): empty #31
,D/CountryDetector( 1014): No listener is left
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/AlarmManagerService( 1014): Setting time of day to sec=1449832330
D/AlarmManagerService( 1014): Trying to open a file
,I/DBG_DM  ( 3134): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/AlarmManagerService( 1014): File Open Success
,D/AlarmManagerService( 1014): File Close Success
I/AlarmManagerService( 1014): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager( 1014): waitForAlarm result :65536
,W/AlarmManagerService( 1014): Unable to set rtc to 1449832330: Invalid argument
,I/NetworkMonitor( 6231): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5747): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5747): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5747): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5747): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/OTPFW   ( 1014): OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1449832330146
V/AlarmManager( 1014): No more alarm at this time.nowELAPSED=97793 batch.start=101430
,D/WifiStateMachine( 1014): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_SET
D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,I/DowntimeConditions( 1014): android.intent.action.TIME_SET ignored because schedule turned off.
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,W/Settings( 1014): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/splitIntent( 1014): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/splitIntent( 1014): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
D/SettingsProvider( 1014): name = lockscreen_zoom_panning_effect
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10054
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/KeyguardEffectViewUtil( 1175): isStrongPowerSavingMode() :false
,V/MusicLeanback( 6231): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/KeyguardEffectViewController( 1175): isPreloadedWallpaper=true
I/GeometricMosaic_Keyguard( 1175): update
,D/KeyguardEffectViewUtil( 1175): getCurrentWallpaper() mWallpaperPath :null
,W/SEC_DRM_PLUGIN_Playready(  282): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1449832330 after conversion: 1449832330
,W/SEC_DRM_PLUGIN_Playready(  282): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1449832330 after conversion: 1449832330
,W/libprocessgroup( 1014): failed to open /acct/uid_10046/pid_5725/cgroup.procs: No such file or directory
,D/accuweather( 1702): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1014): mCursor = null
,I/FOTA_Client( 6246): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,I/FOTA_Client( 6246): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6246): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 6246): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/accuweather( 1702): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1702): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1702): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1702): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/SecurityLogAgent( 6345): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6345): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6345): StateMachine : Current State = 1
,I/KLMS-2.5.183: ( 3671): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Dec 11 12:12:10 GMT+01:00 2015
,D/accuweather( 1702): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SecurityLogAgent( 6345): StateMachine : Changed Current State = 1
,D/accuweather( 1702): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/DIAGMON_AGENT( 6428): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6428): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6428): ./extraInfo: "NG700"
D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
I/DIAGMON_AGENT( 6428): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3671): KLMSAbstractReciever(): onReceive().END.
,I/KeyguardEffectViewUtil( 1175): set current wallpaper info
,D/SettingsProvider( 1014): name = keyguard_current_wallpaper_type
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10054
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
I/KLMS-2.5.183: ( 3671): KLMSIntentService(): onCreate()
,D/SettingsProvider( 1014): name = keyguard_current_wallpaper_file_path
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
I/KLMS-2.5.183: ( 3671): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10054
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/SettingsProvider( 1014): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10054
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,I/KLMS-2.5.183: ( 3671): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3671): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3671): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,D/WaitQueueForNetworkActivate( 5829): notifyNetworkActivated
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3671): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3671): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3671): NetworkChangeOperations(): uploadRequestLog().START 
,W/ContextImpl( 5829): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,I/KLMS-2.5.183: ( 3671): NetworkChangeOperations(): uploadRequestLog().END 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/KLMS-2.5.183: ( 3671): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3671): KLMSIntentService(): onDestroy()
,D/QuickConnect( 6462): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/TEST    ( 1175): run!!!
,I/QuickConnect( 6462): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6462): PeriphStartReceiver.onReceive - no need to start
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SPPClientService( 5855): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/GeometricMosaic_Renderer( 1175): setBackgroundBitmap
,I/SA      ( 5999): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5999): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5999): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5796): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 5999): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5999): [OR] == isSIMCardReady false ==
I/DBG_POLICYDM( 5796): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,I/SA      ( 5999): [SCU] == networkStateCheck == true
,E/DBG_POLICYDM( 5796): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,I/SA      ( 5999): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5999): isChinaCountryCode : false
I/SA      ( 5999): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5999): [OR] == networkStateCheck true ==
,I/SA      ( 5999): [OR] GetMyCountryZoneTask
,I/SA      ( 5999): [OR] onReceive END
,V/DownloadManager( 1222): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 5999): [SRS] prepareGetMyCountryZone
,I/DBG_POLICYDM( 5796): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5796): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/SA      ( 5999): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/DBG_POLICYDM( 5796): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/SA      ( 5999): [SSP] query invoked
,I/DBG_POLICYDM( 5796): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5796): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5796): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5796): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5796): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/SecContentProvider2( 1014): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1014): mCursor = null
,E/DBG_POLICYDM( 5796): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/SA      ( 5999): [TPMU] GetMccFromDB : null
I/SA      ( 5999): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5999): [TPM] isNoProxy(default) : true
,E/File    ( 5999): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5796): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5829): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5829): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5829): exit::IDLE
D/InitializeManagerStateMachine( 5829): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5829): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5829): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5829): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5829): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5829): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5829): entry::SUCCESS
D/hcjo    ( 5829): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/iu.Environment( 2006): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2006): num queued entries: 0
,I/iu.UploadsManager( 2006): num updated entries: 0
,I/iu.SyncManager( 2006): NEXT; no task
,D/hcjo    ( 5829): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5829): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5829): exit::SUCCESS
D/InitializeManagerStateMachine( 5829): entry::IDLE
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1014): Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/splitIntent( 1014): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=24
,I/splitIntent( 1014): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10012
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,I/FOTA_Client( 6246): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService( 1014): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,E/Zygote  ( 6532): MountEmulatedStorage()
I/libpersona( 6532): KNOX_SDCARD checking this for 10062
,E/Zygote  ( 6532): v2
I/libpersona( 6532): KNOX_SDCARD not a persona
I/SELinux ( 6532): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6532 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SELinux ( 6532): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6532): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/art     (  303): Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 22.506ms
,D/TimaKeyStoreProvider( 6532): TimaSignature is unavailable
,D/ActivityThread( 6532): Added TimaKeyStore provider
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 17.938ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 599us total 16.871ms
,E/Zygote  ( 6547): MountEmulatedStorage()
,E/Zygote  ( 6547): v2
I/libpersona( 6547): KNOX_SDCARD checking this for 10135
I/libpersona( 6547): KNOX_SDCARD not a persona
,I/SELinux ( 6547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6547): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6547 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6547): TimaSignature is unavailable
,D/ActivityThread( 6547): Added TimaKeyStore provider
,D/daemonapp( 1302): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1302): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/ResourcesManager( 6547): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6547): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6547): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/FOTA_Client( 6246): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/daemonapp( 1302): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1302): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1302): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1302): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1302): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1302): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.5.183: ( 3671): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Fri Dec 11 12:12:10 GMT+01:00 2015
,D/daemonapp( 1302): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/daemonapp( 1302): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1302): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1302): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.5.183: ( 3671): KLMSAbstractReciever(): onReceive().END.
,I/ExternalOEMControlProvider( 6532): onCreate
,I/SA      ( 5999): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/KLMS-2.5.183: ( 3671): KLMSIntentService(): onCreate()
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,I/KLMS-2.5.183: ( 3671): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/daemonapp( 1302): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/KLMS-2.5.183: ( 3671): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3671): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.5.183: ( 3671): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.5.183: ( 3671): StateImplV2(): dateTimeChanged().START : Fri Dec 11 12:12:10 GMT+01:00 2015,
,E/Zygote  ( 6568): MountEmulatedStorage()
E/Zygote  ( 6568): v2
I/libpersona( 6568): KNOX_SDCARD checking this for 1000
I/libpersona( 6568): KNOX_SDCARD not a persona
,I/SELinux ( 6568): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=6568 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/KLMS-2.5.183: ( 3671): StateImplV2(): dateTimeChanged().END
,I/SELinux ( 6568): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
E/SELinux ( 6568): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/comdaemonstockapp( 1302): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 1302): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,I/ Time Manager ( 6532): Time Difference not stored. TIME_DIFFERENCE
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/KLMS-2.5.183: ( 3671): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6568): TimaSignature is unavailable
,D/ActivityThread( 6568): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6568): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 6587): MountEmulatedStorage(),
E/Zygote  ( 6587): v2
,I/libpersona( 6587): KNOX_SDCARD checking this for 10046
I/libpersona( 6587): KNOX_SDCARD not a persona
,I/SELinux ( 6587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6587): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=6587 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,D/SecurityLogAgent( 6345): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6345): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6345): StateMachine : Current State = 1
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6601): MountEmulatedStorage()
I/libpersona( 6601): KNOX_SDCARD checking this for 10157
E/Zygote  ( 6601): v2
I/libpersona( 6601): KNOX_SDCARD not a persona
I/SELinux ( 6601): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6601): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6601): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6601 uid=10157 gids={50157, 9997} abi=armeabi-v7a,
D/TimaKeyStoreProvider( 6587): TimaSignature is unavailable
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityThread( 6587): Added TimaKeyStore provider
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6601): TimaSignature is unavailable
,D/ActivityThread( 6601): Added TimaKeyStore provider,
,E/Zygote  ( 6615): MountEmulatedStorage()
,E/Zygote  ( 6615): v2
I/libpersona( 6615): KNOX_SDCARD checking this for 10042
I/libpersona( 6615): KNOX_SDCARD not a persona
,I/SELinux ( 6615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6615 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6615): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,I/CheckinService( 2006): Checkin interval check for package: unspecified last checkin: 1449470940712 min interval config: 0 actual interval: 361390231
,W/ResourcesManager( 6601): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/accuweather( 1702): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1702): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
W/ResourcesManager( 6587): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6587): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6587): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6587): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6615): TimaSignature is unavailable
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
D/ActivityThread( 6615): Added TimaKeyStore provider
W/ResourcesManager( 6587): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6587): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SA      ( 5999): [RC New] Execute method=[GET] start
,E/Zygote  ( 6632): MountEmulatedStorage()
I/libpersona( 6632): KNOX_SDCARD checking this for 10085
E/Zygote  ( 6632): v2
I/libpersona( 6632): KNOX_SDCARD not a persona
,I/SELinux ( 6632): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6632): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6632 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6632): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6615): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6632): TimaSignature is unavailable
,D/ActivityThread( 6632): Added TimaKeyStore provider
,E/Zygote  ( 6647): MountEmulatedStorage(),
I/libpersona( 6647): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6647): v2,
I/libpersona( 6647): KNOX_SDCARD not a persona
I/SA      ( 5999): [RC New] Security=[true]
I/SELinux ( 6647): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/System.out( 5999): Thread-1020(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 5999): Thread-1020(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5999): Thread-1020(ApacheHTTPLog):isShipBuild true,
I/System.out( 5999): Thread-1020(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5999): Thread-1020(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  278): uids 10041
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10041
,I/ActivityManager( 1014): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6647 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6647): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Killing 5933:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,E/SELinux ( 6647): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/MmsApp( 6587): [start]    onCreate() consume time = 0.0,
,I/ActivityManager( 1014): Killing 5956:com.wsomacp/u0a25 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6632): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6632): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6647): TimaSignature is unavailable
,D/ActivityThread( 6647): Added TimaKeyStore provider
,I/CalendarProvider2( 6615): CalendarProvider2.onCreate() called
,D/ConnectivityService( 1014): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2006): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2006): CM callback handler got msg 524295
,W/libprocessgroup( 1014): failed to open /acct/uid_10047/pid_5933/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10025/pid_5956/cgroup.procs: No such file or directory
,D/TimeService( 6647): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449832331122
D/        ( 6647): TimeServiceNative: User Time to be set is 1449832331123
D/QC-time-services( 6647): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6647): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6647): Lib:time_genoff_operation: pargs->ts_val = 1449832331123
,D/QC-time-services(  316): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 6647): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  316): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449832331123
D/QC-time-services(  316): Daemon:genoff_opr: Base = 2, val = 1449832331123, operation = 0
,D/QC-time-services(  316): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/11/70 9:19:4
,D/QC-time-services(  316): Daemon:Value read from RTC seconds = 13943944000
D/QC-time-services(  316): Daemon:new time 1449832331123 
D/QC-time-services(  316): Daemon: delta 1435888387123 genoff 1435888387123 
D/QC-time-services(  316): Daemon:genoff_persistent_update: Writing genoff = 1435888387123 to memory
D/QC-time-services(  316): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  316): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/SettingsProvider( 1014): name = next_alarm_formatted
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10085
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/QC-time-services(  316): Updating the TOD offset
D/QC-time-services(  316): Daemon:genoff_persistent_update: Writing genoff = 1435888387123 to memory
D/QC-time-services(  316): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  316): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  316): Daemon:Update to modem bit set
D/QC-time-services(  316): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  316): Daemon: Base = 2, Value being sent to MODEM = 1119923587123
,E/QC-time-services( 6647): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  316): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  316): Daemon: Time-services: Waiting to acceptconnection
,I/ActivityManager( 1014): Killing 5976:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 5313:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,W/art     ( 6587): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 120.208ms
,I/rmt_storage(  269): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8a917c8
I/rmt_storage(  269): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  269): wakelock acquired: 1, error no: 42
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1196878536)
,W/art     ( 6632): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 113.214ms,
,W/libprocessgroup( 1014): failed to open /acct/uid_10053/pid_5976/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10057/pid_5313/cgroup.procs: No such file or directory
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1196878536) wakelock released: 1, error no: 0
I/rmt_storage(  269): 
,I/rmt_storage(  269): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8a917c8,
,D/Mms/ArtClassLoader( 6587): init before art
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 36724(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 2.663ms total 156.707ms
,D/Mms/TelephonyPermission( 6587): start operation mode monitor
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ResourcesManager( 6587): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 6587): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 6587): isDefault true
,D/Mms/MmsApp( 6587): onCreate() com.android.mms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6671): MountEmulatedStorage(),
E/Zygote  ( 6671): v2
D/Mms/MmsApp( 6587): [start]    initCountryIso consume time = 358.929166
I/libpersona( 6671): KNOX_SDCARD checking this for 10094
I/libpersona( 6671): KNOX_SDCARD not a persona
,I/SELinux ( 6671): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/CountryDetector( 1014): The first listener is added,
I/SELinux ( 6671): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6671 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 6671): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 5880:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,D/Mms/MmsApp( 6587): [end]    initCountryIso consume time = 14.868698
D/Mms/MmsConfig( 6587): [start]    MmsConfig.init() consume time = 0.115938
,D/Mms/MmsConfig( 6587): before partial update
,D/TimaKeyStoreProvider( 6671): TimaSignature is unavailable
D/ActivityThread( 6671): Added TimaKeyStore provider
,D/Mms/MmsConfig( 6587): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 6587): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 6587): isAuth is false
D/Mms/MmsConfig( 6587): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1458): query,matched:2117, calling pid = 6587
,D/TP/MmsSmsProvider( 1458): match 2117:Elapsed time : 1.749 ms
,W/libprocessgroup( 1014): failed to open /acct/uid_10038/pid_5880/cgroup.procs: No such file or directory
,D/EasySignUpManager_1.0.1( 6587): isAuth is false
D/EasySignUpManager_1.0.1( 6587): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 6587): mps_code.dat does not exist
E/CscParser( 6587): customer_path =/system/csc/customer.xml
E/CscParser( 6587): fileName + /system/csc/customer.xml
,I/ActivityManager( 1014): Killing 5811:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,E/CscParser( 6587): mps_code.dat does not exist
,E/CscParser( 6587): customer_path =/system/csc/customer.xml
E/CscParser( 6587): fileName + /system/csc/customer.xml
,D/elm:15183( 6671): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15183( 6671): ELMEngine.ELMEngine( context ).
,D/elm:15183( 6671): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1014): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 6671): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/elm:15183( 6671): ElmAgentService : onCreate()
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/elm:15183( 6671): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
D/CscParser( 6587): getInstance fileName =/system/csc/customer.xml,
D/Mms/MmsConfig( 6587):  enable multiwindow = true
,D/elm:15183( 6671): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15183( 6671): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:15183( 6671): ModuleBase.ModifySetAlarm()
D/elm:15183( 6671): MDMBridge.getInstance()
D/elm:15183( 6671): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 6691): MountEmulatedStorage()
I/libpersona( 6691): KNOX_SDCARD checking this for 10134
E/Zygote  ( 6691): v2
I/libpersona( 6691): KNOX_SDCARD not a persona
,I/SELinux ( 6691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6691): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6691 uid=10134 gids={50134, 9997} abi=armeabi-v7a
,D/elm:15183( 6671): ElmAgentService : onDestroy().
,E/Mms/MessageUtils( 6587): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 6587): updateCountryIso : update country iso info 
,I/ActivityManager( 1014): Killing 6030:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/Mms/MmsConfig( 6587): [end]    init() consume time = 124.336093
,D/Mms/Contact( 6587): [start]    init() consume time = 1.398594
,D/TimaKeyStoreProvider( 6691): TimaSignature is unavailable
,D/ActivityThread( 6691): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 1458): query,matched:13, calling pid = 6587
,D/TP/MmsSmsProvider( 1458): match 13:Elapsed time : 1.897 ms
W/ResourcesManager( 6691): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Mms/Contact( 6587): [end]    init consume time = 22.273594
W/ResourcesManager( 6691): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/Mms/DraftCache( 6587): [start]    rebuildCache consume time = 9.307604
,D/Mms/MethodReflector( 6587): getSubId is called
D/Mms/TelephonyUtils( 6587): getLongSubId from simSlot 0, return Value = -1
,D/TP/MmsSmsProvider( 1458): query,matched:12, calling pid = 6587
,I/ActivityManager( 1014): Killing 6052:com.samsung.helphub/1000 (adj 15): empty #31
,D/TP/MmsSmsProvider( 1458): match 12:Elapsed time : 3.604 ms
,D/Mms/MethodReflector( 6587): getTelephonyProperty is called
D/Mms/DownloadManager( 6587): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6587): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6587): auto download without roaming -> true
D/Mms/DownloadManager( 6587): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 6587): getSubId is called
,D/Mms/MethodReflector( 6587): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 6587): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 6587): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 6587): getTelephonyProperty is called
D/Mms/DownloadManager( 6587): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 6587): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 6587): auto download without roaming -> true
D/Mms/DownloadManager( 6587): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 6587): auto download during roaming secondary -> false
D/Mms/DownloadManager( 6587): mAutoDownload ------> true
,D/Mms/DraftCache( 6587): [end]    rebuildCache consume time = 19.393489
,W/libprocessgroup( 1014): failed to open /acct/uid_10091/pid_5811/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10100/pid_6030/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_6052/cgroup.procs: No such file or directory
,D/ComposerPerformance( 6587): 1449832331622 ms / [DONE] Composer constructor
,D/Mms/Conversation( 6587): [start]    init() consume time = 46.720834
,E/CII     ( 6587): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 6587): ReservationManager()
,I/Mms/ReservationManager( 6587): resetAfterConnected()
,D/TP/MmsSmsProvider( 1458): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1458): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1458): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1458): sUpgradeVersion = 0, db.getVersion() = 81
,D/TP/MmsSmsProvider( 1458): query,matched:7, calling pid = 6587
,D/TP/MmsSmsProvider( 1458): match 7:Elapsed time : 1.332 ms
,D/TP/MmsSmsProvider( 1458): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1458): need read changed broadcast:false
,D/Mms/Conversation( 6587): [end]    init consume time = 13.542604
,I/Mms/ReservationManager( 6587): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/MessagingNotification( 6587): [start]    init() consume time = 3.250677
,D/Mms/MessagingNotification( 6587): [end]    init consume time = 2.199948
,D/Mms/MmsApp( 6587): [end]    onCreate() consume time = 1.462969
,D/Mms/DownloadManager( 6587): Service state changed: Bundle[mParcelledData.dataSize=744]
,I/splitIntent( 1014): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,D/Mms/DownloadManager( 6587): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 6587): getSubId is called
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,D/Mms/SpamFilter( 6587): [start]    SpamFilter fill() begin consume time = 5.231562
,D/Mms/TelephonyUtils( 6587): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 6587): getTelephonyProperty is called
D/Mms/DownloadManager( 6587): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6587): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6587): auto download without roaming -> true
D/Mms/DownloadManager( 6587): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 6587): mAutoDownload ------> true
,D/TP/MmsSmsProvider( 1458): query,matched:0, calling pid = 6587
V/TP/MmsSmsProvider( 1458): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1458): match 0:Elapsed time : 0.935 ms
,I/jxcore-log( 6123): BLE supported!!
I/jxcore-log( 6123): 
,D/Mms/Synchronizer( 6587): [start]    doSync consume time = 13.374063
,D/TP/MmsSmsProvider( 1458): query,matched:400, calling pid = 6587
,D/TP/MmsSmsProvider( 1458): update, matched:300, calling pid = 6587
V/TP/MmsSmsProvider( 1458): syncDBData start
,V/TP/MmsSmsProvider( 1458): syncDBData sms end
,D/Mms/ArtClassLoader( 6587): init [DONE] art
V/TP/MmsSmsProvider( 1458): syncDBData mms end
,V/TP/MmsSmsProvider( 1458): syncDBData end
,D/Mms/Synchronizer( 6587): [end]    doSync consume time = 8.976302
,D/Mms/SpamFilter( 6587): [end]    SpamFilter fill() finished consume time = 1.257552
,D/Mms/MessagingNotification( 6587): checkBadgeCount unreadCount=0 badgeCount=0
,I/ActivityManager( 1014): Killing 5913:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/TP/SmsProvider( 1458): query,matched:26, calling pid = 6587
,D/TP/SmsProvider( 1458): match 26:Elapsed time : 1.259 ms
,D/TP/MmsSmsProvider( 1458): query,matched:6, calling pid = 6587
,D/TP/MmsSmsProvider( 1458): match 6:Elapsed time : 0.817 ms
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6713): MountEmulatedStorage()
I/libpersona( 6713): KNOX_SDCARD checking this for 10025
E/Zygote  ( 6713): v2
I/libpersona( 6713): KNOX_SDCARD not a persona
I/SELinux ( 6713): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6713 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,I/SELinux ( 6713): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6713): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1014): failed to open /acct/uid_10072/pid_5913/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6713): TimaSignature is unavailable
,D/ActivityThread( 6713): Added TimaKeyStore provider
,I/ActivityManager( 1014): Killing 5630:com.android.defcontainer/u0a4 (adj 15): empty #31
,W/ResourcesManager( 6713): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/OMACP   ( 6713): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 6587): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/OMACP   ( 6713): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 6713): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 6713): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 6713): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 6713): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 6713): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 6713): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 6713): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 6713): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 6713): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 6713): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 6713): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 6713): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,W/libprocessgroup( 1014): failed to open /acct/uid_10004/pid_5630/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6360): wlan0: sending IPv6 Router Solicitation
,I/CalendarProvider2( 6615): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar },
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/ActivityManager( 1014): Killing 5747:com.sec.pcw.device/1000 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5747/cgroup.procs: No such file or directory
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/SA      ( 5999): [RC New] [v2liruge] api execute + 1615
,I/SA      ( 5999): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5999): AsyncTask #1 calls detatch()
,I/SA      ( 5999): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5999): [OCP] update openData : PL
,I/SA      ( 5999): [TPMU] getNetworkMcc : 
,I/SA      ( 5999): [SCU] saveMccToPreferece Start
,I/SA      ( 5999): [SCU] RegionMCC : 260
,I/SA      ( 5999): [SSP] query invoked
,I/SA      ( 5999): [TPMU] GetMccFromDB : null
,I/SA      ( 5999): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5999): [SCU] saveMccToPreferece End
,I/SA      ( 5999): [RC New] executeRequest [v2liruge] end. 1692
,I/SA      ( 5999): [RC New] Execute end
,I/SA      ( 5999): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5999): [OR] GetMyCountryZoneTask Success
,E/SMD     (  288): DCD OFF,
,I/SurfaceFlinger(  257): id=15 Removed Uoast (8/9),
I/SurfaceFlinger(  257): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1014): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1014) eventTime = 100819
,D/PowerManagerService( 1014): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014 (0x0)
,D/PowerManagerService( 1014): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1014, ws=WorkSource{10054}) (elapsedTime=3487)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1840): callingUid 10012, callindPid: 1840
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/GmsUtils( 6231): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 6231): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
D/ActivityManager( 1014): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/MusicLeanback( 6231): Conditions not met for autocaching.
I/MusicLeanback( 6231): Stop autocaching.
,I/GAV4    ( 6322): Thread[GAThread,5,main]: No campaign data found.
,I/Mms/MmsApp( 6587):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 6587): [start]    fillCache consume time = 1971.806249
,D/Mms/ComposeMessageFragment( 6587): fillCache, easy = false
,D/AbsListView( 6587): Get MotionRecognitionManager
,D/MotionRecognitionService( 1014):  ssp status : false
,D/Mms/ComposeMessageFragment( 6587): [end]    fillCache consume time = 102.957656
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6740): MountEmulatedStorage()
,E/Zygote  ( 6740): v2
I/libpersona( 6740): KNOX_SDCARD checking this for 10028
I/SELinux ( 6740): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6740): KNOX_SDCARD not a persona
I/SELinux ( 6740): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6740 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6740): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/AlarmManager( 1014): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1014): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1014): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,I/art     (  303): Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 796us total 30.300ms
D/TimaKeyStoreProvider( 6740): TimaSignature is unavailable
D/ActivityThread( 6740): Added TimaKeyStore provider
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: android, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,I/BackgroundCompactionService( 1014): onStart. jobID=801
,I/BackgroundCompactionService( 1014): onStart done. jobID=801
,I/BackgroundCompactionService( 1014): Execute BGCompaction (type1). (0 times)
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 17.524ms
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
I/BackgroundCompactionService( 1014): compact_memory command done
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 17.545ms
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/Mms/BubbleViewCache( 6587): fillCache bubble = 1
,D/Finsky  ( 6740): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{1a960606 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/Finsky  ( 6740): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6740): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6740): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 6740): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6740): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6740): Skipping gmscore version check
,D/Finsky  ( 6740): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6740): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Finsky  ( 6740): [1180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6740): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager( 1014): Killing 6258:com.android.email/u0a145 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10145/pid_6258/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF
,I/dhcpcd  ( 6360): wlan0: sending IPv6 Router Solicitation
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4,
,D/SSRM:n  ( 1014): SIOP:: AP = 320
,I/PowerManagerService( 1014): [PWL] Off : 30s ago
,I/dhcpcd  ( 6360): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6360): wlan0: no IPv6 Routers available
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5829): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5829): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5829): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5829): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5829): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5829): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5829): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5829): entry::IDLE
,E/Watchdog( 1014): !@Sync 3
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1840): Vacuum at: now=1449832342166 tag=VacuumService
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1840): Scheduling Phenotype for one-off execution 13273 seconds from now (1449832342529)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1840): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1840): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1840): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1840): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10012
,D/FactoryTest( 5251): Not factory mode
,D/FactoryTest( 5251): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5251): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5251): still no open session command from host, so toast
,W/ContextImpl( 5251): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5251): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5251): Timeline: Activity_launch_request id:com.android.settings time:110509
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
,I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1014): mDVFSHelper.acquire()
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 6123
,E/MTPRx   ( 5251): started activity for popup
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,I/System.out( 1840): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1840): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1840, getuid(): 10012
,W/ResourcesManager( 5251): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5251): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5251): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5251): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5251): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5251): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/qtaguid ( 1840): Tagging socket 91 with tag 1000120100000000{268440065,0} for uid -1, pid: 1840, getuid(): 10012
,E/SettingsReceiverActivity( 5251): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus entered window: 6123
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1014): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@7aff59e attribute=null, token = android.os.BinderProxy@482affe
,D/SettingsReceiverActivity( 5251): dev.kiessupport is : TRUE
,D/PhoneWindow( 5251): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5251): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,V/ActivityThread( 6123): updateVisibility : ActivityRecord{3e7c8935 token=android.os.BinderProxy@2df9c01f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6123): Timeline: Activity_idle id: android.os.BinderProxy@2df9c01f time:110686
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1840): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1840): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1840, getuid(): 10012
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1840): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1840): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1840, getuid(): 10012
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1840): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1840): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1840, getuid(): 10012
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1840): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1840): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1840): Tagging socket 87 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1840, getuid(): 10012
,I/qtaguid ( 1840): Tagging socket 94 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1840, getuid(): 10012
,I/System.out( 1840): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1840): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1840, getuid(): 10012
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  288): DCD OFF
,W/ActivityManager( 1014): mDVFSHelper.release()
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1014): SIOP:: AP = 300
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1014): SIOP:: AP = 300
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 50s ago
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/Watchdog( 1014): !@Sync 4
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4343, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,D/BatteryService( 1014): stay LED for charging,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 39291(2MB) AllocSpace objects, 21(336KB) LOS objects, 33% free, 27MB/41MB, paused 2.512ms total 168.665ms
,I/PowerManagerService( 1014): [PWL] Off : 75s ago
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 270
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,I/ClearcutLoggerApiImpl( 1840): disconnect managed GoogleApiClient,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4343, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10,
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/Watchdog( 1014): !@Sync 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 105s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4343, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/SMD     (  288): DCD OFF
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/Watchdog( 1014): !@Sync 6
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/lights  ( 1014): write_int failed to open -1
D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/LightsService( 1014): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1014) 
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1014): turn on LED for fully charged
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1014): mCursor = null
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,I/ValidateNoPeople( 1014): skipping global notification
D/WindowManager( 1014): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 1014): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1175
I/PowerManagerService( 1014): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
,I/PowerManagerService( 1014): Waking up from sleep (uid 10054)...
,D/PowerManagerService( 1014): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/KeyguardServiceDelegate( 1014): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@2b870)
,D/KeyguardViewMediator( 1175): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1175): notifyScreenOnLocked
D/PowerManagerService( 1014): [s] UserActivityState : 0 -> 1
,I/DisplayPowerController( 1014): Blocking screen on until initial contents have been drawn.
,D/PowerManagerService( 1014): [PWL] sb acquire: PowerManagerService.Display
,D/WindowOrientationListener( 1014): sensor enabled
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/DisplayPowerController( 1014): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/Sensors ( 1014): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1014): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/libsuspend( 1014): !@autosuspend_wakeup_count_disable
I/libsuspend( 1014): !@autosuspend_wakeup_count_disable done
D/DisplayManagerService( 1014): !@display_state: OFF -> ON
,I/DisplayManagerService( 1014): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  257): Set power mode=2, type=0 flinger=0xb82ae690
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 2 on display: 0
V/ActivityManager( 1014): Display changed displayId=0
E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SensorService( 1014): [SO] changed settle time [1]
D/SensorService( 1014): [SO] setDelay [66000000]
D/SensorService( 1014): [SO] activate (ident=0xb7a39930, enabled=1)
D/SensorService( 1014): [SO] AR_init
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1014): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,D/KeyguardViewMediator( 1175): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1175): onScreenTurnedOn()
,D/SecKeyguardClockSingleView( 1175): onScreenTurnedOn
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,I/PalmMotion( 1014): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1014): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1014): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
E/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1014): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1014) 
,D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SamsungIME( 1785): showDlgMsgBox : false true true
,D/SSRM:a  ( 1014): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1014): SettingsAirViewInfo:: 000000000
,D/NfcService( 1441): call the applyRouting
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/SensorService( 1014): [SO] currT = 217020088926, prevT = 76910079970, diff = 140110008956, [0.192 0.096 10.075]
D/SensorService( 1014): [SO] Reset Rotation Old [100], Init [1]
,D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1014) 
,D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 1014): turn off LED
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,E/SmartFaceService( 1014): onReceive: android.intent.action.SCREEN_ON
W/System.err( 1014): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1014): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1014): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1014): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1014): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1014): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1014): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/SmartFaceService( 1014): fail to set sysfs 1
W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1014): 	... 10 more
,D/KnoxNotification( 1175): ----- inflateViews : modified publicViewLocal -----
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/KnoxNotification( 1175): ----- inflateViews : modified KnoxViewLocal -----
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 1
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 2 on display 0
,D/SurfaceControl( 1014): Excessive delay in setPowerMode(): 122ms
,D/PowerManagerService( 1014): Excessive delay in !@display_state: ON: 123ms
D/PersonaManager( 1175): PersonaID is invalid or persona doesn't exists. : -1
,D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,D/InputMethodManagerService( 1014): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event1/device/enabled: 1
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,V/UserPresentBroadcastReceiver( 1840): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/StatusBarKeyguardViewManager( 1175): callback.onShown()
D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
V/KeyguardServiceDelegate( 1014): **** SHOWN CALLED ****
,D/DisplayPowerController( 1014): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/DisplayPowerController( 1014): Unblocked screen on after 163 ms
D/DisplayPowerState( 1014): !@ ColorFade exit
D/SensorService( 1014): [SO] currT = 217090089082, prevT = 76910079970, diff = 140180009112, [0.172 0.057 10.036]
D/SensorService( 1014): [SO] 0.172 0.057 10.036
,D/SensorService( 1014): [SO] [100 -> 255]
,I/SurfaceFlinger(  257): id=12 Removed DolorFade (8/8)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
E/libEGL  ( 1014): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1014): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  ( 1014): lcd : 5 +
,D/BatteryMeterView( 1175): onDraw batteryColor : -1
,D/lights  ( 1014): lcd : 5 -
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1014): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/Timeline( 6123): Timeline: Activity_idle id: android.os.BinderProxy@2df9c01f time:217115
D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1014): SecHardwareInterface.setBatteryADC : true
,D/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_SCREEN_ON
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MotionRecognitionService( 1014):  handler : SCREEN_ON end
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,D/NotificationService( 1014): ACTION_SCREEN_ON
D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1014) 
,D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
E/WifiNative-wlan0( 1014): do suspend false
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/wpa_supplicant( 2075): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2075): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2075): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 2075): Scan requested (ret=0) - scan timeout 30 seconds
,D/IpRemoteDisplayController( 1014): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 1014): Bridge Server is not available
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
,D/PowerManagerService-JNI( 1014): Excessive delay in MISC setInteractive(true) while turning screen on: 167ms
I/QCOM PowerHAL( 1014): Got set_interactive hint
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/PowerManagerService( 1014): Excessive delay in nativeSetInteractive(true): 171ms
D/lights  ( 1014): button : 1 +
D/PowerManagerService( 1014): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 295ms
,D/PersonaManagerService( 1014): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1014): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,D/lights  ( 1014): button : 1 -
,I/NfcService( 1441): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1441): call the applyRouting
,D/accuweather( 1702): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1702): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1702): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1702): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1702): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1702): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1702): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1702): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1702): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1702): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1702): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 12 14
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1785): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PowerManagerService( 1014): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  ( 1014): SIOP:: AP = 270
,D/daemonapp( 1302): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1302): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1302): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1302): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1302): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1302): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1302): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1302): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1302): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1302): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1302): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1449853860000
D/daemonapp( 1302): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1449832449764
D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1302): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1302): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1302): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1302): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1302): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/BatteryStatsDumper( 1014): In refreshStats isReason Screen ON/OFF: true
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,I/BatteryStatsDumper( 1014): Screen bin #0: time=30305 power=0.17677916666666665
,I/BatteryStatsDumper( 1014): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1014): Previous Battery Level: 100 Current Level: 100 Delta: 0
,E/SMD     (  288): DCD OFF
,I/BatteryStatsDumper( 1014): Writing to database completed
,D/SSRM:a  ( 1014): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1014): SettingsAirViewInfo:: 000000000
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/lights  ( 1014): button : 0 +
,D/lights  ( 1014): button : 0 -
,I/wpa_supplicant( 2075): nl80211: Received scan results (4 BSSes)
,D/WifiP2pService( 1014): InactiveState{ what=147461 }
,D/WifiP2pService( 1014): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1014): DefaultState{ what=147461 }
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {1aa4be1e}
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): start check captive portal 
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1014): [SO] 0.172 0.077 10.036
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/Watchdog( 1014): !@Sync 7
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  288): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1014): [SO] 0.172 0.077 10.017
,E/SMD     (  288): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/PowerManagerService( 1014): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1175 (0x0)
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1014): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1014): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1014): lcd : 1 +
D/DisplayPowerController( 1014): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1014): lcd : 1 -
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1014): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/SMD     (  288): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1014): [SO] 0.172 0.077 10.017
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  288): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1014): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1014): Nap time (uid 1000)...
D/PowerManagerService( 1014): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1014): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
I/PowerManagerService( 1014): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 1014): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1014): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService( 1014): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1014): handleSandman : startDream(true)
E/PowerManagerService( 1014): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1014): Sleeping (uid 1000)...
D/PowerManagerService( 1014): [s] UserActivityState : 4 -> 0
,V/WindowOrientationListener( 1014): WindowOrientationListener disabled
D/SensorService( 1014): [SO] activate (ident=0xb7a39930, enabled=0)
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
I/SurfaceFlinger(  257): id=16 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1014): unregisterListener ::   
,D/KeyguardViewMediator( 1175): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1175): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1175): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1175): notifyScreenOffLocked
,D/PowerManagerService( 1014): Excessive delay in ColorFade : createSurface: 13ms
,D/KeyguardViewMediator( 1175): timeout : 5000
,V/ActivityThread( 6123): updateVisibility : ActivityRecord{3e7c8935 token=android.os.BinderProxy@2df9c01f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PowerManagerService( 1014): Excessive delay in ColorFade : createEglSurface: 15ms
,D/LightsService( 1014): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1014) 
,D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1014): turn on LED for fully charged
,E/lights  ( 1014): write_int failed to open -1
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/KeyguardViewMediator( 1175): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1175): handleNotifyScreenOff
,D/VolumePanel( 1175): onScreenTurnedOff()
D/VolumePanel( 1175): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1175): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1175): onScreenTurnedOff
,D/PowerManagerService( 1014): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 31ms
,E/SmartFaceService( 1014): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1014): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
E/SmartFaceService( 1014): fail to set sysfs 0
W/System.err( 1014): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1014): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1014): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1014): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1014): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1014): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1014): 	... 10 more
,D/PowerManagerService( 1014): Excessive delay in ColorFade : initGLShaders: 10ms
,D/DisplayPowerController( 1014): ColorFade: onAnimationStart
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1014): performScreenOffTransition : no brightness animation
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
,D/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1014):  handler : SCREEN_OFF end 
,D/NotificationService( 1014): ACTION_SCREEN_OFF
D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1014) 
,D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: enter: screen_state=off
,V/voice   (  283): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
,V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
,D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
,E/WifiNative-wlan0( 1014): do suspend true
,I/BackgroundCompactionService( 1014): Schedule Type1 BGCompaction
,D/IpRemoteDisplayController( 1014): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1014): Bridge Server is not available
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PersonaManagerService( 1014): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1014): MSG_ACTION_SCREEN_OFF called
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1416): [EmergencyStateReceiver] binteractive [false] why[3]
,D/NfcService( 1441): call the applyRouting
,D/accuweather( 1702): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1702): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1014): stay LED for fully charged
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1702): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1702): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1702): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1702): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1702): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1702): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1937): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,D/PowerManagerService( 1014): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1702): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1702): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! ,
,D/accuweather( 1702): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1702): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1702): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1702): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/DisplayPowerState( 1014): !@ ColorFade entry
,D/DisplayPowerController( 1014): ColorFade: onAnimationEnd
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 0 -> 0
,D/lights  ( 1014): lcd : 0 +
D/DisplayPowerController( 1014): performScreenOffTransition : no brightness animation
,D/lights  ( 1014): lcd : 0 -
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 0 -> 0
,D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/DisplayPowerController( 1014): performScreenOffTransition : no brightness animation
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/PowerManagerService( 1014): [PWL] sb release: PowerManagerService.Display,
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1014): Got set_interactive hint
,D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb82ae690
,D/DisplayManagerService( 1014): !@display_state: ON -> OFF
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0
I/DisplayManagerService( 1014): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager( 1014): Display changed displayId=0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/BatteryStatsDumper( 1014): In refreshStats isReason Screen ON/OFF: true
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,I/BatteryStatsDumper( 1014): Screen bin #0: time=30305 power=0.17677916666666665
,I/BatteryStatsDumper( 1014): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1014): Previous Battery Level: 100 Current Level: 100 Delta: 0
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl( 1014): Excessive delay in setPowerMode(): 263ms
D/PowerManagerService( 1014): Excessive delay in !@display_state: OFF: 264ms
I/libsuspend( 1014): !@autosuspend_wakeup_count_enable
I/libsuspend( 1014): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1014): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 269ms
I/PowerManagerService( 1014): [PWL] Off : 0s ago
I/PowerManagerService( 1014): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1014): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1014): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1014, ws=null) (elapsedTime=240)
,I/BatteryStatsDumper( 1014): Writing to database completed
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardViewMediator( 1175): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1175): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1175): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1014): [PWL] Off : 5s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :8
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1014): !@Sync 8
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :8
,I/PowerManagerService( 1014): [PWL] Off : 15s ago,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 1014): waitForAlarm result :8
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: android, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,I/BackgroundCompactionService( 1014): onStart. jobID=801
I/BackgroundCompactionService( 1014): onStart done. jobID=801,
I/BackgroundCompactionService( 1014): Execute BGCompaction (type1). (1 times)
D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
I/BackgroundCompactionService( 1014): compact_memory command done
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1014): [PWL] Off : 30s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
,I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1014): !@Sync 9
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6123): Connected to the server!
I/jxcore-log( 6123): 
,I/chromium( 6123): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1014): [PWL] Off : 50s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1014): initializing...
,I/TLC_TIMA_PKM_initialize( 1014): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1014): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1014): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1014): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1014): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1014): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1014): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1014): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1014): App is not loaded in QSEE,
,D/QSEECOMAPI: ( 1014): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1014): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1014): Trustlet response is completed
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 10,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 75s ago
,E/SMD     (  288): DCD OFF
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,V/AlarmManager( 1014): waitForAlarm result :8
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ClearcutLoggerApiImpl( 1840): disconnect managed GoogleApiClient
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 11,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1014): [PWL] Off : 105s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 12,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/PowerManagerService( 1014): [PWL] Off : 140s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1014): waitForAlarm result :8
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1014): !@Sync 13
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 180s ago
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/Watchdog( 1014): !@Sync 14
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/Watchdog( 1014): !@Sync 15
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1014): [PWL] Off : 225s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/bootchecker(  311): bootchecker wake up!!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/Watchdog( 1014): !@Sync 16
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 275s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/Watchdog( 1014): !@Sync 17
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/Watchdog( 1014): !@Sync 18
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :8
,V/AlarmManager( 1014): No more alarm at this time.nowELAPSED=567647 batch.start=801501
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1014): [PWL] Off : 330s ago,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,I/Atfwd_Daemon(  314): Stop the daemon....,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/Watchdog( 1014): !@Sync 19
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/Watchdog( 1014): !@Sync 20
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :8,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1014): [PWL] Off : 390s ago,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/Watchdog( 1014): !@Sync 21
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/Watchdog( 1014): !@Sync 22
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 455s ago,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/Watchdog( 1014): !@Sync 23
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/Watchdog( 1014): !@Sync 24
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 25,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1014): [PWL] Off : 525s ago,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 26
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2006): Aggregate from 1449831021738 (log), 1449831021738 (data)
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ProcessCpuTracker( 1014): Skipping unknown process pid 7118,
,V/AlarmManager( 1014): waitForAlarm result :8
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 27
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 600s ago,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1014): !@Sync 28
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,E/SMD     (  288): DCD OFF
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 29
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,E/SMD     (  288): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1014): !@Sync 30,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 680s ago
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1014): !@Sync 31
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 32
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 33
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 765s ago
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 34
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 35
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1014): !@Sync 36
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 855s ago
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 37
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 38,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 39
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 950s ago,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1014): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1014): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1014): Updating Usage Statistics in DB @ 1449833448434
,I/ApplicationPolicy( 1014): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1014): ::getAppControlDB: DB is Created ,
I/NetworkDataUsageDb( 1014): ::isTableExists: Table exists 
,I/ApplicationUsage( 1014): Done Updating Usage Statistics in DB @ 1449833448902
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 40
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 41
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 42
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1014): [PWL] Off : 1050s ago
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 43
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 44
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 45
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 46
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 1155s ago
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 47
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 48
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 49
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 1265s ago,
,E/SMD     (  288): DCD OFF
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1014): !@Sync 50
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 51
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1014): !@Sync 52
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 53
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1014): stay LED for fully charged
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1014): [PWL] Off : 1380s ago
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1014): !@Sync 54
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1014): stay LED for fully charged
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1014): !@Sync 55
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1014): !@Sync 56
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/art     ( 1014): Background partial concurrent mark sweep GC freed 70764(7MB) AllocSpace objects, 364(5MB) LOS objects, 33% free, 27MB/41MB, paused 2.482ms total 172.160ms
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 57,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 1500s ago
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 58
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 59
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1014): stay LED for fully charged,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 60
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 61
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 1625s ago,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 62
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,I/ActivityManager( 1014): Killing 6601:com.sec.android.app.taskmanager/u0a157 (adj 15): empty for 1800s
,I/ActivityManager( 1014): Killing 6587:com.android.mms/u0a46 (adj 15): empty for 1800s
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
I/ActivityManager( 1014): Killing 6345:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1800s
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,I/ActivityManager( 1014): Killing 5999:com.osp.app.signin/u0a41 (adj 15): empty for 1800s
,I/ActivityManager( 1014): Killing 6246:com.sec.android.fotaclient/u0a9 (adj 15): empty for 1800s
,I/ActivityManager( 1014): Killing 6532:com.samsung.android.scloud.sync/u0a62 (adj 15): empty for 1800s
,I/ActivityManager( 1014): Killing 5796:com.policydm/1000 (adj 15): empty for 1800s
,I/ActivityManager( 1014): Killing 6462:com.samsung.android.sconnect/u0a125 (adj 15): empty for 1800s
,I/ActivityManager( 1014): Killing 6084:com.google.android.apps.plus/u0a120 (adj 15): empty for 1800s
I/ActivityManager( 1014): Killing 6301:com.sec.android.soagent/u0a34 (adj 15): empty for 1800s
,I/ActivityManager( 1014): Killing 6322:com.google.android.apps.magazines/u0a113 (adj 15): empty for 1800s
D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/ActivityManager( 1014): Killing 6369:com.samsung.android.service.travel/u0a159 (adj 15): empty for 1800s
,I/ActivityManager( 1014): Killing 6428:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
,I/ActivityManager( 1014): Killing 6277:com.android.chrome/u0a81 (adj 15): empty for 1800s
I/ActivityManager( 1014): Killing 6396:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1800s
,I/ProcessStatsService( 1014): Prepared write state in 17ms
,I/ActivityManager( 1014): Killing 6632:com.sec.android.app.clockpackage/u0a85 (adj 15): empty for 1800s
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,I/ActivityManager( 1014): Killing 6647:com.qualcomm.timeservice/1000 (adj 15): empty for 1800s
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/CountryDetector( 1014): No listener is left
,I/ProcessStatsService( 1014): Pruning old procstats: /data/system/procstats/state-2015-12-10-15-41-43.bin
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_6345/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10159/pid_6369/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10125/pid_6462/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10081/pid_6277/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10041/pid_5999/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_6647/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_6428/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10002/pid_6396/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10034/pid_6301/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10009/pid_6246/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10157/pid_6601/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10120/pid_6084/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10113/pid_6322/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10046/pid_6587/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5796/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10062/pid_6532/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10085/pid_6632/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms),D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1014): stay LED for fully charged
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRM:n  ( 1014): SIOP:: AP = 260
E/SMD     (  288): DCD OFF
D/AndroidRuntime( 7567): 
D/AndroidRuntime( 7567): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7567): CheckJNI is OFF
D/AndroidRuntime( 7567): readGMSProperty: start
D/AndroidRuntime( 7567): readGMSProperty: already setted!!
D/AndroidRuntime( 7567): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7567): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7567): readGMSProperty: end
D/AndroidRuntime( 7567): addProductProperty: start
E/AffinityControl( 7567): AffinityControl: registerfunction enter
D/AndroidRuntime( 7567): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1014): START PACKAGE DELETE: observer{22334811}
D/PackageManager( 1014): pkg{<packageName>}
D/PackageManager( 1014): user{0}
D/PackageManager( 1014): caller{2000}
D/PackageManager( 1014): flags{3}
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1014): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1014): !@killApplicatoin: 10175, uninstall pkg
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
I/ActivityManager( 1014): Killing 6123:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1014): Skipping PackageSetting{346c2595 com.example.hello/10174} due to missing metadata
I/WindowState( 1014): WIN DEATH: Window{19b8835f u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  257): id=14 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=14 Removed NainActivit (-2/8)
D/InputDispatcher( 1014): Focus left window: 6123
I/SurfaceFlinger(  257): id=14 Removed NainActivit (-2/8)
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1014): Killing 6691:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty for 1803s
I/ActivityManager( 1014): Killing 6713:com.wsomacp/u0a25 (adj 15): empty for 1804s
I/ActivityManager( 1014): Killing 6188:com.google.android.talk/u0a104 (adj 15): empty for 1804s
I/ActivityManager( 1014): Killing 6671:com.sec.esdk.elm/u0a94 (adj 15): empty for 1804s
I/ActivityManager( 1014): Killing 6615:com.android.providers.calendar/u0a42 (adj 15): empty for 1804s
I/ActivityManager( 1014):   Force finishing activity ActivityRecord{1453195 u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager( 1014): mDVFSHelper.acquire()
W/ActivityManager( 1014): Spurious death for ProcessRecord{170f59f8 6123:com.test.thalitest/u0a175}, curProc for 6123: null
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
I/ActivityManager( 1014):   Force finishing activity ActivityRecord{1453195 u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager( 1014): Duplicate finish request for ActivityRecord{1453195 u0 com.test.thalitest/.MainActivity t3 f}
E/JavaBinder( 1014): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1014): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1014): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1014): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1014): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1014): CustomStartingWindow se packge removed so remove capture also
I/art     ( 5558): Explicit concurrent mark sweep GC freed 2390(140KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 743us total 31.246ms
I/DBG_DM  ( 3134): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
D/InputDispatcher( 1014): Focused application released
I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
I/art     ( 2006): Explicit concurrent mark sweep GC freed 10397(592KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 14MB/19MB, paused 1.320ms total 66.606ms
E/SamsungIME( 1785): mOCRHelper is null
I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
W/GeofencerStateMachine( 1840): Ignoring removeGeofence because network location is disabled.
I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
I/DBG_DM  ( 3134): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
W/SQLiteConnectionPool( 2006): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/DBG_DM  ( 3134): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
I/KLMS-2.5.183: ( 3671): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Dec 11 12:42:16 GMT+01:00 2015
D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/RegisteredComponentCache( 1441): Collect Tech packages for Knox
D/PersonaManager( 1441): isKioskContainerExistOnDevice
I/DBG_DM  ( 3134): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/KLMS-2.5.183: ( 3671): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1014): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1014): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
I/ActivityManager( 1014): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7582 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
E/Zygote  ( 7582): MountEmulatedStorage()
I/libpersona( 7582): KNOX_SDCARD checking this for 10094
E/Zygote  ( 7582): v2
I/libpersona( 7582): KNOX_SDCARD not a persona
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SELinux ( 7582): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/KLMS-2.5.183: ( 3671): KLMSIntentService(): onCreate()
I/SELinux ( 7582): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7582): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Zygote  ( 7591): MountEmulatedStorage()
I/libpersona( 7591): KNOX_SDCARD checking this for 10044
E/Zygote  ( 7591): v2
I/libpersona( 7591): KNOX_SDCARD not a persona
I/SELinux ( 7591): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7591): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7591): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7591 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3671): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/TimaKeyStoreProvider( 7582): TimaSignature is unavailable
D/ActivityThread( 7582): Added TimaKeyStore provider
E/Zygote  ( 7612): MountEmulatedStorage()
E/Zygote  ( 7612): v2
I/libpersona( 7612): KNOX_SDCARD checking this for 10149
I/libpersona( 7612): KNOX_SDCARD not a persona
I/SELinux ( 7612): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
I/SELinux ( 7612): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7612 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 7612): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7591): TimaSignature is unavailable
D/ActivityThread( 7591): Added TimaKeyStore provider
I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
I/art     ( 1014): Explicit concurrent mark sweep GC freed 29273(2MB) AllocSpace objects, 85(1534KB) LOS objects, 33% free, 27MB/41MB, paused 4.040ms total 233.812ms
I/art     ( 1014): WaitForGcToComplete blocked for 193.375ms for cause Explicit
I/KLMS-2.5.183: ( 3671): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
I/DBG_DM  ( 3134): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3134): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
I/DBG_DM  ( 3134): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
D/TimaKeyStoreProvider( 7612): TimaSignature is unavailable
D/ActivityThread( 7612): Added TimaKeyStore provider
D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
I/DBG_DM  ( 3134): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
I/KLMS-2.5.183: ( 3671): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.183: ( 3671): KLMSIntentService(): PACKAGE_REMOVED
D/PersonaManager( 1441): isKioskContainerExistOnDevice
I/SurfaceFlinger(  257): id=17 createSurf (720x1280),1 flag=404, YUIInstallC
D/RegisteredServicesCache( 1441): empty dynamic service
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/KLMS-2.5.183: ( 3671): KLMSIntentService(): listeningToPackageRemoved().START
D/elm:15183( 7582): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/elm:15183( 7582): ELMEngine.ELMEngine( context ).
D/elm:15183( 7582): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1014): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/InputDispatcher( 1014): Focus entered window: 3134
D/SRIB_DCS( 3134): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
I/KLMS-2.5.183: ( 3671): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/elm:15183( 7582): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
D/elm:15183( 7582): ElmAgentService : onCreate()
D/elm:15183( 7582): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 7582): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 7582): MDMBridge.getInstance()
D/elm:15183( 7582): MDMBridge.getAllLicenseInfoFromSDK()
V/ActivityThread( 3134): updateVisibility : ActivityRecord{32efa580 token=android.os.BinderProxy@1960afd7 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
W/ResourcesManager( 7591): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7591): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7591): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7591): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7591): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7591): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7591): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7591): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/art     ( 6568): Explicit concurrent mark sweep GC freed 569(43KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 731us total 83.739ms
E/SQLiteLog( 6568): (284) automatic index on crash_info_summary(package_name_touched)
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7630): MountEmulatedStorage()
E/Zygote  ( 7630): v2
I/libpersona( 7630): KNOX_SDCARD checking this for 1000
I/libpersona( 7630): KNOX_SDCARD not a persona
I/SELinux ( 7630): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=7630 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/elm:15183( 7582): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 7630): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7630): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ThemeInfoUtil( 7612): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 7612): isCurrentFestival = false
W/InputMethodManagerService( 1014): Got RemoteException sending setActive(false) notification to pid 6123 uid 10175
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
I/Timeline( 3134): Timeline: Activity_idle id: android.os.BinderProxy@1960afd7 time:1904279
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 7630): TimaSignature is unavailable
D/ActivityThread( 7630): Added TimaKeyStore provider
D/SamsungIME( 1785): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
I/ActivityManager( 1014): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7648 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
D/RCPManagerService( 1014): PackageReceiver onReceive()
I/HarmonyEASService( 1014): onReceive : android.intent.action.PACKAGE_REMOVED for 0
E/Zygote  ( 7648): MountEmulatedStorage()
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7648): v2
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SELinux ( 7648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 7648): KNOX_SDCARD checking this for 10152
I/libpersona( 7648): KNOX_SDCARD not a persona
D/KnoxMUMContainerPolicy( 1014): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1014): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1014): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1014): DBIntegrity::getInstance - New instance created
I/SELinux ( 7648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7648): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/OTPFW   ( 1014): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
I/OTPFW   ( 1014): ProvisionData::getAllEntries Enter
E/Zygote  ( 7656): MountEmulatedStorage()
I/libpersona( 7656): KNOX_SDCARD checking this for 10072
E/Zygote  ( 7656): v2
I/libpersona( 7656): KNOX_SDCARD not a persona
I/SELinux ( 7656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7656 uid=10072 gids={50072, 9997} abi=armeabi-v7a
E/OTPFW   ( 1014): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1014): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1014): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10175
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
I/SELinux ( 7656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7656): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): mDVFSHelper.release()
D/EnterpriseDeviceManagerService( 1014): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1014): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1014): no available spell checker services found
I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{23b0aced u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t2} time:1904337
D/elm:15183( 7582): ElmAgentService : onDestroy().
I/KLMS-2.5.183: ( 3671): KLMSIntentService(): listeningToPackageRemoved().END
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10175
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
D/SSRM:aZ ( 1014): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
D/TimaKeyStoreProvider( 7648): TimaSignature is unavailable
D/ActivityThread( 7648): Added TimaKeyStore provider
W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
V/AlarmManagerEXT( 1014): com.test.thalitest(10175) is removed.
E/SMD     (  288): DCD OFF
I/KLMS-2.5.183: ( 3671): KLMSIntentService(): onDestroy()
D/TaskPersister( 1014): removeObsoleteFile: deleting file=3_task.xml
D/TimaKeyStoreProvider( 7656): TimaSignature is unavailable
D/ActivityThread( 7656): Added TimaKeyStore provider
I/ActivityManager( 1014): Killing 6547:com.android.calendar/u0a135 (adj 15): empty for 1804s
D/TaskPersister( 1014): removeObsoleteFile: deleting file=2_task.xml
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AASAservice-UpdateReceiver( 7630): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 7630): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 7630): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 7630): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 7630): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 7630): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 7630): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 7630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7630): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7630): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 7630): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7630): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7630): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7630): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/Zygote  ( 7680): MountEmulatedStorage()
I/libpersona( 7680): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7680): v2
I/libpersona( 7680): KNOX_SDCARD not a persona
I/SELinux ( 7680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7680 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 5855:com.sec.spp.push/u0a35 (adj 15): empty for 1803s
I/ActivityManager( 1014): Killing 6231:com.google.android.music:main/u0a111 (adj 15): empty for 1803s
E/SELinux ( 7680): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
D/PersonaManager( 1014): isKioskContainerExistOnDevice
I/StatusBar( 1175): Icon Only
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
I/ActivityManager( 1014): Killing 6740:com.android.vending/u0a28 (adj 15): empty for 1802s
E/SQLiteLog( 7648): (284) automatic index on shooting_modes(title_id)
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 7680): TimaSignature is unavailable
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
D/ActivityThread( 7680): Added TimaKeyStore provider
I/art     ( 1014): Explicit concurrent mark sweep GC freed 12866(749KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 8.105ms total 367.182ms
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 7656): onCreate
D/BadgeProvider( 7656): DatabaseHelper
E/Zygote  ( 7696): MountEmulatedStorage()
E/Zygote  ( 7696): v2
I/libpersona( 7696): KNOX_SDCARD checking this for 1000
I/SELinux ( 7696): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 7696): KNOX_SDCARD not a persona
I/SELinux ( 7696): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7696 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 7696): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BadgeProvider( 7656): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 7656): sendNotify, [notify] : null
D/PackageManager( 1014): delete codoeFile: 
D/BadgeProvider( 7656): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 7656): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7656): update, [UpdateCount] : 1
D/AASAuninstall( 1014): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
I/AASA_removePackage( 1014): UID=10175 Target=com.test.thalitest
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
D/PackageManager( 1014): result of delete: 1{22334811}
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
D/AndroidRuntime( 7567): Shutting down VM
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
```
