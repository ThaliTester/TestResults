#### Test 54312298af2c956_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1854): Loading module APK com.google.android.play.games
D/PackageBroadcastService( 1854): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
E/CII     ( 5744): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5744): ReservationManager()
I/Mms/ReservationManager( 5744): resetAfterConnected()
--------- beginning of system
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
D/Mms/Conversation( 5744): [start]    init() consume time = 47.626094
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1478): query,matched:7, calling pid = 5744
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
D/TP/MmsSmsProvider( 1478): match 7:Elapsed time : 3.029 ms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/Mms/ReservationManager( 5744): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1478): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1478): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1478): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1478): sUpgradeVersion = 0, db.getVersion() = 81
D/Mms/MmsApp( 5744): [end]    onCreate() consume time = 35.590937
D/TP/MmsSmsProvider( 1478): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1478): need read changed broadcast:false
D/Mms/Conversation( 5744): [end]    init consume time = 8.053386
D/Mms/MessagingNotification( 5744): [start]    init() consume time = 1.119166
D/Mms/MessagingNotification( 5744): [end]    init consume time = 1.523959
D/Mms/SpamFilter( 5744): [start]    SpamFilter fill() begin consume time = 1.784271
D/TP/MmsSmsProvider( 1478): query,matched:0, calling pid = 5744
V/TP/MmsSmsProvider( 1478): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1478): query,matched:400, calling pid = 5744
D/TP/MmsSmsProvider( 1478): match 0:Elapsed time : 0.752 ms
I/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Mms/ArtClassLoader( 5744): init [DONE] art
I/DBG_POLICYDM( 5809): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Mms/Synchronizer( 5744): [start]    doSync consume time = 19.382291
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Mms/DownloadManager( 5744): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5744): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5744): getSubId is called
D/Mms/TelephonyUtils( 5744): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5744): getTelephonyProperty is called
D/Mms/DownloadManager( 5744): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5744): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5744): auto download without roaming -> true
D/Mms/DownloadManager( 5744): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5744): mAutoDownload ------> true
E/Zygote  ( 5924): MountEmulatedStorage()
I/libpersona( 5924): KNOX_SDCARD checking this for 10072
E/Zygote  ( 5924): v2
I/libpersona( 5924): KNOX_SDCARD not a persona
I/SELinux ( 5924): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5924 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/SELinux ( 5924): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/Mms/SpamFilter( 5744): [end]    SpamFilter fill() finished consume time = 29.353594
E/SELinux ( 5924): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5809): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
D/TP/MmsSmsProvider( 1478): update, matched:300, calling pid = 5744
V/TP/MmsSmsProvider( 1478): syncDBData start
V/TP/MmsSmsProvider( 1478): syncDBData sms end
V/TP/MmsSmsProvider( 1478): syncDBData mms end
V/TP/MmsSmsProvider( 1478): syncDBData end
D/Mms/Synchronizer( 5744): [end]    doSync consume time = 17.273698
D/TimaKeyStoreProvider( 5924): TimaSignature is unavailable
D/ActivityThread( 5924): Added TimaKeyStore provider
D/Mms/FreeMessageStatusReceiver( 5744): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5940): MountEmulatedStorage()
E/Zygote  ( 5940): v2
I/libpersona( 5940): KNOX_SDCARD checking this for 10047
I/libpersona( 5940): KNOX_SDCARD not a persona
I/SELinux ( 5940): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5940 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 5940): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5940): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5809): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
D/BadgeProvider( 5924): onCreate
D/BadgeProvider( 5924): DatabaseHelper
D/TimaKeyStoreProvider( 5940): TimaSignature is unavailable
D/ActivityThread( 5940): Added TimaKeyStore provider
D/Mms/FreeMessageReceiverService( 5744): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5744): onHandleIntent: ACTION_PACKAGE_ADDED
I/DBG_POLICYDM( 5809): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
W/ResourcesManager( 5940): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5940): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5940): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 1017): Killing 3718:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/ActivityManager( 1017): Killing 5189:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #32
D/Mms/MessagingNotification( 5744): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1478): query,matched:26, calling pid = 5744
D/TP/SmsProvider( 1478): match 26:Elapsed time : 1.992 ms
V/AlarmManager( 1017): waitForAlarm result :4
D/TP/MmsSmsProvider( 1478): query,matched:6, calling pid = 5744
D/TP/MmsSmsProvider( 1478): match 6:Elapsed time : 2.105 ms
I/SL_DEBUG( 5846): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5846): isLoggable:: SL_DEBUG_EXIST = false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5960): MountEmulatedStorage()
E/Zygote  ( 5960): v2
I/libpersona( 5960): KNOX_SDCARD checking this for 10025
I/libpersona( 5960): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5960 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 5960): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5960): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5960): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5189/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10042/pid_3718/cgroup.procs: No such file or directory
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/TimaKeyStoreProvider( 5960): TimaSignature is unavailable
D/ActivityThread( 5960): Added TimaKeyStore provider
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ConfigFetchService( 1854): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ActivityManager( 1017): Killing 3866:com.google.android.talk/u0a104 (adj 15): empty #31
I/ConfigFetchService( 1854): launchTask
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1854): Module APK com.google.android.play.games already loaded
V/ConfigFetchTask( 1854): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WtUtSrHyY81FlZpCEJ6MBwoAsPUWIUq_pk8IfBGrokGcZc5MPXx412u332v3cmdFK7J1e9kYLTc3j1SlSbbysQ3T-BZWI0l3ZRKIIYiKCL_igionrHc2cE0qG35zMJo8t3L6hwpHD8-S6y2J5N-GeuTR165YeXcCNyE7BzTMU4KnwgqFmfjhzDqYWC7HHrHhbEfFfQUqeMp9POPEW170e_TRVxwRWW7uCcu-a68HLfrBjeykU
D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/Vision  ( 1854): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
W/ResourcesManager( 5960): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Vision  ( 1854): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1854): No vision deps
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GoogleURLConnFactory( 1854): Using platform SSLCertificateSocketFactory
I/PeopleContactsSync( 1854): CP2 sync disabled
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1017): failed to open /acct/uid_10104/pid_3866/cgroup.procs: No such file or directory
I/OMACP   ( 5960): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5846): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/Mms/Omacp( 5744): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/OMACP   ( 5960): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5960): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5960): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5960): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5960): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5960): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5960): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5960): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5960): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5960): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5960): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5960): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5960): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
I/System.out( 1854): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1854): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1854): (HTTPLog)-Static: isShipBuild true
I/System.out( 1854): (HTTPLog)-Thread-263-594844595: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1854): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
D/MyFiles ( 5940): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
I/TactileAssist( 1017): enable value -1
I/TactileAssist( 1017): internal enable value -1
I/TactileAssist( 1017): intensity value -1
I/TactileAssist( 1017): saveAppList value true
I/TactileAssist( 1017): List of disabled apps :
I/GAv4    ( 5764): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5764):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5764):   adb logcat -s GAv4
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/System.out( 1854): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1854): Tagging socket 92 with tag 40b00000000{1035,0} for uid -1, pid: 1854, getuid(): 10012
E/Zygote  ( 5987): MountEmulatedStorage()
E/Zygote  ( 5987): v2
I/libpersona( 5987): KNOX_SDCARD checking this for 10053
I/libpersona( 5987): KNOX_SDCARD not a persona
I/SELinux ( 5987): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5987): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5987): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5987 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
W/GAv4    ( 5764): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/TimaKeyStoreProvider( 5987): TimaSignature is unavailable
D/ActivityThread( 5987): Added TimaKeyStore provider
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5846): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ResourcesManager( 5987): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/PackageManager( 1017): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
W/GAv4    ( 5764): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
W/GAv4    ( 5764): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/Compatibility( 5987): onReceive() it will make start service
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
W/AnalyticsTrackerProxyImpl( 5764): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5987): onHandleIntent()
E/Zygote  ( 6008): MountEmulatedStorage()
E/Zygote  ( 6008): v2
I/libpersona( 6008): KNOX_SDCARD checking this for 1000
I/libpersona( 6008): KNOX_SDCARD not a persona
I/SELinux ( 6008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6008): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6008 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/Compatibility( 5987): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
D/Compatibility( 5987): found: 2
I/art     ( 1707): Explicit concurrent mark sweep GC freed 17302(974KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/17MB, paused 1.050ms total 51.802ms
D/TimaKeyStoreProvider( 6008): TimaSignature is unavailable
D/ActivityThread( 6008): Added TimaKeyStore provider
I/qtaguid ( 1854): Tagging socket 108 with tag 40b00000000{1035,0} for uid -1, pid: 1854, getuid(): 10012
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
D/Compatibility( 5987): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5987): skipping ResolveInfo{1e7aa3a8 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5987): considering ResolveInfo{14050ec1 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5987): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5987): enabling receiver ResolveInfo{3aec4666 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5987): enabling receiver ResolveInfo{2cf13da7 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/ContextImpl( 6008): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
D/Compatibility( 5987): enabling receiver ResolveInfo{39aa5254 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/Compatibility( 5987): enabling receiver ResolveInfo{3392d5fd com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5987): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6030 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 6030): MountEmulatedStorage()
E/Zygote  ( 6030): v2
I/libpersona( 6030): KNOX_SDCARD checking this for 1000
I/libpersona( 6030): KNOX_SDCARD not a persona
I/SELinux ( 6030): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
I/ActivityManager( 1017): Killing 5418:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/SELinux ( 6030): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6030): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 5433:com.sec.knox.bridge/1000 (adj 15): empty #31
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6030): TimaSignature is unavailable
D/ActivityThread( 6030): Added TimaKeyStore provider
E/Zygote  ( 6047): MountEmulatedStorage()
E/Zygote  ( 6047): v2
I/libpersona( 6047): KNOX_SDCARD checking this for 10041
I/libpersona( 6047): KNOX_SDCARD not a persona
I/SELinux ( 6047): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6047): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6047 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6047): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
D/TimaKeyStoreProvider( 6047): TimaSignature is unavailable
D/ActivityThread( 6047): Added TimaKeyStore provider
W/ResourcesManager( 6030): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
W/libprocessgroup( 1017): failed to open /acct/uid_10069/pid_5418/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5433/cgroup.procs: No such file or directory
I/PowerManagerService( 1017): [PWL] Off : 5s ago
I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1854, ws=null) (elapsedTime=47906)
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1017, ws=WorkSource{10054}) (elapsedTime=655)
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'Config Service fetch' (uid=10012, pid=1854, ws=WorkSource{10175 com.test.thalitest}) (elapsedTime=549)
I/qtaguid ( 1854): Untagging socket 92
I/ConfigFetchService( 1854): fetch service done; releasing wakelock
I/ConfigFetchService( 1854): stopping self
I/SA      ( 6047): [SSP] onCreated
I/SA      ( 6047): [TPM] There is no property file
I/ActivityManager( 1017): Killing 5449:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/SA      ( 6047): [SCU] isHaveSA() - false
I/SA      ( 6047): [TPM] getModelProperty : null
I/SA      ( 6047): [TPM] getCSCProperty : null
I/SA      ( 6047): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6047): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6047): [DM] TFT FEATURE: false
I/SA      ( 6047): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6047): [DM] init START
I/SA      ( 6047): [DM] This device is not a Vodafone
W/ResourceType( 6047): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6047): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6047): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ResourceType( 6047): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ResourceType( 6047): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ResourceType( 6047): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6047): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6047): [SCU] isHaveSA() - false
I/SA      ( 6047): support phone number id : false
I/SA      ( 6047): [DM] Supports Ref Jpn : true
I/SA      ( 6047): [DM] init END
I/SA      ( 6047): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 6047): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
E/Zygote  ( 6070): MountEmulatedStorage()
E/Zygote  ( 6070): v2
I/libpersona( 6070): KNOX_SDCARD checking this for 1000
I/libpersona( 6070): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6070 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5523:com.google.android.apps.plus/u0a120 (adj 15): empty #31
I/SELinux ( 6070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6070): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 5358:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
W/libprocessgroup( 1017): failed to kill pid 5449: No such process
D/TimaKeyStoreProvider( 6070): TimaSignature is unavailable
D/ActivityThread( 6070): Added TimaKeyStore provider
I/ActivityManager( 1017): Killing 4968:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
E/JavaBinder( 1017): !!! FAILED BINDER TRANSACTION !!!
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/BroadcastQueue( 1017): Exception when sending broadcast to ComponentInfo{com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor}
W/BroadcastQueue( 1017): android.os.TransactionTooLargeException
W/BroadcastQueue( 1017): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1017): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1017): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1017): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1017): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1017): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1017): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1017): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1017): 	at android.os.Binder.execTransact(Binder.java:461)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 5764): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
E/Zygote  ( 6087): MountEmulatedStorage()
E/Zygote  ( 6087): v2
I/libpersona( 6087): KNOX_SDCARD checking this for 10120
I/libpersona( 6087): KNOX_SDCARD not a persona
I/SELinux ( 6087): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6087): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6087 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6087): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): Spurious death for ProcessRecord{42adf8 6087:com.google.android.apps.plus/u0a120}, curProc for 5523: null
W/ResourcesManager( 6070): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 6087): TimaSignature is unavailable
D/ActivityThread( 6087): Added TimaKeyStore provider
I/art     (  305): Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.133ms total 29.058ms
I/ActivityManager( 1017): Killing 5500:com.google.android.gms:car/u0a12 (adj 15): empty #31
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5449/cgroup.procs: No such file or directory
W/ResourcesManager( 6087): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 18.121ms
W/ResourcesManager( 5764): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5764): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup( 1017): failed to open /acct/uid_10120/pid_5523/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10057/pid_5358/cgroup.procs: No such file or directory
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 18.790ms
I/art     ( 1017): Explicit concurrent mark sweep GC freed 219202(14MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/41MB, paused 3.296ms total 214.555ms
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4968/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10012/pid_5500/cgroup.procs: No such file or directory
V/JNIHelp ( 5764): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/AndroidRuntime( 6102): 
D/AndroidRuntime( 6102): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6102): CheckJNI is OFF
D/AndroidRuntime( 6102): readGMSProperty: start
D/AndroidRuntime( 6102): readGMSProperty: already setted!!
D/AndroidRuntime( 6102): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6102): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6102): readGMSProperty: end
D/AndroidRuntime( 6102): addProductProperty: start
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
W/System  ( 5764): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@382e62c2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 5764): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 5764): Installed default security provider GmsCore_OpenSSL
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/AffinityControl( 6102): AffinityControl: registerfunction enter
I/ActivityManager( 1017): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6122 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/Zygote  ( 6122): MountEmulatedStorage()
E/Zygote  ( 6122): v2
I/libpersona( 6122): KNOX_SDCARD checking this for 10057
I/libpersona( 6122): KNOX_SDCARD not a persona
I/SELinux ( 6122): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Killing 5583:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/SELinux ( 6122): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6122): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 6102): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 6122): TimaSignature is unavailable
D/ActivityThread( 6122): Added TimaKeyStore provider
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1017): mDVFSHelper.acquire()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
E/Zygote  ( 6140): MountEmulatedStorage()
E/Zygote  ( 6140): v2
I/libpersona( 6140): KNOX_SDCARD checking this for 10175
I/libpersona( 6140): KNOX_SDCARD not a persona
I/SELinux ( 6140): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6140 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 3029
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=13 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6140): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5583/cgroup.procs: No such file or directory
D/AndroidRuntime( 6102): Shutting down VM
E/SELinux ( 6140): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6140): TimaSignature is unavailable
D/ActivityThread( 6140): Added TimaKeyStore provider
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/ActivityManager( 1017): Display changed displayId=0
E/SMD     (  287): DCD OFF
V/ActivityThread( 3029): updateVisibility : ActivityRecord{538aac4 token=android.os.BinderProxy@1bdbe1e5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6157): MountEmulatedStorage()
E/Zygote  ( 6157): v2
I/libpersona( 6157): KNOX_SDCARD checking this for 10010
I/libpersona( 6157): KNOX_SDCARD not a persona
I/SELinux ( 6157): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6157 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 6157): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6157): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  256): id=11 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  256): id=11 Removed YUIInstallC (-2/9)
D/TimaKeyStoreProvider( 6157): TimaSignature is unavailable
D/ActivityThread( 6157): Added TimaKeyStore provider
I/art     ( 1854): Background sticky concurrent mark sweep GC freed 19564(1295KB) AllocSpace objects, 9(455KB) LOS objects, 13% free, 13MB/15MB, paused 5.273ms total 72.650ms
W/art     ( 6102): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1854): Module APK com.google.android.play.games already loaded
,I/WebViewFactory( 6140): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/splitIntent( 1017): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1017): Killing 5606:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/KeyguardViewMediator( 1175): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1175): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1175): *** Keyguard wallpaper service already unbounded
,I/LibraryLoader( 6140): Time to load native libraries: 2 ms (timestamps 5327-5329)
,I/LibraryLoader( 6140): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6140): Binding Chromium to main looper Looper (main, tid 1) {39aa5254}
,I/LibraryLoader( 6140): Expected native library version number "",actual native library version number ""
,I/chromium( 6140): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/LocationManagerService( 1017): getProviders()=[passive]
,I/BrowserStartupController( 6140): Initializing chromium process, singleProcess=true
,W/art     ( 6140): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6140): ApplicationContext is null in ApplicationStatus
,W/chromium( 6140): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6140): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6140): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6140): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6140): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6140): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6140): Local Branch: 
I/Adreno-EGL( 6140): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6140): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6140):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/libprocessgroup( 1017): failed to open /acct/uid_10142/pid_5606/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 6122): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Mms/MmsApp( 5744):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5744): [start]    fillCache consume time = 1929.438853
D/Mms/ComposeMessageFragment( 5744): fillCache, easy = false
,D/AbsListView( 5744): Get MotionRecognitionManager
,D/MotionRecognitionService( 1017):  ssp status : false
,D/Mms/ComposeMessageFragment( 5744): [end]    fillCache consume time = 63.149219
,I/UpdateIcingCorporaServi( 6122): UpdateCorporaTask done [took 132 ms] updated apps [took 132 ms] 
,I/ActivityManager( 1017): Killing 5204:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/Mms/BubbleViewCache( 5744): fillCache bubble = 1
,W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{aba30d3 u0 com.test.thalitest/.MainActivity t229}
,W/art     ( 6140): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6140): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6140): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6140): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6140): CordovaWebView is running on device made by: samsung
W/art     ( 6140): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6140): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup( 1017): failed to open /acct/uid_10150/pid_5204/cgroup.procs: No such file or directory
,D/OpenGLRenderer( 6140): Render dirty regions requested: true
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false,
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
W/chromium( 6140): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,V/ActivityThread( 6140): updateVisibility : ActivityRecord{133eee69 token=android.os.BinderProxy@d98cd33 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4178, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/PhoneWindow( 6140): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6140): *FMB* isFloatingMenuEnabled return false
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/SurfaceFlinger(  256): id=14 createSurf (1x1),1 flag=404, NainActivit
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/InputDispatcher( 1017): Focus entered window: 6140
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6140): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 6140): Initialized EGL, version 1.4
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/OpenGLRenderer( 6140): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6140): Enabling debug mode 0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1175): There is/are notification(s) 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1781): getCurrentCandidateView
,I/ActivityManager( 1017): Displayed Component not be shown by security: +817ms (total +917ms)
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{aba30d3 u0 com.test.thalitest/.MainActivity t229} time:85942
W/ActivityManager( 1017): mDVFSHelper.release()
,I/SurfaceFlinger(  256): id=13 Removed uhalitest (7/9)
,I/SurfaceFlinger(  256): id=13 Removed uhalitest (-2/9)
,W/IInputConnectionWrapper( 6140): showStatusIcon on inactive InputConnection
,I/Timeline( 6140): Timeline: Activity_idle id: android.os.BinderProxy@d98cd33 time:85951
,D/SamsungIME( 1781): Dismiss ExpandCandiate
,I/SamsungIME( 1781): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1781): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1781): KeybaordView init() : load resources
,I/SamsungIME( 1781): getCurrentKeyboard
I/SamsungIME( 1781): getTextKeyboard
,W/BindingManager( 6140): Cannot call determinedVisibility() - never saw a connection for the pid: 6140
,D/SamsungIME( 1781): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/JsMessageQueue( 6140): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6140): JniHelper::setJavaVM(0xb870e450), pthread_self() = -1194950040
,D/JX-Cordova( 6140): jxcore cordova android initializing
,I/DBG_POLICYDM( 5809): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5809): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/AcmsKeyStoreHelper( 5825):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5825): Key Store exist
,I/AcmsKeyStoreHelper( 5825): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 5825):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 5825): getKeyStoreForApplication success 
D/AcmsCore( 5825): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
,D/AcmsServiceMonitor( 5825): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5825): Decrementing - Counter value: 1
D/AcmsCore( 5825): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5825): This is NOT a valid MirrorLink app
D/AcmsCore( 5825): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5825): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5825): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5825): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5825): getSvcCounter - Counter value: 0
D/AcmsService( 5825): Enter onDestroy
I/AcmsService( 5825): cleanUp(): inside service clean up
D/AcmsCore( 5825): AcmsCore: inside DeInit
D/AcmsCore( 5825): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5825): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5825): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5825): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5825): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5825): getSvcCounter - Counter value: 0
D/AcmsService( 5825): killing acms process
I/Process ( 5825): Sending signal. PID: 5825 SIG: 9
,I/ActivityManager( 1017): Process ACMS.Process (pid 5825)(adj 0) has died(38,1071)
,W/jxcore-log( 6140): Initializing JXcore engine
W/jxcore-log( 6140): JXcore engine is ready
,W/jxcore-log( 6140): Starting JXcore engine
,E/audit   ( 1879): type=1400 msg=audit(1450836464.930:205): avc:  denied  { ioctl } for  pid=6140 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3080 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1879):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1879): type=1300 msg=audit(1450836464.930:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bea69d58 items=0 ppid=305 ppcomm=main pid=6140 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1879): type=1320 msg=audit(1450836464.930:205): 
,W/jxcore-log( 6140): Platform android
W/jxcore-log( 6140): 
,W/jxcore-log( 6140): Process ARCH arm
W/jxcore-log( 6140): 
,E/SMD     (  287): DCD OFF
,I/ActivityManager( 1017): Killing 5071:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10040/pid_5071/cgroup.procs: No such file or directory
,I/jxcore-log( 6140): JXcore Cordova bridge is ready!
I/jxcore-log( 6140): 
,W/jxcore-log( 6140): JXcore engine is started
,I/chromium( 6140): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1017): SIOP:: AP = 380
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigService( 1707): onDestroy
,I/jxcore-log( 6140): Toggling radios to true
I/jxcore-log( 6140): 
,D/BluetoothAdapter( 6140): enable()
,D/BluetoothAdapter( 6140): enable(): BT is already enabled..!
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
,D/WifiService( 1017): setWifiEnabled: true pid=6140, uid=10175
D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
,W/ActivityManager( 1017): Permission Denial: getCurrentUser() from pid=6140, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
D/SecContentProvider2( 1017): mCursor = null
W/WifiService( 1017): Failed getting userId using ActivityManagerNative
,W/WifiService( 1017): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6140, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1017): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1017): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1017): 	,at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1017): name = wifi_on
I/WifiService( 1017): disconnect: pid=6140, uid=10175
I/wpa_supplicant( 2044): [wpa_supplicant_ctrl_iface_process] : DISCONNECT,
,I/jxcore-log( 6140): Radios toggled,
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): Got Device Bluetooth address: 7C:F9:0E:51:18:22
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): Perf Test app loaded loaded
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): check test folder
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): found test : ./testFindPeers.js
I/jxcore-log( 6140): 
,I/wpa_supplicant( 2044): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2044): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2044): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 2044): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2044): wlan0: State: DISCONNECTED -> DISCONNECTED
D/Tethering( 1017): InitialState.processMessage what=4
E/wpa_supplicant( 2044): Cmd 35605 not handled
,E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 2044): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2044): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2044): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2044): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 2044): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 2044): First Scan Start
I/wpa_supplicant( 2044): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,E/Tethering( 1017): No numeric data
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0,
D/Tethering( 1017): clearTetheredNotification()
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
V/AlarmManager( 1017): waitForAlarm result :4
,D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1175): updateTetherState():false, false
,V/NetworkStats( 1017): performPollLocked() took 8ms,
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1017): do suspend true
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,V/NativeCrypto( 1707): Read error: ssl=0xb8c62f60: I/O error during system call, Connection timed out
,V/NativeCrypto( 1707): SSL shutdown failed: ssl=0xb8c62f60: I/O error during system call, Broken pipe
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation,
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1017): Tagging socket 384 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1017, getuid(): 1000
E/WifiStateMachine( 1017): Start Disconnecting Watchdog 1,
I/wpa_supplicant( 2044): wlan0: Setting scan request: 0 sec 0 usec
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2,
,E/ConnectivityService( 1017): updateNetworkInfo()
I/jxcore-log( 6140): found test : ./testSendData.js
I/jxcore-log( 6140): 
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14949 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6950 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 1017): Untagging socket 384
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
E/WifiNative-wlan0( 1017): do suspend true
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 3566): Starting #8
,I/Hs20UtilService( 3566): Message received 5007
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,I/jxcore-log( 6140): found test : ./testSendData2.js
I/jxcore-log( 6140): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6224): MountEmulatedStorage()
,E/Zygote  ( 6224): v2
I/libpersona( 6224): KNOX_SDCARD checking this for 10104
I/libpersona( 6224): KNOX_SDCARD not a persona
,I/SELinux ( 6224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6224 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/EnterpriseController(  277): uids 1000,
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  277): Clearing all IP addresses on wlan0
I/SELinux ( 6224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524292
E/SELinux ( 6224): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1478): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1478): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): updateIfacesLocked()
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked() took 4ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/TimaKeyStoreProvider( 6224): TimaSignature is unavailable
,D/ActivityThread( 6224): Added TimaKeyStore provider
,W/ResourcesManager( 6224): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/chromium( 6140): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3,
D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/PhoneApp( 1478): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,I/Babel_SMS( 6224): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6224): MmsConfig.loadMmsSettings
I/Babel_SMS( 6224): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 6224): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6224): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6224): MmsConfig.loadFromResources
,E/Babel_SMS( 6224): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6224): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  282): getCameraInfo: X
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  282): getCameraInfo: X
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6224): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6224): startup - clean
,I/Babel   ( 6224): deleted: false for 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3566): Starting #9
,I/Hs20UtilService( 3566): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/VideoCapabilities( 6224): Unrecognized profile 2130706433 for video/avc
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6224): Unsupported mime audio/evrc
,W/AudioCapabilities( 6224): Unsupported mime audio/qcelp
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6224): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6224): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6224): Unsupported mime audio/x-ms-wma
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/AudioCapabilities( 6224): Unsupported mime audio/x-ima
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6224): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6224): Unsupported mime audio/evrc
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6224): Unsupported mime video/wvc1,
,W/VideoCapabilities( 6224): Unsupported mime video/x-ms-wmv
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1017): updateDataUsageMap
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/VideoCapabilities( 6224): Unrecognized profile/level 32768/2 for video/mp4v-es
,I/DBG_DM  ( 3029): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,W/VideoCapabilities( 6224): Unsupported mime video/wvc1
,I/DBG_DM  ( 3029): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,W/VideoCapabilities( 6224): Unsupported mime video/x-ms-wmv
,I/PCWCLIENTTRACE_PushUtil( 5779): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5779): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5779): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5779): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
I/splitIntent( 1017): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1017): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,W/VideoCapabilities( 6224): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6224): Unsupported mime video/x-ms-wmv8
,V/MusicLeanback( 5005): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/VideoCapabilities( 6224): Unsupported mime video/mp43
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5779): noConnectivity : true
,W/VideoCapabilities( 6224): Unsupported mime video/sorenson
,W/VideoCapabilities( 6224): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6224): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6224): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6224): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6224): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6224): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1017): Killing 5310:com.google.android.gm/u0a101 (adj 15): empty #31
,I/vclib   ( 6224): onServiceConnected
,W/Babel   ( 6224): Attempted to change video mute state without an active call.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10101/pid_5310/cgroup.procs: No such file or directory
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6269): MountEmulatedStorage()
,E/Zygote  ( 6269): v2
I/libpersona( 6269): KNOX_SDCARD checking this for 10002
I/libpersona( 6269): KNOX_SDCARD not a persona
,I/SELinux ( 6269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6269 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6269): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 2044): nl80211: Received scan results (7 BSSes),
I/wpa_supplicant( 2044): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 2044): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 2044): Trying to associate with  'G700'
I/wpa_supplicant( 2044): Re-associate with C0.AA.48
D/WifiMonitor( 1017): didn't find BSSID Trying to associate with SSID 'NG700'
I/wpa_supplicant( 2044): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 2044): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/TimaKeyStoreProvider( 6269): TimaSignature is unavailable
,D/ActivityThread( 6269): Added TimaKeyStore provider
,E/SMD     (  287): DCD OFF
,I/ActivityManager( 1017): Killing 5088:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,E/wpa_supplicant( 2044): Cmd 35605 not handled
,I/wpa_supplicant( 2044): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Tethering( 1017): interfaceStatusChanged wlan0, false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/wpa_supplicant( 2044): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2044): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 2044): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 2044): Associated with C0.AA.48
I/wpa_supplicant( 2044): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2044): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2044): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 2044): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2044): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2044): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 2044): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceStatusChanged wlan0, true
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true,
I/wpa_supplicant( 2044): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2044): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 2044): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 2044): Blacklist: Clear (temp) ,
I/wpa_supplicant( 2044): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1017): interfaceStatusChanged wlan0, true
E/Tethering( 1017): No numeric data
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1017): mCursor = null
,E/Zygote  ( 6286): MountEmulatedStorage()
E/Zygote  ( 6286): v2
I/libpersona( 6286): KNOX_SDCARD checking this for 1000,
I/libpersona( 6286): KNOX_SDCARD not a persona
,I/SELinux ( 6286): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6286): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6286): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6286 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1017): clearTetheredNotification()
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
D/HotspotTile( 1175): updateTetherState():false, false
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked() took 4ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit,
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/WifiNative-wlan0( 1017): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1017): setLastSelectedConfiguration -1,
,D/ConnectivityService( 1017): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1017): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider( 6286): TimaSignature is unavailable
,D/ActivityThread( 6286): Added TimaKeyStore provider
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  277): Setting iface cfg
W/libprocessgroup( 1017): failed to open /acct/uid_10044/pid_5088/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1017): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1017): mCursor = null
,E/WifiNative-wlan0( 1017): do suspend false
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled,
D/SecContentProvider2( 1017): mCursor = null
,I/DIAGMON_AGENT( 6286): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 6286): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6286): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,I/DIAGMON_AGENT( 6286): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6286): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6286): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6286): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 6303): MountEmulatedStorage()
,E/Zygote  ( 6303): v2
I/libpersona( 6303): KNOX_SDCARD checking this for 10009
I/libpersona( 6303): KNOX_SDCARD not a persona
,I/SELinux ( 6303): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6303): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6303): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6303 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 4165:com.sec.spp.push/u0a35 (adj 15): empty #31
,E/SQLiteLog( 1707): (10) POSIX Error : 11 SQLite Error : 3850
,D/TimaKeyStoreProvider( 6303): TimaSignature is unavailable
,D/ActivityThread( 6303): Added TimaKeyStore provider
,E/dhcpcd  ( 6318): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6318): version 5.5.6 starting,
,E/dhcpcd  ( 6318): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/ActivityManager( 1017): Killing 5292:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3603): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 23 03:07:48 GMT+01:00 2015
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3603): KLMSAbstractReciever(): onReceive().END.
I/dhcpcd  ( 6318): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6318): wlan0: sendmsg: Cannot assign requested address
,I/dhcpcd  ( 6318): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6318): bssid match
,I/dhcpcd  ( 6318): wlan0: rebinding lease of 192.168.1.137
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3603): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3603): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3603): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3603): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3603): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  ( 6326): MountEmulatedStorage()
,E/Zygote  ( 6326): v2
I/libpersona( 6326): KNOX_SDCARD checking this for 10034
I/libpersona( 6326): KNOX_SDCARD not a persona
,I/SELinux ( 6326): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/KLMS-2.5.183: ( 3603): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3603): StateImplV2(): networkChangeListener().END,
,I/SELinux ( 6326): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6326 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 6326): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3603): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6326): TimaSignature is unavailable
,D/ActivityThread( 6326): Added TimaKeyStore provider
,I/SO_AGENT( 6326): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5809): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_4165/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_5292/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 6047): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6047): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6047): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6047): [SLFUCHKMGR] constructor called
I/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5809): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 6047): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6047): [OR] == isSIMCardReady false ==
,I/SA      ( 6047): [SCU] == networkStateCheck == false
I/SA      ( 6047): [OR] onReceive END
,I/ActivityManager( 1017): Killing 5731:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,I/dhcpcd  ( 6318): wlan0: acknowledged 192.168.1.137 from 192.168.1.1
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1544): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1544): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1544): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1544): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1544): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1544): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1544): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6343): MountEmulatedStorage(),
E/Zygote  ( 6343): v2
I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6343 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/libpersona( 6343): KNOX_SDCARD checking this for 10125,
I/libpersona( 6343): KNOX_SDCARD not a persona
,I/SELinux ( 6343): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6343): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6343): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 6318): wlan0: leased 192.168.1.137 for 86400 seconds,
,D/TimaKeyStoreProvider( 6343): TimaSignature is unavailable,
D/ActivityThread( 6343): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10100/pid_5731/cgroup.procs: No such file or directory
,W/ResourcesManager( 6343): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6343): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6343): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6343): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
I/QuickConnect( 6343): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6343): PeriphStartReceiver.onReceive - no need to start
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6369 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5384:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,E/Zygote  ( 6369): MountEmulatedStorage(),
I/libpersona( 6369): KNOX_SDCARD checking this for 10145
E/Zygote  ( 6369): v2
I/libpersona( 6369): KNOX_SDCARD not a persona
I/SELinux ( 6369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6369): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6369): TimaSignature is unavailable
,D/ActivityThread( 6369): Added TimaKeyStore provider
,W/ResourcesManager( 6369): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
W/ResourcesManager( 6369): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6369): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6369): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6369): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_10015/pid_5384/cgroup.procs: No such file or directory
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/BadgeProvider( 5924): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 5924): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5924): sendNotify, [notify] : null
D/Launcher.Model( 1501): reloadBadges entered.
D/BadgeProvider( 5924): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5924): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5924): update, [UpdateCount] : 1
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/WifiNative-wlan0( 1017): do suspend true
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,E/Zygote  ( 6402): MountEmulatedStorage(),
,E/Zygote  ( 6402): v2
,I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6402 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
E/WifiStateMachine( 1017): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1017): VerifyingLinkState enter
I/libpersona( 6402): KNOX_SDCARD checking this for 1000,
I/libpersona( 6402): KNOX_SDCARD not a persona
,I/SELinux ( 6402): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6402): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6402): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/WifiNative-wlan0( 1017): callSECApiInt - ID [210]
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1017): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1017): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/art     (  305): Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 687us total 29.735ms
,E/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/TimaKeyStoreProvider( 6402): TimaSignature is unavailable,
D/ActivityThread( 6402): Added TimaKeyStore provider
,D/ConnectivityService( 1017): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1017): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1017): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 18.154ms
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,E/WifiStateMachine( 1017): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiStateMachine( 1017): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService( 1017): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1017): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 1017): LTETest block dns file not exists
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling,
I/WifiTrafficPoller( 1017): mBoosterFLAG : 0
I/WifiTrafficPoller( 1017): current booster mode : FullMode
,D/WifiNative-wlan0( 1017): callSECApiVoid - ID [212],
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 17.633ms
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 1017):    accepting network in place of null
,D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1478): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1478): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1017): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1017): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1017): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,V/NetworkStats( 1017): updateIfacesLocked()
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked() took 7ms
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 65131(3MB) AllocSpace objects, 9(192KB) LOS objects, 33% free, 27MB/41MB, paused 6.494ms total 197.102ms
,I/ActivityManager( 1017): Killing 5764:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/SecurityLogAgent( 6402): KnoxConfiguration : Current State = 1
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/SecurityLogAgent( 6402): KnoxConfiguration : Current State Mapping Found 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
D/SecurityLogAgent( 6402): StateMachine : Current State = 1
,D/SecurityLogAgent( 6402): StateMachine : Changed Current State = 1
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6425): MountEmulatedStorage(),
E/Zygote  ( 6425): v2
I/libpersona( 6425): KNOX_SDCARD checking this for 10159
I/libpersona( 6425): KNOX_SDCARD not a persona
I/SELinux ( 6425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6425 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6425): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 5794:com.samsung.helphub/1000 (adj 15): empty #31
I/System.out( 1017): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/TimaKeyStoreProvider( 6425): TimaSignature is unavailable
,D/ActivityThread( 6425): Added TimaKeyStore provider
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Dec 2015 02:07:49 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450836469725], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450836469707]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
,D/ConnectivityService( 1017): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ActivityManager( 1017): Killing 5398:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6443): MountEmulatedStorage(),
E/Zygote  ( 6443): v2
I/libpersona( 6443): KNOX_SDCARD checking this for 10035
I/libpersona( 6443): KNOX_SDCARD not a persona
I/SELinux ( 6443): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6443 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
,I/SELinux ( 6443): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SELinux ( 6443): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6224): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6224): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6224): (HTTPLog)-Static: isShipBuild true
I/System.out( 6224): (HTTPLog)-Thread-1081-459265353: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6224): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10104
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10104
,D/TimaKeyStoreProvider( 6443): TimaSignature is unavailable
D/ActivityThread( 6443): Added TimaKeyStore provider
,I/GLSUser ( 1707): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1707): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1707): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1707): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/libprocessgroup( 1017): failed to open /acct/uid_10091/pid_5764/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5794/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_5398/cgroup.procs: No such file or directory
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6224): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/SPPClientService( 6443): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6443): [SystemStateMoniter] Current Time : 92552
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
E/SPPClientService( 6443): ============PushLog. commonIsShipBuild. stop!
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SPPClientService( 6443): [PushClientApplication] Push log off : This is Ship build version
E/SPPClientService( 6443): [SystemStateMoniter] No Connect : true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
W/Kids    ( 1854): [AccountUtils] Account not ready
W/Kids    ( 1854): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1854): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1854): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1854): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1854): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1854): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1854): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1854): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1854): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1854): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1854): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1854): 	at java.lang.Thread.run(Thread.java:818)
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
I/Babel   ( 6224): connection state changed from UNKNOWN to CONNECTED
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6443): PushLog.txt file is not deleted.
D/SPPClientService( 6443): PushLog.txt file is not deleted.
D/SPPClientService( 6443): ============PushLog. stop!
,E/Zygote  ( 6462): MountEmulatedStorage()
I/libpersona( 6462): KNOX_SDCARD checking this for 10113
E/Zygote  ( 6462): v2
I/libpersona( 6462): KNOX_SDCARD not a persona
I/SELinux ( 6462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6462 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6462): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 6443): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 6462): TimaSignature is unavailable
,D/ActivityThread( 6462): Added TimaKeyStore provider
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/GAv4    ( 6462): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6462):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6462):   adb logcat -s GAv4
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6462): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6462): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6462): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6462): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3029): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 5005): type=WIFI subType= reason=null isConnected=true
,W/GAv4    ( 6462): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6462): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,W/GAv4    ( 6462): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6462): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6462): Time to load native libraries: 2 ms (timestamps 3029-3031)
I/LibraryLoader( 6462): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6462): Binding Chromium to main looper Looper (main, tid 1) {6dfac80}
,I/LibraryLoader( 6462): Expected native library version number "",actual native library version number ""
I/chromium( 6462): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6462): Initializing chromium process, singleProcess=true
,W/art     ( 6462): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6462): ApplicationContext is null in ApplicationStatus
,W/chromium( 6462): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6462): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6462): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6462): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6462): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6462): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6462): Local Branch: 
I/Adreno-EGL( 6462): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6462): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6462):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/SQLiteLog( 1707): (10) POSIX Error : 11 SQLite Error : 3850
,W/AudioManagerAndroid( 6462): Requires BLUETOOTH permission
,I/NSApplication( 6462): Starting up...
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6520 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1017): Killing 5885:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
E/Zygote  ( 6520): MountEmulatedStorage()
E/Zygote  ( 6520): v2
I/ActivityManager( 1017): Killing 5862:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #32
,I/libpersona( 6520): KNOX_SDCARD checking this for 10081
,I/libpersona( 6520): KNOX_SDCARD not a persona
I/SELinux ( 6520): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6520): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6520): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6520): TimaSignature is unavailable
,D/ActivityThread( 6520): Added TimaKeyStore provider
,D/ConnectivityService( 1017): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/libprocessgroup( 1017): failed to open /acct/uid_10156/pid_5885/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10152/pid_5862/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 6157): notifyNetworkActivated
,W/ContextImpl( 6157): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6157): AutoUpdateManager:IDLE:execute
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,D/InitializeManagerStateMachine( 6157): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6157): exit::IDLE
D/InitializeManagerStateMachine( 6157): entry::NETWORK_CHECK
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/InitializeManagerStateMachine( 6157): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6157): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6157): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6157): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6157): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6157): entry::SUCCESS
D/hcjo    ( 6157): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 3566): Starting #10
,I/Hs20UtilService( 3566): Message received 5007
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/hcjo    ( 6157): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6157): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,D/InitializeManagerStateMachine( 6157): exit::SUCCESS
D/InitializeManagerStateMachine( 6157): entry::IDLE
,I/ActivityManager( 1017): Killing 5465:com.android.vending/u0a28 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3566): Starting #11
,I/Hs20UtilService( 3566): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3566): Starting #12
,I/Hs20UtilService( 3566): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3566): Starting #13
,I/Hs20UtilService( 3566): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1017): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1017): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5779): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5779): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5779): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5779): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
I/splitIntent( 1017): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1017): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 5005): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  256): id=15 createSurf (1x1),1 flag=4, Uoast
,W/libprocessgroup( 1017): failed to open /acct/uid_10028/pid_5465/cgroup.procs: No such file or directory
,D/PowerManagerService( 1017): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,D/SRIB_DCS( 1175): log_dcs ThreadedRenderer::initialize entered! 
,I/DIAGMON_AGENT( 6286): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6286): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6286): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6286): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/DBG_POLICYDM( 5809): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5809): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5809): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5809): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6303): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6303): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.183: ( 3603): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 23 03:07:51 GMT+01:00 2015
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3603): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3603): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3603): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3603): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3603): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3603): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3603): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3603): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3603): NetworkChangeOperations(): uploadRequestLog().START 
,I/DBG_POLICYDM( 5809): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.183: ( 3603): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3603): StateImplV2(): networkChangeListener().END
,I/DBG_POLICYDM( 5809): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 6047): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6047): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6047): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/KLMS-2.5.183: ( 3603): KLMSIntentService(): onDestroy()
,I/SA      ( 6047): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6047): [OR] == isSIMCardReady false ==
I/DBG_POLICYDM( 5809): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 6047): [SCU] == networkStateCheck == true
,I/SA      ( 6047): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6047): isChinaCountryCode : false
,I/SA      ( 6047): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6047): [OR] == networkStateCheck true ==
,I/SA      ( 6047): [OR] GetMyCountryZoneTask
,I/SA      ( 6047): [OR] onReceive END
,I/SA      ( 6047): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/accuweather( 1544): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5809): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/SA      ( 6047): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
I/SA      ( 6047): [SSP] query invoked
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1017): mCursor = null
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
I/DBG_POLICYDM( 5809): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/accuweather( 1544): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
D/accuweather( 1544): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1544): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1544): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 6047): [TPMU] GetMccFromDB : null
I/SA      ( 6047): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6047): [TPM] isNoProxy(default) : true
,E/DBG_POLICYDM( 5809): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,E/File    ( 6047): fail readDirectory() errno=2
,D/accuweather( 1544): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1544): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6343): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6343): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6343): PeriphStartReceiver.onReceive - no need to start
I/DBG_POLICYDM( 5809): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6402): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6402): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6402): StateMachine : Current State = 1
,D/SecurityLogAgent( 6402): StateMachine : Changed Current State = 1
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6443): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6443): [SystemStateMoniter] Current Time : 94043
,E/SPPClientService( 6443): [SystemStateMoniter] No Connect : false
,I/System.out( 6224): (HTTPLog)-Static: isSBSettingEnabled false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
D/PackageManager( 1017): [MSG] MCS_UNBIND
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6157): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6157): execute::IDLE:EXECUTE
,I/GLSUser ( 1707): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1707): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1707): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1707): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/InitializeManagerStateMachine( 6157): exit::IDLE
,D/InitializeManagerStateMachine( 6157): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6157): execute::NETWORK_CHECK:NETWORK_STATE_OK
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/InitializeManagerStateMachine( 6157): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6157): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6157): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6157): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6157): entry::SUCCESS
D/hcjo    ( 6157): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6157): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,D/hcjo    ( 6157): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/InitializeManagerStateMachine( 6157): exit::SUCCESS
,D/InitializeManagerStateMachine( 6157): entry::IDLE
,E/SMD     (  287): DCD OFF
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Kids    ( 1854): [AccountUtils] Account not ready
W/Kids    ( 1854): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1854): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1854): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1854): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1854): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1854): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1854): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1854): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1854): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1854): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1854): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1854): 	at java.lang.Thread.run(Thread.java:818)
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/PowerManagerService( 1017): [PWL] Off : 15s ago
,I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1854, ws=null) (elapsedTime=57907)
,I/SA      ( 6047): [RC New] Execute method=[GET] start
,I/SA      ( 6047): [RC New] Security=[true]
,I/System.out( 6047): Thread-1045(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6047): Thread-1045(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6047): Thread-1045(ApacheHTTPLog):isShipBuild true
I/System.out( 6047): Thread-1045(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6047): Thread-1045(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10041
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10041
,I/ActivityManager( 1017): Killing 4472:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10012/pid_4472/cgroup.procs: No such file or directory
,I/SA      ( 6047): [RC New] [v2liruge] api execute + 673
,I/SA      ( 6047): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6047): AsyncTask #1 calls detatch()
I/SA      ( 6047): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6047): [OCP] update openData : PL
,I/SA      ( 6047): [TPMU] getNetworkMcc : 
,I/SA      ( 6047): [SCU] saveMccToPreferece Start
,I/SA      ( 6047): [SCU] RegionMCC : 260
,I/SA      ( 6047): [SSP] query invoked
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6140): BLE supported!!
I/jxcore-log( 6140): 
,I/SA      ( 6047): [TPMU] GetMccFromDB : null
,I/SA      ( 6047): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6047): [SCU] saveMccToPreferece End
,I/SA      ( 6047): [RC New] executeRequest [v2liruge] end. 739
,I/SA      ( 6047): [RC New] Execute end
I/SA      ( 6047): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6047): [OR] GetMyCountryZoneTask Success
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/dhcpcd  ( 6318): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6318): wlan0: sendmsg: Cannot assign requested address
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4245, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging,
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push,
,E/SMD     (  287): DCD OFF
,I/SurfaceFlinger(  256): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  256): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1017): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 97152,
,D/PowerManagerService( 1017): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0)
,D/PowerManagerService( 1017): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10054}) (elapsedTime=3479)
,D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295,
D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{34eb2025 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService},
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5779): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5779): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5779): [GetString-S]
,I/ReactiveServiceManager( 5779): Supported : 1
,D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 12
,D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 12
,E/terrier ( 1017): handleString: Failed to handle string(-4)
,E/terrier ( 1017): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5779): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5779): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5779): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5779): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5779): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5779): [ensureRegistration] - No Samsung account
,D/SSRM:n  ( 1017): SIOP:: AP = 360
,I/dhcpcd  ( 6318): wlan0: sending IPv6 Router Solicitation
,V/AlarmManager( 1017): waitForAlarm result :4
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,E/SMD     (  287): DCD OFF
,D/GCM     ( 1707): Connected,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1707): Message class com.google.f.a.a.p
,V/AlarmManager( 1017): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6572): MountEmulatedStorage()
E/Zygote  ( 6572): v2
I/libpersona( 6572): KNOX_SDCARD checking this for 10028
,I/libpersona( 6572): KNOX_SDCARD not a persona
,I/SELinux ( 6572): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6572 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,V/AlarmManager( 1017): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1017): <AppSync3 Whitelist>,
V/AlarmManagerEXT( 1017): (AppSync) ### 0 added ###
,I/SELinux ( 6572): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
E/SELinux ( 6572): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/TimaKeyStoreProvider( 6572): TimaSignature is unavailable
,D/ActivityThread( 6572): Added TimaKeyStore provider
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/PreloadUpdateManagerStateMachine( 6157): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6157): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6157): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/SViewCoverWidget( 1175): Weather changed action :android.intent.action.TIME_TICK
,D/hcjo    ( 6157): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/SViewCoverWidget( 1175): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/hcjo    ( 6157): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 6157): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/PreloadUpdateManagerStateMachine( 6157): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6157): entry::IDLE
,D/SViewCoverWidget( 1175): getCheckCurrent: result = 0
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1175): cityId=
,D/SViewCoverWidget( 1175): cityId=
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/Finsky  ( 6572): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6572): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 6318): wlan0: sending IPv6 Router Solicitation,
I/dhcpcd  ( 6318): wlan0: no IPv6 Routers available
,E/Zygote  ( 6607): MountEmulatedStorage()
,E/Zygote  ( 6607): v2
I/libpersona( 6607): KNOX_SDCARD checking this for 10012
I/libpersona( 6607): KNOX_SDCARD not a persona
,I/SELinux ( 6607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6607 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6607): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Settings( 6572): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6572): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TimaKeyStoreProvider( 6607): TimaSignature is unavailable
,D/ActivityThread( 6607): Added TimaKeyStore provider
,W/ResourcesManager( 6607): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6607): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 6572): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6572): [1] 2.run: Finished loading 1 libraries.
,I/MultiDex( 6607): VM with version 2.1.0 has multidex support
I/MultiDex( 6607): install
I/MultiDex( 6607): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6572): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/JNIHelp ( 6607): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 6572): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ActivityThread( 6607): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6607): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@32706967: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6607): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1017): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1017): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1017): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1707): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1707): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6631): MountEmulatedStorage()
E/Zygote  ( 6631): v2
I/libpersona( 6631): KNOX_SDCARD checking this for 10012
I/libpersona( 6631): KNOX_SDCARD not a persona
,I/SELinux ( 6631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6631): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6631 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6631): TimaSignature is unavailable
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 6631): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6631): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6631): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1854): Restart initialization of location
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6157): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6157): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6157): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/hcjo    ( 6157): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 6157): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/MultiDex( 6631): VM with version 2.1.0 has multidex support
I/MultiDex( 6631): install
I/MultiDex( 6631): VM has multidex support, MultiDex support library is disabled.
,D/PreloadUpdateManagerStateMachine( 6157): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6157): entry::IDLE
,V/JNIHelp ( 6631): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityThread( 6631): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6631): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@32706967: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6631): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1017): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1017): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
D/WearableService( 6631): callingUid 10012, callindPid: 6631
I/splitIntent( 1017): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1707): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1707): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/Finsky  ( 6572): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1854): Restart initialization of location
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 42769(2MB) AllocSpace objects, 7(152KB) LOS objects, 33% free, 27MB/41MB, paused 2.696ms total 170.376ms
,E/MDM     ( 1632): [172] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1632): [172] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1707): Explicit concurrent mark sweep GC freed 12701(661KB) AllocSpace objects, 5(180KB) LOS objects, 40% free, 10MB/17MB, paused 1.204ms total 43.033ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1707): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1707): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1707): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1707): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6572): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6572): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6572): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager( 1017): Killing 5940:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 5744:com.android.mms/u0a46 (adj 15): empty #32,
,D/CountryDetector( 1017): No listener is left
,W/libprocessgroup( 1017): failed to open /acct/uid_10046/pid_5744/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10047/pid_5940/cgroup.procs: No such file or directory
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6572): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1707): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1707): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1707): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1707): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6572): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1707): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1707): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1707): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1707): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1707): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1707): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1707): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1707): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6572): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1707): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1707): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1707): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1707): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6572): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6572): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6572): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6572): [1] DailyHygiene.reschedule: Scheduling new run in 752 minutes (failures=5)
,D/DeviceConnectionService( 1632): client connected with version: 7571000
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4255, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2644): Disconnected process message: 10,
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1017): !@Sync 3
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1017): waitForAlarm result :4
,D/SSRM:n  ( 1017): SIOP:: AP = 330
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 30s ago
,I/ActivityManager( 1017): Killing 5960:com.wsomacp/u0a25 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10025/pid_5960/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/FactoryTest( 5558): Not factory mode
,D/FactoryTest( 5558): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5558): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5558): still no open session command from host, so toast
,W/ContextImpl( 5558): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5558): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5558): Timeline: Activity_launch_request id:com.android.settings time:117765
,E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus left window: 6140
,E/MTPRx   ( 5558): started activity for popup
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5558): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5558): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5558): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5558): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5558): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5558): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5558): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus entered window: 6140
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1017): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@4307372 attribute=null, token = android.os.BinderProxy@10493a5
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SettingsReceiverActivity( 5558): dev.kiessupport is : TRUE
,D/PhoneWindow( 5558): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5558): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,V/ActivityThread( 6140): updateVisibility : ActivityRecord{133eee69 token=android.os.BinderProxy@d98cd33 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6140): Timeline: Activity_idle id: android.os.BinderProxy@d98cd33 time:117946,
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1017): SIOP:: AP = 320
,W/ActivityManager( 1017): mDVFSHelper.release()
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1707): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1707): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1707): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1707): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6572): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6572): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6572): [1] 5.onFinished: Scheduling replication attempt 3.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
,I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/SSRM:n  ( 1017): SIOP:: AP = 310
,I/PowerManagerService( 1017): [PWL] Off : 50s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4263, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1017): !@Sync 4
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4,
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1707): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1707): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1707): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1707): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6572): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6572): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6572): [1] 5.onFinished: Scheduling replication attempt 4.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 75s ago
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4266, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,V/AlarmManager( 1017): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
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
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1175): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1175): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SViewCoverWidget( 1175): getCheckCurrent: result = 0
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1175): cityId=
,D/SViewCoverWidget( 1175): cityId=
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1707): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1707): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1707): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1707): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6572): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6572): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6572): [1] 5.onFinished: Scheduling replication attempt 5.,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4245, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 5
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4267, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1017): stay LED for charging
,I/MotionRecognitionService( 1017): Plugged
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 105s ago
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,V/AlarmManager( 1017): waitForAlarm result :4
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1707): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1707): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1707): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1707): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6572): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6572): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6572): [1] 5.onFinished: Giving up after 6 failures.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 6
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1707): Vacuum at: now=1450836582569 tag=VacuumService
,I/GoogleURLConnFactory( 1707): Using platform SSLCertificateSocketFactory
,W/Uploader( 1707): No account for auth token provided
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1707): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1707): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1707): (HTTPLog)-Static: isShipBuild true
I/System.out( 1707): (HTTPLog)-Thread-202-925883384: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1707): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1707): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1707): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1707, getuid(): 10012
,I/qtaguid ( 1707): Tagging socket 61 with tag 120100000000{4609,0} for uid -1, pid: 1707, getuid(): 10012
,W/Uploader( 1707): No account for auth token provided
,I/System.out( 1707): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1707): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1707, getuid(): 10012
,W/Uploader( 1707): No account for auth token provided
,I/System.out( 1707): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1707): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1707, getuid(): 10012
,W/Uploader( 1707): No account for auth token provided
,I/System.out( 1707): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1707): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1707, getuid(): 10012
,W/Uploader( 1707):  no longer exists, so no auth token.
,I/System.out( 1707): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1707): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1707, getuid(): 10012
,W/Uploader( 1707): No account for auth token provided
,I/System.out( 1707): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1707): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1707, getuid(): 10012
,E/SQLiteLog( 1707): (10) POSIX Error : 11 SQLite Error : 3850
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4257, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 140s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/Watchdog( 1017): !@Sync 7
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 8
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 180s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 9
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 225s ago
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1017): initializing...
,I/TLC_TIMA_PKM_initialize( 1017): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1017): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 13
,I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1017): Trustlet response is completed
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4267, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 10
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10,
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/jxcore-log( 6140): Connected to the server!
I/jxcore-log( 6140): 
,I/chromium( 6140): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 11
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,I/PowerManagerService( 1017): [PWL] Off : 275s ago
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4267, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging,
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 12
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,V/AlarmManager( 1017): No more alarm at this time.nowELAPSED=402642 batch.start=1000285
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 50733(3MB) AllocSpace objects, 121(1937KB) LOS objects, 33% free, 27MB/41MB, paused 2.508ms total 170.578ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1707): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1707): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1707): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1707): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1707): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PanelView( 1175): There is/are notification(s) 
,D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
W/GLSActivity( 1707): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1707): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1707): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1707): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1707): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1707): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1707): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 6572): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6572): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6572): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6572): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6572): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6572): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6572): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 6572): Ignoring header User-Agent because its value was null.
,I/System.out( 6572): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6572): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6572): (HTTPLog)-Static: isShipBuild true
I/System.out( 6572): (HTTPLog)-Thread-1148-368750965: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6572): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10028
,I/System.out( 6572): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  287): DCD OFF
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 13,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 330s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1017): stay LED for charging
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1017): !@Sync 14
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2644): Disconnected process message: 10,
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2644): Disconnected process message: 10,
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/jxcore-log( 6140): --- start :testFindPeers.js---
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): testFindPeers created [object Object]
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): serverPort is 8876
I/jxcore-log( 6140): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): start: Peer ID: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT1715
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6140): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6140): initialize: My bluetooth address is 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6140): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): startListeningForIncomingConnections: Starting...
,D/BluetoothSocket( 6140): bindListen(): myUserId = 0
,W/BluetoothAdapter( 6140): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6140): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,D/BluetoothSocket( 6140): bindListen(), new LocalSocket 
D/BluetoothSocket( 6140): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6140): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b8baab8
,D/BluetoothSocket( 6140): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): start: OK
I/io.jxcore.node.ConnectionHelper( 6140): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6140): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): start: Peer ID: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT1715
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6140): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6140): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): start: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6140): start: Identity string: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState add service
,D/WifiP2pService( 1017): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6140): start: OK
I/jxcore-log( 6140): StartBroadcasting started ok
I/jxcore-log( 6140): 
I/chromium( 6140): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
D/WifiP2pService( 1017): InactiveState{ what=139265 }
,I/io.jxcore.node.ConnectionHelper( 6140): onConnectionManagerStateChanged: RUNNING
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onWifiStateChanged: State changed to 2
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6140): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6140): onDiscoveryManagerStateChanged: RUNNING
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): P2P device discovery started successfully
D/WifiP2pService( 1017): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 1 device(s) discovered
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 6140): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service request added successfully
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2462
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 2 device(s) discovered
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 2044): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service discovery started successfully
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 4 device(s) discovered
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 4 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 4 device(s) discovered
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,I/wpa_supplicant( 2044): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1017): !@Sync 15
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7770","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
,I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
,D/io.jxcore.node.ConnectionHelper( 6140): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770] is available
,I/jxcore-log( 6140): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT7770","peerAvailable":true}]
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): weAreDoneNow
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): done, now sending data to server
I/jxcore-log( 6140): 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 390s ago,
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6438","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438],
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6140): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] is available
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): restart: Restarting...
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState add service request
D/WifiP2pManager( 6140): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service request added successfully
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service discovery started successfully
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 6140): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] is available
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 6140): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 6140): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] is available
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1694","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 6140): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694] is available
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4263, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 290,
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 8 device(s) discovered,
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80,
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): restart: Restarting...
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState add service request
D/WifiP2pManager( 6140): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service request added successfully
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service discovery started successfully,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86,
D/io.jxcore.node.ConnectionHelper( 6140): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6438","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] already in the list, will not add again
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 6140): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003] is available
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/bootchecker(  314): bootchecker wake up!!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], add/update: true
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, gr,oupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c,
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4257, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): restart: Restarting...
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pManager( 6140): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service request added successfully
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service discovery started successfully,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003] already in the list, will not add again,
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac,
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] already in the list, will not add again
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7855","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6140): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] is available
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,E/Watchdog( 1017): !@Sync 16
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): InactiveState{ what=139307 },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): restart: Restarting...
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pManager( 6140): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1017): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service request added successfully
D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service discovery started successfully,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1017): !@Sync 17,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerLost: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
D/io.jxcore.node.ConnectionHelper( 6140): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770] removed
D/io.jxcore.node.ConnectionHelper( 6140): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770] not available
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 2044): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,I/PowerManagerService( 1017): [PWL] Off : 455s ago
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1017): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462,
I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.Disc,overyManager( 6140): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): restart: Restarting...
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 6140): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service request added successfully
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service discovery started successfully,
,E/SMD     (  287): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/WifiP2pService( 1017): P2pEnabledState receive service response,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6438","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7770","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6140): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770] is available
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac,
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1017): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6140): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] is available
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 11 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 },
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d,
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 614,0): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4265, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 },
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): restart: Restarting...
D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 6140): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service request added successfully
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service discovery started successfully,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437,
D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1694","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
,W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694] already in the list, will not add again
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] already in the list, will not add again
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
,D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017): Received list of peers.
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], add/update: true
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/Watchdog( 1017): !@Sync 18
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 },
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  287): DCD OFF,
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 },
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): restart: Restarting...
,D/WifiP2pService( 1017): InactiveState{ what=139301 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pManager( 6140): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1017): P2pEnabledState add service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service request added successfully
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,D/WifiP2pService( 1017): InactiveState{ what=139310 },
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiP2pService( 1017): P2pEnabledState{ what=139310 },
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiP2pService( 1017): P2pEnabledState discover services
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service discovery started successfully
,D/SSRM:n  ( 1017): SIOP:: AP = 290,
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430],
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7855","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] already in the list, will not add again
,E/SMD     (  287): DCD OFF,
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7770","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
,I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6438","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1694","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
,I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462,
,D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6140): teardown
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): testFindPeers stopped
I/jxcore-log( 6140): 
,I/io.jxcore.node.ConnectionHelper( 6140): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6140): shutdown
D/BluetoothSocket( 6140): close() in, this: android.bluetooth.BluetoothSocket@34acba64, channel: 6, state: LISTENING
D/BluetoothSocket( 6140): close() this: android.bluetooth.BluetoothSocket@34acba64, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b8baab8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1bae04cdmSocket: android.net.LocalSocket@121cb182 impl:android.net.LocalSocketImpl@d96093 fd:FileDescriptor[111]
D/BluetoothSocket( 6140): Closing mSocket: android.net.LocalSocket@121cb182 impl:android.net.LocalSocketImpl@d96093 fd:FileDescriptor[111]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6140): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6140): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6140): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6140): release: The given listener does not exist in the list
D/WifiP2pService( 1017): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6140): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): setState: NOT_STARTED
,I/jxcore-log( 6140): StopBroadcasting went ok
I/jxcore-log( 6140): 
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 1017): P2pEnabledState clear service
,I/chromium( 6140): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6140): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6140): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 2044): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6140): Local services cleared successfully
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
,I/jxcore-log( 6140): --- start :testSendData.js---
I/jxcore-log( 6140): 
D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pService( 1017): remove channel information from framework
I/jxcore-log( 6140): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log( 6140): 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,I/jxcore-log( 6140): check server
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): serverPort is 36800
I/jxcore-log( 6140): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): start: Peer ID: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT1715
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6140): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6140): initialize: My bluetooth address is 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6140): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): startListeningForIncomingConnections: Starting...
,D/BluetoothSocket( 6140): bindListen(): myUserId = 0
,W/BluetoothAdapter( 6140): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6140): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,D/BluetoothSocket( 6140): bindListen(), new LocalSocket 
D/BluetoothSocket( 6140): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6140): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@342320c9
D/BluetoothSocket( 6140): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): start: OK
I/io.jxcore.node.ConnectionHelper( 6140): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): start: Peer ID: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT1715
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6140): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6140): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6140): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): start: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6140): start: Identity string: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: INITIALIZED,
D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): start: Starting P2P device discovery...
D/WifiP2pService( 1017): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiP2pService( 1017): add a new client
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): start: OK
D/WifiP2pService( 1017): InactiveState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): setState: RUNNING
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 },
I/io.jxcore.node.ConnectionHelper( 6140): start: OK
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/jxcore-log( 6140): StartBroadcasting started ok
,I/jxcore-log( 6140): 
I/jxcore-log( 6140): null
I/jxcore-log( 6140): 
D/WifiP2pService( 1017): discovery change broadcast true
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiP2pService( 1017): InactiveState{ what=139268 }
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
D/WifiP2pService( 1017): InactiveState{ what=147493 }
,I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
I/jxcore-log( 6140): 2015-12-23T02:15:57.900Z SendDataTCPServer.js: TCP/IP server is bound to port: 36800
I/jxcore-log( 6140): 
D/WifiP2pService( 1017): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): P2P device discovery stopped successfully
I/chromium( 6140): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6140): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onWifiStateChanged: State changed to 2
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6140): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6140): Local service added successfully
I/wpa_supplicant( 2044): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WifiP2pService( 1017): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: RESTARTING
,I/Atfwd_Daemon(  317): Stop the daemon....
,E/SMD     (  287): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1017): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): P2P device discovery started successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pManager( 6140): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service request added successfully
D/WifiP2pService( 1017): P2pEnabledState add service request
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service discovery started successfully
,E/Watchdog( 1017): !@Sync 19
,I/wpa_supplicant( 2044): p2p0: P2P: Reject scan trigger since one is already pending
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/IOP_DB_BT( 2644): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 2644): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2644): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2644): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2644): db_query_execute: result 1
,D/IOP_DB_BT( 2644): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 2644): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2644): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2644): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2644): db_query_execute: result 1
W/bt-btif ( 2644): info:x10
D/        ( 2644): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2644): aclStateChangeCallback: Device is NULL,
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2644): getBtEnabledContainers(): btContainers = []
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2644): getBtEnabledContainers(): btContainers = []
,D/BluetoothUtils( 2644): getBtEnabledContainers(): btContainers = []
,I/BluetoothBondStateMachine( 2644): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2644): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2644): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 2644): isSecureModeOn:false
I/BluetoothBondStateMachine( 2644): Entering PendingCommandState State
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1175):  onBluetoothPairedDevicesChanged:
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1175):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1316): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6884): MountEmulatedStorage(),
E/Zygote  ( 6884): v2
I/libpersona( 6884): KNOX_SDCARD checking this for 10100
I/libpersona( 6884): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/.GMHFPReceiver: pid=6884 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 6884): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6884): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6884): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6884): TimaSignature is unavailable
,D/ActivityThread( 6884): Added TimaKeyStore provider
,D/btif_config_util( 2644): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2644): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2644): Failed to remove device: 7C:F9:0E:34:8A:A0
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2644): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2644): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1175):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1175):  handleUpdatestate:false name:null
,E/BluetoothHeadset( 6884): BTStateChangeCB is registed
,D/BluetoothHeadset( 6884): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6884): BluetoothHeadset service is binded
D/GMFPReceiver( 6884): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 6884): jangil::setProperties()
,D/HidService( 2644): getHidService(): returning com.android.bluetooth.hid.HidService@26a47314
D/GMFPReceiver( 6884): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = bluetooth_input_device_priority_7C:F9:0E:34:8A:A0
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SettingsProvider( 1017): name = Wearable0001
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10100
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/HidService( 2644): Saved priority 7C:F9:0E:34:8A:A0 = -1
D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_7C:F9:0E:34:8A:A0
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_7C:F9:0E:34:8A:A0
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/BluetoothBondStateMachine( 2644): StableState(): Entering Off State
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10100
,D/GMFPReceiver( 6884): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10100
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10100
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GMFPReceiver( 6884): ::::::::Wearable0002::false
D/GMFPReceiver( 6884): onServiceConnected() : 1
D/GMFPReceiver( 6884): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 5987:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1316): onReceive
,W/bt-btif ( 2644): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2644): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2644): bta_dm_pm_ssr:2, lat:1200
D/BluetoothSocket( 6140): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@1212f1fc
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
E/BluetoothRemoteDevices( 2644): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6140): Incoming connection accepted
,D/BluetoothSocket( 6140): getInputStream(): myUserId = 0
,E/BluetoothHeadset( 6884): BTStateChangeCB is registed
,D/BluetoothHeadset( 6884): doBind(): CallingUid(myUserHandle) = 0
D/BluetoothSocket( 6140): getOutputStream(): myUserId = 0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6140): Incoming connection initialized (thread ID: 1084)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6140): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6140): Entering thread (ID: 1084)
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6884): BluetoothHeadset service is binded
,D/GMFPReceiver( 6884): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 6884): jangil::setProperties()
,D/GMFPReceiver( 6884): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10100
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 6884): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10100
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 6884): ::::::::Wearable0002::false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/GMFPReceiver( 6884): onServiceConnected() : 1
D/GMFPReceiver( 6884): mBluetoothHeadset = true
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6140): onBytesRead: Read 82 bytes successfully (thread ID: 1084)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6140): Got valid identity from [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6140): onBytesWritten: 83 bytes successfully written (thread ID: 1084)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6140): removeThreadFromList: Removing thread with ID 1084
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6140): Handshake thread disposed (thread ID: 1084)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6140): Exiting thread (ID: 1084)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/io.jxcore.node.ConnectionHelper( 6140): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/io.jxcore.node.ConnectionHelper( 6140): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] already in the list, will not add again,
E/SMD     (  287): DCD OFF
W/libprocessgroup( 1017): failed to open /acct/uid_10053/pid_5987/cgroup.procs: No such file or directory
,D/BluetoothSocket( 6140): getInputStream(): myUserId = 0,
,D/BluetoothSocket( 6140): getOutputStream(): myUserId = 0
I/io.jxcore.node.ConnectionHelper( 6140): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], created successfully
,D/io.jxcore.node.ConnectionHelper( 6140): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 6140): Entering thread (ID: 1085)
,D/EnterpriseController(  277): uids 10175
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10175
,I/io.jxcore.node.IncomingSocketThread( 6140): Local host address: localhost/127.0.0.1, port: 36800,
D/io.jxcore.node.IncomingSocketThread( 6140): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6140): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6140): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6140): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 6140): Exiting thread (ID: 1085)
I/jxcore-log( 6140): 2015-12-23T02:16:15.726Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6140): 
,D/io.jxcore.node.StreamCopyingThread( 6140): Entering thread (ID: 1086, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6140): Entering thread (ID: 1087, name: Receiver)
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/jxcore-log( 6140): 2015-12-23T02:16:16.718Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data,
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.721Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.725Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.728Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.732Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.736Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.769Z SendDataTCPServer.js: TCP/IP server has received 20432 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.795Z SendDataTCPServer.js: TCP/IP server has received 22456 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.829Z SendDataTCPServer.js: TCP/IP server has received 36624 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.833Z SendDataTCPServer.js: TCP/IP server has received 38648 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.836Z SendDataTCPServer.js: TCP/IP server has received 40672 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.869Z SendDataTCPServer.js: TCP/IP server has received 56864 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.874Z SendDataTCPServer.js: TCP/IP server has received 60912 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.881Z SendDataTCPServer.js: TCP/IP server has received 62936 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.919Z SendDataTCPServer.js: TCP/IP server has received 77104 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.945Z SendDataTCPServer.js: TCP/IP server has received 79128 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.949Z SendDataTCPServer.js: TCP/IP server has received 81152 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.989Z SendDataTCPServer.js: TCP/IP server has received 99368 bytes of data
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:16.994Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6140): 
,W/bt-btif ( 2644): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 6140): Either failed to read from the output stream or write to the input stream (thread ID: 1087, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6140): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6140): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 6140): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1085
,D/io.jxcore.node.IncomingSocketThread( 6140): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6140): doStop: Thread ID: 1087
,D/io.jxcore.node.IncomingSocketThread( 6140): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6140): doStop: Thread ID: 1086
D/io.jxcore.node.IncomingSocketThread( 6140): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 6140): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6140): Either failed to read from the output stream or write to the input stream (thread ID: 1086, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6140): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6140): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6140): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6140): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6140): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6140): close() in, this: android.bluetooth.BluetoothSocket@1cb40085, channel: 6, state: CONNECTED
D/BluetoothSocket( 6140): close() this: android.bluetooth.BluetoothSocket@1cb40085, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3caaeeda, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a4f0bmSocket: android.net.LocalSocket@239b31e8 impl:android.net.LocalSocketImpl@33b92001 fd:FileDescriptor[114]
D/BluetoothSocket( 6140): Closing mSocket: android.net.LocalSocket@239b31e8 impl:android.net.LocalSocketImpl@33b92001 fd:FileDescriptor[114]
D/BluetoothSocket( 6140): close() in, this: android.bluetooth.BluetoothSocket@1cb40085, channel: 6, state: CLOSED
D/BluetoothSocket( 6140): close() in, this: android.bluetooth.BluetoothSocket@1cb40085, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6140): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6140): Exiting thread (ID: 1087, name: Receiver)
,W/bt-rfcomm( 2644): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0,
D/io.jxcore.node.ConnectionHelper( 6140): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6140): Exiting thread (ID: 1086, name: Sender)
W/bt-rfcomm( 2644): RFCOMM_DisconnectInd LCID:0x41
,I/jxcore-log( 6140): 2015-12-23T02:16:17.147Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6140): 
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 },
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): restart: Restarting...
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState add service request
D/WifiP2pManager( 6140): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service request added successfully
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service discovery started successfully
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7855","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] already in the list, will not add again
,E/bt-btm  ( 2644): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2644): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothUtils( 2644): getBtEnabledContainers(): btContainers = []
D/KeyguardViewMediator( 1175): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.ACL_DISCONNECTED
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
E/BluetoothEventManager( 1316): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1175): isGear1: device is not B1!
,D/BluetoothAdapterService( 2644): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316662f2,
D/BtConfig.SecureMode( 2644): isSecureModeOn:false
D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
I/BluetoothPbapService( 2644): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6122): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6122): Bluetooth Device Name: S5-1
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
,I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6140): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270] is available
I/jxcore-log( 6140): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT4270","peerAvailable":true}]
I/jxcore-log( 6140): 
I/jxcore-log( 6140): Found peer : samsung-SM-A300FU_PT4270, Available: true
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): startWithNextDevice
I/jxcore-log( 6140): 
I/jxcore-log( 6140): device[1]: 08:EC:A9:50:75:41
I/jxcore-log( 6140): 
I/jxcore-log( 6140): 2015-12-23T02:16:21.125Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:21.126Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6140): 
I/jxcore-log( 6140): 2015-12-23T02:16:21.126Z SendDataConnector.js: do connect now
I/jxcore-log( 6140): 
,I/io.jxcore.node.ConnectionHelper( 6140): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 6140): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6140): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6140): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 6140): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6140): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 1088)
,D/BluetoothUtils( 6140): isSocketAllowedBySecurityPolicy start : device null
D/BluetoothSocket( 6140): connect(): myUserId = 0
W/BluetoothAdapter( 6140): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2644): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/IOP_DB_BT( 2644): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 2644): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 2644): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 2644): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 2644): db_query_execute: result 1
,D/BluetoothSocket( 6140): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 525s ago,
I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=2644, ws=null) (elapsedTime=577)
,D/IOP_DB_BT( 2644): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 2644): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2644): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2644): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2644): db_query_execute: result 1
,W/bt-btif ( 2644): info:x10
D/        ( 2644): remote version info [08:ec:a9:50:75:41]: 7, f, 610c
,E/BluetoothRemoteDevices( 2644): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2644): getBtEnabledContainers(): btContainers = []
,W/bt-sdp  ( 2644): process_service_search_attr_rsp
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2644): getBtEnabledContainers(): btContainers = []
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.CLASS_CHANGED
,D/BluetoothUtils( 2644): getBtEnabledContainers(): btContainers = []
,I/BluetoothBondStateMachine( 2644): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,D/BluetoothTile( 1175):  onBluetoothPairedDevicesChanged:
,I/BluetoothBondStateMachine( 2644): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11,
D/BluetoothTile( 1175):  handleUpdatestate:false name:null
D/BtConfig.SecureMode( 2644): isSecureModeOn:false
,I/BluetoothBondStateMachine( 2644): Entering PendingCommandState State
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
E/bt-btif ( 2644): check_cod: remote_cod = 0x5a020c
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.BOND_STATE_CHANGED
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1316): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 6884): BTStateChangeCB is registed
,D/BluetoothHeadset( 6884): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6884): BluetoothHeadset service is binded
,D/GMFPReceiver( 6884): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 6884): jangil::setProperties()
,D/GMFPReceiver( 6884): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10100
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 6884): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10100
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 6884): ::::::::Wearable0002::false
,D/GMFPReceiver( 6884): onServiceConnected() : 1
D/GMFPReceiver( 6884): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,E/SMD     (  287): DCD OFF
,D/btif_config_util( 2644): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2644): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2644): Failed to remove device: 08:EC:A9:50:75:41
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2644): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2644): isSecureModeOn:false
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1175):  onBluetoothPairedDevicesChanged:
,D/HidService( 2644): getHidService(): returning com.android.bluetooth.hid.HidService@26a47314
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/SettingsProvider( 1017): name = bluetooth_input_device_priority_08:EC:A9:50:75:41
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/HidService( 2644): Saved priority 08:EC:A9:50:75:41 = -1
D/BluetoothTile( 1175):  handleUpdatestate:false name:null
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_08:EC:A9:50:75:41
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/BluetoothNotiBroadcastReceiver( 1316): onReceive
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_08:EC:A9:50:75:41
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/BluetoothBondStateMachine( 2644): StableState(): Entering Off State
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 6884): BTStateChangeCB is registed
,D/BluetoothHeadset( 6884): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
E/BluetoothHeadset( 6884): BluetoothHeadset service is binded
D/GMFPReceiver( 6884): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 6884): jangil::setProperties()
,D/GMFPReceiver( 6884): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10100
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 6884): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10100
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 6884): ::::::::Wearable0002::false
,D/GMFPReceiver( 6884): onServiceConnected() : 1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
D/GMFPReceiver( 6884): mBluetoothHeadset = true
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,W/bt-btif ( 2644): new conn_srvc id:26, app_id:1
W/bt-btif ( 2644): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2644): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2644): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): onSocketConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6140): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1088)
,D/BluetoothSocket( 6140): getInputStream(): myUserId = 0
,D/BluetoothSocket( 6140): getOutputStream(): myUserId = 0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6140): onBytesWritten: 83 bytes successfully written (thread ID: 1089)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6140): Outgoing connection initialized (*handshake* thread ID: 1089)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6140): Exiting thread (thread ID: 1088)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6140): Entering thread (ID: 1089)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6140): onBytesRead: Read 83 bytes successfully (thread ID: 1089)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6140): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): onHandshakeSucceeded: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
,I/io.jxcore.node.ConnectionHelper( 6140): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/io.jxcore.node.ConnectionHelper( 6140): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270] already in the list, will not add again
,D/BluetoothSocket( 6140): getInputStream(): myUserId = 0
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6140): Exiting thread (ID: 1089)
,D/BluetoothSocket( 6140): getOutputStream(): myUserId = 0
,I/io.jxcore.node.ConnectionHelper( 6140): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 6140): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6140): Entering thread (ID: 1090)
,D/io.jxcore.node.OutgoingSocketThread( 6140): Server socket local port: 41638
,I/io.jxcore.node.OutgoingSocketThread( 6140): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6140): onListeningForIncomingConnections: Outgoing connection is using port 41638 (peer ID: 08:EC:A9:50:75:41)
,I/jxcore-log( 6140): 2015-12-23T02:16:25.199Z SendDataConnector.js: CLIENT connected to 41638, error: null
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:25.200Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6140): 
,I/io.jxcore.node.OutgoingSocketThread( 6140): Incoming data from address: /127.0.0.1, port: 41638
,D/io.jxcore.node.OutgoingSocketThread( 6140): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6140): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6140): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6140): 2015-12-23T02:16:25.212Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6140): 
,I/io.jxcore.node.OutgoingSocketThread( 6140): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 6140): Exiting thread (ID: 1090)
,D/io.jxcore.node.StreamCopyingThread( 6140): Entering thread (ID: 1092, name: Receiver),
,D/io.jxcore.node.StreamCopyingThread( 6140): Entering thread (ID: 1091, name: Sender)
,D/        ( 2644): PORT_WriteDataCO: tx queue is full,tx.queue_size:10216,tx.queue.count:11,available:25520
,I/jxcore-log( 6140): 2015-12-23T02:16:25.773Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6140): 
,D/        ( 2644): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:15400
,I/jxcore-log( 6140): 2015-12-23T02:16:25.813Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6140): 
,D/        ( 2644): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:8316
,I/jxcore-log( 6140): 2015-12-23T02:16:25.889Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6140): 
,D/        ( 2644): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:1232
,I/jxcore-log( 6140): 2015-12-23T02:16:25.930Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:25.934Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:25.967Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:25.971Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:26.071Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:26.109Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:26.110Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): oneRoundDownNow
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:26.113Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:16:26.114Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6140): 
,D/io.jxcore.node.ConnectionHelper( 6140): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
,I/io.jxcore.node.ConnectionHelper( 6140): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
,I/io.jxcore.node.OutgoingSocketThread( 6140): close
D/io.jxcore.node.OutgoingSocketThread( 6140): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6140): doStop: Thread ID: 1092
,D/io.jxcore.node.OutgoingSocketThread( 6140): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6140): doStop: Thread ID: 1091
,D/io.jxcore.node.OutgoingSocketThread( 6140): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6140): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6140): Either failed to read from the output stream or write to the input stream (thread ID: 1091, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6140): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6140): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6140): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6140): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6140): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 6140): close() in, this: android.bluetooth.BluetoothSocket@2f591ea6, channel: 6, state: CONNECTED
D/BluetoothSocket( 6140): close() this: android.bluetooth.BluetoothSocket@2f591ea6, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2aacd0e7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@ce58494mSocket: android.net.LocalSocket@a96bb3d impl:android.net.LocalSocketImpl@3d687f32 fd:FileDescriptor[115],
D/BluetoothSocket( 6140): Closing mSocket: android.net.LocalSocket@a96bb3d impl:android.net.LocalSocketImpl@3d687f32 fd:FileDescriptor[115]
,W/io.jxcore.node.StreamCopyingThread( 6140): Either failed to read from the output stream or write to the input stream (thread ID: 1092, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6140): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 6140): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket( 6140): close() in, this: android.bluetooth.BluetoothSocket@2f591ea6, channel: 6, state: CLOSED,
,D/BluetoothSocket( 6140): close() in, this: android.bluetooth.BluetoothSocket@2f591ea6, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6140): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6140): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 6140): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6140): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 6140): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
I/jxcore-log( 6140): 2015-12-23T02:16:26.129Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 6140): 
D/io.jxcore.node.ConnectionHelper( 6140): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6140): Exiting thread (ID: 1092, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6140): Exiting thread (ID: 1091, name: Sender)
,I/jxcore-log( 6140): ---- round done--------
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): startWithNextDevice
I/jxcore-log( 6140): 
,W/bt-btif ( 2644): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/bt-btm  ( 2644): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2644): btm_sec_disconnected - Clearing Pending flag
D/KeyguardViewMediator( 1175): Received android.bluetooth.device.action.ACL_DISCONNECTED
D/BluetoothUtils( 2644): getBtEnabledContainers(): btContainers = []
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1316): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2644): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316662f2
,D/BtConfig.SecureMode( 2644): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,D/KeyguardViewMediator( 1175): isGear1: device is not B1!
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothPbapService( 2644): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6122): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6122): Bluetooth Device Name: A3-1
,E/SMD     (  287): DCD OFF
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1017): !@Sync 20
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4266, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
E/SMD     (  287): DCD OFF
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 290,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 2044): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): P2P device discovery started successfully,
D/WifiP2pService( 1017): discovery change broadcast true,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): restart: Restarting...,
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pManager( 6140): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1017): P2pEnabledState add service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service request added successfully,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 2044): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service discovery started successfully
,I/wpa_supplicant( 2044): p2p0: P2P: Reject scan trigger since one is already pending,
I/wpa_supplicant( 2044): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270] already in the list, will not add again
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7855","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] already in the list, will not add again
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 },
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): restart: Restarting...
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 6140): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service request added successfully
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 },
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service discovery started successfully
,E/Watchdog( 1017): !@Sync 21
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998],
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
,W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] already in the list, will not add again
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4267, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging,
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4266, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1017): !@Sync 22,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: RESTARTING
D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 2044): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,I/PowerManagerService( 1017): [PWL] Off : 600s ago
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/jxcore-log( 6140): timeout now
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): weAreDoneNow, resultArray.length: 1
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): sendReportNow
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): done, now sending data to server
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): 2015-12-23T02:17:37.905Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6140): 
,E/SMD     (  287): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1017): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered,
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): DefaultState{ what=139283 },
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/WifiDisplayController( 1017): Received list of peers.
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
,D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): restart: Restarting...
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/WifiP2pManager( 6140): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service request added successfully
D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b,
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 2044): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service discovery started successfully
,I/wpa_supplicant( 2044): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 2044): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7770","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6438","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 6140): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145] is available
I/jxcore-log( 6140): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"LGE-Nexus 5_PT8145","peerAvailable":true}]
I/jxcore-log( 6140): 
I/jxcore-log( 6140): Found peer : LGE-Nexus 5_PT8145, Available: true
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): startWithNextDevice
I/jxcore-log( 6140): 
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.,
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 290,
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, ,wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270] already in the list, will not add again
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2044): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): restart: Restarting...
,D/WifiP2pService( 1017): InactiveState{ what=139301 },
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
D/WifiP2pManager( 6140): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service request added successfully
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/WifiP2pService( 1017): InactiveState{ what=139310 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13],
I/wpa_supplicant( 2044): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service discovery started successfully
,E/SMD     (  287): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
,I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1017): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/io.jxcore.node.ConnectionHelper( 6140): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6140): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] already in the list, will not add again
,I/jxcore-log( 6140): teardown
I/jxcore-log( 6140): 
,I/jxcore-log( 6140): testSendData stopped
I/jxcore-log( 6140): 
,I/io.jxcore.node.ConnectionHelper( 6140): stop,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6140): shutdown
D/BluetoothSocket( 6140): close() in, this: android.bluetooth.BluetoothSocket@eeb9483, channel: 6, state: LISTENING
D/BluetoothSocket( 6140): close() this: android.bluetooth.BluetoothSocket@eeb9483, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@342320c9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e05600mSocket: android.net.LocalSocket@2ab8ce39 impl:android.net.LocalSocketImpl@389b5c7e fd:FileDescriptor[113]
,D/BluetoothSocket( 6140): Closing mSocket: android.net.LocalSocket@2ab8ce39 impl:android.net.LocalSocketImpl@389b5c7e fd:FileDescriptor[113]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6140): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6140): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6140): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6140): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6140): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): stop: Stopping P2P device discovery...
D/WifiP2pService( 1017): InactiveState{ what=139298 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): setState: NOT_INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): onIsWifiPeerDiscoveryStartedChanged: false,
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 },
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): stopWifiPeerDiscovery: Stopped,
D/WifiP2pService( 1017): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6140): release: No more listeners, de-initializing...
D/WifiP2pService( 1017): InactiveState{ what=139268 }
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6140): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6140): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6140): setState: NOT_STARTED
I/jxcore-log( 6140): StopBroadcasting went ok
I/jxcore-log( 6140): 
I/jxcore-log( 6140): 2015-12-23T02:17:57.160Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 6140): 
I/wpa_supplicant( 2044): P2P-FIND-STOPPED 
D/WifiP2pService( 1017): InactiveState{ what=139307 }
I/chromium( 6140): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6140): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6140): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6140): Local services cleared successfully
D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pService( 1017): remove channel information from framework
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,I/jxcore-log( 6140): ****TEST TOOK:  ms ****
I/jxcore-log( 6140): 
I/jxcore-log( 6140): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6140): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6140): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6140): Service requests cleared successfully
D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4266, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1439): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1439): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2644): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,D/AndroidRuntime( 6958): 
D/AndroidRuntime( 6958): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6958): CheckJNI is OFF
,D/AndroidRuntime( 6958): readGMSProperty: start
D/AndroidRuntime( 6958): readGMSProperty: already setted!!
D/AndroidRuntime( 6958): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6958): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6958): readGMSProperty: end
D/AndroidRuntime( 6958): addProductProperty: start
,E/AffinityControl( 6958): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6958): Calling main entry com.android.commands.pm.Pm,
,D/PackageManager( 1017): START PACKAGE DELETE: observer{565973234},
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1017): !@killApplicatoin: 10175, uninstall pkg,
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 6140:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1017): Skipping PackageSetting{326d29ad com.example.hello/10176} due to missing metadata
,E/SMD     (  287): DCD OFF
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{aba30d3 u0 com.test.thalitest/.MainActivity t229}
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{aba30d3 u0 com.test.thalitest/.MainActivity t229 f}
,W/ActivityManager( 1017): Duplicate finish request for ActivityRecord{aba30d3 u0 com.test.thalitest/.MainActivity t229 f}
,I/WindowState( 1017): WIN DEATH: Window{2a8d537a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (6/8)
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (-2/8)
I/SurfaceFlinger(  256): id=14 Removed NainActivit (-2/8)
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,D/InputDispatcher( 1017): Focus left window: 6140
,D/InputDispatcher( 1017): Focused application released
,I/DBG_DM  ( 3029): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/art     ( 6122): Explicit concurrent mark sweep GC freed 11029(697KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 9MB/12MB, paused 865us total 47.392ms
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 3029): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 11
,E/SamsungIME( 1781): mOCRHelper is null
,I/art     ( 4007): Explicit concurrent mark sweep GC freed 2896(173KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 6MB/11MB, paused 751us total 54.537ms
,I/DBG_DM  ( 3029): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,W/GeofencerStateMachine( 1632): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 3029): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3029): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 11
,I/DBG_DM  ( 3029): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3029): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,D/RegisteredComponentCache( 1467): Collect Tech packages for Knox
,D/PersonaManager( 1467): isKioskContainerExistOnDevice
,I/KLMS-2.5.183: ( 3603): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 23 03:17:57 GMT+01:00 2015
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 3029): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3603): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1017): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
I/splitIntent( 1017): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1017): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3603): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3603): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3603): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/DBG_DM  ( 3029): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,E/Zygote  ( 6972): MountEmulatedStorage()
E/Zygote  ( 6972): v2
I/libpersona( 6972): KNOX_SDCARD checking this for 10094,
I/libpersona( 6972): KNOX_SDCARD not a persona
,I/SELinux ( 6972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6972): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6972 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.183: ( 3603): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3603): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.183: ( 3603): KLMSIntentService(): listeningToPackageRemoved().START
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,I/KLMS-2.5.183: ( 3603): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 32495(3MB) AllocSpace objects, 12(212KB) LOS objects, 33% free, 27MB/41MB, paused 2.984ms total 177.800ms
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/art     ( 1017): WaitForGcToComplete blocked for 146.667ms for cause Explicit
D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,I/DBG_DM  ( 3029): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 11
,I/DBG_DM  ( 3029): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3029): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3029): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3029): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3029): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/TimaKeyStoreProvider( 6972): TimaSignature is unavailable
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/ActivityThread( 6972): Added TimaKeyStore provider
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,I/DBG_DM  ( 3029): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/SurfaceFlinger(  256): id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1017): Focus entered window: 3029
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/SRIB_DCS( 3029): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,V/ActivityThread( 3029): updateVisibility : ActivityRecord{538aac4 token=android.os.BinderProxy@1bdbe1e5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/PersonaManager( 1467): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1467): empty dynamic service
,I/KLMS-2.5.183: ( 3603): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.183: ( 3603): KLMSIntentService(): onDestroy()
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 6140 uid 10175
,D/elm:15183( 6972): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 6972): ELMEngine.ELMEngine( context ).
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/elm:15183( 6972): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,D/SamsungIME( 1781): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 6972): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/Timeline( 3029): Timeline: Activity_idle id: android.os.BinderProxy@1bdbe1e5 time:700761
,D/elm:15183( 6972): ElmAgentService : onCreate()
,D/elm:15183( 6972): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 6972): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6972): MDMBridge.getInstance()
,D/elm:15183( 6972): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15183( 6972): MDMBridge.getAllLicenseInfoFromSDK()
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,D/RCPManagerService( 1017): PackageReceiver onReceive()
,I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/elm:15183( 6972): ElmAgentService : onDestroy().
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1017): PackageRemovalReceiver::onReceive Enter
I/ActivityManager( 1017): Killing 5846:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,D/OTPFW   ( 1017): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1017): DBIntegrity::getInstance - New instance created
,W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{37831d09 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t228} time:700784
,D/OTPFW   ( 1017): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
,I/OTPFW   ( 1017): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1017): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10175
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,V/EnterpriseBillingPolicy( 1017): uID is 10175
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
D/TaskPersister( 1017): removeObsoleteFile: deleting file=229_task.xml
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=228_task.xml
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,D/PanelView( 1175): There is/are notification(s) 
,I/PCWCLIENTTRACE_PushUtil( 5779): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5779): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5779): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5779): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 12092(677KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 10.990ms total 233.511ms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6992): MountEmulatedStorage()
I/libpersona( 6992): KNOX_SDCARD checking this for 10032
E/Zygote  ( 6992): v2
I/libpersona( 6992): KNOX_SDCARD not a persona,
I/SELinux ( 6992): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6992): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6992 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/SELinux ( 6992): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/TimaKeyStoreProvider( 6992): TimaSignature is unavailable
,D/ActivityThread( 6992): Added TimaKeyStore provider
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1017): delete codoeFile: 
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
I/AASA_removePackage( 1017): UID=10175 Target=com.test.thalitest
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 1017): result of delete: 1{565973234}
,I/FeatureConfig( 6992): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/AndroidRuntime( 6958): Shutting down VM
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/Zygote  ( 7009): MountEmulatedStorage()
E/Zygote  ( 7009): v2
I/libpersona( 7009): KNOX_SDCARD checking this for 10038
I/libpersona( 7009): KNOX_SDCARD not a persona
,I/SELinux ( 7009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 7009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 7009): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=7009 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 6008:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/art     (  305): Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 664us total 21.934ms
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 7009): TimaSignature is unavailable
,D/ActivityThread( 7009): Added TimaKeyStore provider
,I/CrashAnrDetector( 1017): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 1017): clearDefaults: com.test.thalitest
W/libprocessgroup( 1017): failed to open /acct/uid_10038/pid_5846/cgroup.procs: No such file or directory
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 16.923ms
W/ResourcesManager( 6992): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_6008/cgroup.procs: No such file or directory
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 16.926ms
,W/ResourcesManager( 7009): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7009): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6992): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6992): system/finder_cp/cpdata.xml file not found
,I/SL_DEBUG( 7009): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 7009): isLoggable:: SL_DEBUG_EXIST = false
,W/art     ( 6958): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7009): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7009): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,I/SA      ( 6047): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6047): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10175 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7040): MountEmulatedStorage()
E/Zygote  ( 7040): v2
I/libpersona( 7040): KNOX_SDCARD checking this for 10044
I/libpersona( 7040): KNOX_SDCARD not a persona
,I/SELinux ( 7040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/SELinux ( 7040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 7040): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7040 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 6030:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 7040): TimaSignature is unavailable
,D/ActivityThread( 7040): Added TimaKeyStore provider
,W/ResourcesManager( 7040): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7040): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7040): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7040): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7040): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7040): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7040): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.

```
