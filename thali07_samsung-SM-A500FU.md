#### Test 549702617cfd775_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
I/DBG_POLICYDM( 5877): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5877): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
--------- beginning of system
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/Mms/ArtClassLoader( 5810): init [DONE] art
D/ComposerPerformance( 5810): 1452520883326 ms / [DONE] Composer constructor
E/CII     ( 5810): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5810): ReservationManager()
I/Mms/ReservationManager( 5810): resetAfterConnected()
I/DBG_POLICYDM( 5877): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
D/TP/MmsSmsProvider( 1457): query,matched:7, calling pid = 5810
D/TP/MmsSmsProvider( 1457): match 7:Elapsed time : 2.883 ms
I/Mms/ReservationManager( 5810): getReservedSendMessageCount(): retMessageCount=0
D/Mms/Conversation( 5810): [start]    init() consume time = 58.668282
D/TP/MmsSmsProvider( 1457): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1457): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1457): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1457): sUpgradeVersion = 0, db.getVersion() = 81
D/TP/MmsSmsProvider( 1457): delete threadId: 9223372036854775807
D/Mms/MmsApp( 5810): [end]    onCreate() consume time = 8.643489
D/TP/MmsSmsProvider( 1457): need read changed broadcast:false
D/Mms/Conversation( 5810): [end]    init consume time = 3.345417
D/Mms/MessagingNotification( 5810): [start]    init() consume time = 2.199115
D/Mms/MessagingNotification( 5810): [end]    init consume time = 1.908437
D/TP/MmsSmsProvider( 1457): query,matched:0, calling pid = 5810
V/TP/MmsSmsProvider( 1457): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1457): match 0:Elapsed time : 0.791 ms
D/Mms/SpamFilter( 5810): [start]    SpamFilter fill() begin consume time = 3.321667
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/TP/MmsSmsProvider( 1457): query,matched:400, calling pid = 5810
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5990): MountEmulatedStorage()
E/Zygote  ( 5990): v2
I/libpersona( 5990): KNOX_SDCARD checking this for 10072
I/libpersona( 5990): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5990 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/SELinux ( 5990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/Mms/Synchronizer( 5810): [start]    doSync consume time = 30.204375
D/Mms/SpamFilter( 5810): [end]    SpamFilter fill() finished consume time = 1.374843
I/SELinux ( 5990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5990): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TP/MmsSmsProvider( 1457): update, matched:300, calling pid = 5810
V/TP/MmsSmsProvider( 1457): syncDBData start
V/TP/MmsSmsProvider( 1457): syncDBData sms end
V/TP/MmsSmsProvider( 1457): syncDBData mms end
V/TP/MmsSmsProvider( 1457): syncDBData end
D/Mms/Synchronizer( 5810): [end]    doSync consume time = 7.542657
D/Mms/DownloadManager( 5810): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5810): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5810): getSubId is called
D/Mms/TelephonyUtils( 5810): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5810): getTelephonyProperty is called
D/Mms/DownloadManager( 5810): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5810): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5810): auto download without roaming -> true
D/Mms/DownloadManager( 5810): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5810): mAutoDownload ------> true
D/TimaKeyStoreProvider( 5990): TimaSignature is unavailable
D/ActivityThread( 5990): Added TimaKeyStore provider
D/Mms/FreeMessageStatusReceiver( 5810): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 5990): onCreate
D/BadgeProvider( 5990): DatabaseHelper
E/Zygote  ( 6005): MountEmulatedStorage()
E/Zygote  ( 6005): v2
I/libpersona( 6005): KNOX_SDCARD checking this for 10047
I/libpersona( 6005): KNOX_SDCARD not a persona
I/SELinux ( 6005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6005 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/DBG_POLICYDM( 5877): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
D/Mms/FreeMessageReceiverService( 5810): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5810): onHandleIntent: ACTION_PACKAGE_ADDED
I/SELinux ( 6005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6005): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 3725:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/ActivityManager( 1017): Killing 5233:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #32
D/Mms/MessagingNotification( 5810): checkBadgeCount unreadCount=0 badgeCount=0
D/TimaKeyStoreProvider( 6005): TimaSignature is unavailable
D/TP/SmsProvider( 1457): query,matched:26, calling pid = 5810
D/ActivityThread( 6005): Added TimaKeyStore provider
D/TP/SmsProvider( 1457): match 26:Elapsed time : 1.586 ms
D/TP/MmsSmsProvider( 1457): query,matched:6, calling pid = 5810
D/TP/MmsSmsProvider( 1457): match 6:Elapsed time : 1.946 ms
W/ResourcesManager( 6005): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6005): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6005): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6023): MountEmulatedStorage()
E/Zygote  ( 6023): v2
I/libpersona( 6023): KNOX_SDCARD checking this for 10025
I/libpersona( 6023): KNOX_SDCARD not a persona
I/SELinux ( 6023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6023 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/SELinux ( 6023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
D/TimaKeyStoreProvider( 6023): TimaSignature is unavailable
D/ActivityThread( 6023): Added TimaKeyStore provider
I/ActivityManager( 1017): Killing 4072:com.google.android.talk/u0a104 (adj 15): empty #31
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5233/cgroup.procs: No such file or directory
W/ResourcesManager( 6023): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/libprocessgroup( 1017): failed to open /acct/uid_10042/pid_3725/cgroup.procs: No such file or directory
I/OMACP   ( 6023): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/MyFiles ( 6005): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager( 1017): Killing 5507:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
W/libprocessgroup( 1017): failed to open /acct/uid_10104/pid_4072/cgroup.procs: No such file or directory
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/Omacp( 5810): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/ConfigFetchService( 1947): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/ConfigFetchService( 1947): launchTask
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/TactileAssist( 1017): enable value -1
I/TactileAssist( 1017): internal enable value -1
I/TactileAssist( 1017): intensity value -1
I/TactileAssist( 1017): saveAppList value true
I/TactileAssist( 1017): List of disabled apps :
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/ChimeraCfgMgr( 1947): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1947): Module APK com.google.android.play.games already loaded
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1017): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
V/ConfigFetchTask( 1947): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VnUzRysUPPPXWr8cOc5NUCJSTyHRVAzQWaeay-hXKPCQT0Lf7czAHvE7FOxCJOKw39misaRLyRB8uwXJFzlhPrEMcaLIGfzDi1ApbyP6dPdetfR4jFw4cNOYOCLW-5FJ8ree0j3AHkxZucLwTDuEWCuUHXbT2iXx1xPF7250Jh9YbpMZ-kN87Pr7cLXomlU4oGYQ5h8HwQ3WO6MtTx-l5YdbBPjZwfuyOQ6Nq1B6xeqaMz_XM
D/ChimeraCfgMgr( 1947): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1947): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1947): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1947): No vision deps
E/Zygote  ( 6049): MountEmulatedStorage()
I/libpersona( 6049): KNOX_SDCARD checking this for 10053
E/Zygote  ( 6049): v2
I/libpersona( 6049): KNOX_SDCARD not a persona
I/SELinux ( 6049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6049): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6049 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6049): TimaSignature is unavailable
D/ActivityThread( 6049): Added TimaKeyStore provider
W/libprocessgroup( 1017): failed to open /acct/uid_10069/pid_5507/cgroup.procs: No such file or directory
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/PeopleContactsSync( 1947): CP2 sync disabled
I/GoogleURLConnFactory( 1947): Using platform SSLCertificateSocketFactory
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 6049): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/System.out( 1947): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1947): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1947): (HTTPLog)-Static: isShipBuild true
I/System.out( 1947): (HTTPLog)-Thread-278-1014812942: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1947): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
I/PowerManagerService( 1017): [PWL] Off : 5s ago
I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1947, ws=null) (elapsedTime=47337)
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1017, ws=WorkSource{10054}) (elapsedTime=646)
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'Config Service fetch' (uid=10012, pid=1947, ws=WorkSource{10175 com.test.thalitest}) (elapsedTime=165)
D/Compatibility( 6049): onReceive() it will make start service
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
I/GAv4    ( 5830): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5830):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5830):   adb logcat -s GAv4
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Compatibility( 6049): onHandleIntent()
D/Compatibility( 6049): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
D/Compatibility( 6049): found: 2
E/Zygote  ( 6070): MountEmulatedStorage()
E/Zygote  ( 6070): v2
I/libpersona( 6070): KNOX_SDCARD checking this for 1000
I/libpersona( 6070): KNOX_SDCARD not a persona
I/SELinux ( 6070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6070 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6070): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/GAv4    ( 5830): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/Compatibility( 6049): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6049): skipping ResolveInfo{1fca28eb com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6049): considering ResolveInfo{324d3648 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6049): default: com.sec.android.app.soundalive.SAControlPanelActivity
I/System.out( 1947): KnoxVpnUidStorageknoxVpnSupported API value returned is false
W/GAv4    ( 5830): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
D/TimaKeyStoreProvider( 6070): TimaSignature is unavailable
D/Compatibility( 6049): enabling receiver ResolveInfo{351a3ce1 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ActivityThread( 6070): Added TimaKeyStore provider
D/Compatibility( 6049): enabling receiver ResolveInfo{11beaa06 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6049): enabling receiver ResolveInfo{2ca068c7 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/qtaguid ( 1947): Tagging socket 95 with tag 40b00000000{1035,0} for uid -1, pid: 1947, getuid(): 10012
D/Compatibility( 6049): enabling receiver ResolveInfo{31236ef4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6049): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
W/BaseAppContext( 1947): Using Auth Proxy for data requests.
W/BaseAppContext( 1947): Using Auth Proxy for data requests.
I/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
I/DBG_POLICYDM( 5877): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
W/ContextImpl( 6070): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/AnalyticsTrackerProxyImpl( 5830): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
E/Zygote  ( 6090): MountEmulatedStorage()
I/libpersona( 6090): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6090): v2
I/libpersona( 6090): KNOX_SDCARD not a persona
I/SELinux ( 6090): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6090): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6090): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6090 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5522:com.sec.knox.bridge/1000 (adj 15): empty #31
I/qtaguid ( 1947): Tagging socket 108 with tag 40b00000000{1035,0} for uid -1, pid: 1947, getuid(): 10012
I/SL_DEBUG( 5935): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5935): isLoggable:: SL_DEBUG_EXIST = false
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
I/art     (  309): Explicit concurrent mark sweep GC freed 8745(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 653us total 28.853ms
W/GAv4    ( 5830): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/BaseAppContext( 1947): Using Auth Proxy for data requests.
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 19.485ms
D/TimaKeyStoreProvider( 6090): TimaSignature is unavailable
D/ActivityThread( 6090): Added TimaKeyStore provider
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 658us total 17.037ms
W/BaseAppContext( 1947): Using Auth Proxy for data requests.
W/BaseAppContext( 1947): Using Auth Proxy for data requests.
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
W/ResourcesManager( 6090): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5935): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/BaseAppContext( 1947): Using Auth Proxy for data requests.
E/Zygote  ( 6109): MountEmulatedStorage()
I/libpersona( 6109): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6109): v2
I/libpersona( 6109): KNOX_SDCARD not a persona
I/SELinux ( 6109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6109): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/art     ( 5830): Suspending all threads took: 19.055ms
I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6109 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5539:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5522/cgroup.procs: No such file or directory
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/TimaKeyStoreProvider( 6109): TimaSignature is unavailable
D/ActivityThread( 6109): Added TimaKeyStore provider
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5935): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/qtaguid ( 1947): Untagging socket 95
I/ConfigFetchService( 1947): fetch service done; releasing wakelock
I/ConfigFetchService( 1947): stopping self
W/ResourcesManager( 6109): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 1017): Killing 5600:com.google.android.apps.plus/u0a120 (adj 15): empty #31
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6129): MountEmulatedStorage()
I/libpersona( 6129): KNOX_SDCARD checking this for 10041
E/Zygote  ( 6129): v2
I/libpersona( 6129): KNOX_SDCARD not a persona
I/SELinux ( 6129): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6129): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6129 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6129): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5539/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10120/pid_5600/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 6129): TimaSignature is unavailable
D/ActivityThread( 6129): Added TimaKeyStore provider
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5830): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6149): MountEmulatedStorage()
I/libpersona( 6149): KNOX_SDCARD checking this for 10120
E/Zygote  ( 6149): v2
I/libpersona( 6149): KNOX_SDCARD not a persona
I/SELinux ( 6149): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6149 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5446:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
I/SELinux ( 6149): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6149): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6149): TimaSignature is unavailable
D/ActivityThread( 6149): Added TimaKeyStore provider
W/ResourcesManager( 5830): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5830): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/SA      ( 6129): [SSP] onCreated
W/ResourcesManager( 6149): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/SA      ( 6129): [TPM] There is no property file
I/SA      ( 6129): [SCU] isHaveSA() - false
I/SA      ( 6129): [TPM] getModelProperty : null
I/SA      ( 6129): [TPM] getCSCProperty : null
I/SA      ( 6129): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6129): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6129): [DM] TFT FEATURE: false
I/SA      ( 6129): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6129): [DM] init START
I/ActivityManager( 1017): Killing 5015:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
I/SA      ( 6129): [DM] This device is not a Vodafone
W/ResourceType( 6129): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6129): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6129): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 6129): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6129): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6129): [SCU] isHaveSA() - false
I/SA      ( 6129): support phone number id : false
I/SA      ( 6129): [DM] Supports Ref Jpn : true
I/SA      ( 6129): [DM] init END
I/SA      ( 6129): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 6129): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
I/ActivityManager( 1017): Killing 5657:com.sec.android.diagmonagent/1000 (adj 15): empty #31
W/libprocessgroup( 1017): failed to open /acct/uid_10057/pid_5446/cgroup.procs: No such file or directory
V/JNIHelp ( 5830): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5015/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5657/cgroup.procs: No such file or directory
I/art     ( 1017): Explicit concurrent mark sweep GC freed 217710(14MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/40MB, paused 5.797ms total 195.670ms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
W/ActivityThread( 5830): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5830): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ee89b2d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5830): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 6170): 
D/AndroidRuntime( 6170): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6170): CheckJNI is OFF
D/AndroidRuntime( 6170): readGMSProperty: start
D/AndroidRuntime( 6170): readGMSProperty: already setted!!
D/AndroidRuntime( 6170): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6170): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6170): readGMSProperty: end
D/AndroidRuntime( 6170): addProductProperty: start
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6189 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/Zygote  ( 6189): MountEmulatedStorage()
I/libpersona( 6189): KNOX_SDCARD checking this for 10057
E/Zygote  ( 6189): v2
I/libpersona( 6189): KNOX_SDCARD not a persona
I/SELinux ( 6189): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Killing 5075:com.google.android.gms:car/u0a12 (adj 15): empty #31
I/SELinux ( 6189): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6189): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/AffinityControl( 6170): AffinityControl: registerfunction enter
D/TimaKeyStoreProvider( 6189): TimaSignature is unavailable
D/ActivityThread( 6189): Added TimaKeyStore provider
W/ActivityManager( 1017): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
D/AndroidRuntime( 6170): Calling main entry com.android.commands.am.Am
W/libprocessgroup( 1017): failed to open /acct/uid_10012/pid_5075/cgroup.procs: No such file or directory
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
E/Zygote  ( 6209): MountEmulatedStorage()
E/Zygote  ( 6209): v2
I/libpersona( 6209): KNOX_SDCARD checking this for 10175
I/libpersona( 6209): KNOX_SDCARD not a persona
I/SELinux ( 6209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6209 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 2985
I/SELinux ( 6209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/AndroidRuntime( 6170): Shutting down VM
E/SELinux ( 6209): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=13 createSurf (1x1),1 flag=404, uhalitest
D/ChimeraCfgMgr( 1947): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1947): Module APK com.google.android.play.games already loaded
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6209): TimaSignature is unavailable
D/ActivityThread( 6209): Added TimaKeyStore provider
V/ActivityManager( 1017): Display changed displayId=0
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/SurfaceFlinger(  256): id=11 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  256): id=11 Removed YUIInstallC (-2/9)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
V/ActivityThread( 2985): updateVisibility : ActivityRecord{86184f7 token=android.os.BinderProxy@222d157c {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
E/Zygote  ( 6228): MountEmulatedStorage()
E/Zygote  ( 6228): v2
I/libpersona( 6228): KNOX_SDCARD checking this for 10010
I/SELinux ( 6228): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 6228): KNOX_SDCARD not a persona
I/SELinux ( 6228): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6228 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 6228): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6228): TimaSignature is unavailable
D/ActivityThread( 6228): Added TimaKeyStore provider
I/splitIntent( 1017): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
W/art     ( 6170): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/ActivityManager( 1017): Killing 5674:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
I/WebViewFactory( 6209): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,D/KeyguardViewMediator( 1176): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1176): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1176): *** Keyguard wallpaper service already unbounded
,I/LibraryLoader( 6209): Time to load native libraries: 2 ms (timestamps 4876-4878)
I/LibraryLoader( 6209): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6209): Binding Chromium to main looper Looper (main, tid 1) {2ca068c7}
,I/LibraryLoader( 6209): Expected native library version number "",actual native library version number ""
,I/chromium( 6209): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/libprocessgroup( 1017): failed to open /acct/uid_10142/pid_5674/cgroup.procs: No such file or directory
,I/BrowserStartupController( 6209): Initializing chromium process, singleProcess=true
,W/art     ( 6209): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6209): ApplicationContext is null in ApplicationStatus
,D/LocationManagerService( 1017): getProviders()=[passive]
,W/chromium( 6209): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6209): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6209): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6209): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6209): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6209): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6209): Local Branch: 
I/Adreno-EGL( 6209): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6209): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6209):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/Mms/MmsApp( 5810):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5810): [start]    fillCache consume time = 1944.206666
,D/Mms/ComposeMessageFragment( 5810): fillCache, easy = false
,I/UpdateIcingCorporaServi( 6189): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/AbsListView( 5810): Get MotionRecognitionManager
,D/MotionRecognitionService( 1017):  ssp status : false
,D/Mms/ComposeMessageFragment( 5810): [end]    fillCache consume time = 91.429583
,D/AcmsKeyStoreHelper( 5892):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5892): Key Store exist
I/AcmsKeyStoreHelper( 5892): Hence loading the keystore file
,D/Mms/BubbleViewCache( 5810): fillCache bubble = 1
,I/UpdateIcingCorporaServi( 6189): UpdateCorporaTask done [took 121 ms] updated apps [took 120 ms] 
,I/ActivityManager( 1017): Killing 5300:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,E/SMD     (  287): DCD OFF
,W/art     ( 6209): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{33411014 u0 com.test.thalitest/.MainActivity t229}
,W/AwContents( 6209): onDetachedFromWindow called when already detached. Ignoring
,D/AcmsKeyStoreHelper( 5892):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5892): getKeyStoreForApplication success 
D/AcmsCore( 5892): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5892): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5892): Decrementing - Counter value: 1
D/AcmsCore( 5892): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5892): This is NOT a valid MirrorLink app
D/AcmsCore( 5892): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5892): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5892): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5892): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5892): getSvcCounter - Counter value: 0
D/AcmsService( 5892): Enter onDestroy
I/AcmsService( 5892): cleanUp(): inside service clean up
D/AcmsCore( 5892): AcmsCore: inside DeInit
D/AcmsCore( 5892): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5892): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5892): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5892): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5892): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5892): getSvcCounter - Counter value: 0
D/AcmsService( 5892): killing acms process
I/Process ( 5892): Sending signal. PID: 5892 SIG: 9
,D/PhoneWindow( 6209): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6209): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6209): CordovaWebView is running on device made by: samsung
,W/art     ( 6209): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6209): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup( 1017): failed to open /acct/uid_10150/pid_5300/cgroup.procs: No such file or directory
,I/ActivityManager( 1017): Process ACMS.Process (pid 5892)(adj 0) has died(42,1088)
,D/OpenGLRenderer( 6209): Render dirty regions requested: true
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,W/chromium( 6209): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6209): updateVisibility : ActivityRecord{30f44790 token=android.os.BinderProxy@29a91242 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6209): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6209): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  256): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1017): Focus entered window: 6209
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6209): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 6209): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6209): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6209): Enabling debug mode 0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1176): There is/are notification(s) 
,I/ActivityManager( 1017): Displayed Component not be shown by security: +698ms (total +794ms)
,I/SamsungIME( 1707): getCurrentCandidateView
W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{33411014 u0 com.test.thalitest/.MainActivity t229} time:85423
,I/SurfaceFlinger(  256): id=13 Removed uhalitest (7/9)
,I/SurfaceFlinger(  256): id=13 Removed uhalitest (-2/9)
,W/IInputConnectionWrapper( 6209): showStatusIcon on inactive InputConnection
,I/Timeline( 6209): Timeline: Activity_idle id: android.os.BinderProxy@29a91242 time:85436
,D/SamsungIME( 1707): Dismiss ExpandCandiate
,I/SamsungIME( 1707): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1707): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1707): KeybaordView init() : load resources
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6282): MountEmulatedStorage()
I/libpersona( 6282): KNOX_SDCARD checking this for 10012
E/Zygote  ( 6282): v2
I/libpersona( 6282): KNOX_SDCARD not a persona
I/SELinux ( 6282): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SamsungIME( 1707): getCurrentKeyboard
I/SamsungIME( 1707): getTextKeyboard
,I/SELinux ( 6282): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=6282 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/SELinux ( 6282): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/SamsungIME( 1707): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/TimaKeyStoreProvider( 6282): TimaSignature is unavailable
,D/ActivityThread( 6282): Added TimaKeyStore provider
,W/BindingManager( 6209): Cannot call determinedVisibility() - never saw a connection for the pid: 6209
,W/ResourcesManager( 6282): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6282): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/MultiDex( 6282): VM with version 2.1.0 has multidex support
I/MultiDex( 6282): install
I/MultiDex( 6282): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6282): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/JsMessageQueue( 6209): Set native->JS mode to OnlineEventsBridgeMode
,W/ActivityThread( 6282): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6282): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22b0ccc6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6282): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1017): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1017): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1017): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 5152:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1947): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
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
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/jxcore_app_log( 6209): JniHelper::setJavaVM(0xb7d76450), pthread_self() = -1205006160
D/JX-Cordova( 6209): jxcore cordova android initializing
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4152, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/WearableService( 4508): callingUid 10012, callindPid: 4508
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2625): Disconnected process message: 10
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1660): [178] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10040/pid_5152/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/LocationInitializer( 1947): Restart initialization of location
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5877): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,W/jxcore-log( 6209): Initializing JXcore engine
W/jxcore-log( 6209): JXcore engine is ready
,W/jxcore-log( 6209): Starting JXcore engine
,E/audit   ( 1833): type=1400 msg=audit(1452520887.395:205): avc:  denied  { ioctl } for  pid=6209 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1833):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1833): type=1300 msg=audit(1452520887.395:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=be890d58 items=0 ppid=309 ppcomm=main pid=6209 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null),
E/audit   ( 1833): type=1320 msg=audit(1452520887.395:205): 
,W/jxcore-log( 6209): Platform android
W/jxcore-log( 6209): 
,W/jxcore-log( 6209): Process ARCH arm
W/jxcore-log( 6209): 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
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
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 6209): JXcore Cordova bridge is ready!
I/jxcore-log( 6209): 
W/jxcore-log( 6209): JXcore engine is started
,I/chromium( 6209): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6209): Toggling radios to true
I/jxcore-log( 6209): 
,D/BluetoothAdapter( 6209): enable()
,D/BluetoothAdapter( 6209): enable(): BT is already enabled..!
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
D/WifiService( 1017): setWifiEnabled: true pid=6209, uid=10175
W/ActivityManager( 1017): Permission Denial: getCurrentUser() from pid=6209, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1017): Failed getting userId using ActivityManagerNative
W/WifiService( 1017): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6209, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1017): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1017): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1017): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1017): name = wifi_on
I/WifiService( 1017): disconnect: pid=6209, uid=10175
I/wpa_supplicant( 1912): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6209): Radios toggled
I/jxcore-log( 6209): 
I/jxcore-log( 6209): My device name is: samsung-SM-A500FU
I/jxcore-log( 6209): 
,I/wpa_supplicant( 1912): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1912): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1912): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1912): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1912): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 1912): Cmd 35605 not handled
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/Tethering( 1017): InitialState.processMessage what=4
E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1912): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1912): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1912): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1912): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1912): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1912): First Scan Start
I/wpa_supplicant( 1912): Scan requested (ret=0) - scan timeout 30 seconds
,E/Tethering( 1017): No numeric data
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,D/Tethering( 1017): clearTetheredNotification()
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1176): updateTetherState():false, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
E/WifiNative-wlan0( 1017): do suspend true
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,V/NetworkStats( 1017): performPollLocked() took 12ms
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit,
V/NativeCrypto( 1730): Read error: ssl=0xb82d5ce8: I/O error during system call, Connection timed out
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit,
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/ConnectivityService( 1017): updateNetworkInfo()
E/ConnectivityService( 1017): updateNetworkInfo()
E/WifiStateMachine( 1017): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1912): wlan0: Setting scan request: 0 sec 0 usec
D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NativeCrypto( 1730): SSL shutdown failed: ssl=0xb82d5ce8: I/O error during system call, Broken pipe
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14949 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6950 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1017): Tagging socket 357 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1017, getuid(): 1000
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,E/WifiNative-wlan0( 1017): do suspend true
,D/WifiP2pService( 1017): InactiveState{ what=143375 },
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,I/qtaguid ( 1017): Untagging socket 357
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3565): Starting #8
,I/Hs20UtilService( 3565): Message received 5007
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1325): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1325): MountReceiver.mPrefHandler - 7002
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524292
D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1457): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1457): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SMD     (  287): DCD OFF
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,E/Zygote  ( 6311): MountEmulatedStorage()
E/Zygote  ( 6311): v2
I/libpersona( 6311): KNOX_SDCARD checking this for 10104
I/libpersona( 6311): KNOX_SDCARD not a persona
,D/SSRM:n  ( 1017): SIOP:: AP = 360
,I/SELinux ( 6311): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6311): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6311 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/SELinux ( 6311): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): updateIfacesLocked()
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1176): EthernetConnected: false
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,V/NetworkStats( 1017): performPollLocked() took 6ms
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider( 6311): TimaSignature is unavailable
,D/ActivityThread( 6311): Added TimaKeyStore provider
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,W/ResourcesManager( 6311): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,I/Babel_SMS( 6311): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6311): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6311): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel_SMS( 6311): MmsConfig.loadFromDatabase
,W/art     ( 6311): Suspending all threads took: 10.867ms
,E/Babel_SMS( 6311): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6311): MmsConfig.loadFromResources
,E/Babel_SMS( 6311): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6311): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  282): getCameraInfo: X
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  282): getCameraInfo: X
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6311): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6311): startup - clean
,I/Babel   ( 6311): deleted: false for 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3565): Starting #9
,I/Hs20UtilService( 3565): Message received 5007
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1325): MountReceiver.onReceive - Set preference state off
,W/VideoCapabilities( 6311): Unrecognized profile 2130706433 for video/avc
V/NearbySettings( 1325): MountReceiver.mPrefHandler - 7002
,W/AudioCapabilities( 6311): Unsupported mime audio/evrc
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6311): Unsupported mime audio/qcelp
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/AudioCapabilities( 6311): Unsupported mime audio/mpeg-L1
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6311): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6311): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6311): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6311): Unsupported mime audio/qcelp
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/AudioCapabilities( 6311): Unsupported mime audio/evrc
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6311): Unsupported mime video/wvc1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6311): Unsupported mime video/x-ms-wmv
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/DBG_DM  ( 2985): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ApplicationPolicy( 1017): updateDataUsageMap
,W/VideoCapabilities( 6311): Unrecognized profile/level 32768/2 for video/mp4v-es
,I/DBG_DM  ( 2985): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,W/VideoCapabilities( 6311): Unsupported mime video/wvc1
,W/VideoCapabilities( 6311): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6311): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6311): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6311): Unsupported mime video/mp43
,W/VideoCapabilities( 6311): Unsupported mime video/sorenson
,W/VideoCapabilities( 6311): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6311): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6311): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6311): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6311): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6311): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1017): Killing 5053:com.google.android.music:main/u0a111 (adj 15): empty #31
,I/vclib   ( 6311): onServiceConnected
,W/Babel   ( 6311): Attempted to change video mute state without an active call.
,I/ConfigService( 1730): onDestroy
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10111/pid_5053/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/PCWCLIENTTRACE_PushUtil( 5846): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5846): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5846): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5846): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
I/splitIntent( 1017): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1017): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5846): noConnectivity : true
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6354): MountEmulatedStorage()
E/Zygote  ( 6354): v2
I/libpersona( 6354): KNOX_SDCARD checking this for 10111
,I/libpersona( 6354): KNOX_SDCARD not a persona
,I/SELinux ( 6354): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6354): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6354): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6354 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/TimaKeyStoreProvider( 6354): TimaSignature is unavailable
,D/ActivityThread( 6354): Added TimaKeyStore provider
,I/MusicStore( 6354): Database version: 120
,I/wpa_supplicant( 1912): nl80211: Received scan results (7 BSSes)
,I/wpa_supplicant( 1912): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1912): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1912): Trying to associate with  'G700'
I/wpa_supplicant( 1912): Re-associate with C0.AA.48
I/wpa_supplicant( 1912): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1912): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1017): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1017): mCursor = null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
V/AlarmManager( 1017): waitForAlarm result :4
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6354): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/wpa_supplicant( 1912): Cmd 35605 not handled
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1912): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1912): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1912): Associated with C0.AA.48
I/wpa_supplicant( 1912): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1912): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1912): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 1912): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1912): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 1912): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1912): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
I/wpa_supplicant( 1912): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
I/wpa_supplicant( 1912): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1912): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1912): Blacklist: Clear (temp) 
W/ContextImpl( 6354): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
I/wpa_supplicant( 1912): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceStatusChanged wlan0, true
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,E/Tethering( 1017): No numeric data
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1017): clearTetheredNotification()
,V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1176): updateTetherState():false, false
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,V/NetworkStats( 1017): performPollLocked() took 4ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/WifiNative-wlan0( 1017): callSECApiVoid - ID [50]
W/ContextImpl( 6354): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,E/WifiConfigStore( 1017): setLastSelectedConfiguration -1
,D/ConnectivityService( 1017): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1017): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  277): Setting iface cfg,
E/WifiStateMachine( 1017): Start Dhcp Watchdog 2
,W/ResourcesManager( 6354): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6354): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1017): mCursor = null
,E/WifiNative-wlan0( 1017): do suspend false
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1017): mCursor = null
,V/JNIHelp ( 6354): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6354): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6354): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c39275: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6354): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6354): GMSCore installation verified
,E/SQLiteLog( 1730): (10) POSIX Error : 11 SQLite Error : 3850
,I/ConfigStore( 6354): Config Database version: 1
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1017): getStreamVolume 3 index 0
,I/MediaRouter( 6354): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6354): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/dhcpcd  ( 6381): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6381): version 5.5.6 starting
E/dhcpcd  ( 6381): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Zygote  ( 6382): MountEmulatedStorage()
,E/Zygote  ( 6382): v2
I/libpersona( 6382): KNOX_SDCARD checking this for 10002
I/libpersona( 6382): KNOX_SDCARD not a persona,
,I/SELinux ( 6382): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6382): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6382): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6382 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 6381): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6381): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6381): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6381): bssid match
,I/dhcpcd  ( 6381): wlan0: rebinding lease of 192.168.1.137
,D/TimaKeyStoreProvider( 6382): TimaSignature is unavailable
,D/ActivityThread( 6382): Added TimaKeyStore provider
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GHttpClientFactory( 6354): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6354): Using platform SSLCertificateSocketFactory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1017): Killing 5394:com.google.android.gm/u0a101 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 5170:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6407): MountEmulatedStorage(),
E/Zygote  ( 6407): v2
I/libpersona( 6407): KNOX_SDCARD checking this for 1000
I/libpersona( 6407): KNOX_SDCARD not a persona
I/SELinux ( 6407): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6407 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6407): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6407): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/art     (  309): Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 25.514ms
,D/TimaKeyStoreProvider( 6407): TimaSignature is unavailable
D/ActivityThread( 6407): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 17.069ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 762us total 17.226ms
,I/DIAGMON_AGENT( 6407): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1017): failed to open /acct/uid_10044/pid_5170/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10101/pid_5394/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6407): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6407): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,I/DIAGMON_AGENT( 6407): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
,I/DIAGMON_AGENT( 6407): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6407): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6407): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6422): MountEmulatedStorage(),
,E/Zygote  ( 6422): v2,
I/libpersona( 6422): KNOX_SDCARD checking this for 10009
I/libpersona( 6422): KNOX_SDCARD not a persona
,I/SELinux ( 6422): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6422 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 6422): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6422): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6422): TimaSignature is unavailable
,D/ActivityThread( 6422): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 4236:com.sec.spp.push/u0a35 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3617): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 15:01:30 GMT+01:00 2016
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3617): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3617): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3617): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3617): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3617): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3617): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3617): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,E/Zygote  ( 6438): MountEmulatedStorage(),
E/Zygote  ( 6438): v2
I/libpersona( 6438): KNOX_SDCARD checking this for 10034
I/libpersona( 6438): KNOX_SDCARD not a persona
,I/SELinux ( 6438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6438 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3617): StateImplV2(): networkChangeListener().END
I/SELinux ( 6438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6438): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3617): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6438): TimaSignature is unavailable
,D/ActivityThread( 6438): Added TimaKeyStore provider
,I/SO_AGENT( 6438): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5877): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 6129): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6129): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6129): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6129): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_4236/cgroup.procs: No such file or directory
,I/SA      ( 6129): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6129): [OR] == isSIMCardReady false ==
,I/SA      ( 6129): [SCU] == networkStateCheck == false
I/SA      ( 6129): [OR] onReceive END
,E/DBG_POLICYDM( 5877): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/ActivityManager( 1017): Killing 5376:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1589): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1589): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1589): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1589): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1589): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1589): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1589): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6455): MountEmulatedStorage()
,E/Zygote  ( 6455): v2
I/libpersona( 6455): KNOX_SDCARD checking this for 10125
I/SELinux ( 6455): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 6455): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6455 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
I/SELinux ( 6455): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6455): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6455): TimaSignature is unavailable
,D/ActivityThread( 6455): Added TimaKeyStore provider
,W/ResourcesManager( 6455): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6455): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6455): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6455): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6455): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6455): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_5376/cgroup.procs: No such file or directory
,I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6470 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/Zygote  ( 6470): MountEmulatedStorage()
I/libpersona( 6470): KNOX_SDCARD checking this for 10145
E/Zygote  ( 6470): v2
I/libpersona( 6470): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Killing 5799:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,I/SELinux ( 6470): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6470): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6470): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6470): TimaSignature is unavailable
,D/ActivityThread( 6470): Added TimaKeyStore provider
,W/ResourcesManager( 6470): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6470): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6470): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6470): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/libprocessgroup( 1017): failed to open /acct/uid_10100/pid_5799/cgroup.procs: No such file or directory
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/BadgeProvider( 5990): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/BadgeProvider( 5990): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5990): sendNotify, [notify] : null
D/BadgeProvider( 5990): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5990): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5990): update, [UpdateCount] : 1
,D/Launcher.Model( 1486): reloadBadges entered.
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6493): MountEmulatedStorage()
E/Zygote  ( 6493): v2
I/libpersona( 6493): KNOX_SDCARD checking this for 1000
I/libpersona( 6493): KNOX_SDCARD not a persona
,I/SELinux ( 6493): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6493): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6493 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 6493): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6493): TimaSignature is unavailable
,D/ActivityThread( 6493): Added TimaKeyStore provider
,D/SecurityLogAgent( 6493): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6493): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6493): StateMachine : Current State = 1
,D/SecurityLogAgent( 6493): StateMachine : Changed Current State = 1
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6510): MountEmulatedStorage(),
,E/Zygote  ( 6510): v2,
I/ActivityManager( 1017): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6510 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/libpersona( 6510): KNOX_SDCARD checking this for 10159,
I/ActivityManager( 1017): Killing 5473:com.google.android.partnersetup/u0a15 (adj 15): empty #31
I/libpersona( 6510): KNOX_SDCARD not a persona,
,I/SELinux ( 6510): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6510): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6510): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6510): TimaSignature is unavailable
,D/ActivityThread( 6510): Added TimaKeyStore provider
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 60132(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 27MB/41MB, paused 3.117ms total 170.586ms
,I/ActivityManager( 1017): Killing 5830:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 5857:com.samsung.helphub/1000 (adj 15): empty #31
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 1947): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1947): num queued entries: 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,I/iu.UploadsManager( 1947): num updated entries: 0
,I/iu.SyncManager( 1947): NEXT; no task
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1947): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/dhcpcd  ( 6381): wlan0: acknowledged 192.168.1.137 from 192.168.1.1
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6531): MountEmulatedStorage()
,E/Zygote  ( 6531): v2
I/libpersona( 6531): KNOX_SDCARD checking this for 10035
I/libpersona( 6531): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6531 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6531): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/SELinux ( 6531): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6531): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1017): failed to open /acct/uid_10091/pid_5830/cgroup.procs: No such file or directory
,I/Babel   ( 6311): connection state changed from UNKNOWN to DISCONNECTED
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5857/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/dhcpcd  ( 6381): wlan0: leased 192.168.1.137 for 86400 seconds
,D/TimaKeyStoreProvider( 6531): TimaSignature is unavailable
D/ActivityThread( 6531): Added TimaKeyStore provider
,E/SPPClientService( 6531): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6531): [SystemStateMoniter] Current Time : 90926
,E/SPPClientService( 6531): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6531): [PushClientApplication] Push log off : This is Ship build version,
E/SPPClientService( 6531): [SystemStateMoniter] No Connect : true
,D/SPPClientService( 6531): PushLog.txt file is not deleted.,
D/SPPClientService( 6531): PushLog.txt file is not deleted.
D/SPPClientService( 6531): ============PushLog. stop!,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 6568): MountEmulatedStorage(),
E/Zygote  ( 6568): v2
I/libpersona( 6568): KNOX_SDCARD checking this for 10113
I/libpersona( 6568): KNOX_SDCARD not a persona
,I/SELinux ( 6568): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6568): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6568): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6568 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5488:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,E/WifiNative-wlan0( 1017): do suspend true
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 6531): [[SystemStateMonitorService]] No Active Internet
,I/ActivityManager( 1017): Killing 5912:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6568): TimaSignature is unavailable
,D/ActivityThread( 6568): Added TimaKeyStore provider
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1017): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1017): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1017): callSECApiInt - ID [210]
,I/ActivityManager( 1017): Killing 5951:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1017): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1017): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1017): Adding Route [fe80::/64 -> :: wlan0] to network 503
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/ConnectivityService( 1017): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1017): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1017): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1017): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1017): LTETest block dns file not exists
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/JavaBinder( 1017): !!! FAILED BINDER TRANSACTION !!!
,E/ConnectivityService( 1017): updateNetworkInfo()
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 1017): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1017): Failed to clear dns cache for: com.sec.android.widgetapp.tapandpay
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 1000
E/JavaBinder( 1017): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1017): Failed to clear dns cache for: com.samsung.android.app.galaxyfinder
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,D/ConnectivityService( 1017):    accepting network in place of null
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1457): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1457): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1017): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 1017): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 1017): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1017): mBoosterFLAG : 0
I/WifiTrafficPoller( 1017): current booster mode : FullMode
,D/WifiNative-wlan0( 1017): callSECApiVoid - ID [212]
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,V/NetworkStats( 1017): updateIfacesLocked()
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,V/NetworkStats( 1017): performPollLocked() took 4ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit,
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
,D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
,D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1017): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6568): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6568): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6568): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6568):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6568):   adb logcat -s GAv4
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 14:01:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452520891509], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452520891488]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/ConnectivityService( 1017): Validated NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6568): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6568): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6568): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_5488/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10156/pid_5951/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10152/pid_5912/cgroup.procs: No such file or directory
,W/GAv4    ( 6568): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6568): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6568): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6568): Time to load native libraries: 1 ms (timestamps 1384-1385)
,I/LibraryLoader( 6568): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6568): Binding Chromium to main looper Looper (main, tid 1) {15e91223}
,I/LibraryLoader( 6568): Expected native library version number "",actual native library version number ""
,I/chromium( 6568): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6568): Initializing chromium process, singleProcess=true
,W/art     ( 6568): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6568): ApplicationContext is null in ApplicationStatus
,W/chromium( 6568): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6568): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6568): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6568): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6568): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6568): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6568): Local Branch: 
I/Adreno-EGL( 6568): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6568): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6568):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/NSApplication( 6568): Starting up...
,W/AudioManagerAndroid( 6568): Requires BLUETOOTH permission
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6631 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6631): MountEmulatedStorage()
I/libpersona( 6631): KNOX_SDCARD checking this for 10081
E/Zygote  ( 6631): v2
I/libpersona( 6631): KNOX_SDCARD not a persona
,I/SELinux ( 6631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Killing 5555:com.android.vending/u0a28 (adj 15): empty #31
,I/SELinux ( 6631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6631): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6631): TimaSignature is unavailable
,D/ActivityThread( 6631): Added TimaKeyStore provider
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 2985): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 6354): type=WIFI subType= reason=null isConnected=true
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6648): MountEmulatedStorage()
E/Zygote  ( 6648): v2
I/libpersona( 6648): KNOX_SDCARD checking this for 10075
I/libpersona( 6648): KNOX_SDCARD not a persona
,I/SELinux ( 6648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6648): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6648 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,W/libprocessgroup( 1017): failed to open /acct/uid_10028/pid_5555/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6648): TimaSignature is unavailable
,D/ActivityThread( 6648): Added TimaKeyStore provider
,D/WaitQueueForNetworkActivate( 6228): notifyNetworkActivated
,W/ContextImpl( 6228): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6228): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6228): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6228): exit::IDLE
D/InitializeManagerStateMachine( 6228): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6228): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6228): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6228): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6228): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6228): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6228): entry::SUCCESS
D/hcjo    ( 6228): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6228): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6228): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,D/InitializeManagerStateMachine( 6228): exit::SUCCESS
D/InitializeManagerStateMachine( 6228): entry::IDLE
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3565): Starting #10
,I/Hs20UtilService( 3565): Message received 5007
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1325): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1017): Killing 5810:com.android.mms/u0a46 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3565): Starting #11
,I/Hs20UtilService( 3565): Message received 5007
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1325): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3565): Starting #12
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/Hs20UtilService( 3565): Message received 5007
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1325): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3565): Starting #13
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1325): MountReceiver.onReceive - Keep current state
I/Hs20UtilService( 3565): Message received 5007
,D/WifiStateMachine( 1017): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1017): mCursor = null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/CountryDetector( 1017): No listener is left
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1017): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1017): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1017): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5846): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5846): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5846): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5846): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
I/splitIntent( 1017): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1017): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6354): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  256): id=15 createSurf (1x1),1 flag=4, Uoast
,W/GAV2    ( 6648): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/libprocessgroup( 1017): failed to open /acct/uid_10046/pid_5810/cgroup.procs: No such file or directory
,D/PowerManagerService( 1017): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,D/ConnectivityService( 1017): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/DIAGMON_AGENT( 6407): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6407): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6407): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6407): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SRIB_DCS( 1176): log_dcs ThreadedRenderer::initialize entered! 
,I/BooksApp( 6648): Created application version: 3.6.9 (30609)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1730): Connected
,I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/GCM     ( 1730): Message class com.google.f.a.a.p
,I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 11949(622KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 1.091ms total 47.017ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/FOTA_Client( 6422): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6422): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.183: ( 3617): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 15:01:32 GMT+01:00 2016
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.183: ( 3617): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3617): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3617): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3617): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/BooksSync( 6648): Starting books sync for 61035162, extras: ade
,I/KLMS-2.5.183: ( 3617): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/KLMS-2.5.183: ( 3617): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3617): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/KLMS-2.5.183: ( 3617): StateImplV2(): networkChangeListener().START
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/KLMS-2.5.183: ( 3617): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.183: ( 3617): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3617): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3617): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5877): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5877): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 6129): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6129): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6129): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 6129): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6129): [OR] == isSIMCardReady false ==
,I/SA      ( 6129): [SCU] == networkStateCheck == true
,I/SA      ( 6129): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6129): isChinaCountryCode : false
I/SA      ( 6129): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6129): [OR] == networkStateCheck true ==
,I/SA      ( 6129): [OR] GetMyCountryZoneTask
I/SA      ( 6129): [OR] onReceive END
,I/SA      ( 6129): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5877): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,D/accuweather( 1589): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/SA      ( 6129): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6129): [SSP] query invoked
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
,I/SA      ( 6129): [TPMU] GetMccFromDB : null
I/SA      ( 6129): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6129): [TPM] isNoProxy(default) : true
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5877): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1017): mCursor = null
,D/accuweather( 1589): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1589): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1589): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1589): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/accuweather( 1589): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/File    ( 6129): fail readDirectory() errno=2
D/accuweather( 1589): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6455): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6455): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6455): PeriphStartReceiver.onReceive - no need to start
,E/DBG_POLICYDM( 5877): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6493): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6493): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6493): StateMachine : Current State = 1
,D/SecurityLogAgent( 6493): StateMachine : Changed Current State = 1
,I/DBG_POLICYDM( 5877): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1017): Tagging socket 367 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1017, getuid(): 1000
,I/iu.Environment( 1947): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/qtaguid ( 1017): Untagging socket 367
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 14:01:32 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452520892795], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452520892779]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/ConnectivityService( 1017): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,I/iu.UploadsManager( 1947): num queued entries: 0
,I/iu.UploadsManager( 1947): num updated entries: 0
D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290
,I/iu.SyncManager( 1947): NEXT; no task
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1947): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1947): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6531): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6531): [SystemStateMoniter] Current Time : 92488
,E/SPPClientService( 6531): [SystemStateMoniter] No Connect : false
,E/SQLiteLog( 6648): (284) automatic index on view_volumes(volume_id)
,I/System.out( 6311): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6311): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6311): (HTTPLog)-Static: isShipBuild true
,I/System.out( 6311): (HTTPLog)-Thread-1102-574418414: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6311): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10104
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10104
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/hcjo    ( 6228): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6228): execute::IDLE:EXECUTE
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/InitializeManagerStateMachine( 6228): exit::IDLE
,D/InitializeManagerStateMachine( 6228): entry::NETWORK_CHECK
,I/BooksConfig( 6648): GmsCore Version = 7.8.99 (2134222-436)
D/InitializeManagerStateMachine( 6228): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6228): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6228): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6228): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6228): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6228): entry::SUCCESS
D/hcjo    ( 6228): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 6228): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6228): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6228): exit::SUCCESS
D/InitializeManagerStateMachine( 6228): entry::IDLE
,I/System.out( 6311): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 6311): connection state changed from DISCONNECTED to CONNECTED
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 1947): [AccountUtils] Account not ready
W/Kids    ( 1947): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1947): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1947): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1947): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1947): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1947): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1947): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1947): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1947): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1947): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1947): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1947): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PanelView( 1176): There is/are notification(s) 
,D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PanelView( 1176): There is/are notification(s) 
,D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found,
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksAccountManager( 6648): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6648): Soft error
E/BooksSync( 6648): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6648): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6648): Sync error
E/BooksSync( 6648): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6648): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6648): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 62950, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,I/SA      ( 6129): [RC New] Execute method=[GET] start,
,I/SA      ( 6129): [RC New] Security=[true]
,I/System.out( 6129): Thread-1065(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6129): Thread-1065(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6129): Thread-1065(ApacheHTTPLog):isShipBuild true
I/System.out( 6129): Thread-1065(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6129): Thread-1065(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10041
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10041
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 40963(2MB) AllocSpace objects, 7(152KB) LOS objects, 33% free, 27MB/41MB, paused 2.575ms total 149.927ms
,D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524295
,V/AlarmManager( 1017): waitForAlarm result :4
,I/ActivityManager( 1017): Killing 6005:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10047/pid_6005/cgroup.procs: No such file or directory
,D/GCM     ( 1730): Connected
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1730): Message class com.google.f.a.a.p
,D/PackageManager( 1017): [MSG] MCS_UNBIND
,I/ActivityManager( 1017): Killing 6023:com.wsomacp/u0a25 (adj 15): empty #31
,I/PowerManagerService( 1017): [PWL] Off : 15s ago
,I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1947, ws=null) (elapsedTime=57339)
,W/libprocessgroup( 1017): failed to open /acct/uid_10025/pid_6023/cgroup.procs: No such file or directory
,I/SA      ( 6129): [RC New] [v2liruge] api execute + 603
,I/SA      ( 6129): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6129): AsyncTask #1 calls detatch()
,I/SA      ( 6129): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6129): [OCP] update openData : PL
,I/SA      ( 6129): [TPMU] getNetworkMcc : 
,I/SA      ( 6129): [SCU] saveMccToPreferece Start
,I/SA      ( 6129): [SCU] RegionMCC : 260
I/SA      ( 6129): [SSP] query invoked
,I/SA      ( 6129): [TPMU] GetMccFromDB : null
,I/SA      ( 6129): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6129): [SCU] saveMccToPreferece End
,I/SA      ( 6129): [RC New] executeRequest [v2liruge] end. 661
I/SA      ( 6129): [RC New] Execute end
,I/SA      ( 6129): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6129): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6381): wlan0: sending IPv6 Router Solicitation
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4508): callingUid 10012, callindPid: 4508
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6354): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6354): Stop autocaching.
,E/GmsUtils( 6354): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6354): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  256): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  256): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1017): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 95546
,D/PowerManagerService( 1017): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0)
,D/PowerManagerService( 1017): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10054}) (elapsedTime=3485)
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4217, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2625): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5846): mConnectivityHandler : connected
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/PCWCLIENTTRACE_AccountUtil( 5846): [hasSamungAccount] - No Samsung Account
,I/GAV2    ( 6648): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5846): [GetString-S]
,I/ReactiveServiceManager( 5846): Supported : 1
,D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 12
,D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 12
,E/terrier ( 1017): handleString: Failed to handle string(-4)
E/terrier ( 1017): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5846): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5846): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5846): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5846): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5846): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5846): [ensureRegistration] - No Samsung account
,E/SMD     (  287): DCD OFF
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{ca43df9 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/dhcpcd  ( 6381): wlan0: sending IPv6 Router Solicitation
,D/SSRM:n  ( 1017): SIOP:: AP = 360
,I/jxcore-log( 6209): Test app app.js loaded
I/jxcore-log( 6209): 
,I/chromium( 6209): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  287): DCD OFF
,I/dhcpcd  ( 6381): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6381): wlan0: no IPv6 Routers available
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6228): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6228): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6228): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6228): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6228): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6228): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6228): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6228): entry::IDLE
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6726): MountEmulatedStorage()
E/Zygote  ( 6726): v2
I/libpersona( 6726): KNOX_SDCARD checking this for 10028
I/libpersona( 6726): KNOX_SDCARD not a persona
,I/SELinux ( 6726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6726 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6726): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     (  309): Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 735us total 30.234ms
,D/TimaKeyStoreProvider( 6726): TimaSignature is unavailable
,D/ActivityThread( 6726): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 794us total 20.780ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 20.565ms
,D/Finsky  ( 6726): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6726): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/Settings( 6726): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6726): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 6726): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6726): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6726): [1161] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/Finsky  ( 6726): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/PreloadUpdateManagerStateMachine( 6228): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6228): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6228): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/hcjo    ( 6228): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 6228): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/PreloadUpdateManagerStateMachine( 6228): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6228): entry::IDLE
,D/Finsky  ( 6726): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6726): [1161] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/ActivityManager( 1017): Killing 6049:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,V/Finsky  ( 6726): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/libprocessgroup( 1017): failed to open /acct/uid_10053/pid_6049/cgroup.procs: No such file or directory,
,V/AlarmManager( 1017): waitForAlarm result :4,
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6726): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6726): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6726): [1] 5.onFinished: Scheduling replication attempt 2.
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6726): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6726): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6726): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6726): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6726): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6726): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6726): [1] DailyHygiene.reschedule: Scheduling new run in 844 minutes (failures=5)
,D/DeviceConnectionService( 1660): client connected with version: 7571000
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4252, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 1017): stay LED for charging
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2625): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1017): !@Sync 3
,V/AlarmManager( 1017): waitForAlarm result :4
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1017): SIOP:: AP = 330
,I/PowerManagerService( 1017): [PWL] Off : 30s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4255, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2625): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/FactoryTest( 5628): Not factory mode
,D/FactoryTest( 5628): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5628): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5628): still no open session command from host, so toast
,W/ContextImpl( 5628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5628): Timeline: Activity_launch_request id:com.android.settings time:116420
,E/PersonaManagerService( 1017): inState():  stateMachine is null !!
,I/PersonaManagerService( 1017): PersonaId don't exist
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
D/InputDispatcher( 1017): Focus left window: 6209
,E/MTPRx   ( 5628): started activity for popup
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5628): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5628): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5628): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5628): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5628): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5628): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5628): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus entered window: 6209
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1017): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3674ca64 attribute=null, token = android.os.BinderProxy@31eda99
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SettingsReceiverActivity( 5628): dev.kiessupport is : TRUE
,D/PhoneWindow( 5628): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5628): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,V/ActivityThread( 6209): updateVisibility : ActivityRecord{30f44790 token=android.os.BinderProxy@29a91242 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6209): Timeline: Activity_idle id: android.os.BinderProxy@29a91242 time:116600
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1017): SIOP:: AP = 310
,W/ActivityManager( 1017): mDVFSHelper.release()
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,V/AlarmManager( 1017): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1017): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1017): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 32433(1671KB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 27MB/41MB, paused 2.575ms total 164.741ms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6726): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6726): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6726): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4252, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2625): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,I/PowerManagerService( 1017): [PWL] Off : 50s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4255, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,V/HeadsetService( 2625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2625): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 4
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3,
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6726): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6726): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6726): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4256, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2625): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :4,
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0,
,I/BooksSync( 6648): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6648): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 29305(1706KB) AllocSpace objects, 6(216KB) LOS objects, 39% free, 10MB/17MB, paused 1.473ms total 58.087ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice,
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6648): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksSync( 6648): Soft error
E/BooksSync( 6648): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6648): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6648): Sync error
E/BooksSync( 6648): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6648): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6648): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 124765, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,E/SQLiteLog( 1730): (10) POSIX Error : 11 SQLite Error : 3850
,I/PowerManagerService( 1017): [PWL] Off : 75s ago
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4257, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1017): stay LED for charging
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2625): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6726): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6726): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6726): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4258, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2625): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 5
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2625): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1017): [PWL] Off : 105s ago
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6726): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6726): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6726): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 6
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1730): Vacuum at: now=1452521005123 tag=VacuumService
,I/GoogleURLConnFactory( 1730): Using platform SSLCertificateSocketFactory
,W/Uploader( 1730): No account for auth token provided
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1730): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1730): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1730): (HTTPLog)-Static: isShipBuild true
I/System.out( 1730): (HTTPLog)-Thread-212-589725414: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1730): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1730): KnoxVpnUidStorageknoxVpnSupported API value returned is false,
I/qtaguid ( 1730): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1730, getuid(): 10012
,I/qtaguid ( 1730): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1730, getuid(): 10012
,W/Uploader( 1730): No account for auth token provided
,I/System.out( 1730): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1730): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1730, getuid(): 10012
,W/Uploader( 1730): No account for auth token provided
,I/System.out( 1730): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1730): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1730, getuid(): 10012
,W/Uploader( 1730): No account for auth token provided
,I/System.out( 1730): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1730): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1730, getuid(): 10012
,W/Uploader( 1730):  no longer exists, so no auth token.
,I/System.out( 1730): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1730): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1730, getuid(): 10012
,E/SMD     (  287): DCD OFF
,W/Uploader( 1730): No account for auth token provided
,I/System.out( 1730): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1730): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1730, getuid(): 10012
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/Uploader( 1730): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1730): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1730): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1730): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1730): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1730): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1730): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1730): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1730): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1730): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1730): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1730): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1730): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/System.out( 1730): (HTTPLog)-Static: isSBSettingEnabled false
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/qtaguid ( 1730): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1730, getuid(): 10012
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PanelView( 1176): There is/are notification(s) 
,D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,E/SQLiteLog( 1730): (10) POSIX Error : 11 SQLite Error : 3850
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6648): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6648): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice,
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1730): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1730): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1730): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1730): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6648): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6648): Soft error
E/BooksSync( 6648): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6648): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6648): Sync error
E/BooksSync( 6648): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6648): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6648): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 216526, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/PowerManagerService( 1017): [PWL] Off : 140s ago
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/Watchdog( 1017): !@Sync 7
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/SSRM:n  ( 1017): SIOP:: AP = 280
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2625): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1017): !@Sync 8
,I/PowerManagerService( 1017): [PWL] Off : 180s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 270,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 280
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2625): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 9
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 225s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4265, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2625): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1017): initializing...
,I/TLC_TIMA_PKM_initialize( 1017): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1017): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1017): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 13
,I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1017): Trustlet response is completed
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6209): --= Surplus to requirements =--
I/jxcore-log( 6209): 
,I/jxcore-log( 6209): ****TEST TOOK:  ms ****
I/jxcore-log( 6209): 
I/jxcore-log( 6209): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6209): 
,D/AndroidRuntime( 6891): ,
D/AndroidRuntime( 6891): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6891): CheckJNI is OFF,
D/AndroidRuntime( 6891): readGMSProperty: start
D/AndroidRuntime( 6891): readGMSProperty: already setted!!
,D/AndroidRuntime( 6891): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6891): readGMSProperty: could not set the property(default)!!,
D/AndroidRuntime( 6891): readGMSProperty: end
D/AndroidRuntime( 6891): addProductProperty: start
,E/AffinityControl( 6891): AffinityControl: registerfunction enter
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AndroidRuntime( 6891): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 1017): START PACKAGE DELETE: observer{1050979176},
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1017): !@killApplicatoin: 10175, uninstall pkg,
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 6209:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{33411014 u0 com.test.thalitest/.MainActivity t229}
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,W/PackageSettings( 1017): Skipping PackageSetting{dc42bb8 com.example.hello/10176} due to missing metadata
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{33411014 u0 com.test.thalitest/.MainActivity t229 f}
W/ActivityManager( 1017): Duplicate finish request for ActivityRecord{33411014 u0 com.test.thalitest/.MainActivity t229 f}
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,I/WindowState( 1017): WIN DEATH: Window{2613e15e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (6/8)
I/SurfaceFlinger(  256): id=14 Removed NainActivit (-2/8)
D/InputDispatcher( 1017): Focus left window: 6209
D/InputDispatcher( 1017): Focused application released
I/art     ( 5136): Explicit concurrent mark sweep GC freed 17604(1007KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 6MB/11MB, paused 867us total 31.881ms
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/art     ( 6189): Explicit concurrent mark sweep GC freed 359(25KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 934us total 45.365ms
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1707): mOCRHelper is null
,W/GeofencerStateMachine( 1660): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 2985): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,D/RegisteredComponentCache( 1440): Collect Tech packages for Knox
,D/PersonaManager( 1440): isKioskContainerExistOnDevice
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 12
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/KLMS-2.5.183: ( 3617): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 15:05:17 GMT+01:00 2016
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/DBG_DM  ( 2985): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 12
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 2985): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 2985): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/KLMS-2.5.183: ( 3617): KLMSAbstractReciever(): onReceive().END.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/splitIntent( 1017): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
,I/splitIntent( 1017): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1017): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4261, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/LightsService( 1017): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1017) 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/lights  ( 1017): write_int failed to open -1
D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/BatteryService( 1017): turn on LED for fully charged
,E/Zygote  ( 6905): MountEmulatedStorage()
E/Zygote  ( 6905): v2
I/libpersona( 6905): KNOX_SDCARD checking this for 10094
I/libpersona( 6905): KNOX_SDCARD not a persona
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/SELinux ( 6905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/KLMS-2.5.183: ( 3617): KLMSIntentService(): onCreate()
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6905 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a,
I/KLMS-2.5.183: ( 3617): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
I/SELinux ( 6905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6905): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 12
,I/KLMS-2.5.183: ( 3617): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/PersonaManager( 1440): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1440): empty dynamic service
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 56401(3MB) AllocSpace objects, 85(1420KB) LOS objects, 33% free, 27MB/41MB, paused 5.429ms total 215.141ms
,I/KLMS-2.5.183: ( 3617): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
D/TimaKeyStoreProvider( 6905): TimaSignature is unavailable
,I/art     ( 1017): WaitForGcToComplete blocked for 24.817ms for cause Explicit
D/ActivityThread( 6905): Added TimaKeyStore provider
,I/DBG_DM  ( 2985): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 2985): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 2985): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,I/KLMS-2.5.183: ( 3617): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.183: ( 3617): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.183: ( 3617): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,I/DBG_DM  ( 2985): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/SurfaceFlinger(  256): id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1017): Focus entered window: 2985
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2985): log_dcs ThreadedRenderer::initialize entered! 
,V/ActivityThread( 2985): updateVisibility : ActivityRecord{86184f7 token=android.os.BinderProxy@222d157c {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/elm:15183( 6905): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 6905): ELMEngine.ELMEngine( context ).
,D/elm:15183( 6905): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 6905): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15183( 6905): ElmAgentService : onCreate()
,D/elm:15183( 6905): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 6905): MainReceiver.listeningToPackageRemoved()
,D/elm:15183( 6905): MDMBridge.getInstance()
D/elm:15183( 6905): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15183( 6905): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15183( 6905): ElmAgentService : onDestroy().
,I/ActivityManager( 1017): Killing 6070:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 6209 uid 10175
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/KLMS-2.5.183: ( 3617): KLMSIntentService(): listeningToPackageRemoved().END
,D/SamsungIME( 1707): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/KLMS-2.5.183: ( 3617): KLMSIntentService(): onDestroy()
,I/Timeline( 2985): Timeline: Activity_idle id: android.os.BinderProxy@222d157c time:317621
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,D/RCPManagerService( 1017): PackageReceiver onReceive()
,I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,I/OTPFW   ( 1017): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1017): OtpDbHelper::getInstance New instance created
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 13134(684KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 5.069ms total 196.484ms
,W/ActivityManager( 1017): mDVFSHelper.release()
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{180e6729 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t228} time:317652
,I/art     ( 1017): WaitForGcToComplete blocked for 407.165ms for cause Explicit
,D/OTPFW   ( 1017): DBIntegrity::getInstance - New instance created
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/OTPFW   ( 1017): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/OTPFW   ( 1017): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1017): ProvisionData::getAllEntries Table is empty
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1017): uID is 10175
,V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicy( 1017): uID is 10175
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1017): mCursor = null
,V/HeadsetService( 2625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2625): Disconnected process message: 10
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=229_task.xml
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=228_task.xml
,I/PCWCLIENTTRACE_PushUtil( 5846): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5846): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5846): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5846): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,D/PowerManagerService( 1017): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1176
I/PowerManagerService( 1017): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
,I/PowerManagerService( 1017): Waking up from sleep (uid 10054)...,
V/KeyguardServiceDelegate( 1017): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@3deed09)
D/PowerManagerService( 1017): [PWL] sb acquire: PowerManagerService.Broadcasts,
D/KeyguardViewMediator( 1176): onScreenTurnedOn, seq = 2
D/PowerManagerService( 1017): [s] UserActivityState : 0 -> 1
D/KeyguardViewMediator( 1176): notifyScreenOnLocked
I/DisplayPowerController( 1017): Blocking screen on until initial contents have been drawn.
,D/WindowOrientationListener( 1017): sensor enabled
D/PowerManagerService( 1017): [PWL] sb acquire: PowerManagerService.Display
,E/Zygote  ( 6925): MountEmulatedStorage()
I/libpersona( 6925): KNOX_SDCARD checking this for 10032
E/Zygote  ( 6925): v2
I/libpersona( 6925): KNOX_SDCARD not a persona
I/SELinux ( 6925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/SELinux ( 6925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/PanelView( 1176): There is/are notification(s) 
D/DisplayPowerController( 1017): getFinalBrightness : Summary is 5 -> 5
I/libsuspend( 1017): !@autosuspend_wakeup_count_disable
D/DisplayPowerController( 1017): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/libsuspend( 1017): !@autosuspend_wakeup_count_disable done
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
D/DisplayPowerController( 1017): getFinalBrightness : Summary is 5 -> 5
D/SurfaceFlinger(  256): Set power mode=2, type=0 flinger=0xb7c44690
D/DisplayPowerController( 1017): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 2 on display: 0
D/DisplayManagerService( 1017): !@display_state: OFF -> ON
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6925 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
I/DisplayManagerService( 1017): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
E/SELinux ( 6925): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
D/SensorService( 1017): [SO] changed settle time [1]
D/SensorService( 1017): [SO] setDelay [66000000]
D/SensorService( 1017): [SO] activate (ident=0xb8892640, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/KeyguardViewMediator( 1176): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1176): onScreenTurnedOn()
D/SecKeyguardClockSingleView( 1176): onScreenTurnedOn
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/KeyguardServiceDelegate( 1017): **** SHOWN CALLED ****
D/DisplayPowerController( 1017): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,D/StatusBarKeyguardViewManager( 1176): callback.onShown()
I/DisplayPowerController( 1017): Unblocked screen on after 55 ms
D/DisplayPowerState( 1017): !@ ColorFade exit
,I/ValidateNoPeople( 1017): skipping global notification
D/WindowManager( 1017): showStatusBarByNotification() mOpenByNotification=false
,I/SurfaceFlinger(  256): id=12 Removed DolorFade (8/8)
W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/SurfaceFlinger(  256): id=12 Removed DolorFade (-2/8)
D/BatteryMeterView( 1176): onDraw batteryColor : -1
D/TimaKeyStoreProvider( 6925): TimaSignature is unavailable
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ActivityThread( 6925): Added TimaKeyStore provider
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1176): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/PowerManagerService( 1017): Excessive delay in ColorFade : dismiss: 18ms
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/DisplayPowerController( 1017): getFinalBrightness : Summary is 5 -> 5
E/libEGL  ( 1017): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController( 1017): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/lights  ( 1017): lcd : 5 +
D/lights  ( 1017): lcd : 5 -
D/DisplayPowerController( 1017): getFinalBrightness : Summary is 5 -> 5
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/DisplayPowerController( 1017): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/PowerManagerService( 1017): [s] DisplayPowerCallbacks : onStateChanged()
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/PowerManagerService( 1017): SecHardwareInterface.setBatteryADC : true
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1017): [SO] currT = 317841019000, prevT = 77791141000, diff = 240049878000, [0.172 0.115 10.171]
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb84727c8
I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received,
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/rmt_storage(  270): wakelock acquired: 1, error no: 42
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1203296968)
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 8261(531KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 8.748ms total 201.748ms
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 2985): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 12
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/StatusBar.NetworkController( 1176): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 2985): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 12
,D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 2 on display 0
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 1
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,D/SurfaceControl( 1017): Excessive delay in setPowerMode(): 136ms
D/PowerManagerService( 1017): Excessive delay in !@display_state: ON: 136ms
D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/input/event1/device/enabled: 1
,V/ActivityManager( 1017): Display changed displayId=0
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1203296968) wakelock released: 1, error no: 0
I/rmt_storage(  270): 
,D/SensorService( 1017): [SO] currT = 317911061000, prevT = 77791141000, diff = 240119920000, [0.172 0.115 10.151]
D/SensorService( 1017): [SO] 0.172 0.115 10.151
D/SensorService( 1017): [SO] [100 -> 255]
I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb84727c8
I/DBG_DM  ( 2985): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,I/DBG_DM  ( 2985): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
D/PackageManager( 1017): delete codoeFile: 
,D/NfcService( 1440): call the applyRouting
,D/SamsungIME( 1707): showDlgMsgBox : false true true
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
I/AASA_removePackage( 1017): UID=10175 Target=com.test.thalitest
I/PalmMotion( 1017): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1017): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1017): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
E/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1017): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
D/PackageManager( 1017): result of delete: 1{1050979176}
,D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1017) 
,D/KnoxNotification( 1176): ----- inflateViews : modified publicViewLocal -----
D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 1017): turn off LED
,E/lights  ( 1017): write_led_info failed to open -1
D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1017): write_led_info failed to open -1
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/lights  ( 1017): write_led_info failed to open -1
E/lights  ( 1017): write_led_info failed to open -1
E/lights  ( 1017): write_led_info failed to open -1
E/lights  ( 1017): write_led_info failed to open -1
E/lights  ( 1017): write_led_info failed to open -1
E/lights  ( 1017): write_led_info failed to open -1
,E/lights  ( 1017): write_led_info failed to open -1
,E/SmartFaceService( 1017): onReceive: android.intent.action.SCREEN_ON
W/System.err( 1017): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
,W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1017): ,	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
E/SmartFaceService( 1017): fail to set sysfs 1
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
,W/System.err( 1017): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1017): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1017): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 1017): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1017): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1017): ,	at libcore.io.Posix.open(Native Method)
W/System.err( 1017): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1017): 	... 10 more
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/AndroidRuntime( 6891): Shutting down VM
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 12
D/KnoxNotification( 1176): ----- inflateViews : modified KnoxViewLocal -----
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,D/PersonaManager( 1176): PersonaID is invalid or persona doesn't exists. : -1
,D/InputMethodManagerService( 1017): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,D/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_SCREEN_ON
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
E/MotionRecognitionService( 1017):  handler : SCREEN_ON end
I/StatusBar( 1176): Icon Only
I/DBG_DM  ( 2985): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/DBG_DM  ( 2985): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
I/FeatureConfig( 6925): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
I/StatusBar( 1176): Icon Only
I/DBG_DM  ( 2985): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
D/PanelView( 1176): There is/are notification(s) 
I/DBG_DM  ( 2985): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
D/NotificationService( 1017): ACTION_SCREEN_ON
D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/WifiNative-wlan0( 1017): do suspend false
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SA      ( 6129): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SA      ( 6129): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10175 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,I/Timeline( 2985): Timeline: Activity_idle id: android.os.BinderProxy@222d157c time:318036
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1017): Killing 6090:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31,
,E/Watchdog( 1017): !@Sync 10
,I/wpa_supplicant( 1912): reset timer : RESET_TIMER 1
I/wpa_supplicant( 1912): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1912): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1912): Scan requested (ret=0) - scan timeout 30 seconds
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/input/event1/device/enabled: 1
D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1017): Excessive delay in MISC setInteractive(true) while turning screen on: 161ms
I/QCOM PowerHAL( 1017): Got set_interactive hint
,D/lights  ( 1017): button : 1 +
D/PowerManagerService( 1017): Excessive delay in nativeSetInteractive(true): 163ms
,D/PowerManagerService( 1017): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 299ms
W/ResourcesManager( 6925): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/UsbSettingsManager( 1017): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1017): onPackageRemoved : com.test.thalitest
,W/ResourcesManager( 6925): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_6070/cgroup.procs: No such file or directory
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6925): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/lights  ( 1017): button : 1 -
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ResourcesManager( 6925): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 6952): MountEmulatedStorage()
I/libpersona( 6952): KNOX_SDCARD checking this for 10044
E/Zygote  ( 6952): v2
I/libpersona( 6952): KNOX_SDCARD not a persona
,I/SELinux ( 6952): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6952): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6952): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6952 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6925): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_6090/cgroup.procs: No such file or directory
,D/IpRemoteDisplayController( 1017): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1017): Bridge Server is not available
,W/ResourcesManager( 6925): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/TimaKeyStoreProvider( 6952): TimaSignature is unavailable
W/ResourcesManager( 6925): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ActivityThread( 6952): Added TimaKeyStore provider
,D/PersonaManagerService( 1017): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 1017): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,W/ResourcesManager( 6925): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/NfcService( 1440): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1440): call the applyRouting
,W/ResourcesManager( 6952): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6952): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6952): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6952): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6952): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6952): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6952): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6952): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/art     ( 6891): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ResourcesManager( 6925): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/accuweather( 1589): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
D/accuweather( 1589): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1589): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1589): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
D/accuweather( 1589): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1589): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/accuweather( 1589): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1589): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
W/ResourcesManager( 6925): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/accuweather( 1589): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1589): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
E/accuweather( 1589): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 05
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SamsungIME( 1707): getNextShiftState() cursorCapsMode : 0
,W/ResourcesManager( 6925): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6925): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6925): system/finder_cp/cpdata.xml file not found
,D/PowerManagerService( 1017): [PWL] sb release: PowerManagerService.Broadcasts
,E/SQLiteLog( 6952): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6952): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase( 6952): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6952): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6952): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6952): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase( 6952): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase( 6952): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6952): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6952): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6952): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6952): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6952): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6952): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6952): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6952): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6952): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6952): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6952): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/NearbySource( 6952): Nearby Source Create!
,D/NearbyContext( 6952): Nearby Context Create!
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6952): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6952): Samsung link source created
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder

```
