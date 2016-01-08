#### Test 55431344e5dd625_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/TP/MmsSmsProvider( 1471): match 13:Elapsed time : 7.914 ms
I/DBG_POLICYDM( 5863): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
D/Mms/MethodReflector( 5792): getSubId is called
D/Mms/TelephonyUtils( 5792): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5792): getTelephonyProperty is called
D/Mms/DownloadManager( 5792): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5792): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5792): auto download without roaming -> true
D/Mms/DownloadManager( 5792): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5792): getSubId is called
D/Mms/MethodReflector( 5792): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5792): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5792): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5792): getTelephonyProperty is called
D/Mms/DownloadManager( 5792): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5792): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5792): auto download without roaming -> true
D/Mms/DownloadManager( 5792): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5792): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5792): mAutoDownload ------> true
D/Mms/DraftCache( 5792): [start]    rebuildCache consume time = 52.79849
D/ComposerPerformance( 5792): 1452237973081 ms / [DONE] Composer constructor
E/CII     ( 5792): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5792): ReservationManager()
I/Mms/ReservationManager( 5792): resetAfterConnected()
D/TP/MmsSmsProvider( 1471): query,matched:12, calling pid = 5792
D/TP/MmsSmsProvider( 1471): match 12:Elapsed time : 1.199 ms
D/TP/MmsSmsProvider( 1471): query,matched:7, calling pid = 5792
D/Mms/DraftCache( 5792): [end]    rebuildCache consume time = 6.262812
D/TP/MmsSmsProvider( 1471): match 7:Elapsed time : 1.697 ms
D/Mms/ArtClassLoader( 5792): init [DONE] art
I/Mms/ReservationManager( 5792): getReservedSendMessageCount(): retMessageCount=0
D/Mms/MmsApp( 5792): [end]    onCreate() consume time = 7.648073
D/Mms/Conversation( 5792): [start]    init() consume time = 3.795729
D/TP/MmsSmsProvider( 1471): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1471): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1471): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1471): sUpgradeVersion = 0, db.getVersion() = 81
D/TP/MmsSmsProvider( 1471): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1471): need read changed broadcast:false
D/Mms/Conversation( 5792): [end]    init consume time = 9.6275
D/Mms/MessagingNotification( 5792): [start]    init() consume time = 1.111615
D/Mms/MessagingNotification( 5792): [end]    init consume time = 1.777916
D/TP/MmsSmsProvider( 1471): query,matched:0, calling pid = 5792
V/TP/MmsSmsProvider( 1471): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1471): match 0:Elapsed time : 0.949 ms
D/Mms/Synchronizer( 5792): [start]    doSync consume time = 6.367032
D/TP/MmsSmsProvider( 1471): update, matched:300, calling pid = 5792
V/TP/MmsSmsProvider( 1471): syncDBData start
V/TP/MmsSmsProvider( 1471): syncDBData sms end
V/TP/MmsSmsProvider( 1471): syncDBData mms end
--------- beginning of system
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Mms/SpamFilter( 5792): [start]    SpamFilter fill() begin consume time = 11.334635
D/Mms/DownloadManager( 5792): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5792): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5792): getSubId is called
D/Mms/TelephonyUtils( 5792): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5792): getTelephonyProperty is called
D/Mms/DownloadManager( 5792): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5792): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5792): auto download without roaming -> true
D/Mms/DownloadManager( 5792): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5792): mAutoDownload ------> true
V/TP/MmsSmsProvider( 1471): syncDBData end
E/Zygote  ( 5965): MountEmulatedStorage()
E/Zygote  ( 5965): v2
I/SELinux ( 5965): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5965): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5965): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/libpersona( 5965): KNOX_SDCARD checking this for 10072
I/libpersona( 5965): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5965 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/TP/MmsSmsProvider( 1471): query,matched:400, calling pid = 5792
D/Mms/Synchronizer( 5792): [end]    doSync consume time = 23.886927
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/Mms/SpamFilter( 5792): [end]    SpamFilter fill() finished consume time = 15.699063
D/ChimeraCfgMgr( 1971): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1971): Loading module APK com.google.android.play.games
D/TimaKeyStoreProvider( 5965): TimaSignature is unavailable
D/ActivityThread( 5965): Added TimaKeyStore provider
D/PackageBroadcastService( 1971): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/FreeMessageStatusReceiver( 5792): onReceive, action : android.intent.action.PACKAGE_ADDED
I/DBG_POLICYDM( 5863): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 5965): onCreate
D/BadgeProvider( 5965): DatabaseHelper
E/Zygote  ( 5982): MountEmulatedStorage()
E/Zygote  ( 5982): v2
I/libpersona( 5982): KNOX_SDCARD checking this for 10047
I/libpersona( 5982): KNOX_SDCARD not a persona
I/SELinux ( 5982): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5982 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 5982): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5982): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5863): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
D/TimaKeyStoreProvider( 5982): TimaSignature is unavailable
D/Mms/MessagingNotification( 5792): checkBadgeCount unreadCount=0 badgeCount=0
D/ActivityThread( 5982): Added TimaKeyStore provider
I/DBG_POLICYDM( 5863): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/TP/SmsProvider( 1471): query,matched:26, calling pid = 5792
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
D/TP/SmsProvider( 1471): match 26:Elapsed time : 2.187 ms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 5982): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5982): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5982): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1471): query,matched:6, calling pid = 5792
D/Mms/FreeMessageReceiverService( 5792): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/TP/MmsSmsProvider( 1471): match 6:Elapsed time : 2.091 ms
I/ActivityManager( 1015): Killing 5191:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
D/Mms/FreeMessageReceiverService( 5792): onHandleIntent: ACTION_PACKAGE_ADDED
I/ActivityManager( 1015): Killing 3703:com.android.providers.calendar/u0a42 (adj 15): empty #31
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6000): MountEmulatedStorage()
E/Zygote  ( 6000): v2
I/libpersona( 6000): KNOX_SDCARD checking this for 10025
I/libpersona( 6000): KNOX_SDCARD not a persona
I/SELinux ( 6000): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6000): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6000): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6000 uid=10025 gids={50025, 9997} abi=armeabi-v7a
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5191/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_3703/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 6000): TimaSignature is unavailable
D/ActivityThread( 6000): Added TimaKeyStore provider
I/ActivityManager( 1015): Killing 3816:com.google.android.talk/u0a104 (adj 15): empty #31
W/ResourcesManager( 6000): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/MyFiles ( 5982): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/OMACP   ( 6000): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
E/installd(  284): system dir 0 : /system/app/
E/installd(  284): system dir 1 : /system/priv-app/
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
D/Mms/Omacp( 5792): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/TactileAssist( 1015): enable value -1
I/TactileAssist( 1015): internal enable value -1
I/TactileAssist( 1015): intensity value -1
I/TactileAssist( 1015): saveAppList value true
I/TactileAssist( 1015): List of disabled apps :
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/OMACP   ( 6000): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 6000): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 6000): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 6000): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 6000): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/ConfigFetchService( 1971): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/OMACP   ( 6000): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/ConfigFetchService( 1971): launchTask
I/OMACP   ( 6000): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 6000): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 6000): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 6000): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 6000): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 6000): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 6000): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1015): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 6023): MountEmulatedStorage()
E/Zygote  ( 6023): v2
I/libpersona( 6023): KNOX_SDCARD checking this for 10053
I/libpersona( 6023): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6023 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1015): failed to open /acct/uid_10104/pid_3816/cgroup.procs: No such file or directory
I/SELinux ( 6023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/ChimeraCfgMgr( 1971): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1971): Module APK com.google.android.play.games already loaded
I/SELinux ( 6023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6023): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/GAv4    ( 5807): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5807):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5807):   adb logcat -s GAv4
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/ConfigFetchTask( 1971): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1X3wtX3bDakR4ZE8tkvokKBccA1GCRpqINdSzLvqu5tHuIH0nyZuZRql44yQIw6gE5U9rV1tix03mze5Vlhqg1oUQOQYVMBrpeJ7OfYmTZrcTZQFmFyqRGvfQFm-bIZeQZUE3pAIarp6Vym_DyUgrZcKdsEO97Pp-8nuxZbIkFo1tvNJXwYS58HSdKt4rsY5uj-CFMQ
D/ChimeraCfgMgr( 1971): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1971): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1971): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1971): No vision deps
D/TimaKeyStoreProvider( 6023): TimaSignature is unavailable
D/ActivityThread( 6023): Added TimaKeyStore provider
I/PeopleContactsSync( 1971): CP2 sync disabled
W/GAv4    ( 5807): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ResourcesManager( 6023): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/GAv4    ( 5807): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
D/Compatibility( 6023): onReceive() it will make start service
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Compatibility( 6023): onHandleIntent()
D/Compatibility( 6023): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
I/GoogleURLConnFactory( 1971): Using platform SSLCertificateSocketFactory
E/Zygote  ( 6044): MountEmulatedStorage()
E/Zygote  ( 6044): v2
I/libpersona( 6044): KNOX_SDCARD checking this for 1000
I/libpersona( 6044): KNOX_SDCARD not a persona
D/Compatibility( 6023): found: 2
I/ActivityManager( 1015): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6044 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/GAv4    ( 5807): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/AnalyticsTrackerProxyImpl( 5807): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
D/Compatibility( 6023): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6023): skipping ResolveInfo{5f31f3a com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6023): considering ResolveInfo{3ce427eb com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6023): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6023): enabling receiver ResolveInfo{3c10c948 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6023): enabling receiver ResolveInfo{2629d3e1 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6023): enabling receiver ResolveInfo{3f63f506 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6023): enabling receiver ResolveInfo{3adb57c7 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6023): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/ActivityManager( 1015): Killing 5462:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/System.out( 1971): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1971): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1971): (HTTPLog)-Static: isShipBuild true
I/System.out( 1971): (HTTPLog)-Thread-276-685605389: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1971): (HTTPLog)-Static: isSBSettingEnabled false
I/SELinux ( 6044): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6044): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
E/SELinux ( 6044): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/art     ( 5807): Suspending all threads took: 5.646ms
D/TimaKeyStoreProvider( 6044): TimaSignature is unavailable
D/ActivityThread( 6044): Added TimaKeyStore provider
I/DBG_POLICYDM( 5863): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
I/System.out( 1971): KnoxVpnUidStorageknoxVpnSupported API value returned is false
W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_5462/cgroup.procs: No such file or directory
I/qtaguid ( 1971): Tagging socket 87 with tag 40b00000000{1035,0} for uid -1, pid: 1971, getuid(): 10012
W/BaseAppContext( 1971): Using Auth Proxy for data requests.
W/ContextImpl( 6044): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/BaseAppContext( 1971): Using Auth Proxy for data requests.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
I/DBG_POLICYDM( 5863): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5863): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
I/ActivityManager( 1015): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6067 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/qtaguid ( 1971): Tagging socket 110 with tag 40b00000000{1035,0} for uid -1, pid: 1971, getuid(): 10012
E/Zygote  ( 6067): MountEmulatedStorage()
E/Zygote  ( 6067): v2
V/AlarmManager( 1015): waitForAlarm result :4
I/libpersona( 6067): KNOX_SDCARD checking this for 1000
I/libpersona( 6067): KNOX_SDCARD not a persona
I/SELinux ( 6067): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6067): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1015): Killing 5477:com.sec.knox.bridge/1000 (adj 15): empty #31
E/SELinux ( 6067): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6067): TimaSignature is unavailable
D/ActivityThread( 6067): Added TimaKeyStore provider
I/SL_DEBUG( 5914): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5914): isLoggable:: SL_DEBUG_EXIST = false
W/ResourcesManager( 6067): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
W/BaseAppContext( 1971): Using Auth Proxy for data requests.
W/BaseAppContext( 1971): Using Auth Proxy for data requests.
E/SMD     (  288): DCD OFF
W/BaseAppContext( 1971): Using Auth Proxy for data requests.
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5807): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
I/ServiceManager(  314): Waiting for service AtCmdFwd...
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/BaseAppContext( 1971): Using Auth Proxy for data requests.
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5477/cgroup.procs: No such file or directory
E/Zygote  ( 6089): MountEmulatedStorage()
I/libpersona( 6089): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6089): v2
I/libpersona( 6089): KNOX_SDCARD not a persona
I/SELinux ( 6089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6089): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6089 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/qtaguid ( 1971): Untagging socket 87
I/ConfigFetchService( 1971): fetch service done; releasing wakelock
I/ActivityManager( 1015): Killing 5493:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/ConfigFetchService( 1971): stopping self
W/ResourcesManager( 5807): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5807): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 6089): TimaSignature is unavailable
D/ActivityThread( 6089): Added TimaKeyStore provider
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5914): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/ResourcesManager( 6089): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
I/ActivityManager( 1015): Killing 5399:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5493/cgroup.procs: No such file or directory
W/ContextImpl( 5914): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/libprocessgroup( 1015): failed to open /acct/uid_10057/pid_5399/cgroup.procs: No such file or directory
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6113): MountEmulatedStorage()
E/Zygote  ( 6113): v2
I/libpersona( 6113): KNOX_SDCARD checking this for 10041
I/libpersona( 6113): KNOX_SDCARD not a persona
I/SELinux ( 6113): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6113 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6113): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6113): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6124 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/Zygote  ( 6124): MountEmulatedStorage()
E/Zygote  ( 6124): v2
I/libpersona( 6124): KNOX_SDCARD checking this for 10057
I/libpersona( 6124): KNOX_SDCARD not a persona
I/SELinux ( 6124): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6124): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6124): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 5006:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 6124): TimaSignature is unavailable
D/ActivityThread( 6124): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 6113): TimaSignature is unavailable
D/ActivityThread( 6113): Added TimaKeyStore provider
V/JNIHelp ( 5807): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/art     ( 1015): Explicit concurrent mark sweep GC freed 220977(14MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/41MB, paused 4.646ms total 226.900ms
I/ActivityManager( 1015): Killing 5627:com.sec.android.diagmonagent/1000 (adj 15): empty #31
D/AndroidRuntime( 6122): 
D/AndroidRuntime( 6122): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/SA      ( 6113): [SSP] onCreated
D/AndroidRuntime( 6122): CheckJNI is OFF
D/AndroidRuntime( 6122): readGMSProperty: start
D/AndroidRuntime( 6122): readGMSProperty: already setted!!
D/AndroidRuntime( 6122): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6122): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6122): readGMSProperty: end
D/AndroidRuntime( 6122): addProductProperty: start
W/ActivityThread( 5807): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/SA      ( 6113): [TPM] There is no property file
I/SA      ( 6113): [SCU] isHaveSA() - false
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/SA      ( 6113): [TPM] getModelProperty : null
I/SA      ( 6113): [TPM] getCSCProperty : null
I/SA      ( 6113): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6113): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6113): [DM] TFT FEATURE: false
I/SA      ( 6113): [PMR] Received action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/SA      ( 6113): [DM] init START
W/System  ( 5807): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34b0ccba: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/SA      ( 6113): [DM] This device is not a Vodafone
I/ProviderInstaller( 5807): Installed default security provider GmsCore_OpenSSL
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/ResourceType( 6113): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6113): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6113): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6113): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6113): [SCU] isHaveSA() - false
I/SA      ( 6113): support phone number id : false
I/SA      ( 6113): [DM] Supports Ref Jpn : true
I/SA      ( 6113): [DM] init END
I/SA      ( 6113): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 6113): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
I/PowerManagerService( 1015): [PWL] Off : 5s ago
I/PowerManagerService( 1015): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1015): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1971, ws=null) (elapsedTime=47778)
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1015, ws=WorkSource{10054}) (elapsedTime=666)
E/Zygote  ( 6162): MountEmulatedStorage()
E/Zygote  ( 6162): v2
I/libpersona( 6162): KNOX_SDCARD checking this for 10010
I/libpersona( 6162): KNOX_SDCARD not a persona
I/SELinux ( 6162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6162 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 6162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6162): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 5543:com.google.android.gms:car/u0a12 (adj 15): empty #31
I/art     (  304): Explicit concurrent mark sweep GC freed 8732(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.542ms total 29.468ms
D/TimaKeyStoreProvider( 6162): TimaSignature is unavailable
D/ActivityThread( 6162): Added TimaKeyStore provider
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 20.697ms
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 17.359ms
E/AffinityControl( 6122): AffinityControl: registerfunction enter
D/AndroidRuntime( 6122): Calling main entry com.android.commands.am.Am
I/splitIntent( 1015): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
I/ActivityManager( 1015): Killing 5652:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1015): mDVFSHelper.acquire()
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6184): MountEmulatedStorage()
E/Zygote  ( 6184): v2
I/libpersona( 6184): KNOX_SDCARD checking this for 10175
I/libpersona( 6184): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6184 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/SELinux ( 6184): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 2984
D/AndroidRuntime( 6122): Shutting down VM
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
D/KeyguardViewMediator( 1177): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, uhalitest
D/KeyguardViewMediator( 1177): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1177): *** Keyguard wallpaper service already unbounded
I/SELinux ( 6184): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6184): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6184): TimaSignature is unavailable
D/ActivityThread( 6184): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/ActivityManager( 1015): Display changed displayId=0
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1015): isKioskContainerExistOnDevice
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5006/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5627/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10012/pid_5543/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10142/pid_5652/cgroup.procs: No such file or directory
I/SurfaceFlinger(  257): id=11 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  257): id=11 Removed YUIInstallC (-2/9)
V/ActivityThread( 2984): updateVisibility : ActivityRecord{415e3f6 token=android.os.BinderProxy@2f98836f {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/LocationManagerService( 1015): getProviders()=[passive]
E/SQLiteLog( 1722): (10) POSIX Error : 11 SQLite Error : 3850
W/art     ( 6122): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/WebViewFactory( 6184): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,I/LibraryLoader( 6184): Time to load native libraries: 7 ms (timestamps 3151-3158)
I/LibraryLoader( 6184): Expected native library version number "",actual native library version number ""
,I/UpdateIcingCorporaServi( 6124): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/ChimeraCfgMgr( 1971): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1971): Module APK com.google.android.play.games already loaded
,V/WebViewChromiumFactoryProvider( 6184): Binding Chromium to main looper Looper (main, tid 1) {3f63f506}
,I/LibraryLoader( 6184): Expected native library version number "",actual native library version number ""
,I/chromium( 6184): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6184): Initializing chromium process, singleProcess=true
,W/art     ( 6184): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6184): ApplicationContext is null in ApplicationStatus
,W/chromium( 6184): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6184): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6184): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6184): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6184): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6184): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6184): Local Branch: 
I/Adreno-EGL( 6184): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6184): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6184):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/Mms/MmsApp( 5792):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5792): [start]    fillCache consume time = 1927.837447
I/UpdateIcingCorporaServi( 6124): UpdateCorporaTask done [took 110 ms] updated apps [took 110 ms] 
D/Mms/ComposeMessageFragment( 5792): fillCache, easy = false
,I/ActivityManager( 1015): Killing 5210:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/AbsListView( 5792): Get MotionRecognitionManager
,D/MotionRecognitionService( 1015):  ssp status : false
,D/Mms/ComposeMessageFragment( 5792): [end]    fillCache consume time = 63.535468
,W/libprocessgroup( 1015): failed to open /acct/uid_10150/pid_5210/cgroup.procs: No such file or directory
,D/Mms/BubbleViewCache( 5792): fillCache bubble = 1
,W/ActivityManager( 1015): Activity pause timeout for ActivityRecord{2484dcdc u0 com.test.thalitest/.MainActivity t231}
,W/art     ( 6184): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6184): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6184): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6184): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6184): CordovaWebView is running on device made by: samsung
,W/art     ( 6184): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6184): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6184): Render dirty regions requested: true
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
,D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,W/chromium( 6184): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6184): updateVisibility : ActivityRecord{3a09b153 token=android.os.BinderProxy@5a2378d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6184): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6184): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1015): Focus entered window: 6184
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6184): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6184): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6184): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6184): Enabling debug mode 0
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1177): There is/are notification(s) 
,I/ActivityManager( 1015): Displayed Component not be shown by security: +738ms (total +840ms)
,I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{2484dcdc u0 com.test.thalitest/.MainActivity t231} time:83733
W/ActivityManager( 1015): mDVFSHelper.release()
,I/SamsungIME( 1775): getCurrentCandidateView
,I/SurfaceFlinger(  257): id=13 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=13 Removed uhalitest (-2/9),
,W/IInputConnectionWrapper( 6184): showStatusIcon on inactive InputConnection
,I/Timeline( 6184): Timeline: Activity_idle id: android.os.BinderProxy@5a2378d time:83748
,D/SamsungIME( 1775): Dismiss ExpandCandiate
,I/SamsungIME( 1775): getDebugLevel  : 0x4f4c
,W/BindingManager( 6184): Cannot call determinedVisibility() - never saw a connection for the pid: 6184
,I/SamsungIME( 1775): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1775): KeybaordView init() : load resources
,I/SamsungIME( 1775): getCurrentKeyboard
I/SamsungIME( 1775): getTextKeyboard
,D/SamsungIME( 1775): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6184): Set native->JS mode to OnlineEventsBridgeMode
,D/AcmsKeyStoreHelper( 5855):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5855): Key Store exist
I/AcmsKeyStoreHelper( 5855): Hence loading the keystore file
,D/jxcore_app_log( 6184): JniHelper::setJavaVM(0xb8f0c450), pthread_self() = -1186594232
,D/JX-Cordova( 6184): jxcore cordova android initializing
,D/AcmsKeyStoreHelper( 5855):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5855): getKeyStoreForApplication success 
D/AcmsCore( 5855): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5855): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5855): Decrementing - Counter value: 1
D/AcmsCore( 5855): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5855): This is NOT a valid MirrorLink app
D/AcmsCore( 5855): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5855): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5855): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5855): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5855): getSvcCounter - Counter value: 0
D/AcmsService( 5855): Enter onDestroy
I/AcmsService( 5855): cleanUp(): inside service clean up
D/AcmsCore( 5855): AcmsCore: inside DeInit
D/AcmsCore( 5855): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5855): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5855): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5855): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5855): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5855): getSvcCounter - Counter value: 0
D/AcmsService( 5855): killing acms process
I/Process ( 5855): Sending signal. PID: 5855 SIG: 9
,I/ActivityManager( 1015): Process ACMS.Process (pid 5855)(adj 0) has died(64,1085)
,I/DBG_POLICYDM( 5863): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5863): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log( 6184): Initializing JXcore engine
,W/jxcore-log( 6184): JXcore engine is ready
,W/jxcore-log( 6184): Starting JXcore engine
,E/audit   ( 1858): type=1400 msg=audit(1452237977.241:205): avc:  denied  { ioctl } for  pid=6184 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1858):  SEPF_SM-A500FU_5.0.2_0027
,E/audit   ( 1858): type=1300 msg=audit(1452237977.241:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=3 a3=bedaad58 items=0 ppid=304 ppcomm=main pid=6184 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1858): type=1320 msg=audit(1452237977.241:205): 
,W/jxcore-log( 6184): Platform android
W/jxcore-log( 6184): 
,W/jxcore-log( 6184): Process ARCH arm
W/jxcore-log( 6184): 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4241, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,I/ActivityManager( 1015): Killing 5117:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/libprocessgroup( 1015): failed to open /acct/uid_10040/pid_5117/cgroup.procs: No such file or directory
,I/jxcore-log( 6184): JXcore Cordova bridge is ready!
I/jxcore-log( 6184): 
,W/jxcore-log( 6184): JXcore engine is started
I/Choreographer( 6184): Skipped 131 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6184): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigService( 1722): onDestroy
,D/SSRM:n  ( 1015): SIOP:: AP = 350
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6184): Toggling radios to true
I/jxcore-log( 6184): 
,D/BluetoothAdapter( 6184): enable()
,D/BluetoothAdapter( 6184): enable(): BT is already enabled..!
,D/SecContentProvider( 1015): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1015): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1015): mCursor = null
,D/WifiService( 1015): setWifiEnabled: true pid=6184, uid=10175
,W/ActivityManager( 1015): Permission Denial: getCurrentUser() from pid=6184, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1015): Failed getting userId using ActivityManagerNative
W/WifiService( 1015): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6184, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1015): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1015): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1015): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1015): name = wifi_on
,I/WifiService( 1015): disconnect: pid=6184, uid=10175
,I/wpa_supplicant( 2073): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6184): Radios toggled
I/jxcore-log( 6184): 
,I/jxcore-log( 6184): Received device characteristics:
I/jxcore-log( 6184): Bluetooth address: 7C:F9:0E:51:18:22
I/jxcore-log( 6184): Bluetooth name: Thali Test (Galaxy A5)
I/jxcore-log( 6184): Device name: samsung-SM-A500FU
I/jxcore-log( 6184): 
,I/jxcore-log( 6184): Perf Test app loaded loaded
I/jxcore-log( 6184): 
,I/jxcore-log( 6184): check test folder
I/jxcore-log( 6184): 
,I/jxcore-log( 6184): found test : ./testFindPeers.js
I/jxcore-log( 6184): 
,I/jxcore-log( 6184): found test : ./testSendData.js
I/jxcore-log( 6184): 
,I/wpa_supplicant( 2073): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2073): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2073): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
D/Tethering( 1015): InitialState.processMessage what=4
I/wpa_supplicant( 2073): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2073): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 2073): Cmd 35605 not handled
E/WifiStateMachine( 1015): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 2073): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2073): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2073): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2073): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 2073): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 2073): First Scan Start
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2073): Scan requested (ret=0) - scan timeout 30 seconds
E/Tethering( 1015): No numeric data
,D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering( 1015): clearTetheredNotification()
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1177): updateTetherState():false, false
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,V/NetworkStats( 1015): performPollLocked() took 9ms
,E/WifiNative-wlan0( 1015): do suspend true
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NativeCrypto( 1722): Read error: ssl=0xb9498440: I/O error during system call, Connection timed out
,V/NativeCrypto( 1722): SSL shutdown failed: ssl=0xb9498440: I/O error during system call, Broken pipe
,E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit,
,E/WifiStateMachine( 1015): Start Disconnecting Watchdog 1
I/wpa_supplicant( 2073): wlan0: Setting scan request: 0 sec 0 usec
D/ConnectivityService( 1015): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1015): Tagging socket 386 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1015, getuid(): 1000
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14949 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6950 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/qtaguid ( 1015): Untagging socket 386
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,E/WifiNative-wlan0( 1015): do suspend true
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/Hs20UtilService( 3639): Starting #8
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
I/Hs20UtilService( 3639): Message received 5007
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1324): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1324): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/CommandListener(  278): Clearing all IP addresses on wlan0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
D/ConnectivityService( 1015): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
D/ConnectivityService( 1015): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1015): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1015): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1015): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1471): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1471): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,V/NetworkStats( 1015): updateIfacesLocked()
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
V/NetworkStats( 1015): performPollLocked() took 3ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/WifiNetworkAgent( 1015): NetworkAgent: NetworkAgent channel lost
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityService( 1015): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): doQuit - quitNow()
I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,E/Zygote  ( 6250): MountEmulatedStorage()
,E/Zygote  ( 6250): v2
I/libpersona( 6250): KNOX_SDCARD checking this for 10104
I/libpersona( 6250): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6250 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 6250): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6250): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 6250): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/Choreographer( 6184): Skipped 122 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6184): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TimaKeyStoreProvider( 6250): TimaSignature is unavailable
,D/ActivityThread( 6250): Added TimaKeyStore provider
,W/ResourcesManager( 6250): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3,
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3,
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3,
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3,
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3,
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,I/Babel_SMS( 6250): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6250): MmsConfig.loadMmsSettings
I/Babel_SMS( 6250): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 6250): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6250): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6250): MmsConfig.loadFromResources
,E/Babel_SMS( 6250): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6250): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  283): getCameraInfo: X
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6250): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6250): startup - clean
,I/Babel   ( 6250): deleted: false for 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3639): Starting #9
,I/Hs20UtilService( 3639): Message received 5007,
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1324): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1324): MountReceiver.mPrefHandler - 7002
,W/VideoCapabilities( 6250): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6250): Unsupported mime audio/evrc
,W/AudioCapabilities( 6250): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6250): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6250): Unsupported mime audio/mpeg-L2
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6250): Unsupported mime audio/x-ms-wma
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6250): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6250): Unsupported mime audio/qcelp
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/AudioCapabilities( 6250): Unsupported mime audio/evrc
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 2984): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/DBG_DM  ( 2984): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,W/VideoCapabilities( 6250): Unsupported mime video/wvc1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ApplicationPolicy( 1015): updateDataUsageMap
,W/VideoCapabilities( 6250): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6250): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6250): Unsupported mime video/wvc1
,W/VideoCapabilities( 6250): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6250): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6250): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6250): Unsupported mime video/mp43
,W/VideoCapabilities( 6250): Unsupported mime video/sorenson
,W/VideoCapabilities( 6250): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6250): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6250): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6250): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6250): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6250): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1015): Killing 5044:com.google.android.music:main/u0a111 (adj 15): empty #31
,I/vclib   ( 6250): onServiceConnected
,W/Babel   ( 6250): Attempted to change video mute state without an active call.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_10111/pid_5044/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/PCWCLIENTTRACE_PushUtil( 5840): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5840): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5840): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5840): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
I/splitIntent( 1015): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1015): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/PCWCLIENTTRACE_SYSTEMReceiver( 5840): noConnectivity : true
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6293): MountEmulatedStorage()
,E/Zygote  ( 6293): v2
I/libpersona( 6293): KNOX_SDCARD checking this for 10111
I/libpersona( 6293): KNOX_SDCARD not a persona
,I/SELinux ( 6293): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6293 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6293): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6293): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 2073): nl80211: Received scan results (10 BSSes)
,I/wpa_supplicant( 2073): wlan0: Setting scan request: 8 sec 0 usec
,V/AlarmManager( 1015): waitForAlarm result :4
I/wpa_supplicant( 2073): Trying to associate with SSID '4E47373030',
I/wpa_supplicant( 2073): Trying to associate with  'G700'
I/wpa_supplicant( 2073): Re-associate with C0.AA.48
D/WifiMonitor( 1015): didn't find BSSID Trying to associate with SSID 'NG700',
I/wpa_supplicant( 2073): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 2073): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1015): mCursor = null
,D/TimaKeyStoreProvider( 6293): TimaSignature is unavailable
,D/ActivityThread( 6293): Added TimaKeyStore provider
,E/wpa_supplicant( 2073): Cmd 35605 not handled
,I/wpa_supplicant( 2073): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2073): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2073): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 2073): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 2073): Associated with C0.AA.48
I/wpa_supplicant( 2073): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2073): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2073): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false,
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false,
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true,
D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceStatusChanged wlan0, true
,E/Tethering( 1015): No numeric data
,D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1015): clearTetheredNotification()
,V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
I/wpa_supplicant( 2073): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
I/wpa_supplicant( 2073): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 2073): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 2073): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 2073): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2073): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2073): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
I/wpa_supplicant( 2073): Blacklist: Clear (temp) 
I/wpa_supplicant( 2073): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceStatusChanged wlan0, true
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,V/NetworkStats( 1015): performPollLocked() took 10ms
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/WifiNative-wlan0( 1015): callSECApiVoid - ID [50]
,I/MusicStore( 6293): Database version: 120
,E/WifiConfigStore( 1015): setLastSelectedConfiguration -1
,D/ConnectivityService( 1015): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1015): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  278): Setting iface cfg
,E/WifiStateMachine( 1015): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1015): mCursor = null
,E/WifiNative-wlan0( 1015): do suspend false
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6293): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6293): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6293): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/SQLiteLog( 1722): (10) POSIX Error : 11 SQLite Error : 3850,
,W/ResourcesManager( 6293): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6293): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6293): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/dhcpcd  ( 6316): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6316): version 5.5.6 starting
,W/ActivityThread( 6293): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6293): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31c678ac: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6293): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6293): GMSCore installation verified
,E/dhcpcd  ( 6316): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/ConfigStore( 6293): Config Database version: 1
,I/dhcpcd  ( 6316): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 6316): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6316): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6316): bssid match
I/dhcpcd  ( 6316): wlan0: rebinding lease of 192.168.1.137
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1015): getStreamVolume 3 index 0
,I/MediaRouter( 6293): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6293): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6327): MountEmulatedStorage(),
E/Zygote  ( 6327): v2
I/libpersona( 6327): KNOX_SDCARD checking this for 10002,
I/libpersona( 6327): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6327 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6327): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6327): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6327): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GHttpClientFactory( 6293): Using our fixed implementation of GMSCore's GoogleHttpClient
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6293): Using platform SSLCertificateSocketFactory
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/TimaKeyStoreProvider( 6327): TimaSignature is unavailable
,D/ActivityThread( 6327): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 5354:com.google.android.gm/u0a101 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 5136:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6346): MountEmulatedStorage()
,E/Zygote  ( 6346): v2,
I/libpersona( 6346): KNOX_SDCARD checking this for 1000
I/libpersona( 6346): KNOX_SDCARD not a persona
,I/SELinux ( 6346): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6346): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6346): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6346 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6346): TimaSignature is unavailable
,D/ActivityThread( 6346): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6346): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1015): failed to open /acct/uid_10101/pid_5354/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10044/pid_5136/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6316): wlan0: acknowledged 192.168.1.137 from 192.168.1.1
,I/DIAGMON_AGENT( 6346): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6346): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/DIAGMON_AGENT( 6346): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6346): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6346): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6346): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6361): MountEmulatedStorage(),
E/Zygote  ( 6361): v2
,I/libpersona( 6361): KNOX_SDCARD checking this for 10009
I/libpersona( 6361): KNOX_SDCARD not a persona
,I/SELinux ( 6361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1015): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6361 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1015): Killing 4127:com.sec.spp.push/u0a35 (adj 15): empty #31
,I/SELinux ( 6361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 6361): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 6316): wlan0: leased 192.168.1.137 for 86400 seconds
,D/TimaKeyStoreProvider( 6361): TimaSignature is unavailable
,D/ActivityThread( 6361): Added TimaKeyStore provider,
,I/ActivityManager( 1015): Killing 5776:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31,
,W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_4127/cgroup.procs: No such file or directory
,I/KLMS-2.5.183: ( 3669): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 08:26:22 GMT+01:00 2016
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3669): KLMSAbstractReciever(): onReceive().END.,
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3669): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3669): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3669): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3669): StateImplV2(): networkChangeListener().END
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6394 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 6394): MountEmulatedStorage()
E/Zygote  ( 6394): v2
I/libpersona( 6394): KNOX_SDCARD checking this for 10034
I/libpersona( 6394): KNOX_SDCARD not a persona
,I/SELinux ( 6394): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onDestroy(),
I/SELinux ( 6394): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6394): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6394): TimaSignature is unavailable,
D/ActivityThread( 6394): Added TimaKeyStore provider
,E/WifiNative-wlan0( 1015): do suspend true
,W/libprocessgroup( 1015): failed to open /acct/uid_10100/pid_5776/cgroup.procs: No such file or directory
,I/SO_AGENT( 6394): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5863): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,I/DBG_POLICYDM( 5863): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 6113): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,E/WifiStateMachine( 1015): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
I/SA      ( 6113): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
E/WifiStateMachine( 1015): VerifyingLinkState enter
I/SA      ( 6113): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 6113): [SLFUCHKMGR] constructor called
,D/WifiNative-wlan0( 1015): callSECApiInt - ID [210]
I/DBG_POLICYDM( 5863): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/ConnectivityService( 1015): updateNetworkInfo()
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1015): Adding iface wlan0 to network 503
E/DBG_POLICYDM( 5863): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5863): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... ,
,I/SA      ( 6113): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6113): [OR] == isSIMCardReady false ==
,I/SA      ( 6113): [SCU] == networkStateCheck == false
I/SA      ( 6113): [OR] onReceive END
D/WifiWatchdogStateMachine( 1015): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1015): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
I/ActivityManager( 1015): Killing 5335:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1015): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1015): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/accuweather( 1560): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService( 1015): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1015): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1015): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1015): LTETest block dns file not exists
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 1015): updateNetworkInfo()
,E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1015): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,D/ConnectivityService( 1015):    accepting network in place of null
,D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1471): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/TelephonyNetworkFactory( 1471): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker( 1015): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1015): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 1000
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1015): mBoosterFLAG : 0
I/WifiTrafficPoller( 1015): current booster mode : FullMode
,D/WifiNative-wlan0( 1015): callSECApiVoid - ID [212]
,D/ConnectivityService( 1015): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/Tethering( 1015): MasterInitialState.processMessage what=3
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NetworkStats( 1015): updateIfacesLocked()
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/accuweather( 1560): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,V/NetworkStats( 1015): performPollLocked() took 2ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/accuweather( 1560): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/accuweather( 1560): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/accuweather( 1560): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/accuweather( 1560): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1560): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1177): EthernetConnected: false,
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Zygote  ( 6421): MountEmulatedStorage(),
I/libpersona( 6421): KNOX_SDCARD checking this for 10125
E/Zygote  ( 6421): v2
I/libpersona( 6421): KNOX_SDCARD not a persona
,I/SELinux ( 6421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6421 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6421): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6421): TimaSignature is unavailable
,D/ActivityThread( 6421): Added TimaKeyStore provider
,W/ResourcesManager( 6421): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6421): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6421): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_5335/cgroup.procs: No such file or directory
,D/QuickConnect( 6421): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6421): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6421): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/System.out( 1015): KnoxVpnUidStorageknoxVpnSupported API value returned is false
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6436 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/Zygote  ( 6436): MountEmulatedStorage()
E/Zygote  ( 6436): v2
I/ActivityManager( 1015): Killing 5427:com.google.android.partnersetup/u0a15 (adj 15): empty #31
I/libpersona( 6436): KNOX_SDCARD checking this for 10145
I/libpersona( 6436): KNOX_SDCARD not a persona
,I/SELinux ( 6436): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6436): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6436): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6436): TimaSignature is unavailable
,D/ActivityThread( 6436): Added TimaKeyStore provider
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 07:26:22 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452237982446], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452237982423]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
,D/ConnectivityService( 1015): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1015): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ResourcesManager( 6436): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6436): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6436): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6436): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6436): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_10015/pid_5427/cgroup.procs: No such file or directory
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 5965): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/Zygote  ( 6459): MountEmulatedStorage()
E/Zygote  ( 6459): v2
I/libpersona( 6459): KNOX_SDCARD checking this for 1000
I/libpersona( 6459): KNOX_SDCARD not a persona
,I/SELinux ( 6459): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6459 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5807:com.google.android.apps.docs/u0a91 (adj 15): empty #31
I/SELinux ( 6459): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6459): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Launcher.Model( 1502): reloadBadges entered.
,D/BadgeProvider( 5965): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5965): sendNotify, [notify] : null
D/BadgeProvider( 5965): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5965): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5965): update, [UpdateCount] : 1
,D/TimaKeyStoreProvider( 6459): TimaSignature is unavailable
,D/ActivityThread( 6459): Added TimaKeyStore provider
,D/SecurityLogAgent( 6459): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6459): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6459): StateMachine : Current State = 1
,D/SecurityLogAgent( 6459): StateMachine : Changed Current State = 1
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6475): MountEmulatedStorage()
,E/Zygote  ( 6475): v2
I/libpersona( 6475): KNOX_SDCARD checking this for 10159
I/libpersona( 6475): KNOX_SDCARD not a persona
,I/SELinux ( 6475): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6475 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6475): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6475): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6475): TimaSignature is unavailable
,D/ActivityThread( 6475): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 34.423ms
,W/libprocessgroup( 1015): failed to open /acct/uid_10091/pid_5807/cgroup.procs: No such file or directory
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 18.777ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 17.176ms
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 67092(3MB) AllocSpace objects, 6(144KB) LOS objects, 33% free, 27MB/41MB, paused 3.105ms total 181.256ms
,I/DBG_DM  ( 2984): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/NetworkMonitor( 6293): type=WIFI subType= reason=null isConnected=true
,E/Zygote  ( 6492): MountEmulatedStorage()
,E/Zygote  ( 6492): v2
I/libpersona( 6492): KNOX_SDCARD checking this for 10075
I/libpersona( 6492): KNOX_SDCARD not a persona
I/SELinux ( 6492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1015): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6492 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6492): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1015): Killing 5823:com.samsung.helphub/1000 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 5439:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,D/TimaKeyStoreProvider( 6492): TimaSignature is unavailable
,D/ActivityThread( 6492): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1971): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  288): DCD OFF
D/ChimeraCfgMgr( 1971): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6510): MountEmulatedStorage()
E/Zygote  ( 6510): v2
I/libpersona( 6510): KNOX_SDCARD checking this for 10035
I/libpersona( 6510): KNOX_SDCARD not a persona
,I/SELinux ( 6510): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6510 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6510): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SELinux ( 6510): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_10032/pid_5439/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5823/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6510): TimaSignature is unavailable
,D/ActivityThread( 6510): Added TimaKeyStore provider
I/System.out( 6250): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6250): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6250): (HTTPLog)-Static: isShipBuild true
I/System.out( 6250): (HTTPLog)-Thread-1071-315774259: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6250): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10104
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10104
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6250): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/SPPClientService( 6510): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6510): [SystemStateMoniter] Current Time : 91234
,E/SPPClientService( 6510): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6510): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6510): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6510): PushLog.txt file is not deleted.
,D/SPPClientService( 6510): PushLog.txt file is not deleted.
,D/SPPClientService( 6510): ============PushLog. stop!
,E/Zygote  ( 6529): MountEmulatedStorage()
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6529 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6529): v2
I/libpersona( 6529): KNOX_SDCARD checking this for 10113
I/libpersona( 6529): KNOX_SDCARD not a persona
,I/SELinux ( 6529): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6529): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/art     ( 1722): Explicit concurrent mark sweep GC freed 11251(614KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/17MB, paused 1.027ms total 42.750ms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0,
E/SELinux ( 6529): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/Babel   ( 6250): connection state changed from UNKNOWN to CONNECTED
,E/SPPClientService( 6510): [[SystemStateMonitorService]] No Active Internet
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
D/TimaKeyStoreProvider( 6529): TimaSignature is unavailable
D/ActivityThread( 6529): Added TimaKeyStore provider
,W/Kids    ( 1971): [AccountUtils] Account not ready
W/Kids    ( 1971): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1971): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1971): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1971): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1971): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1971): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1971): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1971): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1971): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1971): 	at java.lang.Thread.run(Thread.java:818)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 6492): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6492): Created application version: 3.6.9 (30609)
,I/GAv4    ( 6529): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6529):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6529):   adb logcat -s GAv4
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6529): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6529): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6529): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6529): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6529): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6529): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6529): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService( 1015): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 6492): Starting books sync for 61035162, extras: ade
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 6492): (284) automatic index on view_volumes(volume_id)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6529): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/BooksConfig( 6492): GmsCore Version = 7.8.99 (2134222-436)
,I/LibraryLoader( 6529): Time to load native libraries: 21 ms (timestamps 1709-1730),
I/LibraryLoader( 6529): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6529): Binding Chromium to main looper Looper (main, tid 1) {97eea52}
,I/LibraryLoader( 6529): Expected native library version number "",actual native library version number ""
,I/chromium( 6529): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/BrowserStartupController( 6529): Initializing chromium process, singleProcess=true
,W/art     ( 6529): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/SysUtils( 6529): ApplicationContext is null in ApplicationStatus
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager( 1015): Killing 5891:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/chromium( 6529): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/libEGL  ( 6529): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6529): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6529): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6529): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6529): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6529): Local Branch: 
I/Adreno-EGL( 6529): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6529): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6529):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/AudioManagerAndroid( 6529): Requires BLUETOOTH permission
,E/BooksAccountManager( 6492): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6492): Soft error
E/BooksSync( 6492): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6492): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6492): Sync error
E/BooksSync( 6492): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6492): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6492): Finished books sync
I/NSApplication( 6529): Starting up...
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1015): failed to open /acct/uid_10152/pid_5891/cgroup.procs: No such file or directory
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/Zygote  ( 6599): MountEmulatedStorage()
E/Zygote  ( 6599): v2
I/libpersona( 6599): KNOX_SDCARD checking this for 10081
I/libpersona( 6599): KNOX_SDCARD not a persona
,I/SELinux ( 6599): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6599 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6599): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6599): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 5931:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 62583, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1015): Killing 4439:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
I/ActivityManager( 1015): Killing 5509:com.android.vending/u0a28 (adj 15): empty #32
,D/TimaKeyStoreProvider( 6599): TimaSignature is unavailable
,D/ActivityThread( 6599): Added TimaKeyStore provider
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,D/WaitQueueForNetworkActivate( 6162): notifyNetworkActivated
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,W/ContextImpl( 6162): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/libprocessgroup( 1015): failed to open /acct/uid_10012/pid_4439/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10028/pid_5509/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10156/pid_5931/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6162): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6162): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6162): exit::IDLE
D/InitializeManagerStateMachine( 6162): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6162): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6162): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6162): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6162): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6162): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6162): entry::SUCCESS
D/hcjo    ( 6162): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6162): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6162): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/InitializeManagerStateMachine( 6162): exit::SUCCESS
D/InitializeManagerStateMachine( 6162): entry::IDLE
I/Hs20UtilService( 3639): Starting #10
I/Hs20UtilService( 3639): Message received 5007
D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
,I/ActivityManager( 1015): Killing 5792:com.android.mms/u0a46 (adj 15): empty #31
I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3639): Starting #11
,I/Hs20UtilService( 3639): Message received 5007
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3639): Starting #12
,I/Hs20UtilService( 3639): Message received 5007
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3639): Starting #13
I/Hs20UtilService( 3639): Message received 5007
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1015): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1015): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5840): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5840): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5840): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5840): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
,I/splitIntent( 1015): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1015): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,D/CountryDetector( 1015): No listener is left
,V/MusicLeanback( 6293): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=4, Uoast
,W/libprocessgroup( 1015): failed to open /acct/uid_10046/pid_5792/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6346): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6346): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6346): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6346): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/PowerManagerService( 1015): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,D/SRIB_DCS( 1177): log_dcs ThreadedRenderer::initialize entered! 
,I/DBG_POLICYDM( 5863): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5863): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5863): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5863): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6361): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6361): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.183: ( 3669): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 08:26:24 GMT+01:00 2016
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3669): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onCreate()
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3669): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3669): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3669): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3669): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3669): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.183: ( 3669): NetworkChangeOperations(): uploadRequestLog().END 
,I/DBG_POLICYDM( 5863): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.183: ( 3669): StateImplV2(): networkChangeListener().END
,I/DBG_POLICYDM( 5863): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5863): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5863): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 6113): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6113): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6113): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6113): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6113): [OR] == isSIMCardReady false ==
,I/DBG_POLICYDM( 5863): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO,
,I/SA      ( 6113): [SCU] == networkStateCheck == true
I/SA      ( 6113): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 6113): isChinaCountryCode : false
I/SA      ( 6113): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6113): [OR] == networkStateCheck true ==
,I/SA      ( 6113): [OR] GetMyCountryZoneTask
I/SA      ( 6113): [OR] onReceive END
,I/SA      ( 6113): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/accuweather( 1560): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5863): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/SA      ( 6113): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/SA      ( 6113): [SSP] query invoked
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/SecContentProvider2( 1015): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1015): mCursor = null
D/accuweather( 1560): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
I/DBG_POLICYDM( 5863): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5863): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
I/SA      ( 6113): [TPMU] GetMccFromDB : null
,D/accuweather( 1560): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1560): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
I/SA      ( 6113): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6113): [TPM] isNoProxy(default) : true
,D/accuweather( 1560): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1560): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1560): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/DBG_POLICYDM( 5863): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,E/File    ( 6113): fail readDirectory() errno=2
,D/QuickConnect( 6421): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6421): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6421): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/DBG_POLICYDM( 5863): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/SecurityLogAgent( 6459): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6459): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6459): StateMachine : Current State = 1
I/DBG_POLICYDM( 5863): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/SecurityLogAgent( 6459): StateMachine : Changed Current State = 1
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1971): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1971): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/PowerManagerService( 1015): [PWL] Off : 15s ago
,I/PowerManagerService( 1015): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1015): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1971, ws=null) (elapsedTime=57780)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/SPPClientService( 6510): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6510): [SystemStateMoniter] Current Time : 92729
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SPPClientService( 6510): [SystemStateMoniter] No Connect : false
,I/System.out( 6250): (HTTPLog)-Static: isSBSettingEnabled false
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6162): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6162): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6162): exit::IDLE
D/InitializeManagerStateMachine( 6162): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6162): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6162): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6162): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6162): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6162): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6162): entry::SUCCESS
D/hcjo    ( 6162): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6162): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6162): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/InitializeManagerStateMachine( 6162): exit::SUCCESS
D/InitializeManagerStateMachine( 6162): entry::IDLE
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 1971): [AccountUtils] Account not ready
W/Kids    ( 1971): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1971): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1971): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1971): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1971): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1971): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1971): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1971): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1971): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1971): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/SA      ( 6113): [RC New] Execute method=[GET] start
,I/SA      ( 6113): [RC New] Security=[true]
,I/System.out( 6113): Thread-1045(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6113): Thread-1045(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6113): Thread-1045(ApacheHTTPLog):isShipBuild true
I/System.out( 6113): Thread-1045(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6113): Thread-1045(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): uids 10041
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10041
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6184): BLE is supported
I/jxcore-log( 6184): 
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/SA      ( 6113): [RC New] [v2liruge] api execute + 620
,I/SA      ( 6113): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6113): AsyncTask #1 calls detatch()
,I/SA      ( 6113): [ODM] saveOpenData( GEO_IP, PL )
,I/dhcpcd  ( 6316): wlan0: sending IPv6 Router Solicitation
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 33406(1755KB) AllocSpace objects, 5(140KB) LOS objects, 33% free, 27MB/41MB, paused 2.574ms total 151.723ms
,I/SA      ( 6113): [OCP] update openData : PL
,I/SA      ( 6113): [TPMU] getNetworkMcc : 
,I/SA      ( 6113): [SCU] saveMccToPreferece Start
,I/SA      ( 6113): [SCU] RegionMCC : 260
,I/SA      ( 6113): [SSP] query invoked
,I/SA      ( 6113): [TPMU] GetMccFromDB : null
,I/SA      ( 6113): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6113): [SCU] saveMccToPreferece End
,I/SA      ( 6113): [RC New] executeRequest [v2liruge] end. 831
I/SA      ( 6113): [RC New] Execute end
I/SA      ( 6113): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6113): [OR] GetMyCountryZoneTask Success
,E/SMD     (  288): DCD OFF
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6645): MountEmulatedStorage()
,I/libpersona( 6645): KNOX_SDCARD checking this for 10012
E/Zygote  ( 6645): v2
I/libpersona( 6645): KNOX_SDCARD not a persona
I/SELinux ( 6645): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6645 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6645): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6645): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/MusicLeanback( 6293): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6293): Stop autocaching.
,D/TimaKeyStoreProvider( 6645): TimaSignature is unavailable
,D/ActivityThread( 6645): Added TimaKeyStore provider
,W/ResourcesManager( 6645): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6645): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6645): VM with version 2.1.0 has multidex support
,I/MultiDex( 6645): install
I/MultiDex( 6645): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6645): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6645): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6645): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d46c9a1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6645): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,D/GCM     ( 1722): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1722): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1971): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6645): callingUid 10012, callindPid: 6645
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1971): Restart initialization of location
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1685): [182] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6293): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6293): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1015): waitForAlarm result :4
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10012
,D/GCM     ( 1722): Connected
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1722): Message class com.google.f.a.a.p
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GCM     ( 1971): Message from null null
E/GCM     ( 1971): Dropping message from null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  257): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1015): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 95849
,D/PowerManagerService( 1015): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0),
D/PowerManagerService( 1015): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{10054}) (elapsedTime=3480),
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4255, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{29ef0fab u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6492): Thread[GAThread,5,main]: No campaign data found.,
,E/SMD     (  288): DCD OFF
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5840): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5840): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5840): [GetString-S]
,I/ReactiveServiceManager( 5840): Supported : 1
,D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 12
,D/QSEECOMAPI: ( 1015): QSEECom_dealloc_memory ,
D/QSEECOMAPI: ( 1015): QSEECom_shutdown_app, app_id = 12
E/terrier ( 1015): handleString: Failed to handle string(-4)
,E/terrier ( 1015): Java_com_android_server_ReactiveService_GetString: error code = [-4],
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5840): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5840): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5840): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5840): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5840): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5840): [ensureRegistration] - No Samsung account
,D/SSRM:n  ( 1015): SIOP:: AP = 340
,I/dhcpcd  ( 6316): wlan0: sending IPv6 Router Solicitation
,I/ActivityManager( 1015): Killing 5982:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,E/SMD     (  288): DCD OFF
,W/libprocessgroup( 1015): failed to open /acct/uid_10047/pid_5982/cgroup.procs: No such file or directory
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6681): MountEmulatedStorage(),
E/Zygote  ( 6681): v2
I/libpersona( 6681): KNOX_SDCARD checking this for 10028
I/libpersona( 6681): KNOX_SDCARD not a persona
,I/SELinux ( 6681): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6681 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6681): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6681): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6681): TimaSignature is unavailable
,D/ActivityThread( 6681): Added TimaKeyStore provider
,D/Finsky  ( 6681): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,D/Finsky  ( 6681): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6716): MountEmulatedStorage()
,E/Zygote  ( 6716): v2
I/libpersona( 6716): KNOX_SDCARD checking this for 10012
I/libpersona( 6716): KNOX_SDCARD not a persona
,I/SELinux ( 6716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1015): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6716 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6716): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,W/Settings( 6681): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6681): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TimaKeyStoreProvider( 6716): TimaSignature is unavailable
,D/ActivityThread( 6716): Added TimaKeyStore provider
,W/ResourcesManager( 6716): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6716): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6716): VM with version 2.1.0 has multidex support
I/MultiDex( 6716): install
I/MultiDex( 6716): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6681): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6681): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6681): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 6681): [1131] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/JNIHelp ( 6716): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6681): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityThread( 6716): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6716): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d46c9a1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6716): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
D/GCM     ( 1722): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 6316): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 6316): wlan0: no IPv6 Routers available
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/AuthorizationBluetoothService( 1722): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,V/GmsCoreStatsServiceLauncher( 1971): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6645): callingUid 10012, callindPid: 6645
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/MDM     ( 1685): [185] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/Finsky  ( 6681): [1131] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1971): Restart initialization of location
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/Finsky  ( 6681): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PreloadUpdateManagerStateMachine( 6162): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6162): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6162): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6162): AutoUpdateTriggerManager:REQUEST2:requestInterval
,D/Finsky  ( 6681): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6681): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6681): [1] 5.onFinished: Scheduling replication attempt 2.
,I/Volley  ( 6162): RestApi Request Add : 2307
,E/File    ( 6162): fail readDirectory() errno=2
,E/SQLiteLog( 1722): (10) POSIX Error : 11 SQLite Error : 3850
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6681): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1722): Explicit concurrent mark sweep GC freed 19978(1107KB) AllocSpace objects, 8(288KB) LOS objects, 39% free, 10MB/17MB, paused 1.045ms total 38.885ms
,W/Finsky  ( 6681): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 6162): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6162): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6162): (HTTPLog)-Static: isShipBuild true
I/System.out( 6162): (HTTPLog)-Thread-1057-1003153723: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6162): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10010
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10010
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6162): execute::CHECK_TIMEOUT_FOR_UPDATE:EXECUTE
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6681): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/System.out( 6162): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6162): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 6162, getuid(): 10010
,I/qtaguid ( 6162): Untagging socket 26
,D/hcjo    ( 6162): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 6162): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 6162): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6162): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6162): entry::REQ_UPDATE_CHECK
,I/Volley  ( 6162): RestApi Request Add : 2315
,I/System.out( 6162): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6162): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6162): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 6162, getuid(): 10010
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 25900(1319KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 2.577ms total 154.312ms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6681): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6681): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6681): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6681): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1685): client connected with version: 7571000,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 6162): Untagging socket -1
,I/qtaguid ( 6162): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 6162): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 6162): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 6162): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine( 6162): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 6162): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 6162): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 6162): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 6162): exit::FINISH,
D/PreloadUpdateManagerStateMachine( 6162): entry::IDLE
,I/ActivityManager( 1015): Killing 6000:com.wsomacp/u0a25 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10025/pid_6000/cgroup.procs: No such file or directory
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4277, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,I/ActivityManager( 1015): Killing 6023:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10053/pid_6023/cgroup.procs: No such file or directory
,V/AlarmManager( 1015): waitForAlarm result :4
,D/SSRM:n  ( 1015): SIOP:: AP = 320
,I/PowerManagerService( 1015): [PWL] Off : 30s ago
,E/Watchdog( 1015): !@Sync 3
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/FactoryTest( 5601): Not factory mode
,D/FactoryTest( 5601): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5601): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5601): still no open session command from host, so toast
,W/ContextImpl( 5601): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5601): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
I/Timeline( 5601): Timeline: Activity_launch_request id:com.android.settings time:115536
,E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): mDVFSHelper.acquire()
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 6184
,E/MTPRx   ( 5601): started activity for popup,
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5601): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5601): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5601): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5601): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5601): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5601): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5601): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus entered window: 6184
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1015): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1a5d1c65 attribute=null, token = android.os.BinderProxy@316fb527
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/SettingsReceiverActivity( 5601): dev.kiessupport is : TRUE,
,D/PhoneWindow( 5601): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5601): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,V/ActivityThread( 6184): updateVisibility : ActivityRecord{3a09b153 token=android.os.BinderProxy@5a2378d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6184): Timeline: Activity_idle id: android.os.BinderProxy@5a2378d time:115717
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 300
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,W/ActivityManager( 1015): mDVFSHelper.release()
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6681): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6681): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6681): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6492): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6492): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice,
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6492): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6492): Soft error
E/BooksSync( 6492): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6492): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6492): Sync error
E/BooksSync( 6492): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6492): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6492): Finished books sync
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 122862, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 300
,I/PowerManagerService( 1015): [PWL] Off : 50s ago,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4286, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/Watchdog( 1015): !@Sync 4
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1015): ___SyncScheduler (v3) ACTIVATED___
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManagerEXT( 1015): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1015): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6681): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6681): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6681): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4287, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 75s ago
,V/AlarmManager( 1015): waitForAlarm result :4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4288, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6681): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6681): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6681): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/Watchdog( 1015): !@Sync 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4290, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 280
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 105s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/Finsky  ( 6681): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6681): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6681): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6492): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6492): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6492): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6492): Soft error
E/BooksSync( 6492): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6492): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6492): Sync error
E/BooksSync( 6492): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6492): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6492): Finished books sync
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 185204, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 270,
,E/Watchdog( 1015): !@Sync 6
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1722): Vacuum at: now=1452238094875 tag=VacuumService
,I/GoogleURLConnFactory( 1722): Using platform SSLCertificateSocketFactory
,W/Uploader( 1722): No account for auth token provided
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1722): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1722): (HTTPLog)-Static: isShipBuild true
I/System.out( 1722): (HTTPLog)-Thread-209-916896308: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1722): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1722): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10012
,I/qtaguid ( 1722): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10012
,W/Uploader( 1722): No account for auth token provided
,I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1722): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10012
,W/Uploader( 1722): No account for auth token provided
,I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1722): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10012
,W/Uploader( 1722):  no longer exists, so no auth token.
,I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1722): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10012
,W/Uploader( 1722): No account for auth token provided
,I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1722): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10012
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 44931(2MB) AllocSpace objects, 45(760KB) LOS objects, 33% free, 27MB/41MB, paused 2.528ms total 164.193ms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1722): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1722): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1722): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1722): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1722): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1722): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1722): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1722): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10012
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,E/Uploader( 1722): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1722): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1722): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1722): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1722): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1722): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1722): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1722): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1722): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1722): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1722, getuid(): 10012
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1722): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1015): waitForAlarm result :4
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 140s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 270,
,E/Watchdog( 1015): !@Sync 7
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :8
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1015): [PWL] Off : 180s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/Watchdog( 1015): !@Sync 8
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4286, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/Watchdog( 1015): !@Sync 9
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4293, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 225s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6492): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6492): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6492): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6492): Soft error
E/BooksSync( 6492): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6492): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6492): Sync error
E/BooksSync( 6492): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6492): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6492): Finished books sync
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 309210, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1015): initializing...
I/TLC_TIMA_PKM_initialize( 1015): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 13
,I/TZ: qc_tlc_communication( 1015): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1015): Trustlet response is completed
,E/SMD     (  288): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4288, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/Watchdog( 1015): !@Sync 10
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6184): Connected to the server!
I/jxcore-log( 6184): 
,I/chromium( 6184): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  288): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6880): MountEmulatedStorage(),
E/Zygote  ( 6880): v2
I/libpersona( 6880): KNOX_SDCARD checking this for 10166
I/libpersona( 6880): KNOX_SDCARD not a persona
,I/SELinux ( 6880): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6880): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1015): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6880 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6880): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6880): TimaSignature is unavailable
,D/ActivityThread( 6880): Added TimaKeyStore provider
,W/ResourcesManager( 6880): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6880): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6880): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6880): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6880): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3daf123: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6880): Installed default security provider GmsCore_OpenSSL
,I/dex2oat ( 6904): ----------------------------------------------------
I/dex2oat ( 6904): <SS>: S T A R T I N G . . .
I/dex2oat ( 6904): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 6904): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1649066357.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-1649066357.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/YouTube MDX( 6880): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/dex2oat ( 6904): dex2oat took 30.415ms (threads: 4)
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6880): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6880): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6880): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6880): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/InstanceID/Rpc( 6880): Found 10012
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6880): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/ActivityManager( 1015): Killing 6044:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/AndroidHttpClient( 6880): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
D/AndroidHttpClient( 6880): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 6880): Thread-1203(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6880): Thread-1203(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6880): Thread-1203(ApacheHTTPLog):isShipBuild true
,I/System.out( 6880): Thread-1203(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6880): Thread-1203(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): uids 10166
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10166
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4288, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_6044/cgroup.procs: No such file or directory
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/System.out( 6880): Thread-1203 calls detatch()
,E/Watchdog( 1015): !@Sync 11
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 275s ago
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 12
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1722): Explicit concurrent mark sweep GC freed 49892(2MB) AllocSpace objects, 53(2MB) LOS objects, 39% free, 10MB/17MB, paused 1.263ms total 60.020ms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1722): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1722): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1722): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1722): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1722): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1722): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1722): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 6681): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 6681): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6681): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6681): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6681): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6681): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6681): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/System  ( 6681): Ignoring header User-Agent because its value was null.
,I/System.out( 6681): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6681): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6681): (HTTPLog)-Static: isShipBuild true
I/System.out( 6681): (HTTPLog)-Thread-1153-727806378: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6681): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10028
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/System.out( 6681): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 330s ago
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1015): !@Sync 13
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 14
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6184): --- start :testFindPeers.js---
I/jxcore-log( 6184): 
,I/jxcore-log( 6184): testFindPeers created [object Object]
I/jxcore-log( 6184): 
,I/jxcore-log( 6184): serverPort is 8876
I/jxcore-log( 6184): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6184): start: Peer ID: 7C:F9:0E:51:18:22, peer name: Thali Test (Galaxy A5)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6184): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6184): initialize: My bluetooth address is 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6184): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6184): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6184): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6184): startListeningForIncomingConnections: Starting...
,D/BluetoothSocket( 6184): bindListen(): myUserId = 0
,W/BluetoothAdapter( 6184): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6184): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]},
D/BluetoothSocket( 6184): bindListen(), new LocalSocket 
D/BluetoothSocket( 6184): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6184): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b3d3e00
D/BluetoothSocket( 6184): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6184): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6184): start: OK
I/io.jxcore.node.ConnectionHelper( 6184): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6184): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): start: Peer ID: 7C:F9:0E:51:18:22, peer name: Thali Test (Galaxy A5)
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6184): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6184): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): start: {"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6184): start: Identity string: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1015): InactiveState{ what=139292 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 1015): P2pEnabledState add service
,D/WifiP2pService( 1015): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onIsWifiPeerDiscoveryStartedChanged: true,
,D/WifiP2pService( 1015): InactiveState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService( 1015): P2pEnabledState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): start: OK
D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6184): start: OK
D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2073): USE_NETWORK : USE_NETWORK OFF
I/jxcore-log( 6184): StartBroadcasting started ok
I/jxcore-log( 6184): 
I/chromium( 6184): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6184): onConnectionManagerStateChanged: RUNNING
D/WifiP2pService( 1015): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6184): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6184): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/SMD     (  288): DCD OFF
,I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1015): InactiveState{ what=147477 },
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiDisplayController( 1015): Received list of peers.,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 1 device(s) discovered
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiP2pService( 1015): InactiveState{ what=139301 },
D/WifiP2pService( 1015): P2pEnabledState{ what=139301 },
,D/WifiP2pManager( 6184): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,D/WifiP2pService( 1015): P2pEnabledState add service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): Service request added successfully
,I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 2073): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=147477 },
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 5 device(s) discovered,
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 5 device(s) discovered
,D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1015): InactiveState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState discover services
,D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2073): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 2073): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): Service discovery started successfully
,I/wpa_supplicant( 2073): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 2073): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, ,deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6184): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6184): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
,I/jxcore-log( 6184): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 6184): 
I/jxcore-log( 6184): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 6184): 
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 6184): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 6184): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
,I/jxcore-log( 6184): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"G3-1","peerAvailable":true}]
I/jxcore-log( 6184): 
I/jxcore-log( 6184): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 6184): 
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6184): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6184): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
,I/jxcore-log( 6184): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 6184): 
,I/jxcore-log( 6184): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 6184): 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/SMD     (  288): DCD OFF
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 390s ago
,E/Watchdog( 1015): !@Sync 15
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): setState: RESTARTING
,D/WifiP2pService( 1015): InactiveState{ what=139268 }
,I/wpa_supplicant( 2073): P2P-FIND-STOPPED 
,D/WifiP2pService( 1015): InactiveState{ what=147493 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1015): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): Start timer timeout, starting now...
,D/WifiP2pService( 1015): InactiveState{ what=139265 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139265 }
D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2073): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1015): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): setState: STARTED,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 },
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.,
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1015): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true,
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): restart: Restarting...
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:,0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1015): InactiveState{ what=139307 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/WifiP2pService( 1015): P2pEnabledState{ what=139307 }
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pManager( 6184): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): Service request added successfully
D/WifiP2pService( 1015): P2pEnabledState clear service request
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiP2pService( 1015): InactiveState{ what=139301 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1015): P2pEnabledState add service request
,I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1015): InactiveState{ what=147477 }
I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76,:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/WifiP2pService( 1015): InactiveState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1015): P2pEnabledState discover services
,D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2073): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): Service discovery started successfully,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/bootchecker(  311): bootchecker wake up!!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/WifiP2pService( 1015): InactiveState{ what=147494 },
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6184): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6184): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC One M8s]
I/io.jxcore.node.ConnectionHelper( 6184): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 6184): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC One M8s] is available
,I/jxcore-log( 6184): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC One M8s","peerAvailable":true}]
I/jxcore-log( 6184): 
,I/jxcore-log( 6184): Found peer : 90:E7:C4:F6:69:77, peerAvailable: true
I/jxcore-log( 6184): 
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 6184): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6184): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/wpa_supplicant( 2073): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/WifiDisplayController( 1015): Received list of peers.
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 6184): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 6184): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
I/jxcore-log( 6184): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":true}]
I/jxcore-log( 6184): 
I/jxcore-log( 6184): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 6184): 
,I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 },
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 2073): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): restart: Restarting...
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8,
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pManager( 6184): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): Service request added successfully
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiP2pService( 1015): InactiveState{ what=139307 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1015): P2pEnabledState clear service request,
D/WifiP2pService( 1015): InactiveState{ what=139301 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1015): P2pEnabledState add service request
,E/SMD     (  288): DCD OFF
,D/WifiP2pService( 1015): InactiveState{ what=139310 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139310 },
D/WifiP2pService( 1015): P2pEnabledState discover services
D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2073): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 2073): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): Service discovery started successfully,
,I/wpa_supplicant( 2073): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 2073): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1015): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiP2pService( 1015): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 6184): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper( 6184): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1],
I/io.jxcore.node.ConnectionHelper( 6184): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6184): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,E/Watchdog( 1015): !@Sync 16
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): setState: RESTARTING
,D/WifiP2pService( 1015): InactiveState{ what=139268 }
,I/wpa_supplicant( 2073): P2P-FIND-STOPPED 
,D/WifiP2pService( 1015): InactiveState{ what=147493 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1015): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 17
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): Start timer timeout, starting now...
,D/WifiP2pService( 1015): InactiveState{ what=139265 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139265 }
D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2073): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): P2P device discovery started successfully
D/WifiP2pService( 1015): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1015): InactiveState{ what=147477 }
I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 10 device(s) discovered
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): restart: Restarting...
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80,
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1015): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1015): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1015):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1015): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1015): P2pEnabledState clear service request
,D/WifiP2pManager( 6184): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1015): InactiveState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): Service request added successfully
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiP2pService( 1015): InactiveState{ what=139301 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1015): P2pEnabledState add service request
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,D/WifiP2pService( 1015): InactiveState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1015): P2pEnabledState discover services
,D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2073): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): Service discovery started successfully,
,I/PowerManagerService( 1015): [PWL] Off : 455s ago
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2073): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 },
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 10 device(s) discovered
,D/WifiDisplayController( 1015): Received list of peers.
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b,
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/WifiDisplayController( 1015):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6184): timeout now
I/jxcore-log( 6184): 
,I/jxcore-log( 6184): weAreDoneNow
I/jxcore-log( 6184): 
,I/jxcore-log( 6184): done, now sending data to server
I/jxcore-log( 6184): 
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :8
,V/AlarmManager( 1015): No more alarm at this time.nowELAPSED=548183 batch.start=557039
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6492): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6492): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6492): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6492): Soft error
E/BooksSync( 6492): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6492): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6492): Sync error
E/BooksSync( 6492): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6492): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6492): Finished books sync
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 557039, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,E/Watchdog( 1015): !@Sync 18
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): setState: RESTARTING
,D/WifiP2pService( 1015): InactiveState{ what=139268 }
,I/wpa_supplicant( 2073): P2P-FIND-STOPPED 
,D/WifiP2pService( 1015): InactiveState{ what=147493 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1015): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,I/jxcore-log( 6184): teardown
I/jxcore-log( 6184): 
,I/jxcore-log( 6184): testFindPeers stopped
I/jxcore-log( 6184): 
,I/io.jxcore.node.ConnectionHelper( 6184): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6184): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6184): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6184): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6184): shutdown
D/BluetoothSocket( 6184): close() in, this: android.bluetooth.BluetoothSocket@3b383a2c, channel: 6, state: LISTENING
D/BluetoothSocket( 6184): close() this: android.bluetooth.BluetoothSocket@3b383a2c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b3d3e00, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b25cf5mSocket: android.net.LocalSocket@18c26a8a impl:android.net.LocalSocketImpl@37f998fb fd:FileDescriptor[111]
D/BluetoothSocket( 6184): Closing mSocket: android.net.LocalSocket@18c26a8a impl:android.net.LocalSocketImpl@37f998fb fd:FileDescriptor[111]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6184): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6184): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6184): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6184): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6184): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): stop: Stopping P2P device discovery...
,D/WifiP2pService( 1015): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6184): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6184): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6184): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6184): setState: NOT_STARTED
,D/WifiP2pService( 1015): P2pEnabledState{ what=139298 }
I/jxcore-log( 6184): StopBroadcasting went ok
I/jxcore-log( 6184): 
,D/WifiP2pService( 1015): P2pEnabledState clear service
,I/chromium( 6184): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 6184): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6184): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 1015): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6184): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6184): P2P device discovery stopped successfully
,D/WifiP2pService( 1015): InactiveState{ what=139307 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1015): P2pEnabledState clear service request
,D/WifiP2pService( 1015): remove channel information from framework
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6184): Service requests cleared successfully
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6184): teardown
I/jxcore-log( 6184): 
,E/jxcore  ( 6184): Error!: self.currentTest is null
E/jxcore  ( 6184): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"169","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:169:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7"}]
,I/chromium( 6184): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/Atfwd_Daemon(  314): Stop the daemon....,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,E/Watchdog( 1015): !@Sync 19
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 525s ago,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 20,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4286, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 21
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF

```
