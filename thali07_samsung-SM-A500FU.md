#### Test 57924002a578a80_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Mms/MessagingNotification( 5183): [end]    init consume time = 2.335365
D/Mms/MmsApp( 5183): [end]    onCreate() consume time = 0.754791
D/TP/MmsSmsProvider( 1465): query,matched:0, calling pid = 5183
V/TP/MmsSmsProvider( 1465): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1465): match 0:Elapsed time : 1.255 ms
D/Mms/Synchronizer( 5183): [start]    doSync consume time = 6.947136
--------- beginning of system
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/Mms/SpamFilter( 5183): [start]    SpamFilter fill() begin consume time = 9.549895
E/Zygote  ( 5359): MountEmulatedStorage()
E/Zygote  ( 5359): v2
I/SELinux ( 5359): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5359): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/libpersona( 5359): KNOX_SDCARD checking this for 10072
I/libpersona( 5359): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5359 uid=10072 gids={50072, 9997} abi=armeabi-v7a
E/SELinux ( 5359): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TP/MmsSmsProvider( 1465): update, matched:300, calling pid = 5183
V/TP/MmsSmsProvider( 1465): syncDBData start
V/TP/MmsSmsProvider( 1465): syncDBData sms end
V/TP/MmsSmsProvider( 1465): syncDBData mms end
V/TP/MmsSmsProvider( 1465): syncDBData end
D/Mms/Synchronizer( 5183): [end]    doSync consume time = 14.167344
D/TP/MmsSmsProvider( 1465): query,matched:400, calling pid = 5183
D/Mms/SpamFilter( 5183): [end]    SpamFilter fill() finished consume time = 2.949115
D/Mms/DownloadManager( 5183): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5183): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5183): getSubId is called
D/Mms/TelephonyUtils( 5183): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5183): getTelephonyProperty is called
D/Mms/DownloadManager( 5183): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5183): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5183): auto download without roaming -> true
D/Mms/DownloadManager( 5183): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5183): mAutoDownload ------> true
D/Mms/ArtClassLoader( 5183): init [DONE] art
D/Mms/FreeMessageStatusReceiver( 5183): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/TimaKeyStoreProvider( 5359): TimaSignature is unavailable
D/ActivityThread( 5359): Added TimaKeyStore provider
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5376): MountEmulatedStorage()
E/Zygote  ( 5376): v2
I/SELinux ( 5376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5376): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/libpersona( 5376): KNOX_SDCARD checking this for 10047
I/libpersona( 5376): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5376 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/TimaKeyStoreProvider( 5376): TimaSignature is unavailable
D/ActivityThread( 5376): Added TimaKeyStore provider
D/Mms/FreeMessageReceiverService( 5183): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
I/ActivityManager( 1014): Killing 4401:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
D/Mms/FreeMessageReceiverService( 5183): onHandleIntent: ACTION_PACKAGE_ADDED
I/ActivityManager( 1014): Killing 3591:com.android.providers.calendar/u0a42 (adj 15): empty #32
W/ResourcesManager( 5376): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5376): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5376): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/BadgeProvider( 5359): onCreate
D/BadgeProvider( 5359): DatabaseHelper
D/Mms/MessagingNotification( 5183): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1465): query,matched:26, calling pid = 5183
D/TP/SmsProvider( 1465): match 26:Elapsed time : 1.663 ms
D/TP/MmsSmsProvider( 1465): query,matched:6, calling pid = 5183
D/TP/MmsSmsProvider( 1465): match 6:Elapsed time : 1.764 ms
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4401/cgroup.procs: No such file or directory
E/Zygote  ( 5396): MountEmulatedStorage()
E/Zygote  ( 5396): v2
I/libpersona( 5396): KNOX_SDCARD checking this for 10025
I/libpersona( 5396): KNOX_SDCARD not a persona
I/SELinux ( 5396): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5396 uid=10025 gids={50025, 9997} abi=armeabi-v7a
W/libprocessgroup( 1014): failed to open /acct/uid_10042/pid_3591/cgroup.procs: No such file or directory
I/SELinux ( 5396): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5396): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5396): TimaSignature is unavailable
D/ActivityThread( 5396): Added TimaKeyStore provider
I/ActivityManager( 1014): Killing 4868:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
W/ResourcesManager( 5396): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/libprocessgroup( 1014): failed to open /acct/uid_10069/pid_4868/cgroup.procs: No such file or directory
W/art     ( 1854): Verification of void com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0(android.content.Context, com.google.android.gms.common.app.BaseApplicationContext) took 271.882ms
D/MyFiles ( 5376): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager( 1014): Killing 4884:com.sec.knox.bridge/1000 (adj 15): empty #31
I/OMACP   ( 5396): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
D/Mms/Omacp( 5183): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/TactileAssist( 1014): enable value -1
I/TactileAssist( 1014): internal enable value -1
I/TactileAssist( 1014): intensity value -1
I/TactileAssist( 1014): saveAppList value true
I/TactileAssist( 1014): List of disabled apps :
I/OMACP   ( 5396): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/OMACP   ( 5396): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/OMACP   ( 5396): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/OMACP   ( 5396): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 5392): 
D/AndroidRuntime( 5392): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5392): CheckJNI is OFF
D/AndroidRuntime( 5392): readGMSProperty: start
D/AndroidRuntime( 5392): readGMSProperty: already setted!!
D/AndroidRuntime( 5392): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5392): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5392): readGMSProperty: end
D/AndroidRuntime( 5392): addProductProperty: start
E/Zygote  ( 5416): MountEmulatedStorage()
I/libpersona( 5416): KNOX_SDCARD checking this for 10053
E/Zygote  ( 5416): v2
I/libpersona( 5416): KNOX_SDCARD not a persona
E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
I/SELinux ( 5416): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5416): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5416): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5416 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
D/TimaKeyStoreProvider( 5416): TimaSignature is unavailable
D/ActivityThread( 5416): Added TimaKeyStore provider
W/ResourcesManager( 5416): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/OMACP   ( 5396): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5396): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5396): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5396): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5396): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5396): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5396): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5396): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
D/PackageManager( 1014): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
I/OMACP   ( 5396): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/Compatibility( 5416): onReceive() it will make start service
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5416): onHandleIntent()
D/Compatibility( 5416): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10174, android.intent.extra.user_handle=0}]
D/Compatibility( 5416): found: 2
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4884/cgroup.procs: No such file or directory
E/Zygote  ( 5443): MountEmulatedStorage()
E/Zygote  ( 5443): v2
I/libpersona( 5443): KNOX_SDCARD checking this for 1000
I/libpersona( 5443): KNOX_SDCARD not a persona
I/SELinux ( 5443): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1014): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=5443 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5443): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5443): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5416): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5416): skipping ResolveInfo{3c66a608 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5416): considering ResolveInfo{307b51a1 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5416): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5416): enabling receiver ResolveInfo{3ae6ffc6 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5416): enabling receiver ResolveInfo{f6d6b87 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5416): enabling receiver ResolveInfo{19c41ab4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5416): enabling receiver ResolveInfo{13da66dd com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/TimaKeyStoreProvider( 5443): TimaSignature is unavailable
D/ActivityThread( 5443): Added TimaKeyStore provider
D/Compatibility( 5416): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ConfigFetchService( 1854): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1854): launchTask
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ContextImpl( 5443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1854): Module APK com.google.android.play.games already loaded
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5463): MountEmulatedStorage()
I/libpersona( 5463): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5463): v2
I/libpersona( 5463): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5463 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/ActivityManager( 1014): Killing 4899:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
D/Vision  ( 1854): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Vision  ( 1854): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1854): No vision deps
V/ConfigFetchTask( 1854): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1ValWPmTt8y7kwHjah-UWvGF9RGC7nhEy_tb65-E4wTL8KdxfhuZOjahZV0EfouNmoRIGUXO23HiWZeNUXSsWa_RRIfT0EK_Mvi4Ej1HdpxfKer2cIkaSOGr0BgLbqSZqYscP3e8KktSxMRNCwYaNhX9EH6XR3W57kCm_sPGjKBVoZGUQK48jALHTvyuxJzzuPnqiOH-OLlc3kQWqKHsPNFlv7hrqwTeLnDF1PXO3XcNgClnC0
I/PeopleContactsSync( 1854): CP2 sync disabled
I/GoogleURLConnFactory( 1854): Using platform SSLCertificateSocketFactory
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/System.out( 1854): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1854): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1854): (HTTPLog)-Static: isShipBuild true
I/System.out( 1854): (HTTPLog)-Thread-244-852884559: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1854): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
I/GAv4    ( 5202): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5202):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5202):   adb logcat -s GAv4
W/GAv4    ( 5202): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ConfigFetchTask( 1854): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1854): fetch service done; releasing wakelock
I/ConfigFetchService( 1854): stopping self
I/SELinux ( 5463): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5463): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5463): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/GAv4    ( 5202): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4899/cgroup.procs: No such file or directory
I/SL_DEBUG( 5329): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5329): isLoggable:: SL_DEBUG_EXIST = false
D/TimaKeyStoreProvider( 5463): TimaSignature is unavailable
W/AnalyticsTrackerProxyImpl( 5202): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
D/ActivityThread( 5463): Added TimaKeyStore provider
W/GAv4    ( 5202): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/ResourcesManager( 5463): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5488): MountEmulatedStorage()
E/Zygote  ( 5488): v2
I/libpersona( 5488): KNOX_SDCARD checking this for 1000
I/libpersona( 5488): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5488 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 4975:com.google.android.apps.plus/u0a120 (adj 15): empty #31
I/SELinux ( 5488): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5488): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5488): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5329): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/art     ( 5202): Suspending all threads took: 40.107ms
D/TimaKeyStoreProvider( 5488): TimaSignature is unavailable
D/ActivityThread( 5488): Added TimaKeyStore provider
W/ResourcesManager( 5488): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
D/AcmsKeyStoreHelper( 5251):  getKeyStoreForApplication Enter
I/ActivityManager( 1014): Killing 4217:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
E/AffinityControl( 5392): AffinityControl: registerfunction enter
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5329): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/AndroidRuntime( 5392): Calling main entry com.android.commands.am.Am
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
I/AcmsKeyStoreHelper( 5251): Key Store exist
I/AcmsKeyStoreHelper( 5251): Hence loading the keystore file
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1014): mDVFSHelper.acquire()
D/FocusedStackFrame( 1014): Set to : 0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1014): *FMB* installDecor flags : 25362712
D/AcmsKeyStoreHelper( 5251):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5251): getKeyStoreForApplication success 
D/AcmsCore( 5251): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5251): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5251): Decrementing - Counter value: 1
D/AcmsCore( 5251): AcmsCore: ACMS_APP_INSTALLED
D/AcmsCore( 5251): This is NOT a valid MirrorLink app
D/AcmsCore( 5251): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5251): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5251): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5251): Counter value is 0: Stopping ACMS service
E/Zygote  ( 5515): MountEmulatedStorage()
E/Zygote  ( 5515): v2
I/libpersona( 5515): KNOX_SDCARD checking this for 10174
I/libpersona( 5515): KNOX_SDCARD not a persona
I/SELinux ( 5515): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5515): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5515): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1014): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5515 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 1488
D/AndroidRuntime( 5392): Shutting down VM
D/AcmsServiceMonitor( 5251): getSvcCounter - Counter value: 0
D/AcmsService( 5251): Enter onDestroy
I/AcmsService( 5251): cleanUp(): inside service clean up
D/AcmsCore( 5251): AcmsCore: inside DeInit
D/AcmsCore( 5251): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5251): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5251): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5251): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5251): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5251): getSvcCounter - Counter value: 0
D/AcmsService( 5251): killing acms process
I/Process ( 5251): Sending signal. PID: 5251 SIG: 9
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=11 createSurf (1x1),1 flag=404, uhalitest
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 5515): TimaSignature is unavailable
W/libprocessgroup( 1014): failed to open /acct/uid_10120/pid_4975/cgroup.procs: No such file or directory
D/ActivityThread( 5515): Added TimaKeyStore provider
E/Zygote  ( 5533): MountEmulatedStorage()
W/libprocessgroup( 1014): failed to open /acct/uid_10057/pid_4217/cgroup.procs: No such file or directory
E/Zygote  ( 5533): v2
I/libpersona( 5533): KNOX_SDCARD checking this for 10041
I/libpersona( 5533): KNOX_SDCARD not a persona
I/SELinux ( 5533): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5533): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5533): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1014): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5533 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
V/WindowManager( 1014): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1014): Display changed displayId=0
W/ContextImpl( 5202): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
I/art     (  306): Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 24.354ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 593us total 17.216ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 16.791ms
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/TimaKeyStoreProvider( 5533): TimaSignature is unavailable
D/ActivityThread( 5533): Added TimaKeyStore provider
V/ActivityThread( 1488): updateVisibility : ActivityRecord{302c8fba token=android.os.BinderProxy@2b7b6b24 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1488): onTrimMemory. Level: 20
D/PersonaManager( 1014): isKioskContainerExistOnDevice
W/ResourcesManager( 5202): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5202): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/SSRM:n  ( 1014): SIOP:: AP = 340
I/SurfaceFlinger(  256): id=8 Removed Mauncher (5/9)
I/SurfaceFlinger(  256): id=8 Removed Mauncher (-2/9)
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/art     ( 1014): Explicit concurrent mark sweep GC freed 193048(12MB) AllocSpace objects, 4(3MB) LOS objects, 33% free, 27MB/40MB, paused 24.828ms total 234.512ms
E/Zygote  ( 5549): MountEmulatedStorage()
E/Zygote  ( 5549): v2
I/libpersona( 5549): KNOX_SDCARD checking this for 10120
I/libpersona( 5549): KNOX_SDCARD not a persona
I/SELinux ( 5549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1014): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5549 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 4625:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
I/SELinux ( 5549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5549): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Process ACMS.Process (pid 5251)(adj 0) has died(43,1105)
W/art     ( 5392): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/TimaKeyStoreProvider( 5549): TimaSignature is unavailable
D/ActivityThread( 5549): Added TimaKeyStore provider
D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,W/ResourcesManager( 5549): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/SA      ( 5533): [SSP] onCreated
,I/WebViewFactory( 5515): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/SA      ( 5533): [TPM] There is no property file
,I/SA      ( 5533): [SCU] isHaveSA() - false
,I/SA      ( 5533): [TPM] getModelProperty : null
,I/SA      ( 5533): [TPM] getCSCProperty : null
,I/SA      ( 5533): [DM] FLOATING AMOLED FEATURE: true
,I/SA      ( 5533): [DM] PRODUCT AMOLED FEATURE: false
,I/SA      ( 5533): [DM] TFT FEATURE: false
,I/SA      ( 5533): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/LibraryLoader( 5515): Time to load native libraries: 3 ms (timestamps 2140-2143)
I/LibraryLoader( 5515): Expected native library version number "",actual native library version number ""
,W/libprocessgroup( 1014): failed to open /acct/uid_10150/pid_4625/cgroup.procs: No such file or directory
,V/JNIHelp ( 5202): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/SA      ( 5533): [DM] init START
,I/SA      ( 5533): [DM] This device is not a Vodafone
,W/ResourceType( 5533): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 5533): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 5533): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5533): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5533): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5533): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75),
W/ResourceType( 5533): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5533): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5533): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 5533): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5533): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 5533): [SCU] isHaveSA() - false
I/SA      ( 5533): support phone number id : false
I/SA      ( 5533): [DM] Supports Ref Jpn : true
I/SA      ( 5533): [DM] init END
,I/SA      ( 5533): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,V/WebViewChromiumFactoryProvider( 5515): Binding Chromium to main looper Looper (main, tid 1) {19c41ab4}
,I/LibraryLoader( 5515): Expected native library version number "",actual native library version number ""
I/SA      ( 5533): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10174 extra.user_handle.:0 ]
,I/ActivityManager( 1014): Killing 3673:com.google.android.talk/u0a104 (adj 15): empty #31
,I/chromium( 5515): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/ActivityThread( 5202): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5202): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2fb1ea04: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5202): Installed default security provider GmsCore_OpenSSL
I/ActivityManager( 1014): Killing 4123:com.google.android.gm/u0a101 (adj 15): empty #31
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BrowserStartupController( 5515): Initializing chromium process, singleProcess=true
,W/art     ( 5515): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5515): ApplicationContext is null in ApplicationStatus
,W/chromium( 5515): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5515): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5515): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5515): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5515): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5515): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5515): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5515): Local Branch: 
I/Adreno-EGL( 5515): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5515): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5515):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5515): 94388638: getState() :  mService = null. Returning STATE_OFF
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1014): failed to open /acct/uid_10101/pid_4123/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10104/pid_3673/cgroup.procs: No such file or directory
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/art     ( 5515): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5515): onDetachedFromWindow called when already detached. Ignoring
,W/ActivityManager( 1014): Activity pause timeout for ActivityRecord{1927dafa u0 com.test.thalitest/.MainActivity t233}
,D/PhoneWindow( 5515): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5515): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5515): CordovaWebView is running on device made by: samsung
,W/art     ( 5515): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5515): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 1656): Explicit concurrent mark sweep GC freed 16920(938KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 1.012ms total 46.546ms
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5598): MountEmulatedStorage(),
,E/Zygote  ( 5598): v2
I/libpersona( 5598): KNOX_SDCARD checking this for 10057
I/libpersona( 5598): KNOX_SDCARD not a persona
,I/SELinux ( 5598): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5598): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1014): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5598 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,E/SELinux ( 5598): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1014): Killing 4535:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5598): TimaSignature is unavailable
,D/ActivityThread( 5598): Added TimaKeyStore provider
,D/OpenGLRenderer( 5515): Render dirty regions requested: true
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
,D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,W/chromium( 5515): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 5515): updateVisibility : ActivityRecord{11ae4e4e token=android.os.BinderProxy@d6d5f50 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 5515): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5515): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  256): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1014): Focus entered window: 5515
,D/SRIB_DCS( 5515): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
I/OpenGLRenderer( 5515): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5515): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5515): Enabling debug mode 0
,W/libprocessgroup( 1014): failed to open /acct/uid_10040/pid_4535/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5619): MountEmulatedStorage()
E/Zygote  ( 5619): v2
I/libpersona( 5619): KNOX_SDCARD checking this for 10010
I/libpersona( 5619): KNOX_SDCARD not a persona
I/SELinux ( 5619): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
I/SELinux ( 5619): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5619): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/PanelView( 1169): There is/are notification(s) 
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1014): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5619 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5619): TimaSignature is unavailable
D/ActivityThread( 5619): Added TimaKeyStore provider
,W/IInputConnectionWrapper( 5515): showStatusIcon on inactive InputConnection
,I/Timeline( 5515): Timeline: Activity_idle id: android.os.BinderProxy@d6d5f50 time:72730
,I/ActivityManager( 1014): Displayed Component not be shown by security: +757ms (total +932ms)
,W/ActivityManager( 1014): mDVFSHelper.release()
,I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{1927dafa u0 com.test.thalitest/.MainActivity t233} time:72737
,I/SamsungIME( 1767): getCurrentCandidateView
,I/SurfaceFlinger(  256): id=11 Removed uhalitest (7/9)
,I/SurfaceFlinger(  256): id=11 Removed uhalitest (-2/9)
,I/Mms/MmsApp( 5183):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5183): [start]    fillCache consume time = 1964.833072
,D/Mms/ComposeMessageFragment( 5183): fillCache, easy = false
,D/SamsungIME( 1767): Dismiss ExpandCandiate
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1854): Module APK com.google.android.play.games already loaded
,D/AbsListView( 5183): Get MotionRecognitionManager
D/MotionRecognitionService( 1014):  ssp status : false
D/Mms/ComposeMessageFragment( 5183): [end]    fillCache consume time = 73.165208
D/LocationManagerService( 1014): getProviders()=[passive]
I/splitIntent( 1014): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 1014): Killing 4422:com.google.android.music:main/u0a111 (adj 15): empty #31
D/Mms/BubbleViewCache( 5183): fillCache bubble = 1
I/SamsungIME( 1767): getDebugLevel  : 0x4f4c
I/UpdateIcingCorporaServi( 5598): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/BindingManager( 5515): Cannot call determinedVisibility() - never saw a connection for the pid: 5515
I/SamsungIME( 1767): getDebugLevel  : 0x4f4c
I/SamsungIME( 1767): KeybaordView init() : load resources
W/libprocessgroup( 1014): failed to open /acct/uid_10111/pid_4422/cgroup.procs: No such file or directory
I/SamsungIME( 1767): getCurrentKeyboard
I/SamsungIME( 1767): getTextKeyboard
D/SamsungIME( 1767): [SwiftkeyWrapper] currentLangauge : 1701729619
I/UpdateIcingCorporaServi( 5598): UpdateCorporaTask done [took 119 ms] updated apps [took 119 ms] 
I/ActivityManager( 1014): Killing 4950:com.google.android.gms:car/u0a12 (adj 15): empty #31
D/JsMessageQueue( 5515): Set native->JS mode to OnlineEventsBridgeMode
W/ActivityManager( 1014): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
W/libprocessgroup( 1014): failed to open /acct/uid_10012/pid_4950/cgroup.procs: No such file or directory
E/SMD     (  287): DCD OFF
D/jxcore_app_log( 5515): JniHelper::setJavaVM(0xb740d450), pthread_self() = -1214877704
I/chromium( 5515): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5654): MountEmulatedStorage(),
I/libpersona( 5654): KNOX_SDCARD checking this for 10012
E/Zygote  ( 5654): v2
I/libpersona( 5654): KNOX_SDCARD not a persona
I/SELinux ( 5654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1014): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=5654 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 5654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5654): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5654): TimaSignature is unavailable
,D/ActivityThread( 5654): Added TimaKeyStore provider
,W/ResourcesManager( 5654): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5654): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5654): VM with version 2.1.0 has multidex support
I/MultiDex( 5654): install
I/MultiDex( 5654): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5654): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 5654): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5654): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bd7747: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5654): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1014): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1014): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1014): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1656): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1656): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1014): Killing 5064:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4281): callingUid 10012, callindPid: 4281
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1695): [191] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5064/cgroup.procs: No such file or directory
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1854): Restart initialization of location
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 5515): Initializing JXcore engine
W/jxcore-log( 5515): JXcore engine is ready
,E/audit   ( 1866): type=1400 msg=audit(1454460100.492:203): avc:  denied  { ioctl } for  pid=5653 comm="Thread-956" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3080 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1866):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1866): type=1300 msg=audit(1454460100.492:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=3 a3=9e7008f8 items=0 ppid=306 ppcomm=main pid=5653 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-956" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1866): type=1320 msg=audit(1454460100.492:203): 
,W/jxcore-log( 5515): Starting JXcore engine
,W/jxcore-log( 5515): Platform android
W/jxcore-log( 5515): 
W/jxcore-log( 5515): Process ARCH arm
W/jxcore-log( 5515): 
,I/jxcore-log( 5515): JXcore Cordova bridge is ready!
I/jxcore-log( 5515): 
,W/jxcore-log( 5515): JXcore engine is started
,E/jxcore  ( 5515): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5515): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5515): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1014): Set to : 0
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 5515
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,W/PluginManager( 5515): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  256): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger(  256): id=12 Removed NainActivit (-2/8)
,W/ActivityManager( 1014): mDVFSHelper.acquire()
,V/WindowManager( 1014): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1488): onRestart, Launcher: 94388638
,D/Launcher( 1488): onStart, Launcher: 94388638
,D/Launcher.HomeView( 1488): onStart
D/Launcher( 1488): onResume, Launcher: 94388638
,D/SettingsProvider( 1014): name = kids_home_mode
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10007
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
D/Launcher.HomeView( 1488): onResume
,D/Launcher( 1488): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/MenuAppsGridFragment( 1488): onResume
,D/WallpaperManager( 1488): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1488): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/splitIntent( 1014): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1014): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 4550): Receive : home resume
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/Recents_RecreateReceiver( 2436): onReceive by home
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 5183): ui event
,D/ActivityManager( 1014): handle home activity for 0
I/WallpaperManagerService( 1014): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1014): post home show event for user 0
D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/WallpaperManagerService( 1014):  force update = false; persona id = 0; current user =0; current persona = 0
D/Launcher.HomeView( 1488): onPause
D/KnoxTimeoutHandler( 1014): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/Launcher( 1488): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,V/TaskCloserActivity( 5080): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,E/Zygote  ( 5676): MountEmulatedStorage()
,E/Zygote  ( 5676): v2
I/libpersona( 5676): KNOX_SDCARD checking this for 10139
I/libpersona( 5676): KNOX_SDCARD not a persona
,I/SELinux ( 5676): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5676): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1014): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5676 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,E/SELinux ( 5676): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1014): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1488, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,I/SurfaceFlinger(  256): id=13 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1014): Focus entered window: 1488
,D/TimaKeyStoreProvider( 5676): TimaSignature is unavailable
,D/ActivityThread( 5676): Added TimaKeyStore provider
,D/SRIB_DCS( 1488): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,V/ActivityThread( 1488): updateVisibility : ActivityRecord{302c8fba token=android.os.BinderProxy@2b7b6b24 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/Launcher.HomeView( 1488): onStop
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 5515): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1767): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/PanelView( 1169): There is/are notification(s) 
,W/ResourcesManager( 5676): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.,
W/ResourcesManager( 5676): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/Timeline( 1488): Timeline: Activity_idle id: android.os.BinderProxy@2b7b6b24 time:75299
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1014): Killing 4323:flipboard.app/u0a98 (adj 15): empty #31
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget,
,W/ActivityManager( 1014): mDVFSHelper.release()
I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{30c51783 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t232} time:75326
,V/TaskCloserActivity( 5080): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,W/libprocessgroup( 1014): failed to open /acct/uid_10098/pid_4323/cgroup.procs: No such file or directory
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4271, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/ConfigService( 1656): onDestroy,
,V/AlarmManager( 1014): waitForAlarm result :4
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,V/AlarmManager( 1014): waitForAlarm result :8
,E/Zygote  ( 5698): MountEmulatedStorage()
E/Zygote  ( 5698): v2
I/libpersona( 5698): KNOX_SDCARD checking this for 10104
I/libpersona( 5698): KNOX_SDCARD not a persona
I/SELinux ( 5698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5698): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5698 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/TimaKeyStoreProvider( 5698): TimaSignature is unavailable
D/ActivityThread( 5698): Added TimaKeyStore provider
,W/ResourcesManager( 5698): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Watchdog( 1014): !@Sync 2
,I/Babel_SMS( 5698): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5698): MmsConfig.loadMmsSettings
I/Babel_SMS( 5698): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel_SMS( 5698): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5698): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5698): MmsConfig.loadFromResources
,E/Babel_SMS( 5698): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5698): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  282): getCameraInfo: X
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  282): getCameraInfo: X
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5698): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5698): startup - clean
,I/Babel   ( 5698): deleted: false for 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/VideoCapabilities( 5698): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5698): Unsupported mime audio/evrc
,W/AudioCapabilities( 5698): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5698): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5698): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5698): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5698): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5698): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5698): Unsupported mime audio/evrc
,W/VideoCapabilities( 5698): Unsupported mime video/wvc1
,W/VideoCapabilities( 5698): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5698): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5698): Unsupported mime video/wvc1
,W/VideoCapabilities( 5698): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5698): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5698): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5698): Unsupported mime video/mp43
,V/AlarmManager( 1014): waitForAlarm result :8
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
W/VideoCapabilities( 5698): Unsupported mime video/sorenson
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  277): uids 1000,
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1014): forceRefresh Fail.
,W/VideoCapabilities( 5698): Unsupported mime video/mp4v-esdp,
,I/VideoCapabilities( 5698): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5698): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5698): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5698): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5698): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1014): Killing 3969:com.sec.spp.push/u0a35 (adj 15): empty #31
,I/vclib   ( 5698): onServiceConnected
,W/Babel   ( 5698): Attempted to change video mute state without an active call.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10035/pid_3969/cgroup.procs: No such file or directory
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SQLiteLog( 1656): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ActivityManager( 1014): Killing 4778:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 5167:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10035/pid_4778/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10100/pid_5167/cgroup.procs: No such file or directory
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/PackageManager( 1014): [MSG] MCS_UNBIND
,I/ActivityManager( 1014): Killing 5202:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10091/pid_5202/cgroup.procs: No such file or directory
,V/AlarmManager( 1014): waitForAlarm result :4
,D/SSRM:n  ( 1014): SIOP:: AP = 330
,I/PowerManagerService( 1014): [PWL] Off : 30s ago,
I/PowerManagerService( 1014): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1014): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1014): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1854, ws=null) (elapsedTime=48534)
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{233b80b6 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4915): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4915): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4915): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 310
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4286, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 300,
,I/PowerManagerService( 1014): [PWL] Off : 50s ago
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4288, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/FactoryTest( 4822): Not factory mode
,D/FactoryTest( 4822): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4822): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4822): still no open session command from host, so toast
,W/ContextImpl( 4822): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4822): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4822): Timeline: Activity_launch_request id:com.android.settings time:107346
,E/PersonaManagerService( 1014): inState():  stateMachine is null !!
,I/PersonaManagerService( 1014): PersonaId don't exist
,I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1014): mDVFSHelper.acquire()
,D/FocusedStackFrame( 1014): Set to : 0
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher,
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1014): Focused application set to: xxxx
,D/InputDispatcher( 1014): Focus left window: 1488
E/MTPRx   ( 4822): started activity for popup
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,W/ResourcesManager( 4822): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4822): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4822): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4822): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4822): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4822): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 4822): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame( 1014): Set to : 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1014): Focused application set to: xxxx
,D/InputDispatcher( 1014): Focus entered window: 1488
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1014): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@87b9a7d attribute=null, token = android.os.BinderProxy@2f3d0a9b
,D/SettingsReceiverActivity( 4822): dev.kiessupport is : TRUE
,D/PhoneWindow( 4822): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4822): *FMB* installDecor flags : 8388610
,E/Watchdog( 1014): !@Sync 3
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,W/ActivityManager( 1014): mDVFSHelper.release()
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0,
,V/AlarmManager( 1014): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1014): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1014): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/SecKeyguardClockView( 1169): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1169): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 34424(1998KB) AllocSpace objects, 19(304KB) LOS objects, 33% free, 27MB/40MB, paused 2.267ms total 148.177ms,
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4915): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4915): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4915): [1] 5.onFinished: Scheduling replication attempt 3.
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4287, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,E/SMD     (  287): DCD OFF
W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1014): [PWL] Off : 75s ago
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1014): stay LED for charging,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1014): !@Sync 4
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1014): forceRefresh Fail.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4915): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4915): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4915): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4290, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.sec.spp.push
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.util.DlcRegiReceiver: pid=5763 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
E/Zygote  ( 5763): MountEmulatedStorage()
E/Zygote  ( 5763): v2
I/libpersona( 5763): KNOX_SDCARD checking this for 10035
I/libpersona( 5763): KNOX_SDCARD not a persona
,I/SELinux ( 5763): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5763): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 5763): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5763): TimaSignature is unavailable
,D/ActivityThread( 5763): Added TimaKeyStore provider
,E/SPPClientService( 5763): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5763): [PushClientApplication] Push log off : This is Ship build version
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.dlc.sender.SenderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/SPPClientService( 5763): PushLog.txt file is not deleted.
D/SPPClientService( 5763): PushLog.txt file is not deleted.
D/SPPClientService( 5763): ============PushLog. stop!
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.dlc.db.DbService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/ActivityManager( 1014): Killing 5217:com.samsung.helphub/1000 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5217/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 270
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4293, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PowerManagerService( 1014): [PWL] Off : 105s ago
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/SecKeyguardClockView( 1169): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1169): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4915): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4915): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4915): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1014): SIOP:: AP = 270
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1014): !@Sync 5
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4915): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4915): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4915): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,I/PowerManagerService( 1014): [PWL] Off : 140s ago
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED,
,I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1014): !@Sync 6
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  277): uids 1000,
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0,
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
D/NtpTrustedTime( 1014): forceRefresh Fail.,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/Watchdog( 1014): !@Sync 7
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 180s ago
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 8
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,D/SecKeyguardClockView( 1169): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1169): HomeTimezone(): 1
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1014): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1014): [PWL] Off : 225s ago,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1014): !@Sync 9
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1014): stay LED for charging
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/SMD     (  287): DCD OFF
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
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
D/QSEECOMAPI: ( 1014): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1014): Loaded image: APP id = 9
,I/TZ: qc_tlc_communication( 1014): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1014): Trustlet response is completed
,E/SMD     (  287): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1014): !@Sync 10
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 275s ago
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1014): stay LED for charging
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1014): !@Sync 11
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1656): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1656): 	,at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1656): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1656): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1656): 	at android.os.Binder.execTransact(Binder.java:461)
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
D/PersonaManager( 1169): isKioskContainerExistOnDevice
,E/PlayEventLogger( 4915): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4915): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4915): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4915): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4915): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4915): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4915): 	at android.os.Binder.execTransact(Binder.java:461)
D/PersonaManager( 1169): isKioskContainerExistOnDevice
W/System  ( 4915): Ignoring header User-Agent because its value was null.
,I/System.out( 4915): (HTTPLog)-Static: isSBSettingEnabled false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): kidsfalse mQsExpansionEnabled:true
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,D/PanelView( 1169): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 1014): stay LED for charging
I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1014): !@Sync 12
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 330s ago
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate,
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 13
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 14,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 390s ago
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1014): waitForAlarm result :8
,V/AlarmManager( 1014): No more alarm at this time.nowELAPSED=454035 batch.start=513170
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 15,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/bootchecker(  317): bootchecker wake up!!,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 16,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1014): [PWL] Off : 455s ago
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/SecKeyguardClockView( 1169): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1169): HomeTimezone(): 1
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 17
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1014): stay LED for charging
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 18
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 525s ago
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/Atfwd_Daemon(  323): Stop the daemon....,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 19,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1014): stay LED for charging
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 20
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 21
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/GLSActivity( 1656): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1656): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1656): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1656): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
,E/PlayEventLogger( 4915): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4915): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4915): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4915): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4915): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4915): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4915): 	at android.os.Binder.execTransact(Binder.java:461)
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): kidsfalse mQsExpansionEnabled:true
W/System  ( 4915): Ignoring header User-Agent because its value was null.
I/System.out( 4915): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,D/PanelView( 1169): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 600s ago
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 22
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1014): stay LED for charging
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 23
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 680s ago
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 24,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 25
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate,
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 26
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 765s ago
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 27
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1014): stay LED for charging
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 28,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 29
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 855s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,E/SMD     (  287): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1014): !@Sync 30
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 31,
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1656): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1656): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1656): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1656): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 4915): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4915): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4915): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4915): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4915): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4915): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4915): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4915): Ignoring header User-Agent because its value was null.
I/System.out( 4915): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
D/PersonaManager( 1169): isKioskContainerExistOnDevice
D/PersonaManager( 1169): isKioskContainerExistOnDevice
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1169): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 32
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1014): [PWL] Off : 950s ago
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 33
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 4915): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecKeyguardClockView( 1169): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardClockView( 1169): HomeTimezone(): 1
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1854): Aggregate from 1454458812891 (log), 1454458812891 (data)
,W/Finsky  ( 4915): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 4915): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/art     ( 1656): Explicit concurrent mark sweep GC freed 29533(1708KB) AllocSpace objects, 7(252KB) LOS objects, 39% free, 10MB/17MB, paused 1.033ms total 52.935ms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 4915): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4915): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4915): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 4915): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 1695): client connected with version: 7571000
,D/Finsky  ( 4915): [1] VerifyInstalledPackagesReceiver.checkPrerequisites: Skipping verification because network inactive
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4256, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): stay LED for charging
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4915): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4915): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4915): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 34
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4297, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/LightsService( 1014): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1014) 
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,E/lights  ( 1014): write_int failed to open -1
,I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1014): turn on LED for fully charged
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1014): mCursor = null
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,I/ValidateNoPeople( 1014): skipping global notification
,D/WindowManager( 1014): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 1014): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1169
I/PowerManagerService( 1014): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
I/PowerManagerService( 1014): Waking up from sleep (uid 10054)...
,D/PowerManagerService( 1014): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/KeyguardServiceDelegate( 1014): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@10a7b2d7)
D/PowerManagerService( 1014): [s] UserActivityState : 0 -> 1
,D/KeyguardViewMediator( 1169): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1169): notifyScreenOnLocked
,D/PowerManagerService( 1014): [PWL] sb acquire: PowerManagerService.Display
,I/DisplayPowerController( 1014): Blocking screen on until initial contents have been drawn.
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WindowOrientationListener( 1014): sensor enabled
I/Sensors ( 1014): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
,D/SensorService( 1014): [SO] changed settle time [0]
D/DisplayPowerController( 1014): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/SensorService( 1014): [SO] setDelay [200000000]
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
I/libsuspend( 1014): !@autosuspend_wakeup_count_disable
D/DisplayPowerController( 1014): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/SensorService( 1014): [SO] activate (ident=0xb7c47c20, enabled=1)
D/DisplayManagerService( 1014): !@display_state: OFF -> ON
D/SensorService( 1014): [SO] AR_init
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
I/libsuspend( 1014): !@autosuspend_wakeup_count_disable done
D/SurfaceFlinger(  256): Set power mode=2, type=0 flinger=0xb711e690
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 2 on display: 0
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
D/Launcher( 1488): onRestart, Launcher: 94388638
,I/DisplayManagerService( 1014): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1014): Display changed displayId=0
,D/SensorManager( 1014): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,D/Launcher( 1488): onStart, Launcher: 94388638
,D/Launcher.HomeView( 1488): onStart
,D/KeyguardViewMediator( 1169): handleNotifyScreenOn
D/StatusBarKeyguardViewManager( 1169): onScreenTurnedOn()
,D/Launcher( 1488): onResume, Launcher: 94388638
,D/SettingsProvider( 1014): name = kids_home_mode
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10007
D/SecKeyguardClockSingleView( 1169): onScreenTurnedOn
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/Launcher.HomeView( 1488): onResume
,I/PalmMotion( 1014): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1014): [PALM] SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1014): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1014) 
D/PalmMotion( 1014): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,D/Launcher( 1488): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
,D/SamsungIME( 1767): showDlgMsgBox : false true true
,D/SSRM:a  ( 1014): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1014): SettingsAirViewInfo:: 000000000
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/NfcService( 1445): call the applyRouting
,I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb82477c8
I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1205569400)
,D/MenuAppsGridFragment( 1488): onResume,
D/ActivityManager( 1014): handle home activity for 0
I/WallpaperManagerService( 1014): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1014): post home show event for user 0
D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 2 on display 0
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 1
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023,
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/SurfaceControl( 1014): Excessive delay in setPowerMode(): 124ms
,D/PowerManagerService( 1014): Excessive delay in !@display_state: ON: 125ms
,D/KnoxNotification( 1169): ----- inflateViews : modified publicViewLocal -----
,I/Timeline( 1488): Timeline: Activity_idle id: android.os.BinderProxy@2b7b6b24 time:1042189
,D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event1/device/enabled: 1,
,D/WallpaperManagerService( 1014):  force update = false; persona id = 0; current user =0; current persona = 0
,D/KnoxTimeoutHandler( 1014): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
D/KnoxNotification( 1169): ----- inflateViews : modified KnoxViewLocal -----
D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1014) 
,D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 1014): turn off LED
E/lights  ( 1014): write_led_info failed to open -1
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1014): write_led_info failed to open -1
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1169): PersonaID is invalid or persona doesn't exists. : -1
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
E/SmartFaceService( 1014): onReceive: android.intent.action.SCREEN_ON
W/System.err( 1014): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
E/SmartFaceService( 1014): fail to set sysfs 1
D/PersonaManager( 1169): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1169): Icon Only
I/StatusBar( 1169): Icon Only
W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
D/PanelView( 1169): There is/are notification(s) 
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1014): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
D/PanelView( 1169): kidsfalse mQsExpansionEnabled:true
W/System.err( 1014): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1014): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1014): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1014): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1014): 	at libcore.io.Posix.open(Native Method)
D/StatusBarKeyguardViewManager( 1169): callback.onShown()
W/System.err( 1014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1014): 	... 10 more
D/PersonaManager( 1169): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1169): Icon Only
I/StatusBar( 1169): Icon Only
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): kidsfalse mQsExpansionEnabled:true
D/DisplayPowerController( 1014): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1205569400) wakelock released: 1, error no: 0
I/rmt_storage(  268): 
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
V/KeyguardServiceDelegate( 1014): **** SHOWN CALLED ****
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluet,ooth
D/STATUSBAR-WifiQuickSettingButton( 1169): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb82477c8
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
I/DisplayPowerController( 1014): Unblocked screen on after 169 ms
D/STATUSBAR-WifiQuickSettingButton( 1169): onWifiSignalChanged enabled=false enabledDesc:null
D/DisplayPowerState( 1014): !@ ColorFade exit
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/PanelView( 1169): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
V/UserPresentBroadcastReceiver( 1695): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/BatteryMeterView( 1169): onDraw batteryColor : -1
,I/SurfaceFlinger(  256): id=10 Removed DolorFade (8/8)
,I/SurfaceFlinger(  256): id=10 Removed DolorFade (-2/8)
E/libEGL  ( 1014): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1014): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  ( 1014): lcd : 5 +
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/InputMethodManagerService( 1014): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1014): lcd : 5 -
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1014): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1014): SecHardwareInterface.setBatteryADC : true
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,I/splitIntent( 1014): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1014): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 4550): Receive : home resume
,I/StatusBar( 1169): Icon Only
D/PanelView( 1169): There is/are notification(s) 
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/Recents_RecreateReceiver( 2436): onReceive by home
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,V/TaskCloserActivity( 5080): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/Mms/UIEventReceiver( 5183): ui event
,D/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_SCREEN_ON
D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event3/device/enabled: 1
D/SensorService( 1014): [SO] currT = 1042271065000, prevT = 51411078000, diff = 990859987000, [0.172 0.096 10.190]
D/SensorService( 1014): [SO] Reset Rotation Old [100], Init [1]
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
I/WifiNative-HAL( 1014): startHal
E/wifi    ( 1014): getStaticLongField sWifiHalHandle 0x9cec17fc
I/WifiNative-HAL( 1014): Could not start hal
,E/MotionRecognitionService( 1014):  handler : SCREEN_ON end
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/BroadcastQueue( 1014): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1488, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
D/NotificationService( 1014): ACTION_SCREEN_ON
D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1014) 
D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/PanelView( 1169): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,I/splitIntent( 1014): Queue : backgroundsplit_2 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/IpRemoteDisplayController( 1014): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 1014): Bridge Server is not available
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1014): Excessive delay in MISC setInteractive(true) while turning screen on: 175ms
I/QCOM PowerHAL( 1014): Got set_interactive hint
,D/lights  ( 1014): button : 1 +,
D/PowerManagerService( 1014): Excessive delay in nativeSetInteractive(true): 179ms
D/PowerManagerService( 1014): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 306ms
,D/lights  ( 1014): button : 1 -
,D/SensorService( 1014): [SO] currT = 1042471350000, prevT = 51411078000, diff = 991060272000, [0.172 0.057 10.094]
,D/SensorService( 1014): [SO] 0.172 0.057 10.094
D/SensorService( 1014): [SO] [100 -> 255]
,E/SQLiteLog( 1656): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1014): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 1014): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1445): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1445): call the applyRouting
,D/accuweather( 1564): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1564): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1564): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1564): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1564): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1564): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 01 57
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1014): button : 0 +
,I/SamsungIME( 1767): getNextShiftState() cursorCapsMode : 0
,D/lights  ( 1014): button : 0 -
D/PowerManagerService( 1014): [PWL] sb release: PowerManagerService.Broadcasts
,W/OpenGLRenderer( 1488): SFEffectCache::get: create texture(0xa1fa3724): name, size, mSize = 40, 146964, 466432
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,D/daemonapp( 1281): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1281): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1281): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1281): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1281): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1281): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1281): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1281): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1281): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1281): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1281): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1281): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1281): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1281): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1281): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1454481600000
D/daemonapp( 1281): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1454461069900
,D/daemonapp( 1281): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1281): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1281): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1281): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1281): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1281): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1281): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/SSRM:a  ( 1014): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1014): SettingsAirViewInfo:: 000000000
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4915): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4915): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4915): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4281, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1169): Icon Only
I/StatusBar( 1169): Icon Only
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1169): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,V/AlarmManager( 1014): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/SecKeyguardClockView( 1169): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1169): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/accuweather( 1564): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1564): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1564): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1564): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1564): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1564): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1564): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1564): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 01 58
,W/OpenGLRenderer( 1488): SFEffectCache::get: create texture(0xa1fa3724): name, size, mSize = 41, 149184, 615616
,E/SMD     (  287): DCD OFF
,D/SensorService( 1014): [SO] 0.153 0.057 10.094
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/PowerManagerService( 1014): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1169 (0x0)
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4287, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,D/PowerManagerService( 1014): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1014): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1014): lcd : 1 +
D/DisplayPowerController( 1014): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1014): lcd : 1 -
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1014): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SMD     (  287): DCD OFF
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4915): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4915): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4915): [1] 5.onFinished: Scheduling replication attempt 3.
,E/Watchdog( 1014): !@Sync 35
,E/SMD     (  287): DCD OFF
,D/PowerManagerService( 1014): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1014): Nap time (uid 1000)...
D/PowerManagerService( 1014): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1014): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
I/PowerManagerService( 1014): Going to sleep due to screen timeout (uid 1000)...
,V/WindowOrientationListener( 1014): WindowOrientationListener disabled
D/SensorService( 1014): [SO] activate (ident=0xb7c47c20, enabled=0)
D/PowerManagerService( 1014): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1014): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService( 1014): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/PowerManagerService( 1014): handleSandman : startDream(true)
,E/PowerManagerService( 1014): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1014): Sleeping (uid 1000)...
D/PowerManagerService( 1014): [s] UserActivityState : 4 -> 0
I/SurfaceFlinger(  256): id=14 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1014): unregisterListener ::   ,
D/KeyguardViewMediator( 1169): onScreenTurnedOff(3)
D/PowerManagerService( 1014): Excessive delay in ColorFade : createSurface: 10ms
I/KeyguardEffectViewController( 1169): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1169): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1169): notifyScreenOffLocked
,D/Launcher.HomeView( 1488): onPause
D/Launcher( 1488): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/KeyguardViewMediator( 1169): timeout : 5000
,D/LightsService( 1014): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1014) 
,D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1014): turn on LED for fully charged
E/lights  ( 1014): write_int failed to open -1
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SmartFaceService( 1014): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1014): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
E/SmartFaceService( 1014): fail to set sysfs 0
,W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1014): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1014): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1014): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1014): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1014): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1014): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1014): 	... 10 more
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/KeyguardViewMediator( 1169): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1169): handleNotifyScreenOff
,D/VolumePanel( 1169): onScreenTurnedOff()
D/VolumePanel( 1169): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
V/TaskCloserActivity( 5080): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1169): onScreenTurnedOff
,V/ActivityThread( 1488): updateVisibility : ActivityRecord{302c8fba token=android.os.BinderProxy@2b7b6b24 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1488): onStop
,D/PowerManagerService( 1014): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 54ms
,I/StatusBar( 1169): Icon Only
,D/PanelView( 1169): There is/are notification(s) 
,D/SamsungIME( 1767): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/DisplayPowerController( 1014): ColorFade: onAnimationStart
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1014): performScreenOffTransition : no brightness animation
,D/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1014):  handler : SCREEN_OFF end 
,I/WifiNative-HAL( 1014): startHal
,E/wifi    ( 1014): getStaticLongField sWifiHalHandle 0x9cec17fc
I/WifiNative-HAL( 1014): Could not start hal
,D/NotificationService( 1014): ACTION_SCREEN_OFF
D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1014) 
,D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
,V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,D/IpRemoteDisplayController( 1014): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1014): Bridge Server is not available
,D/PanelView( 1169): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4283, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/DisplayPowerState( 1014): !@ ColorFade entry
D/DisplayPowerController( 1014): ColorFade: onAnimationEnd
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 0 -> 0
,D/lights  ( 1014): lcd : 0 +
D/DisplayPowerController( 1014): performScreenOffTransition : no brightness animation,
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/lights  ( 1014): lcd : 0 -
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1014): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1014): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1014): Got set_interactive hint
D/SurfaceFlinger(  256): Set power mode=0, type=0 flinger=0xb711e690
D/DisplayManagerService( 1014): !@display_state: ON -> OFF
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 0 on display: 0
I/DisplayManagerService( 1014): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager( 1014): Display changed displayId=0
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1169): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl( 1014): Excessive delay in setPowerMode(): 262ms
D/PowerManagerService( 1014): Excessive delay in !@display_state: OFF: 267ms
I/libsuspend( 1014): !@autosuspend_wakeup_count_enable
,I/libsuspend( 1014): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1014): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 272ms
I/PowerManagerService( 1014): [PWL] Off : 0s ago
I/PowerManagerService( 1014): [PWL]   PowerManagerService.Broadcasts: ref count=1
,E/SMD     (  287): DCD OFF,
D/GpsLocationProvider( 1014): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/PersonaManagerService( 1014): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1014): MSG_ACTION_SCREEN_OFF called
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
V/EmergencyMode( 1403): [EmergencyStateReceiver] binteractive [false] why[3]
,D/NfcService( 1445): call the applyRouting
,D/accuweather( 1564): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1564): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/daemonapp( 1281): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/accuweather( 1564): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1564): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1564): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1564): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1281): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1914): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/PowerManagerService( 1014): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 1281): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/SSRM:n  ( 1014): SIOP:: AP = 270
,D/accuweather( 1564): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1564): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1564): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1564): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardViewMediator( 1169): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1169): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1169): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1014): [PWL] Off : 5s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4302, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4915): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4915): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4915): [1] 5.onFinished: Scheduling replication attempt 4.
,I/PowerManagerService( 1014): [PWL] Off : 15s ago
,E/SQLiteLog( 1656): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 36
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1014): [PWL] Off : 30s ago
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4915): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4915): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4915): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4303, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,V/AlarmManager( 1014): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 50s ago
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4305, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/SecKeyguardClockView( 1169): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1169): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4915): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4915): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4915): [1] 5.onFinished: Giving up after 6 failures.
,E/Watchdog( 1014): !@Sync 37
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4302, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4298, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 75s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1014): stay LED for fully charged,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 38
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1014): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 105s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4300, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 39
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4296, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1014): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1014): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1014): Updating Usage Statistics in DB @ 1454461241917
,I/ApplicationUsage( 1014): Done Updating Usage Statistics in DB @ 1454461241919
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 40
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 41,
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 58855(4MB) AllocSpace objects, 106(1717KB) LOS objects, 33% free, 27MB/41MB, paused 2.358ms total 151.626ms
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1656): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1656): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1656): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1656): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1169): Icon Only
I/StatusBar( 1169): Icon Only
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1169): Icon Only
E/PlayEventLogger( 4915): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4915): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4915): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4915): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4915): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4915): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4915): 	at android.os.Binder.execTransact(Binder.java:461)
I/StatusBar( 1169): Icon Only
W/System  ( 4915): Ignoring header User-Agent because its value was null.
,I/System.out( 4915): (HTTPLog)-Static: isSBSettingEnabled false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): kidsfalse mQsExpansionEnabled:true
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,D/PanelView( 1169): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 180s ago
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 42,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1403): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1403): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  287): DCD OFF
D/AndroidRuntime( 6285): 
D/AndroidRuntime( 6285): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6285): CheckJNI is OFF
D/AndroidRuntime( 6285): readGMSProperty: start
D/AndroidRuntime( 6285): readGMSProperty: already setted!!
D/AndroidRuntime( 6285): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6285): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6285): readGMSProperty: end
D/AndroidRuntime( 6285): addProductProperty: start
E/AffinityControl( 6285): AffinityControl: registerfunction enter
D/AndroidRuntime( 6285): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1014): START PACKAGE DELETE: observer{753705656}
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
D/PackageManager( 1014): !@killApplicatoin: 10174, uninstall pkg
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10174 user=-1: uninstall pkg
I/ActivityManager( 1014): Killing 5515:com.test.thalitest/u0a174 (adj 15): stop com.test.thalitest cause uninstall pkg
W/ActivityManager( 1014): Spurious death for ProcessRecord{ca58891 5515:com.test.thalitest/u0a174}, curProc for 5515: null
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10174 user=0: pkg removed
W/ActivityManager( 1014): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3696): Explicit concurrent mark sweep GC freed 2487(148KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 6MB/11MB, paused 838us total 32.542ms
I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
I/art     ( 5598): Explicit concurrent mark sweep GC freed 380(26KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 896us total 47.451ms
E/SamsungIME( 1767): mOCRHelper is null
W/GeofencerStateMachine( 1695): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.183: ( 3411): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Feb 03 02:01:53 GMT+01:00 2016
D/RegisteredComponentCache( 1445): Collect Tech packages for Knox
D/PersonaManager( 1445): isKioskContainerExistOnDevice
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.183: ( 3411): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1014): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
I/splitIntent( 1014): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1014): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3411): KLMSIntentService(): onCreate()
I/KLMS-2.5.183: ( 3411): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/Zygote  ( 6298): MountEmulatedStorage()
E/Zygote  ( 6298): v2
I/libpersona( 6298): KNOX_SDCARD checking this for 10094
I/libpersona( 6298): KNOX_SDCARD not a persona
I/SELinux ( 6298): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1014): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6298 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6298): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6298): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/EnterpriseDeviceManagerService( 1014): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1014): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1014): no available spell checker services found
I/KLMS-2.5.183: ( 3411): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/TimaKeyStoreProvider( 6298): TimaSignature is unavailable
D/ActivityThread( 6298): Added TimaKeyStore provider
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.183: ( 3411): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.183: ( 3411): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3411): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3411): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PersonaManager( 1445): isKioskContainerExistOnDevice
D/RegisteredServicesCache( 1445): empty dynamic service
W/ResourcesManager( 1014): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/art     ( 1014): Explicit concurrent mark sweep GC freed 22200(1913KB) AllocSpace objects, 21(356KB) LOS objects, 33% free, 27MB/40MB, paused 3.298ms total 208.610ms
I/art     ( 1014): WaitForGcToComplete blocked for 135.319ms for cause Explicit
D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
D/elm:15183( 6298): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6298): ELMEngine.ELMEngine( context ).
D/elm:15183( 6298): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15183( 6298): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15183( 6298): ElmAgentService : onCreate()
I/KLMS-2.5.183: ( 3411): KLMSIntentService(): listeningToPackageRemoved().END
D/elm:15183( 6298): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6298): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6298): MDMBridge.getInstance()
D/elm:15183( 6298): MDMBridge.getAllLicenseInfoFromSDK()
I/KLMS-2.5.183: ( 3411): KLMSIntentService(): onDestroy()
D/elm:15183( 6298): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 6298): ElmAgentService : onDestroy().
W/ResourceType( 1014): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1014): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/art     ( 1014): Explicit concurrent mark sweep GC freed 8349(364KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 3.285ms total 196.417ms
D/PackageManager( 1014): delete codoeFile: 
D/AASAuninstall( 1014): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.test.thalitest
I/AASA_removePackage( 1014): UID=10174 Target=com.test.thalitest
D/PackageManager( 1014): result of delete: 1{753705656}
D/AndroidRuntime( 6285): Shutting down VM
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1014): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1014): onPackageRemoved : com.test.thalitest
D/RCPManagerService( 1014): PackageReceiver onReceive()
I/HarmonyEASService( 1014): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1014): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1014): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1014): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1014): DBIntegrity::getInstance - New instance created
D/OTPFW   ( 1014): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10174 container id = 0
I/OTPFW   ( 1014): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1014): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1014): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1014): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10174
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TaskPersister( 1014): removeObsoleteFile: deleting file=233_task.xml
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/SSRM:aZ ( 1014): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1014): uID is 10174
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
I/PCWCLIENTTRACE_PushUtil( 5235): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5235): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5235): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5235): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SA      ( 5533): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 5533): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10174 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/PackagesMonitor( 4550): PackagesMonitor onReceive :com.test.thalitest
D/Mms/FreeMessageStatusReceiver( 5183): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1014): enable value -1
I/TactileAssist( 1014): internal enable value -1
I/TactileAssist( 1014): intensity value -1
I/TactileAssist( 1014): saveAppList value true
D/Mms/FreeMessageReceiverService( 5183): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5183): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1014): List of disabled apps :
D/Compatibility( 5416): onReceive() it will make start service
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5416): onHandleIntent()
D/Compatibility( 5416): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10174, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
E/Zygote  ( 6318): MountEmulatedStorage()
E/Zygote  ( 6318): v2
I/libpersona( 6318): KNOX_SDCARD checking this for 10003
D/Compatibility( 5416): found: 2
D/Compatibility( 5416): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5416): skipping ResolveInfo{de22e20 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5416): considering ResolveInfo{201b93d9 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5416): default: com.sec.android.app.soundalive.SAControlPanelActivity
W/art     ( 6285): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/Compatibility( 5416): enabling receiver ResolveInfo{5a0419e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/libpersona( 6318): KNOX_SDCARD not a persona
I/SELinux ( 6318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1014): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6318 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/Compatibility( 5416): enabling receiver ResolveInfo{176e447f com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/SELinux ( 6318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6318): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5416): enabling receiver ResolveInfo{c0c0c4c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5416): enabling receiver ResolveInfo{1ba89495 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5416): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/TimaKeyStoreProvider( 6318): TimaSignature is unavailable
D/ActivityThread( 6318): Added TimaKeyStore provider
D/UserAnalysis.PlaceProvider( 6318): PlaceProvider onCreate()
D/UserAnalysis.SecureDbManager( 6318): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6318): SecurePlaceDbHelper() 
D/UserAnalysis( 6318): Create SecureDbHelper
D/IntelligenceServiceApplication( 6318): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6318): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
E/SQLiteLog( 6318): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6318): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 6318): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6318): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6318): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6318): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteDatabase( 6318): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteDatabase( 6318): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6318): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6318): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6318): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6318): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6318): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6318): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6318): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6318): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 6318): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6318): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6318): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6318): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6318): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6318): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6318): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6318): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6318): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6318): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6318): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6318): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6318): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6318): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6318): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteOpenHelper( 6318): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteOpenHelper( 6318): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 6318): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 6318): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6318): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6318): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6318): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6318): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6318): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ContextImpl( 5443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/SQLiteOpenHelper( 6318): Opened privacy in read-only mode
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
D/IntelligenceServiceApplication( 6318): no applications having user consent for prediction
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
V/PlaceDetection v1.0.19 ( 6318): [PlaceDetection::stopService] Service stopped.
D/RCPManager( 5488):  in createShortcut() for packageName: com.test.thalitest userId0
V/PlaceDetection v1.0.19 ( 6318): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/SQLiteLog( 6318): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6318): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 6318): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6318): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6318): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6318): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6318): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
E/SQLiteDatabase( 6318): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
E/SQLiteDatabase( 6318): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6318): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6318): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6318): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6318): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6318): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6318): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6318): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 6318): Shutting down VM
E/AndroidRuntime( 6318): FATAL EXCEPTION: main
E/AndroidRuntime( 6318): Process: com.samsung.android.intelligenceservice, PID: 6318
E/AndroidRuntime( 6318): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6318): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6318): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6318): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6318): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6318): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6318): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6318): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6318): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 6318): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6318): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6318): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6318): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6318): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6318): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
E/AndroidRuntime( 6318): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
E/AndroidRuntime( 6318): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 6318): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6318): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6318): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/AndroidRuntime( 6318): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6318): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6318): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 6318): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
E/SQLiteLog( 5443): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5443): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5443): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5443): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5443): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5443): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5443): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
E/SQLiteDatabase( 5443): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5443): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5443): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5443): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 5443): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 5443): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5443): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5443): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 5443): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 5443): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5443): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 5443): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5443): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5443): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5443): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5443): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
W/System.err( 5443): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5443): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5443): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5443): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/RCPManagerService( 1014):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1014): queryAllProviders():  providerCallBack is not register for 0
I/Process ( 6318): Sending signal. PID: 6318 SIG: 9
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/DropBoxManagerService( 1014): Can't write: system_app_crash
E/DropBoxManagerService( 1014): java.io.FileNotFoundException: /data/system/dropbox/drop167.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1014): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1014): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1014): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1014): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1014): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1014): 	... 5 more

```
