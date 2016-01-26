#### Test 564496605d11e75_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
D/ComposerPerformance( 5026): 1453807549247 ms / [DONE] Composer constructor
E/CII     ( 5026): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5026): ReservationManager()
I/Mms/ReservationManager( 5026): resetAfterConnected()
D/TP/MmsSmsProvider( 1443): query,matched:7, calling pid = 5026
D/PackageBroadcastService( 1990): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/TP/MmsSmsProvider( 1443): match 7:Elapsed time : 4.168 ms
D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1990): Loading module APK com.google.android.play.games
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
--------- beginning of system
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
D/Mms/Conversation( 5026): [start]    init() consume time = 62.062344
I/Mms/ReservationManager( 5026): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1443): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1443): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1443): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1443): sUpgradeVersion = 0, db.getVersion() = 81
D/Mms/MmsApp( 5026): [end]    onCreate() consume time = 10.973281
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1443): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1443): need read changed broadcast:false
D/Mms/Conversation( 5026): [end]    init consume time = 6.812188
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/Mms/MessagingNotification( 5026): [start]    init() consume time = 3.691823
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MessagingNotification( 5026): [end]    init consume time = 5.521562
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
D/TP/MmsSmsProvider( 1443): query,matched:0, calling pid = 5026
V/TP/MmsSmsProvider( 1443): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1443): match 0:Elapsed time : 0.853 ms
D/Mms/Synchronizer( 5026): [start]    doSync consume time = 5.94974
D/Mms/SpamFilter( 5026): [start]    SpamFilter fill() begin consume time = 1.418385
D/TP/MmsSmsProvider( 1443): update, matched:300, calling pid = 5026
V/TP/MmsSmsProvider( 1443): syncDBData start
V/TP/MmsSmsProvider( 1443): syncDBData sms end
V/TP/MmsSmsProvider( 1443): syncDBData mms end
V/TP/MmsSmsProvider( 1443): syncDBData end
D/Mms/Synchronizer( 5026): [end]    doSync consume time = 7.556719
D/TP/MmsSmsProvider( 1443): query,matched:400, calling pid = 5026
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/PhotosPlugin( 5114): Loading PhotosPlugin
E/Zygote  ( 5208): MountEmulatedStorage()
E/Zygote  ( 5208): v2
I/SELinux ( 5208): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5208): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5208): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/libpersona( 5208): KNOX_SDCARD checking this for 10072
I/libpersona( 5208): KNOX_SDCARD not a persona
D/Mms/SpamFilter( 5026): [end]    SpamFilter fill() finished consume time = 28.54875
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5208 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/Mms/DownloadManager( 5026): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5026): roaming ------> false, mSimSlot = 0
D/TimaKeyStoreProvider( 5208): TimaSignature is unavailable
D/ActivityThread( 5208): Added TimaKeyStore provider
D/Mms/MethodReflector( 5026): getSubId is called
D/Mms/TelephonyUtils( 5026): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5026): getTelephonyProperty is called
D/Mms/DownloadManager( 5026): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5026): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5026): auto download without roaming -> true
D/Mms/DownloadManager( 5026): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5026): mAutoDownload ------> true
W/libprocessgroup( 1015): failed to open /acct/uid_10135/pid_4117/cgroup.procs: No such file or directory
D/Mms/FreeMessageStatusReceiver( 5026): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1015): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/art     (  317): Explicit concurrent mark sweep GC freed 8740(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 48.421ms
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Mms/ArtClassLoader( 5026): init [DONE] art
D/BadgeProvider( 5208): onCreate
D/BadgeProvider( 5208): DatabaseHelper
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 17.290ms
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 17.041ms
E/Zygote  ( 5225): MountEmulatedStorage()
E/Zygote  ( 5225): v2
I/libpersona( 5225): KNOX_SDCARD checking this for 10047
I/libpersona( 5225): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5225 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 5225): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5225): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/Mms/MessagingNotification( 5026): checkBadgeCount unreadCount=0 badgeCount=0
E/SELinux ( 5225): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/TP/SmsProvider( 1443): query,matched:26, calling pid = 5026
D/TP/SmsProvider( 1443): match 26:Elapsed time : 1.855 ms
D/TimaKeyStoreProvider( 5225): TimaSignature is unavailable
D/ActivityThread( 5225): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 1443): query,matched:6, calling pid = 5026
D/TP/MmsSmsProvider( 1443): match 6:Elapsed time : 1.061 ms
D/Mms/FreeMessageReceiverService( 5026): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5026): onHandleIntent: ACTION_PACKAGE_ADDED
W/ResourcesManager( 5225): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5225): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5225): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Killing 4447:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5242): MountEmulatedStorage()
E/Zygote  ( 5242): v2
I/libpersona( 5242): KNOX_SDCARD checking this for 10025
I/libpersona( 5242): KNOX_SDCARD not a persona
I/SELinux ( 5242): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5242 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 5242): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5242): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5242): TimaSignature is unavailable
D/ActivityThread( 5242): Added TimaKeyStore provider
I/ActivityManager( 1015): Killing 3549:com.google.android.gm/u0a101 (adj 15): empty #31
W/ResourcesManager( 5242): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/MyFiles ( 5225): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
E/installd(  284): system dir 0 : /system/app/
E/installd(  284): system dir 1 : /system/priv-app/
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
I/OMACP   ( 5242): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
I/TactileAssist( 1015): enable value -1
I/TactileAssist( 1015): internal enable value -1
I/TactileAssist( 1015): intensity value -1
I/TactileAssist( 1015): saveAppList value true
I/TactileAssist( 1015): List of disabled apps :
D/PackageManager( 1015): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
W/libprocessgroup( 1015): failed to open /acct/uid_10150/pid_4447/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10101/pid_3549/cgroup.procs: No such file or directory
D/Mms/Omacp( 5026): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5259): MountEmulatedStorage()
I/libpersona( 5259): KNOX_SDCARD checking this for 10053
E/Zygote  ( 5259): v2
I/libpersona( 5259): KNOX_SDCARD not a persona
I/SELinux ( 5259): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5259): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5259 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 5259): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5259): TimaSignature is unavailable
D/ActivityThread( 5259): Added TimaKeyStore provider
I/OMACP   ( 5242): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5242): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5242): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5242): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5242): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5242): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5242): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
W/ResourcesManager( 5259): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/OMACP   ( 5242): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5242): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5242): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5242): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5242): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5242): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
I/SL_DEBUG( 5179): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5179): isLoggable:: SL_DEBUG_EXIST = false
D/Compatibility( 5259): onReceive() it will make start service
D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/Compatibility( 5259): onHandleIntent()
D/Compatibility( 5259): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 5259): found: 2
I/UpdateIcingCorporaServi( 4725): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 5259): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5259): skipping ResolveInfo{32f4639d com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5259): considering ResolveInfo{10d67012 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5259): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5259): enabling receiver ResolveInfo{15f63e3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5259): enabling receiver ResolveInfo{a9ee1e0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5259): enabling receiver ResolveInfo{1b89c99 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5259): enabling receiver ResolveInfo{32a77b5e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5259): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5179): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/SSRM:n  ( 1015): SIOP:: AP = 320
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5179): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5291): MountEmulatedStorage()
E/Zygote  ( 5291): v2
I/libpersona( 5291): KNOX_SDCARD checking this for 10041
I/libpersona( 5291): KNOX_SDCARD not a persona
I/SELinux ( 5291): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5291): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5291 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5291): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5291): TimaSignature is unavailable
D/ActivityThread( 5291): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1990): Module APK com.google.android.play.games already loaded
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SA      ( 5291): [SSP] onCreated
D/AsyncTaskServiceImpl( 1990): Submit a task: k
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 5291): [TPM] There is no property file
I/SA      ( 5291): [SCU] isHaveSA() - false
I/SA      ( 5291): [TPM] getModelProperty : null
I/SA      ( 5291): [TPM] getCSCProperty : null
I/SA      ( 5291): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5291): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5291): [DM] TFT FEATURE: false
D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/SA      ( 5291): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5291): [DM] init START
I/SA      ( 5291): [DM] This device is not a Vodafone
D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.vision from APK com.google.android.gms
W/ResourceType( 5291): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
D/k       ( 1990): Processing package: com.test.thalitest
W/ResourceType( 5291): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 5291): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 5291): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5291): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 5291): [SCU] isHaveSA() - false
I/SA      ( 5291): support phone number id : false
I/SA      ( 5291): [DM] Supports Ref Jpn : true
I/SA      ( 5291): [DM] init END
I/SA      ( 5291): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 5291): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
W/IcingInternalCorpora( 1990): getNumBytesRead when not calculated.
I/ActivityManager( 1015): Killing 4020:com.android.providers.calendar/u0a42 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Killing 4383:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
W/BaseAppContext( 1990): Using Auth Proxy for data requests.
W/BaseAppContext( 1990): Using Auth Proxy for data requests.
I/UpdateIcingCorporaServi( 4725): UpdateCorporaTask done [took 493 ms] updated apps [took 493 ms] 
I/ActivityManager( 1015): Killing 4269:com.google.android.music:main/u0a111 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1015): failed to open /acct/uid_10040/pid_4383/cgroup.procs: No such file or directory
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/GassUtils( 1990): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 1990): Found info for package com.test.thalitest in db.
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 1990): Using Auth Proxy for data requests.
W/BaseAppContext( 1990): Using Auth Proxy for data requests.
I/PeopleDatabaseHelper( 1990): cleanUpNonGplusAccounts done.
W/BaseAppContext( 1990): Using Auth Proxy for data requests.
W/BaseAppContext( 1990): Using Auth Proxy for data requests.
W/BaseAppContext( 1990): Using Auth Proxy for data requests.
W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_4020/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10111/pid_4269/cgroup.procs: No such file or directory
W/GAV2    ( 5114): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/AndroidRuntime( 5315): 
D/AndroidRuntime( 5315): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5315): CheckJNI is OFF
D/AndroidRuntime( 5315): readGMSProperty: start
D/AndroidRuntime( 5315): readGMSProperty: already setted!!
D/AndroidRuntime( 5315): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5315): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5315): readGMSProperty: end
D/AndroidRuntime( 5315): addProductProperty: start
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5338): MountEmulatedStorage()
E/Zygote  ( 5338): v2
I/libpersona( 5338): KNOX_SDCARD checking this for 10100
I/libpersona( 5338): KNOX_SDCARD not a persona
I/SELinux ( 5338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5338 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
I/SELinux ( 5338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5338): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
W/GAV2    ( 5114): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 5338): TimaSignature is unavailable
D/ActivityThread( 5338): Added TimaKeyStore provider
W/AccountFeatureHelper( 5114): Write apps_features disabled false
D/PackageIntentReceiver( 5338): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5338): Not GearManger package! 
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5360): MountEmulatedStorage()
E/Zygote  ( 5360): v2
I/SELinux ( 5360): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5360): KNOX_SDCARD checking this for 1000
I/libpersona( 5360): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5360 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5360): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5360): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 1015): Explicit concurrent mark sweep GC freed 234534(15MB) AllocSpace objects, 8(4MB) LOS objects, 33% free, 27MB/41MB, paused 2.827ms total 188.884ms
E/AffinityControl( 5315): AffinityControl: registerfunction enter
I/ActivityManager( 1015): Killing 3703:com.google.android.talk/u0a104 (adj 15): empty #31
D/TimaKeyStoreProvider( 5360): TimaSignature is unavailable
D/ActivityThread( 5360): Added TimaKeyStore provider
D/AndroidRuntime( 5315): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1015): mDVFSHelper.acquire()
D/FocusedStackFrame( 1015): Set to : 0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
E/Zygote  ( 5378): MountEmulatedStorage()
E/Zygote  ( 5378): v2
I/libpersona( 5378): KNOX_SDCARD checking this for 10155
I/libpersona( 5378): KNOX_SDCARD not a persona
I/SELinux ( 5378): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5378): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
E/SELinux ( 5378): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, uhalitest
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5378 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TimaKeyStoreProvider( 5378): TimaSignature is unavailable
D/ActivityThread( 5378): Added TimaKeyStore provider
D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 1467
D/AndroidRuntime( 5315): Shutting down VM
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
V/WindowManager( 1015): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1015): Display changed displayId=0
W/libprocessgroup( 1015): failed to open /acct/uid_10104/pid_3703/cgroup.procs: No such file or directory
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1015): isKioskContainerExistOnDevice
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
V/ActivityThread( 1467): updateVisibility : ActivityRecord{18a6a988 token=android.os.BinderProxy@3a4bf84e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1467): onTrimMemory. Level: 20
E/Zygote  ( 5393): MountEmulatedStorage()
E/Zygote  ( 5393): v2
I/libpersona( 5393): KNOX_SDCARD checking this for 1000
I/libpersona( 5393): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5393 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5393): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5393): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5393): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/ActivityManager( 1015): Killing 4787:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
W/GAV2    ( 5114): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1015): Killing 4818:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 5393): TimaSignature is unavailable
D/ActivityThread( 5393): Added TimaKeyStore provider
D/AcmsPackageEventListener( 5393): Received: android.intent.action.PACKAGE_ADDED
W/ContextImpl( 5393): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/AcmsService( 5393): Enter Oncreate
D/AcmsServiceMonitor( 5393): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5393): creating AcmsCore
D/AcmsCore( 5393): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5393): AcmsCore
D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/AcmsCore( 5393): init
D/AcmsCore( 5393): Looper handler is not null
I/WebViewFactory( 5378): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
D/AcmsCore( 5393): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5393): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5393): Incrementing - Counter value: 1
D/AcmsCore( 5393): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 5393): onStartCommand
D/AcmsService( 5393): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5393): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5393): Incrementing - Counter value: 2
D/AcmsService( 5393): Incremented Counter Value : onStartCommand
W/art     ( 5315): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/AcmsCertificateMngr( 5393): AcmsCertificateMngr
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityThread( 5393): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/AcmsRevocationMngr( 5393): AcmsRevocationMngr
I/LibraryLoader( 5378): Time to load native libraries: 2 ms (timestamps 3537-3539)
I/LibraryLoader( 5378): Expected native library version number "",actual native library version number ""
,W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_4787/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4818/cgroup.procs: No such file or directory
,V/WebViewChromiumFactoryProvider( 5378): Binding Chromium to main looper Looper (main, tid 1) {15f63e3}
,I/LibraryLoader( 5378): Expected native library version number "",actual native library version number ""
,I/chromium( 5378): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/AcmsService( 5393): Inside handle Intent
D/AcmsService( 5393): App added - package name: com.test.thalitest
D/AcmsCore( 5393): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5393): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5393): Incrementing - Counter value: 3
D/AcmsCore( 5393): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5393): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5393): Decrementing - Counter value: 2
,E/SMD     (  290): DCD OFF
,I/BrowserStartupController( 5378): Initializing chromium process, singleProcess=true
,W/art     ( 5378): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5378): ApplicationContext is null in ApplicationStatus
,W/chromium( 5378): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
W/chromium( 5378): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 5378): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 5378): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
I/Adreno-EGL( 5378): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5378): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5378): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5378): Local Branch: 
I/Adreno-EGL( 5378): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5378): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5378):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/Icing   ( 1990): Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
,D/BluetoothAdapter( 5378): 563764031: getState() :  mService = null. Returning STATE_OFF
,I/Mms/MmsApp( 5026):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5026): [start]    fillCache consume time = 1946.40776
,D/Mms/ComposeMessageFragment( 5026): fillCache, easy = false
,D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1990): Module APK com.google.android.play.games already loaded
,W/chromium( 5378): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,I/Icing   ( 1990): Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
I/Icing   ( 1990): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,W/art     ( 5378): Attempt to remove local handle scope entry from IRT, ignoring
,D/AbsListView( 5026): Get MotionRecognitionManager
,D/MotionRecognitionService( 1015):  ssp status : false
,D/Mms/ComposeMessageFragment( 5026): [end]    fillCache consume time = 126.65375
,W/AwContents( 5378): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5378): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5378): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5378): CordovaWebView is running on device made by: samsung
,W/art     ( 5378): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5378): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1015): Activity pause timeout for ActivityRecord{1289b2f u0 com.test.thalitest/.MainActivity t7}
,I/Icing   ( 1990): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/OpenGLRenderer( 5378): Render dirty regions requested: true
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,V/ActivityThread( 5378): updateVisibility : ActivityRecord{2550c03c token=android.os.BinderProxy@16d7780e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 5378): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5378): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1015): Focus entered window: 5378
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 5378): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5378): Initialized EGL, version 1.4
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 5378): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5378): Enabling debug mode 0
,D/Mms/BubbleViewCache( 5026): fillCache bubble = 1
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
I/Timeline( 5378): Timeline: Activity_idle id: android.os.BinderProxy@16d7780e time:73995
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 5378): showStatusIcon on inactive InputConnection
,I/SamsungIME( 1788): getCurrentCandidateView
,I/ActivityManager( 1015): Displayed Component not be shown by security: +650ms (total +759ms)
,W/ActivityManager( 1015): mDVFSHelper.release()
I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{1289b2f u0 com.test.thalitest/.MainActivity t7} time:74010
,I/SurfaceFlinger(  257): id=11 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=11 Removed uhalitest (-2/9)
,W/BindingManager( 5378): Cannot call determinedVisibility() - never saw a connection for the pid: 5378
,D/SamsungIME( 1788): Dismiss ExpandCandiate
,D/JsMessageQueue( 5378): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1788): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1788): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1788): KeybaordView init() : load resources
,I/SamsungIME( 1788): getCurrentKeyboard
I/SamsungIME( 1788): getTextKeyboard
,D/jxcore_app_log( 5378): JniHelper::setJavaVM(0xb8983450), pthread_self() = -1192403392
,D/SamsungIME( 1788): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/chromium( 5378): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager( 1015): Killing 4940:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10142/pid_4940/cgroup.procs: No such file or directory
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1788): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/jxcore-log( 5378): Initializing JXcore engine
W/jxcore-log( 5378): JXcore engine is ready
,D/AcmsKeyStoreHelper( 5393):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5393): Key Store exist
I/AcmsKeyStoreHelper( 5393): Hence loading the keystore file
,E/audit   ( 1906): type=1400 msg=audit(1453807553.166:203): avc:  denied  { ioctl } for  pid=5451 comm="Thread-941" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1906):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1906): type=1300 msg=audit(1453807553.166:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e9c08f8 items=0 ppid=317 ppcomm=main pid=5451 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-941" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1906): type=1320 msg=audit(1453807553.166:203): 
,W/jxcore-log( 5378): Starting JXcore engine
,D/AcmsKeyStoreHelper( 5393):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5393): getKeyStoreForApplication success 
D/AcmsCore( 5393): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5393): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5393): Decrementing - Counter value: 1
D/AcmsCore( 5393): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5393): This is NOT a valid MirrorLink app
D/AcmsCore( 5393): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5393): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5393): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5393): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5393): getSvcCounter - Counter value: 0
D/AcmsService( 5393): Enter onDestroy
I/AcmsService( 5393): cleanUp(): inside service clean up
D/AcmsCore( 5393): AcmsCore: inside DeInit
D/AcmsCore( 5393): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5393): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5393): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5393): KeyStoreHelper: inside cleanup
,D/AcmsAppEntryInterface( 5393): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5393): getSvcCounter - Counter value: 0
D/AcmsService( 5393): killing acms process
I/Process ( 5393): Sending signal. PID: 5393 SIG: 9
,W/jxcore-log( 5378): Platform android,
W/jxcore-log( 5378): 
W/jxcore-log( 5378): Process ARCH arm
W/jxcore-log( 5378): 
,I/ActivityManager( 1015): Process ACMS.Process (pid 5393)(adj 0) has died(29,1160)
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 5378): JXcore Cordova bridge is ready!
I/jxcore-log( 5378): 
,W/jxcore-log( 5378): JXcore engine is started
,I/jxcore-log( 5378): Toggling radios to true
I/jxcore-log( 5378): 
,D/BluetoothAdapter( 5378): enable()
,W/ActivityManager( 1015): Permission Denial: getCurrentUser() from pid=5378, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 1015): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 1015): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5378, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 1015): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/BluetoothManagerService( 1015): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
W/BluetoothManagerService( 1015): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
W/BluetoothManagerService( 1015): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/BluetoothManagerService( 1015): 	at android.os.Binder.execTransact(Binder.java:461)
E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 1015): name = bluetooth_on
,E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider( 1015): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1015): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1015): mCursor = null
,E/Zygote  ( 5458): MountEmulatedStorage()
,E/Zygote  ( 5458): v2
I/libpersona( 5458): KNOX_SDCARD checking this for 1002
I/libpersona( 5458): KNOX_SDCARD not a persona
,I/SELinux ( 5458): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/WifiService( 1015): setWifiEnabled: true pid=5378, uid=10155
W/WifiService( 1015): Failed getting userId using ActivityManagerNative
W/WifiService( 1015): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5378, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1015): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
,W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1015): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1015): 	at android.os.Binder.execTransact(Binder.java:461)
W/ActivityManager( 1015): Permission Denial: getCurrentUser() from pid=5378, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
D/SettingsProvider( 1015): name = wifi_on
I/SELinux ( 5458): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5458 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,E/SELinux ( 5458): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/WifiService( 1015): disconnect: pid=5378, uid=10155,
E/WifiHW  ( 1015): ##################### set firmware type 0 #####################
I/jxcore-log( 5378): Radios toggled
I/jxcore-log( 5378): 
I/jxcore-log( 5378): My device name is: samsung-SM-A500FU
I/jxcore-log( 5378): 
,D/TimaKeyStoreProvider( 5458): TimaSignature is unavailable
,D/ActivityThread( 5458): Added TimaKeyStore provider
,W/ResourcesManager( 5458): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 5458): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SMD     (  290): DCD OFF
,I/BluetoothA2dpSinkServiceJni( 5458): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 5458): Adding GattService
,D/BtSettings.ProfileConfig( 5458): Adding HeadsetService
,D/BtSettings.ProfileConfig( 5458): Adding A2dpService
,D/BtSettings.ProfileConfig( 5458): Adding HidService
,D/BtSettings.ProfileConfig( 5458): Adding HealthService
D/BtSettings.ProfileConfig( 5458): Adding PanService
,D/BtSettings.ProfileConfig( 5458): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 5458): Adding SapService
D/BtSettings.ProfileConfig( 5458): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 5458): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 5458): Adding SapClientService
,D/BtSettings.ProfileConfig( 5458): Adding HidDevService
,I/BtSettings.ProfileConfig( 5458): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
,D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService,
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed,
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hid.HidService
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
,D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hid.HidDevService
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/BluetoothAdapterState( 5458): make
,I/bluedroid( 5458): init
,I/BluetoothAdapterState( 5458): Entering OffState
,I/bte_conf( 5458): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5458): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5458): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5458): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 5458): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 5458): get_profile_interface socket
I/bluedroid( 5458): get_profile_interface map_client
,D/BluetoothAdapterService( 5458): checkAddrForIOP: Loading from conf
,I/GKI_LINUX( 5458): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothA2dp( 5458): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1015): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,D/BluetoothAdapterProperties( 5458): Address is:7C:F9:0E:37:96:AB
E/BluetoothServiceJni( 5458): populateRssiValuesNative
I/bluedroid( 5458): getModelRssiValues
E/BluetoothServiceJni( 5458): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5458): modelRssiValuesCallback, low, mid, high = -70,-60,127
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 5458): Name is: A5-1
,D/SettingsProvider( 1015): name = bluetooth_name
,I/bluedroid( 5458): config_hci_snoop_log
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothManagerService( 1015): Ble is always on enable gatt
,I/BluetoothManagerService( 1015): enableGattForLeMode, doBind called
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,I/BtGatt.JNI( 5458): classInitNative(L900): classInitNative: Success!
,E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 1015): uri = 3 selection = isBluetoothEnabled
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/BluetoothAdapterState( 5458): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 5458): Setting state to 11
I/BluetoothAdapterState( 5458): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5458): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5458): updateAdapterState state is 11
,D/BluetoothAdapterService( 5458): Autoconnection is available 
,D/BluetoothAdapterService( 5458): updateAdapterState prevState = 10newState = 11
W/InputMethodManagerService( 1015): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1015): [BT Setting State] State =11
,D/BluetoothSecureManager( 5458): getInstant: null
,D/BluetoothSecureManager( 5458): calling getMethod for getService
D/BluetoothSecureManager( 5458): calling getService
D/BluetoothSecureManager( 5458): getService return binder: android.os.BinderProxy@de27337
,D/BluetoothSecureManagerService( 1015): isSecureModeEnabled
,D/BluetoothSecureManagerService( 1015): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode( 5458): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5458): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/BluetoothTile( 1172):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1172): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1172):  getBluetoothState : 11
,W/BluetoothAdapterService( 5458): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5458): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5458): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5458): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.pan.PanService
I/SamsungIME( 1788): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
W/BluetoothAdapterService( 5458): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5458): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/StatusBarManagerService( 1015): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1015): setIconVisibility slot=bluetooth visible=false
,W/BluetoothAdapterService( 5458): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
D/PhoneStatusBar( 1172): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
D/BluetoothTile( 1172):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1172): onStateChanged: Bluetooth
W/BluetoothAdapterService( 5458): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5458): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5458): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5458): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 5458): make
,D/BluetoothNotiBroadcastReceiver( 1281): onReceive
,W/BluetoothAdapterService( 5458): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5458): Not skipping com.android.bluetooth.gatt.GattService
,I/BluetoothBondStateMachine( 5458): StableState(): Entering Off State
D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BtGatt.DebugUtils( 5458): handleDebugAction() action=null
,D/BtGatt.GattService( 5458): Received start request. Starting profile...
,D/BtGatt.GattService( 5458): start()
,D/BtGatt.GattService( 5458): start()
I/bluedroid( 5458): get_profile_interface gatt
,D/BluetoothAdapterService( 5458): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a77b5e
,D/BtGatt.AdvertiseManager( 5458): advertise manager created
,W/BluetoothAdapterService( 5458): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5458): Not skipping com.android.bluetooth.hfp.HeadsetService
,V/BluetoothStatusReceiver( 1172): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1172): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5458): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,W/BluetoothAdapterService( 5458): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BtGatt.GattService( 5458): mStartError = false
D/BluetoothAdapterService( 5458): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a77b5e
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5497): MountEmulatedStorage()
,E/Zygote  ( 5497): v2
I/libpersona( 5497): KNOX_SDCARD checking this for 10003
I/libpersona( 5497): KNOX_SDCARD not a persona,
,I/SELinux ( 5497): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5497 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 5497): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5497): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/HeadsetService( 5458): Received start request. Starting profile...
D/HeadsetService( 5458): start()
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,I/BluetoothHeadsetServiceJni( 5458): classInitNative: succeeds
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/HeadsetStateMachine( 5458): make
,W/BluetoothAdapterService( 5458): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5458): Not skipping com.android.bluetooth.hid.HidService
D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/Tethering( 1015): interfaceAdded wlan0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/HeadsetStateMachine( 5458): # of Max HF connection is 2
,W/BluetoothAdapterService( 5458): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
W/BluetoothAdapterService( 5458): Not skipping com.android.bluetooth.hdp.HealthService
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/WifiHW  (  277): wifi_change_fw_path(): fwpath = sta
,D/SoftapController(  277): Softap fwReload - Ok
W/BluetoothAdapterService( 5458): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5458): Not skipping com.android.bluetooth.pan.PanService
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/Tethering( 1015): No numeric data
,W/BluetoothAdapterService( 5458): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/ActivityManager( 1015): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
W/BluetoothAdapterService( 5458): Not skipping com.android.bluetooth.map.BluetoothMapService
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,D/Tethering( 1015): interfaceAdded p2p0
,D/Tethering( 1015): p2p0 is not a tetherable iface, ignoring
,D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1015): clearTetheredNotification()
,D/Tethering( 1015): InitialState.processMessage what=4
D/Tethering( 1015): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged p2p0, false
D/Tethering( 1015): interfaceStatusChanged p2p0, false
,D/CommandListener(  277): Setting iface cfg
D/CommandListener(  277): Trying to bring down wlan0
,D/HotspotTile( 1172): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/HotspotTile( 1172): updateTetherState():false, false
D/NtpTrustedTime( 1015): forceRefresh() from cache miss
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,E/Tethering( 1015): No numeric data
D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1015): forceRefresh Fail.
,D/ActivityManager( 1015): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,E/WifiHW  ( 1015): supplicant_name : p2p_supplicant
,V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated,
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/TimaKeyStoreProvider( 5497): TimaSignature is unavailable
W/BluetoothAdapterService( 5458): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5458): Not skipping com.broadcom.bt.service.sap.SapService
D/ActivityThread( 5497): Added TimaKeyStore provider
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
V/NetworkStats( 1015): performPollLocked() took 5ms
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
I/bluedroid( 5458): get_profile_interface handsfree
,D/Tethering( 1015): clearTetheredNotification()
,D/HotspotTile( 1172): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1172): updateTetherState():false, false
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,W/BluetoothAdapterService( 5458): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/WifiMonitor( 1015): startMonitoring(wlan0) with mConnected = false
,D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5458): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5458): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5458): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5458): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5458): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5458): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5458): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5458): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 5458): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/NtpTrustedTime( 1015): forceRefresh() from cache miss
D/NtpTrustedTime( 1015): forceRefresh Fail.
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
V/NetworkStats( 1015): performPollLocked() took 3ms
D/NtpTrustedTime( 1015): forceRefresh() from cache miss
D/NtpTrustedTime( 1015): forceRefresh Fail.
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1172): Wifi onReceive(2)
,D/STATUSBAR-QSTileView( 1172): onStateChanged: Wi-Fi
,D/HotspotTile( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1172): onReceive : 2, 0
,D/WifiCredService( 1281): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/NtpTrustedTime( 1015): forceRefresh() from cache miss
,D/NtpTrustedTime( 1015): forceRefresh Fail.
,I/DualScoManager( 5458): Instantiating Dual Sco Manager
,I/DualScoManager( 5458): Set HeadsetServiceHelper
D/UserAnalysis.PlaceProvider( 5497): PlaceProvider onCreate()
D/BluetoothAtMessage( 5458): createCMTIContentObservers
,D/SettingsProvider( 1015): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/wpa_supplicant( 5516): [wpa_supplicant_init]: use SECRIL
,I/wpa_supplicant( 5516): Successfully initialized wpa_supplicant
I/SecureStorage( 5516): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/HeadsetStateMachine( 5458): Enter Disconnected: -2
,D/HeadsetService( 5458): mStartError = false
,D/BluetoothAdapterService( 5458): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a77b5e
E/BluetoothAdapterService(849836894)( 5458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,D/BluetoothA2dp( 1015): Proxy object connected
,D/A2dpService( 5458): Received start request. Starting profile...
D/A2dpService( 5458): start()
,I/BluetoothAvrcpServiceJni( 5458): classInitNative: succeeds
,I/bluedroid( 5458): get_profile_interface avrcp
,D/HeadsetStateMachine( 5458): Clear mHeadsetBrsf
D/HeadsetStateMachine( 5458): map size, before remove : 0
D/HeadsetStateMachine( 5458): map size, after remove: 0
,D/BluetoothA2dp( 2703): Proxy object connected
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,E/RemoteController( 5458): Cannot set synchronization mode on an unregistered RemoteController
I/SecureStorage( 5516): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  379): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5516
I/SecureStorage(  379): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5516): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 5516): ssSupport state is = 1
I/wpa_supplicant( 5516): >>>>> GET KEY, IV <<<<<
I/SecureStorage( 5516): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  379): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5516
I/SecureStorage(  379): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,D/UserAnalysis.SecureDbManager( 5497): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5497): SecurePlaceDbHelper() 
D/UserAnalysis( 5497): Create SecureDbHelper
,D/IntelligenceServiceApplication( 5497): onCreate()
,I/Avrcp   ( 5458):  Updating now playing list upon AVRCP Start
,I/BluetoothA2dpServiceJni( 5458): classInitNative: succeeds
,D/IntelligenceServiceApplication( 5497): no applications having user consent for prediction
,D/A2dpStateMachine( 5458): make
,D/BluetoothMediaBrowser( 5458):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/ActivityManager( 1015): Killing 4907:com.google.android.gms:car/u0a12 (adj 15): empty #31
,I/bluedroid( 5458): get_profile_interface a2dp
I/GKI_LINUX( 5458): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 5458): warning : media task started media_task_refcnt 1 
,D/A2dpService( 5458): mStartError = false
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
D/BluetoothAdapterService( 5458): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a77b5e
D/A2dpStateMachine( 5458): Enter Disconnected: -2
I/BluetoothHidServiceJni( 5458): classInitNative: succeeds
,V/PlaceDetection v1.0.19 ( 5497): [PlaceDetection::stopService] Service stopped.
,D/HidService( 5458): Received start request. Starting profile...
D/HidService( 5458): start()
I/bluedroid( 5458): get_profile_interface hidhost
D/HidService( 5458): setHidService(): set to: null
D/HidService( 5458): mStartError = false
D/BluetoothAdapterService( 5458): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a77b5e
,I/BluetoothHealthServiceJni( 5458): classInitNative: succeeds
,D/HealthService( 5458): Received start request. Starting profile...
D/HealthService( 5458): start()
,I/bluedroid( 5458): get_profile_interface health
,D/HealthService( 5458): mStartError = false
D/BluetoothAdapterService( 5458): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a77b5e
,I/BluetoothPanServiceJni( 5458): classInitNative(L105): succeeds
,D/BluetoothMediaBrowser( 5458): no now playing list
D/BluetoothMediaBrowser( 5458):  getNowPlayingId now playing id : -1
,D/BluetoothPan( 1015): BluetoothPAN Proxy object connected
,D/PanService( 5458): Received start request. Starting profile...
D/PanService( 5458): start()
D/BluetoothPanServiceJni( 5458): initializeNative(L110): pan
I/bluedroid( 5458): get_profile_interface pan
,D/PanService( 5458): mStartError = false
D/BluetoothAdapterService( 5458): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a77b5e
,D/HeadsetStateMachine( 5458): Try to query the phonestate on bind
,V/PlaceDetection v1.0.19 ( 5497): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
I/Telecom ( 1417): BluetoothPhoneService: queryPhoneState
I/Telecom ( 1417): BluetoothPhoneService: handleMessage(7) / param 0
I/Telecom ( 1417): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1417): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1417): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,I/Telecom ( 1417): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1417): Proxy not attached to service
,I/Telecom ( 1417): BluetoothPhoneService: Result of Message : true
,D/BluetoothMapService( 5458): Received start request. Starting profile...
D/BluetoothMapService( 5458): start()
,W/libprocessgroup( 1015): failed to open /acct/uid_10012/pid_4907/cgroup.procs: No such file or directory
,D/BluetoothMapService( 5458): mStartError = false
D/BluetoothAdapterService( 5458): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a77b5e
,D/HeadsetStateMachine( 5458): Proxy object connected
D/HeadsetPhoneState( 5458): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine( 5458): Disconnected process message: 11
I/BluetoothSAPServiceJni( 5458): classInitNative(L204): succeeds
,D/SapService( 5458): Received start request. Starting profile...
,D/SapService( 5458): start()
,D/BluetoothSAPServiceJni( 5458): initializeNative(L209): sap
I/bluedroid( 5458): get_profile_interface sap
D/SapService( 5458): mStartError = false
,D/BluetoothAdapterService( 5458): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a77b5e
,D/HeadsetPhoneState( 5458): sendDeviceDataStateChanged
,D/HeadsetPhoneState( 5458): Signal level : previous=0 curr=0
,E/BluetoothAdapterService(849836894)( 5458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 5458): Proxy object connected
,D/BluetoothAdapterService( 5458): Bluetooth A2dp source service connected
E/BluetoothAdapterService(849836894)( 5458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,E/BluetoothAdapterService(849836894)( 5458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(849836894)( 5458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,D/HeadsetStateMachine( 5458): Disconnected process message: 18
D/HeadsetStateMachine( 5458): Disconnected process message: 10
,D/HeadsetPhoneState( 5458): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5458): Disconnected process message: 11
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5525): MountEmulatedStorage()
,E/Zygote  ( 5525): v2
I/libpersona( 5525): KNOX_SDCARD checking this for 10107
,I/libpersona( 5525): KNOX_SDCARD not a persona
,I/SELinux ( 5525): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1015): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=5525 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/BluetoothAdapterService(849836894)( 5458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true,
,I/SELinux ( 5525): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
,E/SELinux ( 5525): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5525): TimaSignature is unavailable
D/ActivityThread( 5525): Added TimaKeyStore provider,
,I/art     (  317): Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 682us total 38.438ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 16.922ms
,I/SecureStorage(  379): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 16.823ms,
,I/SecureStorage( 5516): [INFO]: SPID(0x00000002)Processing data has been completed,
,E/Zygote  ( 5540): MountEmulatedStorage(),
E/Zygote  ( 5540): v2
I/libpersona( 5540): KNOX_SDCARD checking this for 10145
I/libpersona( 5540): KNOX_SDCARD not a persona
,I/SELinux ( 5540): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5540): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5540): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1015): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5540 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5540): TimaSignature is unavailable
D/ActivityThread( 5540): Added TimaKeyStore provider
,W/ResourcesManager( 5540): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 5540): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5540): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5540): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5540): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/wpa_supplicant( 5516): Ctrl_iface: loading cred from phone,
I/SecureStorage( 5516): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,I/SecureStorage( 5516): [INFO]: SPID(0x00000002)This device supports Secure Storage
,I/SecureStorage(  379): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5516
I/SecureStorage(  379): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 5516): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5516): ssSupport state is = 1
,I/wpa_supplicant( 5516): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 5516): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5516): SIM READ ERROR
I/wpa_supplicant( 5516): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5516): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5516): SIM READ ERROR
I/wpa_supplicant( 5516): Blacklist: Clear (all) 
D/RCPManagerService( 1015): exchangeData() failure , invalid userId
I/wpa_supplicant( 5516): wpa_default_ap_write_once
I/wpa_supplicant( 5516): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5516): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5516): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 5516): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5516): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
I/wpa_supplicant( 5516): rfkill: Cannot open RFKILL control device
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/ProcessCpuTracker( 1015): Skipping unknown process pid 5555
,I/wpa_supplicant( 5516): wlan0: Setting scan request: 0 sec 100000 usec
,E/BluetoothAdapterService(849836894)( 5458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(849836894)( 5458): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,I/ActivityManager( 1015): Killing 4706:com.samsung.aasaservice/1000 (adj 15): empty #31
,D/BluetoothAdapterState( 5458): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5458): enable
,I/bt_hci_bdroid( 5458): init
,I/GKI_LINUX( 5458): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor( 5458): bt-vendor : init
,I/bt_vendor( 5458): bt-vendor : get_bt_soc_type
,E/bt_vendor( 5458): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 5458): init: Local BD Address : ab:96:37:0e:f9:7c
D/bt_userial_mct( 5458): userial_init
,I/bt_vendor( 5458): bt-vendor : BT_VND_OP_POWER_CTRL: Off
,I/bt_vendor( 5458): Starting hciattach daemon
I/bt_vendor( 5458): try to set false
,I/bt_vendor( 5458): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 5458): Starting hciattach daemon
I/bt_vendor( 5458): try to set true
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId,
,I/qcom-bluetooth( 5571): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4706/cgroup.procs: No such file or directory,
,I/qcom-bluetooth( 5579): /system/etc/init.qcom.bt.sh: Transport : smd ,
,I/wpa_supplicant( 5516): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage( 5516): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,I/qcom-bluetooth( 5580): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/SecureStorage( 5516): [INFO]: SPID(0x00000002)This device supports Secure Storage,
I/SecureStorage(  379): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5516
I/SecureStorage(  379): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,I/SecureStorage( 5516): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5516): ssSupport state is = 1
,I/wpa_supplicant( 5516): Ctrl_iface: loading cred from phone,
I/SecureStorage( 5516): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,I/qcom-bluetooth( 5585): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,I/SecureStorage( 5516): [INFO]: SPID(0x00000002)This device supports Secure Storage
I/SecureStorage(  379): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5516
I/SecureStorage(  379): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,I/SecureStorage( 5516): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5516): ssSupport state is = 1
I/wpa_supplicant( 5516): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5516): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5516): SIM READ ERROR
I/wpa_supplicant( 5516): wpa_default_ap_write_once
I/wpa_supplicant( 5516): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5516): rfkill: Cannot open RFKILL control device
,I/Nat464Xlat( 1015): interfaceLinkStateChanged p2p0, false
D/Tethering( 1015): interfaceLinkStateChanged p2p0, false
D/Tethering( 1015): interfaceStatusChanged p2p0, false
,I/qcom-bluetooth( 5586): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
D/Tethering( 1015): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged p2p0, false
D/Tethering( 1015): interfaceStatusChanged p2p0, false
,I/qcom-bluetooth( 5587): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5588): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 5516): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 5516): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,D/StrictMode( 5525): StrictMode policy violation; ~duration=296 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5525): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5525): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5525): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 5525): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 5525): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 5525): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 5525): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 5525): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 5525): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5525): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5525): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5525): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5525): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5525): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5525): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5525): StrictMode policy violation; ~duration=284 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5525): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5525): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5525): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 5525): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 5525): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 5525): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 5525): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5525): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5525): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5525): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5525): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5525): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5525): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5525): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5525): StrictMode policy violation; ~duration=212 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5525): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5525): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5525): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5525): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5525): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 5525): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 5525): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 5525): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5525): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5525): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5525): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5525): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5525): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5525): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5525): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5525): StrictMode policy violation; ~duration=210 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5525): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5525): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5525): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 5525): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 5525): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 5525): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190),
D/StrictMode( 5525): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5525): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5525): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5525): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5525): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5525): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5525): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5525): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 5525): StrictMode policy violation; ~duration=206 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5525): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5525): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 5525): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 5525): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 5525): 	,at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 5525): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5525): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
,D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5525): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5525): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5525): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5525): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5525): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5525): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5525): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5525): StrictMode policy violation; ~duration=204 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5525): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5525): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 5525): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 5525): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 5525): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 5525): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 5525): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 5525): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 5525): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 5525): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 5525): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 5525): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 5525): 	at com.google.r.e.b(PG:170)
D/StrictMode( 5525): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5525): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5525): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5525): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5525): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5525): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5525): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5525): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 5525): StrictMode policy violation; ~duration=202 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5525): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5525): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 5525): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 5525): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 5525): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 5525): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 5525): 	,at com.google.r.k.c(PG:1187)
D/StrictMode( 5525): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 5525): 	at com.google.r.k.c(PG:583)
D/StrictMode( 5525): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 5525): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 5525): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 5525): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 5525): 	at com.google.r.e.b(PG:170)
D/StrictMode( 5525): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5525): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5525): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5525): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5525): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5525): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5525): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5525): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5525): StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5525): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5525): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5525): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5525): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5525): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 5525): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 5525): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 5525): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 5525): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5525): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5525): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5525): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5525): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5525): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5525): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(N,ative Method)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5525): StrictMode policy violation; ~duration=173 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5525): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5525): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5525): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5525): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 5525): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
,D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5525): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5525): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5525): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5525): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5525): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5525): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5525): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5525): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5525): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AuthorizationBluetoothService( 1778): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 4398:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3380): Starting #2
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,I/Hs20UtilService( 3380): Message received 5011
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 5208): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/libpersona( 5592): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5592): MountEmulatedStorage()
I/libpersona( 5592): KNOX_SDCARD not a persona
E/Zygote  ( 5592): v2
,E/Watchdog( 1015): !@Sync 2
I/SELinux ( 5592): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5592 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5592): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5592): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 5516): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 5516): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5516): Skip scan - bUseNetwork false
E/WifiStateMachine( 1015): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 5516): HOTSPOT20_ENABLE called
I/wpa_supplicant( 5516): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5516): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,E/wpa_supplicant( 5516): SIM READ ERROR
I/wpa_supplicant( 5516): Blacklist: Clear (all) 
,I/wpa_supplicant( 5516): wlan0: Setting scan request: 0 sec 0 usec
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/wpa_supplicant( 5516): Skip scan - bUseNetwork false
,D/WifiNative-wlan0( 1015): callSECApiInt - ID [210]
,D/TimaKeyStoreProvider( 5592): TimaSignature is unavailable
D/ActivityThread( 5592): Added TimaKeyStore provider
,D/WifiConfigStore( 1015): Loading config and enabling all networks 
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1172): Wifi onReceive(3)
,D/STATUSBAR-QSTileView( 1172): onStateChanged: Wi-Fi
,D/HotspotTile( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1172): onReceive : 3, 0
,W/libprocessgroup( 1015): failed to open /acct/uid_10044/pid_4398/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,E/WifiConfigStore( 1015): Not a HS20
,E/WifiConfigStore( 1015): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-wlan0( 1015): callSECApiInt - ID [65]
,D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 5516): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 5516): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5516): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 5516): P2P: Current p2p state = IDLE
I/wpa_supplicant( 5516): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 5516): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5516): First Scan Start
I/wpa_supplicant( 5516): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-wlan0( 1015): Setting external_sim to 1
,D/WifiStateMachine( 1015): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1015): startHal
E/wifi    ( 1015): getStaticLongField sWifiHalHandle 0x9c6b888c
I/WifiNative-HAL( 1015): Could not start hal
,E/WifiNative-wlan0( 1015): do suspend true
,D/WifiP2pService( 1015): P2pDisabledState{ what=131203 }
,E/WifiStateMachine( 1015): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,I/wpa_supplicant( 5516): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
W/com.google.a.a.b.d.a( 5525): Application name is not set. Call Builder#setApplicationName.
,D/CommandListener(  277): Setting iface cfg
D/CommandListener(  277): Trying to bring up p2p0
,I/wpa_supplicant( 5516): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/WifiMonitor( 1015): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 5516): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiP2pService( 1015): P2pEnablingState
D/WifiScanningService( 1015): SCAN_AVAILABLE : 3
D/WifiScanningService( 1015): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1015): startHal
,D/RttService( 1015): SCAN_AVAILABLE : 3
,D/RttService( 1015): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnablingState{ what=143376 }
,D/WifiP2pService( 1015): DefaultState{ what=143376 }
,D/WifiP2pService( 1015): P2pEnablingState{ what=147457 }
,D/WifiP2pService( 1015): P2p socket connection successful
,I/qcom-bluetooth( 5613): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab 
,E/wifi    ( 1015): getStaticLongField sWifiHalHandle 0x9d8629bc
I/WifiNative-HAL( 1015): Could not start hal
,E/WifiScanningService( 1015): could not start HAL
,D/WifiP2pService( 1015): P2pEnabledState
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 1015): sending p2p connection changed broadcast: IDLE
D/SecContentProvider2( 1015): mCursor = null
E/WifiStateMachine( 1015): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 1015): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController( 1015): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1015): disconnect,
D/WifiDisplayController( 1015): updateConnection,
,D/WifiDisplayController( 1015): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null,
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/qcom-bluetooth( 5614): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/WifiP2pService( 1015): create mNetworkAgent
,D/AllShareCastTile( 1172): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1172): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/ConnectivityService( 1015): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/SecurityLogAgent( 5592): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5592): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5592): StateMachine : Current State = 1
,D/ConnectivityService( 1015): hsengiv:checkWhatTypeOfNetwork and the value is false
,D/WifiDisplayController( 1015): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Nat464Xlat( 1015): interfaceLinkStateChanged p2p0, false
,E/ConnectivityService( 1015): updateNetworkInfo()
D/Tethering( 1015): interfaceLinkStateChanged p2p0, false
D/Tethering( 1015): interfaceStatusChanged p2p0, false
,D/ConnectivityService( 1015): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/CSLegacyTypeTracker( 1015): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,D/WifiCredService( 1281): Action received :android.net.wifi.WIFI_STATE_CHANGED
,E/WifiStateMachine( 1015): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1015): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1015): invaild command id : 215
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/bt_vendor( 5458): bluetooth satus is on
D/bt_userial_mct( 5458): userial_open(port:0)
I/bt_vendor( 5458): bt-vendor : BT_VND_OP_USERIAL_OPEN
,D/WifiNative-p2p0( 1015): p2pGetDeviceAddress
I/bt_vendor( 5458): Done intiailizing UART
D/WifiNative-p2p0( 1015): p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,I/bt_vendor( 5458): Done intiailizing UART
I/bt_userial_mct( 5458): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 5458): Bluetooth Firmware and transport layer are initialized
,D/bt_userial_mct( 5458): Entering userial_read_thread()
,D/WifiDisplayController( 1015): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
D/WifiDisplayController( 1015):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1015):  primary type: 10-0050F204-5
D/WifiDisplayController( 1015):  secondary type: null
D/WifiDisplayController( 1015):  wps: 0
D/WifiDisplayController( 1015):  grpcapab: 0
D/WifiDisplayController( 1015):  devcapab: 0
D/WifiDisplayController( 1015):  status: 3
D/WifiDisplayController( 1015):  wfdInfo: null
D/WifiDisplayController( 1015):  groupownerAddress: null
D/WifiDisplayController( 1015):  GOdeviceName: null
D/WifiDisplayController( 1015):  interfaceAddress: 
D/WifiDisplayController( 1015):  SConnectInfo : null
,D/Launcher.Model( 1467): reloadBadges entered.
,D/WifiP2pService( 1015): DeviceAddress: 7e:96:ac
,D/BadgeProvider( 5208): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5208): sendNotify, [notify] : null
D/BadgeProvider( 5208): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5208): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5208): update, [UpdateCount] : 1
,V/AlarmManager( 1015): waitForAlarm result :8
,V/AlarmManager( 1015): No more alarm at this time.nowELAPSED=78029 batch.start=82251
,D/WifiP2pService( 1015): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 1015): InactiveState
,E/ConnectivityService( 1015): updateNetworkInfo()
,D/WifiP2pService( 1015): InactiveState{ what=143376 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 5516): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 38244(2037KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.504ms total 189.386ms,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/        ( 5458): BTE_InitTraceLevels -- TRC_HCI
I/        ( 5458): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5458): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5458): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5458): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5458): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5458): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5458): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5458): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5458): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5458): BTE_InitTraceLevels -- TRC_SAP
I/        ( 5458): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5458): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5458): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5458): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5458): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 5458): BTE_InitTraceLevels -- TRC_PROTOCOL
,D/SecurityLogAgent( 5592): StateMachine : Changed Current State = 1
,I/ActivityManager( 1015): Killing 4604:com.samsung.android.sm/1000 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3380): Starting #3
,I/Hs20UtilService( 3380): Message received 5011
,E/WifiStateMachine( 1015): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1015): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1015): invaild command id : 215
,D/SecurityLogAgent( 5592): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5592): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 5592): StateMachine : Current State = 1
,D/SecurityLogAgent( 5592): StateMachine : Changed Current State = 1
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1281): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1281): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1281): MountReceiver.mPrefHandler - 7002
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/bt-l2cap( 5458): l2c_link_processs_ble_num_bufs 16
,E/bt-btm  ( 5458): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f956e9 ,
E/bt-btm  ( 5458): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f956e9 
,E/Zygote  ( 5620): MountEmulatedStorage()
,E/Zygote  ( 5620): v2
I/libpersona( 5620): KNOX_SDCARD checking this for 10068
I/libpersona( 5620): KNOX_SDCARD not a persona
,I/SELinux ( 5620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5620): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5620 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/BluetoothAdapterProperties( 5458): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,E/bt-btif ( 5458): Calling BTA_HhEnable
,E/bt-btif ( 5458):                : sec: 0xb6, service name [] (up to 21 ch
,D/BluetoothAdapterProperties( 5458): Address is:7C:F9:0E:37:96:AB
E/BluetoothServiceJni( 5458): populateRssiValuesNative
I/bluedroid( 5458): getModelRssiValues
E/BluetoothServiceJni( 5458): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5458): modelRssiValuesCallback, low, mid, high = -70,-60,127
D/BluetoothAdapterProperties( 5458): Name is: A5-1
,D/SettingsProvider( 1015): name = bluetooth_name
,D/BluetoothUtils( 5458): getBtEnabledContainers(): btContainers = []
,D/BluetoothAdapterProperties( 5458): Scan Mode:20
,D/BluetoothAdapterProperties( 5458): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5458): LE Address is:FC:F3:1C:6E:2D:57
E/bt-btif ( 5458): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 5458): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 5458): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 5458): btif_sock_init: !vhci_init
D/IOP_DB_BT( 5458): db_open: file /etc/bluetooth/iop_bt.db
,E/bt_mct  ( 5458): hci lib postload completed
D/IOP_DB_BT( 5458): db_open: db_open : handle 3027722256l, read 13894 bytes onto local cache
D/IOP_DB_BT( 5458): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5458): db_query: result 1
I/        ( 5458): iop_db_open: iop_db_open status 0
,D/bte_conf( 5458): Device ID record 1 : primary
,D/bte_conf( 5458):   vendorId            = 0075
,D/bte_conf( 5458):   vendorIdSource      = 0001
D/bte_conf( 5458):   product             = 0100
,D/bte_conf( 5458):   version             = 0200
D/bte_conf( 5458):   clientExecutableURL = 
,D/bte_conf( 5458):   serviceDescription  = 
,D/bte_conf( 5458):   documentationURL    = 
,D/bte_conf( 5458): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 5458): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5458): ScanMode =  20
D/BluetoothAdapterProperties( 5458): State =  11
,D/SecContentProvider( 1015): uri = 3 selection = isDiscoverableEnabled
D/BluetoothPanServiceJni( 5458): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterProperties( 5458): Setting state to 12
I/BluetoothAdapterState( 5458): Bluetooth adapter state changed: 11-> 12
,D/BluetoothUtils( 5458): getBtEnabledContainers(): btContainers = []
,D/BluetoothAdapterProperties( 5458): Scan Mode:21
,D/SettingsProvider( 1015): name = bluetooth_a2dp_sink_mode
,D/TimaKeyStoreProvider( 5620): TimaSignature is unavailable
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/ActivityThread( 5620): Added TimaKeyStore provider
,D/BluetoothAdapterProperties( 5458): Discoverable Timeout:120
,D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4604/cgroup.procs: No such file or directory
,D/BluetoothAdapterService( 5458): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5458): updateAdapterState state is 12
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 5458): Autoconnection is available 
,D/BluetoothAdapterService( 5458): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 5458): starting service from this receiver
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapter( 1778): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 5458): Entering On State from state = 11
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/BluetoothAdapter( 1778): onBluetoothStateChange: Bluetooth is on
,D/BluetoothA2dp( 5458): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1015): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1015): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1443): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1443): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 5458): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5458): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 2703): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 2703): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1417): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1417): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 5378): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5378): onBluetoothStateChange: Bluetooth is on
,D/BluetoothA2dp( 2703): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 5525): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5525): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1172): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1172): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1434): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1434): onBluetoothStateChange: Bluetooth is on
,I/BluetoothPbapService( 5458): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
D/BluetoothA2dp( 1015): onBluetoothStateChange: up=true
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
W/InputMethodManagerService( 1015): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1015): [BT Setting State] State =12
I/InputMethodManagerService( 1015): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothTile( 1172):  onBluetoothStateChange:
,D/BluetoothHeadset( 1417): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2529d917, true
,W/ResourcesManager( 5620): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/BluetoothTile( 1172):  onBluetoothPairedDevicesChanged:
D/BluetoothHeadset( 1417): registerMessageListener
,D/BluetoothTile( 1172): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1172):  getBluetoothState : 12
,D/HeadsetService( 5458): registerMessageListener
,D/HeadsetService( 5458): registerMessageListener
,D/HeadsetStateMachine( 5458): Disconnected process message: 70
,D/HeadsetStateMachine( 5458): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@d78d40f
,I/Telecom ( 1417): BluetoothPhoneService: handleMessage(7) / param null
,I/Telecom ( 1417): BluetoothPhoneService: updateHeadsetWithCallState
,D/BluetoothTile( 1172):  handleUpdatestate:false name:null
,I/SamsungIME( 1788): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 1172):  handleUpdatestate:false name:null
,I/BluetoothPbapService( 5458): Handler(): got msg=1
,D/FileShare-Client( 5620): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/SecContentProvider( 1015): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/Telecom ( 1417): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1417): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,I/Telecom ( 1417): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/HeadsetStateMachine( 5458): Disconnected process message: 9
D/FileShare-Client( 5620): ClientBroadcastReceiver.onReceive - disconnected
,D/HeadsetStateMachine( 5458): mNumActive: 0 mNumHeld: 0 mCallState: 6
,V/BluetoothPbapService( 5458): PBAP Service initSocket try: 0
,D/StatusBarManagerService( 1015): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1015): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 1172): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/BluetoothMapMasInstance( 5458): set MAP SDP message type : 1
,D/audio_hw_primary(  283): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  283): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
,E/HeadsetStateMachine( 5458): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothTile( 1172):  handleUpdatestate:false name:null
,D/BluetoothSocket( 5458): bindListen(): myUserId = 0
W/BluetoothAdapter( 5458): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5458): bindListen(): myUserId = 0
W/BluetoothAdapter( 5458): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5458): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 5458): bindListen(), new LocalSocket 
D/BluetoothSocket( 5458): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5458): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21885688
,D/BluetoothSocket( 5458): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 5458): bindListen(), new LocalSocket 
,D/BluetoothSocket( 5458): channel: 5
D/BluetoothSocket( 5458): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5458): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@69a7821
D/BluetoothSocket( 5458): channel: 19
D/BluetoothPbapService( 5458): PBAP Socket is BluetoothServerSocket
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/FileShare-Client( 5620): Outbound.stopDelayTimer - 
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5643): MountEmulatedStorage(),
I/libpersona( 5643): KNOX_SDCARD checking this for 10069
E/Zygote  ( 5643): v2
I/libpersona( 5643): KNOX_SDCARD not a persona
,I/SELinux ( 5643): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5643 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5017:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,I/SELinux ( 5643): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5643): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5643): TimaSignature is unavailable
,D/ActivityThread( 5643): Added TimaKeyStore provider
,D/FileShare-Server( 5643): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1015): Killing 4744:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,W/ContextImpl( 1281): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/ActivityManager( 1015): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/LocalBluetoothProfileManager( 1281): Adding local A2DP profile
,D/BluetoothA2dp( 1281): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1015): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1281): Adding local HEADSET profile
,E/BluetoothHeadset( 1281): BTStateChangeCB is registed
,D/BluetoothHeadset( 1281): doBind(): CallingUid(myUserHandle) = 0
D/ActivityManager( 1015): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
E/BluetoothHeadset( 1281): BluetoothHeadset service is binded
D/BluetoothMap( 1281): Create BluetoothMap proxy object
D/ActivityManager( 1015): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ContextImpl( 1281): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/ActivityManager( 1015): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/Bluetoothsap( 1281): bindService called to Bluetooth SAP Service
,D/ActivityManager( 1015): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1281): PANU : true
,W/LocalBluetoothProfileManager( 1281): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1281): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1281): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1281): onReceive
,D/BluetoothA2dp( 1281): Proxy object connected
D/A2dpProfile( 1281): Bluetooth service connected
,V/BluetoothStatusReceiver( 1172): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1172): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,W/libprocessgroup( 1015): failed to open /acct/uid_10152/pid_5017/cgroup.procs: No such file or directory
,D/HeadsetProfile( 1281): Bluetooth service connected
W/libprocessgroup( 1015): failed to open /acct/uid_10015/pid_4744/cgroup.procs: No such file or directory
,D/BluetoothMap( 1281): Proxy object connected
D/MapProfile( 1281): Bluetooth service connected
,D/BluetoothMap( 1281): getConnectedDevices()
,D/BluetoothAdapterService( 5458): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a77b5e
,D/BtConfig.SecureMode( 5458): isSecureModeOn:false
,D/BluetoothPbap( 1281): Proxy object connected
D/PbapServerProfile( 1281): Bluetooth service connected
,D/Bluetoothsap( 1281): BluetoothSAP Proxy object connected
D/SapProfile( 1281): Bluetooth service connected
D/Bluetoothsap( 1281): getConnectedDevices()
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,D/BluetoothInputDevice( 1281): Proxy object connected
D/HidProfile( 1281): Bluetooth service connected
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothPan( 1281): BluetoothPAN Proxy object connected
D/PanProfile( 1281): Bluetooth service connected
,D/AuthorizationBluetoothService( 1778): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider( 1015): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/BluetoothSocket( 5458): bindListen(): myUserId = 0
,W/BluetoothAdapter( 5458): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5458): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
D/BluetoothSocket( 5458): bindListen(), new LocalSocket 
D/BluetoothSocket( 5458): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5458): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c8d2ba3
,D/BluetoothSocket( 5458): channel: 12
I/BtOppRfcommListener( 5458): Accept thread started.
,I/wpa_supplicant( 5516): nl80211: Received scan results (3 BSSes),
I/wpa_supplicant( 5516): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5516): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 5516): Trying to associate with  'G700'
I/wpa_supplicant( 5516): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 5516): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1015): didn't find BSSID Trying to associate with SSID 'NG700'
,I/WifiNative-HAL( 1015): startHal
,E/wifi    ( 1015): getStaticLongField sWifiHalHandle 0x9c6b88ac
I/WifiNative-HAL( 1015): Could not start hal
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1015): mCursor = null
,E/wpa_supplicant( 5516): Cmd 35605 not handled
,I/wpa_supplicant( 5516): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 5516): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 5516): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 5516): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 5516): Associated with C0.AA.48
I/wpa_supplicant( 5516): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 5516): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE,
I/wpa_supplicant( 5516): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceStatusChanged wlan0, true
,E/Tethering( 1015): No numeric data
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime( 1015): forceRefresh() from cache miss
D/Tethering( 1015): clearTetheredNotification()
,D/NtpTrustedTime( 1015): forceRefresh Fail.
D/HotspotTile( 1172): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1172): updateTetherState():false, false
V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,V/NetworkStats( 1015): performPollLocked() took 7ms
,D/NtpTrustedTime( 1015): forceRefresh() from cache miss
,D/NtpTrustedTime( 1015): forceRefresh Fail.
,I/wpa_supplicant( 5516): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5516): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 5516): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 5516): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 5516): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5516): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 5516): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 5516): Blacklist: Clear (temp) 
I/wpa_supplicant( 5516): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceStatusChanged wlan0, true
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/WifiNative-wlan0( 1015): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1015): setLastSelectedConfiguration -1
,D/ConnectivityService( 1015): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1015): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3380): Starting #4
,I/Hs20UtilService( 3380): Message received 5007
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1281): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1281): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1281): MountReceiver.mPrefHandler - 7002,
E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,D/CommandListener(  277): Setting iface cfg
,E/WifiStateMachine( 1015): Start Dhcp Watchdog 1
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1015): mCursor = null
,E/WifiNative-wlan0( 1015): do suspend false
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/dhcpcd  ( 5666): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5666): version 5.5.6 starting,
,E/dhcpcd  ( 5666): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5666): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 5666): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 5666): if(wlan0) info get Success. (MAC : C0.AA.48),
I/dhcpcd  ( 5666): bssid match,
,I/dhcpcd  ( 5666): wlan0: rebinding lease of 192.168.1.129
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/dhcpcd  ( 5666): wlan0: acknowledged 192.168.1.129 from 192.168.1.1
,I/dhcpcd  ( 5666): wlan0: leased 192.168.1.129 for 86400 seconds,
,E/WifiNative-wlan0( 1015): do suspend true,
,D/WifiP2pService( 1015): InactiveState{ what=143375 },
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1015): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1015): VerifyingLinkState enter
,D/WifiNative-wlan0( 1015): callSECApiInt - ID [210]
,E/ConnectivityService( 1015): updateNetworkInfo()
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1015): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 1015): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1015): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,D/ConnectivityService( 1015): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
E/WifiStateMachine( 1015): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3380): Starting #5
D/ConnectivityService( 1015): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1281): MountReceiver.onReceive - Keep current state
E/ConnectivityService( 1015): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1015): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService( 1015): LTETest block dns file not exists
,I/Hs20UtilService( 3380): Message received 5007
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,E/ConnectivityService( 1015): updateNetworkInfo()
,E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1015): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 502]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,D/ConnectivityService( 1015):    accepting network in place of null
,D/ConnectivityService( 1015): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1443): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1443): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1015): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1015): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1015): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1015): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1015): (HTTPLog)-Thread-170-1002276932: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 1000
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1015): mBoosterFLAG : 0
I/WifiTrafficPoller( 1015): current booster mode : FullMode
D/WifiNative-wlan0( 1015): callSECApiVoid - ID [212]
,I/Hs20UtilService( 3380): Starting #6
,I/Hs20UtilService( 3380): Message received 5007
,D/ConnectivityService( 1015): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/NtpTrustedTime( 1015): forceRefresh() from cache miss
,V/NetworkStats( 1015): updateIfacesLocked()
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 1000
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NetworkStats( 1015): performPollLocked() took 6ms
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
V/NearbySettings( 1281): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
,D/StatusBar.NetworkController( 1172): EthernetConnected: false
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1172): updateLTEICONDataNetType:0
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1281): MountReceiver.onReceive - Keep current state
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 3380): Starting #7
,I/Hs20UtilService( 3380): Message received 5007
,I/NearbySettings( 1281): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1015): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityXOffset,
D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1015): mCursor = null
,D/NtpTrustedTime( 1015): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1453807561096 mCachedNtpElapsedRealtime : 81070 mCachedNtpCertainty : 10
,D/SecContentProvider2( 1015): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1015): mCursor = null
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/SecContentProvider2( 1015): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1015): mCursor = null
,I/System.out( 1015): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1015): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,D/SRIB_DCS( 1172): log_dcs ThreadedRenderer::initialize entered! 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 26 Jan 2016 11:26:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453807558733], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453807558674]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
,D/ConnectivityService( 1015): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1015): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1172): EthernetConnected: false
,D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1172): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/AlarmManagerService( 1015): Setting time of day to sec=1453807561
D/AlarmManagerService( 1015): Trying to open a file
,I/DBG_DM  ( 2912): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/AlarmManagerService( 1015): File Open Success
D/AlarmManagerService( 1015): File Close Success
I/AlarmManagerService( 1015): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager( 1015): waitForAlarm result :65536
,I/DBG_DM  ( 2912): [com.wssyncmldm.llllIIIllIlIIIIllllI(230/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
W/AlarmManagerService( 1015): Unable to set rtc to 1453807561: Invalid argument
,I/DBG_DM  ( 2912): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/PCWCLIENTTRACE_PushUtil( 5053): SPPPushClient is installed : true
V/AlarmManager( 1015): waitForAlarm result :8
I/PCWCLIENTTRACE_PushUtil( 5053): sales region : global
V/AlarmManager( 1015): No more alarm at this time.nowELAPSED=81532 batch.start=82251
I/PCWCLIENTTRACE_PushUtil( 5053): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5053): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/OTPFW   ( 1015): OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1453807561563
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/WifiStateMachine( 1015): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,I/DowntimeConditions( 1015): android.intent.action.TIME_SET ignored because schedule turned off.
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,I/DBG_DM  ( 2912): [IlIlllIlllllIlIllllI(403/llIIllllIIlllIIIIlll)] Check completed.
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_SET
,W/Settings( 1015): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/splitIntent( 1015): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=10, mSplitNum[1]=19, mSplitNum[2]=27, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=35
I/splitIntent( 1015): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/SettingsProvider( 1015): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10054
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/KeyguardEffectViewUtil( 1172): isStrongPowerSavingMode() :false
,I/DBG_DM  ( 2912): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,W/SEC_DRM_PLUGIN_Playready(  281): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1453807559 after conversion: 1453807559,
I/libpersona( 5709): KNOX_SDCARD checking this for 10111
W/SEC_DRM_PLUGIN_Playready(  281): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1453807561 after conversion: 1453807561
I/libpersona( 5709): KNOX_SDCARD not a persona
,D/KeyguardEffectViewController( 1172): isPreloadedWallpaper=true
,I/ActivityManager( 1015): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5709 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/GeometricMosaic_Keyguard( 1172): update
E/Zygote  ( 5709): MountEmulatedStorage()
,E/Zygote  ( 5709): v2
D/KeyguardEffectViewUtil( 1172): getCurrentWallpaper() mWallpaperPath :null
I/SELinux ( 5709): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5709): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5709): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5709): TimaSignature is unavailable
,D/ActivityThread( 5709): Added TimaKeyStore provider,
,I/KLMS-2.5.183: ( 3433): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 26 12:26:01 GMT+01:00 2016
,E/Zygote  ( 5724): MountEmulatedStorage()
I/libpersona( 5724): KNOX_SDCARD checking this for 10081
E/Zygote  ( 5724): v2
I/libpersona( 5724): KNOX_SDCARD not a persona
I/SELinux ( 5724): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5724 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5724): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
E/SELinux ( 5724): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=5734 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 5734): MountEmulatedStorage()
E/Zygote  ( 5734): v2
I/libpersona( 5734): KNOX_SDCARD checking this for 10159
,I/libpersona( 5734): KNOX_SDCARD not a persona
I/SELinux ( 5734): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/TimaKeyStoreProvider( 5724): TimaSignature is unavailable,
I/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/SELinux ( 5734): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5734): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3433): KLMSAbstractReciever(): onReceive().END.
D/ActivityThread( 5724): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 5734): TimaSignature is unavailable
D/ActivityThread( 5734): Added TimaKeyStore provider
,I/KeyguardEffectViewUtil( 1172): set current wallpaper info
,D/SettingsProvider( 1015): name = keyguard_current_wallpaper_type
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10054
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/SettingsProvider( 1015): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10054
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/SettingsProvider( 1015): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10054
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/DBG_DM  ( 2912): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.games.chimera.GamesSyncServiceMainProxy; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/KLMS-2.5.183: ( 3433): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3433): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TEST    ( 1172): run!!!
,D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1990): Module APK com.google.android.play.games already loaded
,I/KLMS-2.5.183: ( 3433): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/GeometricMosaic_Renderer( 1172): setBackgroundBitmap,
E/Zygote  ( 5755): MountEmulatedStorage()
E/Zygote  ( 5755): v2,
I/libpersona( 5755): KNOX_SDCARD checking this for 10034
I/libpersona( 5755): KNOX_SDCARD not a persona
,I/SELinux ( 5755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5755): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5755 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0,
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3433): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3433): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,D/TimaKeyStoreProvider( 5755): TimaSignature is unavailable
,D/ActivityThread( 5755): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3433): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false,
,I/KLMS-2.5.183: ( 3433): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3433): NetworkChangeOperations(): uploadRequestLog().START 
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
I/DBG_DM  ( 2912): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/DBG_DM  ( 2912): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 2912): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/KLMS-2.5.183: ( 3433): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3433): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3433): KLMSIntentService(): onDestroy()
,I/DBG_DM  ( 2912): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GoogleURLConnFactory( 1778): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2912): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 2912): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2912): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
I/GamesSyncServiceMain( 1990): Found unexpected GCM tag when scheduling; aborting
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
W/GamesSyncServiceMain( 1990): Failed to execute periodic sync, missing client context - aborting
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.metadata.ContactMetadataSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,I/MusicStore( 5709): Database version: 108
,I/DBG_POLICYDM( 5099): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5099): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5099): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,E/DBG_POLICYDM( 5099): [com.policydm.XDMBroadcastReceiver(240/xdmNotInitSetResume)] DM Not Init
,I/DBG_POLICYDM( 5099): [com.policydm.XDMApplication(286/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_POLICYDM( 5099): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 5099): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/WaitQueueForNetworkActivate( 5132): notifyNetworkActivated
,E/SPPClientService( 5153): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 5291): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5291): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SA      ( 5291): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5291): [SLFUCHKMGR] constructor called
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/DBG_DM  ( 2912): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/DBG_DM  ( 2912): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,I/SA      ( 5291): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5291): [OR] == isSIMCardReady false ==
,I/SA      ( 5291): [SCU] == networkStateCheck == true
,I/SA      ( 5291): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5291): isChinaCountryCode : false
I/SA      ( 5291): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5291): [OR] == networkStateCheck true ==
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5099): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,E/Zygote  ( 5798): MountEmulatedStorage()
E/Zygote  ( 5798): v2
I/libpersona( 5798): KNOX_SDCARD checking this for 10044
I/libpersona( 5798): KNOX_SDCARD not a persona
,I/SELinux ( 5798): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5798): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5798): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5099): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,I/ActivityManager( 1015): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=5798 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 5132): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/TimaKeyStoreProvider( 5798): TimaSignature is unavailable
,D/ActivityThread( 5798): Added TimaKeyStore provider
,I/DBG_DM  ( 2912): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,I/SA      ( 5291): [OR] GetMyCountryZoneTask
,I/DBG_POLICYDM( 5099): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,I/SA      ( 5291): [OR] onReceive END
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500,
,W/ResourcesManager( 5798): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5798): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5798): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5798): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5798): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 5798): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5798): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5798): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/DownloadManager( 1225): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,V/AlarmManager( 1015): waitForAlarm result :4
,W/ResourcesManager( 5709): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5709): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SA      ( 5291): [SRS] prepareGetMyCountryZone
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842,
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_DM  ( 2912): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,I/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,D/SSRM:n  ( 1015): SIOP:: AP = 330
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/DBG_DM  ( 2912): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
I/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5099): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/PowerManagerService( 1015): [PWL] Off : 30s ago
I/PowerManagerService( 1015): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1015): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5458, ws=null) (elapsedTime=4304)
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.gms.chromesync/com.google/eM_ADDR' (uid=1000, pid=1015, ws=WorkSource{10012}) (elapsedTime=782)
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10012, pid=1778, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=723)
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.gms.auth.api.credentials/com.google/eM_ADDR' (uid=1000, pid=1015, ws=WorkSource{10012}) (elapsedTime=507)
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.android.contacts.metadata/com.google/eM_ADDR' (uid=1000, pid=1015, ws=WorkSource{10012}) (elapsedTime=478)
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.gms.drive.sync/com.google/eM_ADDR' (uid=1000, pid=1015, ws=WorkSource{10012}) (elapsedTime=461)
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.sec.android.gallery3d.picasa.contentprovider/com.google/eM_ADDR' (uid=1000, pid=1015, ws=WorkSource{10044}) (elapsedTime=337)
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              'GpsLocationProvider' (uid=1000, pid=1015, ws=null) (elapsedTime=283)
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10012, pid=1778, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=224)
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1015, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=215)
,I/DBG_POLICYDM( 5099): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5099): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5099): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5099): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/SA      ( 5291): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/art     ( 1015): Explicit concurrent mark sweep GC freed 52567(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 3.085ms total 206.528ms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,I/DBG_POLICYDM( 5099): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5099): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5099): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5099): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
I/SA      ( 5291): [SSP] query invoked
,I/DBG_POLICYDM( 5099): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/01/25/12:51:01
,V/JNIHelp ( 5709): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/DBG_POLICYDM( 5099): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/01/26/12:26:02
,E/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,E/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@19290a59
,I/DBG_POLICYDM( 5099): [com.policydm.polling.XPollingAgent(323/xpollingDefaultPollingTime)] 
,I/DBG_POLICYDM( 5099): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2( 1015): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1015): mCursor = null
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5825 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/DBG_POLICYDM( 5099): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0,
,E/Zygote  ( 5825): MountEmulatedStorage(),
E/Zygote  ( 5825): v2
,I/libpersona( 5825): KNOX_SDCARD checking this for 10104
I/libpersona( 5825): KNOX_SDCARD not a persona
,I/SELinux ( 5825): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0,
,I/SELinux ( 5825): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5825): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/SA      ( 5291): [TPMU] GetMccFromDB : null
I/SA      ( 5291): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5291): [TPM] isNoProxy(default) : true
,I/ActivityManager( 1015): Killing 3668:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.youtube
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService; callingUser = 0; userId(target) = 0
,W/ActivityThread( 5709): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5709): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a037ed2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5709): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5709): GMSCore installation verified
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.youtube
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/SMD     (  290): DCD OFF
,E/Zygote  ( 5840): MountEmulatedStorage(),
E/Zygote  ( 5840): v2
I/libpersona( 5840): KNOX_SDCARD checking this for 10166
I/libpersona( 5840): KNOX_SDCARD not a persona
,I/SELinux ( 5840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5840): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService: pid=5840 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NearbySource( 5798): Nearby Source Create!
,D/NearbyContext( 5798): Nearby Context Create!
,I/DBG_POLICYDM( 5099): [com.policydm.polling.XPollingAgent(347/xpollingDefaultPollingTime)] Next Polling Time:2016/01/27/21:49:38,
,D/TimaKeyStoreProvider( 5825): TimaSignature is unavailable,
D/ActivityThread( 5825): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 48.193ms,
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,D/accuweather( 1711): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE,
E/GpsLocationProvider( 1015): No APN found to select.
E/ActivityThread( 1990): Failed to find provider info for com.android.contacts.metadata
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 845us total 18.274ms
,D/TimaKeyStoreProvider( 5840): TimaSignature is unavailable
,D/ActivityThread( 5840): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 19.493ms
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml,
,I/DBG_POLICYDM( 5099): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,I/DBG_POLICYDM( 5099): [com.policydm.restclient.XRCProcess(921/xspdHandler)] XEVENT_RC_GET_VERSION
,I/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,E/File    ( 5291): fail readDirectory() errno=2
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,W/ContextImpl( 5798): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 5798): Samsung link source created
,D/accuweather( 1711): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,D/accuweather( 1711): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1711): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1711): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3668/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ResourcesManager( 5825): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/accuweather( 1711): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1711): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 23045, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 1015): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 114335, reason: UserStart
,I/DBG_DM  ( 2912): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,W/ContextImpl( 2912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/SettingsProvider( 1015): name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,I/ConfigStore( 5709): Config Database version: 1
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/ContactProvider( 5798): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/DBG_DM  ( 2912): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/System.out( 1778): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,W/ResourcesManager( 5840): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5840): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/System.out( 1778): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1778): Tagging socket 48 with tag 1000120300000000{268440067,0} for uid -1, pid: 1778, getuid(): 10012
,I/DBG_POLICYDM( 5099): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBSpdAdp(158/xdbSetSpdState)] nRestClientMode = 6
,E/DBG_POLICYDM( 5099): [com.policydm.restclient.XRCProcess(212/RestClientProcess)] SPD SERVICE Start!!
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,V/JNIHelp ( 5840): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ContactProvider( 5798): getAllContactInfoList End
,I/syncContacts( 5798): thread: 988, sync time = 226
,I/DBG_POLICYDM( 5099): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,W/ContextImpl( 5099): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.policydm.restclient.XRCProcess.RestClientProcess:213 com.policydm.restclient.XRCProcess.access$100:77 com.policydm.restclient.XRCProcess$RestClientThread.run:134 
,D/ActivityManager( 1015): startService callerProcessName:com.policydm, calleePkgName: com.policydm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.policydm/com.policydm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.policydm, destAppInfo.processName = com.policydm
,I/DBG_POLICYDM( 5099): [com.policydm.restclient.XRCProcess(622/execute)] 
,I/DBG_POLICYDM( 5099): [com.policydm.XDMService(60/onCreate)] 
,W/ActivityThread( 5099): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1015): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager( 1172): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5099): [com.policydm.XDMService(82/onStartCommand)] 
,W/ActivityThread( 5840): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5840): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ae56446: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5840): Installed default security provider GmsCore_OpenSSL
I/DBG_DM  ( 2912): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1015): mCursor = null
,I/qtaguid ( 1778): Tagging socket 77 with tag 1000120300000000{268440067,0} for uid -1, pid: 1778, getuid(): 10012
,D/KnoxNotification( 1172): ----- inflateViews : modified publicViewLocal -----
,I/System.out( 5099): Thread-868(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5099): Thread-868(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5099): Thread-868(ApacheHTTPLog):isShipBuild true
I/System.out( 5099): Thread-868(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5099): Thread-868(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/KnoxNotification( 1172): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1172): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 1000
,I/PhoneStatusBar( 1172): Icon Only
,I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1015): mCursor = null
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5132): AutoUpdateManager:IDLE:execute
,E/Auth.Api.Credentials( 1990): [CredentialSyncAdapter] Unknown sync event.
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CheckinService( 1990): Checkin interval check for package: unspecified last checkin: 1453002886666 min interval config: 0 actual interval: 804676567
,D/SecContentProvider2( 1015): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1015): mCursor = null
,D/InitializeManagerStateMachine( 5132): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5132): exit::IDLE
D/InitializeManagerStateMachine( 5132): entry::NETWORK_CHECK
,D/SecContentProvider2( 1015): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1015): mCursor = null
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/InitializeManagerStateMachine( 5132): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5132): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5132): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5132): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5132): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5132): entry::SUCCESS
D/hcjo    ( 5132): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/jxcore-log( 5378): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5378): 
,D/hcjo    ( 5132): AutoUpdateTriggerManager:REQUEST2:requestInterval
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 2912): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 2912): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,W/ContextImpl( 5709): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5709): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/iu.SyncManager( 1990): SYNC; picasa accounts
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/art     ( 5840): Suspending all threads took: 101.150ms
,W/ContextImpl( 5709): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/NetworkLogImpl( 1990): Loaded NetworkSpeedPredictor
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/iu.Environment( 1990): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1990): num queued entries: 0
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/iu.UploadsManager( 1990): num updated entries: 0
,I/iu.SyncManager( 1990): NEXT; no task
,I/CheckinService( 1990): Checking schedule, now: 1453807563377 next: 1453542149524
,I/CheckinService( 1990): active receiver: enabled
,I/Volley  ( 5132): RestApi Request Add : 2307
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,I/CheckinService( 1990): Preparing to send checkin request
I/EventLogService( 1990): Accumulating logs since 1453806202451
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/File    ( 5132): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.gmsproc.GcmIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/System.out( 5099): Thread-868 calls detatch()
,I/DBG_POLICYDM( 5099): [com.policydm.restclient.XRCProcess(328/RestClientProcess)] HTTP status is 200
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/dhcpcd  ( 5666): wlan0: sending IPv6 Router Solicitation
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/DBG_POLICYDM( 5099): [com.policydm.polling.XPollingAgent(204/xpollingNextPollingTime)] Next Polling Time:2016/02/02/14:24:23
,I/AudioService( 1015): getStreamVolume 3 index 0
,I/MediaRouter( 5709): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/DBG_POLICYDM( 5099): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,V/MusicLeanback( 5709): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5709): type=WIFI subType= reason=null isConnected=true
,I/DBG_POLICYDM( 5099): [com.policydm.polling.XPollingAgent(165/xpollingSaveXMLData)] Next StatusReport Time:2016/02/04/15:20:33
,E/DBG_POLICYDM( 5099): [com.policydm.restclient.XRCProcess(388/RestClientProcess)] bPolicyUpdate is false
,I/Babel   ( 5825): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5825): MmsConfig.loadMmsSettings
,I/DBG_POLICYDM( 5099): [com.policydm.restclient.XRCProcess(948/callRestClientFinish)] 
,I/Babel   ( 5825): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
E/DBG_POLICYDM( 5099): [com.policydm.XDMBroadcastReceiver(540/xdmSetCheckedIntent)] b_AlreadyReceivedIntent : false
,I/Babel   ( 5825): MmsConfig.loadFromDatabase
,W/ResourcesManager( 5840): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5840): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBSpdAdp(158/xdbSetSpdState)] nRestClientMode = 0
,I/DBG_POLICYDM( 5099): [com.policydm.ui.XUIAdapter(33/xuiAdpGetUiMode)] nDmUiMode : 0
,E/DBG_POLICYDM( 5099): [com.policydm.restclient.XRCProcess(983/callRestClientFinish)] SPD SERVICE Stop!!
,W/ContextImpl( 5099): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.policydm.restclient.XRCProcess.callRestClientFinish:984 com.policydm.restclient.XRCProcess.RestClientProcess:504 com.policydm.restclient.XRCProcess.access$100:77 
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/Babel   ( 5825): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5825): MmsConfig.loadFromResources
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
E/Babel   ( 5825): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5825): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.policydm/com.policydm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.policydm, destAppInfo.processName = com.policydm
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 5099): [com.policydm.XDMService(43/onDestroy)] 
,W/Settings( 5825): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1015): Killing 5068:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,I/NetworkMonitor( 5709): type=WIFI subType= reason=null isConnected=true
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5897): MountEmulatedStorage(),
E/Zygote  ( 5897): v2
,I/libpersona( 5897): KNOX_SDCARD checking this for 10002
I/libpersona( 5897): KNOX_SDCARD not a persona
,W/System.err( 5840): YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.,
,I/ActivityManager( 1015): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=5897 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5897): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5897): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5897): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Babel_StickerModule( 5825): App launched.
,D/TimaKeyStoreProvider( 5897): TimaSignature is unavailable
,D/ActivityThread( 5897): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5068/cgroup.procs: No such file or directory
I/Babel_StickerModule( 5825): Sticker update initiated. last:1453376102948 empty:false
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/System.out( 5840): YouTube MDX: MDX video stage moved to NEW
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,I/System.out( 5840): YouTube MDX: MDX video player state moved to UNSTARTED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/System.out( 5840): YouTube MDX: MDX ad player state moved to UNSTARTED
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5709): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5709): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5921 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 5921): MountEmulatedStorage(),
E/Zygote  ( 5921): v2
,I/libpersona( 5921): KNOX_SDCARD checking this for 10113
I/libpersona( 5921): KNOX_SDCARD not a persona
,I/SELinux ( 5921): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5921): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0,
W/QCamera2Factory(  283): getCameraInfo: X
,E/SELinux ( 5921): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  283): getCameraInfo: X
,I/GHttpClientFactory( 5709): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/art     ( 1778): Explicit concurrent mark sweep GC freed 47039(2MB) AllocSpace objects, 18(311KB) LOS objects, 40% free, 12MB/21MB, paused 1.366ms total 263.192ms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/TimaKeyStoreProvider( 5921): TimaSignature is unavailable
,D/ActivityThread( 5921): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 5825): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5825): Unsupported mime audio/evrc
,W/AudioCapabilities( 5825): Unsupported mime audio/qcelp
,I/System.out( 1778): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,W/AudioCapabilities( 5825): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5825): Unsupported mime audio/mpeg-L2
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5947): MountEmulatedStorage(),
E/Zygote  ( 5947): v2
I/libpersona( 5947): KNOX_SDCARD checking this for 1000
I/SELinux ( 5947): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 5947): KNOX_SDCARD not a persona
,I/SELinux ( 5947): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5947): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=5947 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/AudioCapabilities( 5825): Unsupported mime audio/x-ms-wma,
,W/AudioCapabilities( 5825): Unsupported mime audio/x-ima
W/AudioCapabilities( 5825): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5825): Unsupported mime audio/evrc,
,W/VideoCapabilities( 5825): Unsupported mime video/wvc1
,D/TimaKeyStoreProvider( 5947): TimaSignature is unavailable
,D/ActivityThread( 5947): Added TimaKeyStore provider
,W/VideoCapabilities( 5825): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5825): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5825): Unsupported mime video/wvc1
,W/VideoCapabilities( 5825): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5825): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5825): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5825): Unsupported mime video/mp43
,W/VideoCapabilities( 5825): Unsupported mime video/sorenson
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5
,W/VideoCapabilities( 5825): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5825): Unsupported profile 4 for video/mp4v-es
,I/DIAGMON_AGENT( 5947): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/btif_config_util( 5458): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/System.out( 1778): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1778): Tagging socket 81 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5825): Creating RTCS
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 2146(82KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 47.779ms total 337.364ms
,I/qtaguid ( 1778): Tagging socket 84 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,I/jxcore-log( 5378): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5378): 
,I/jxcore-log( 5378): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5378): 
,I/GCM     ( 1778): GCM config loaded
,I/ActivityManager( 1015): Killing 5081:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,I/jxcore-log( 5378): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5378): 
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,I/jxcore-log( 5378): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5378): 
,I/jxcore-log( 5378): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5378): 
,I/DIAGMON_AGENT( 5947): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.PeopleSyncService; callingUser = 0; userId(target) = 0
,I/jxcore-log( 5378): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5378): 
,W/PhenotypeConfigurator( 1778): Server returned 404
,I/DIAGMON_AGENT( 5947): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5947): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 5947): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 5947): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 5947): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 32710(1598KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.859ms total 169.480ms
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/libprocessgroup( 1015): failed to open /acct/uid_10156/pid_5081/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  257): id=13 Removed Uoast (8/9)
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/SurfaceFlinger(  257): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 1015): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 84820
,D/PowerManagerService( 1015): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
,D/PowerManagerService( 1015): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{10054}) (elapsedTime=3713)
,D/OpenGLRenderer( 2912): Render dirty regions requested: true
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5840): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=4, Uoast
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,D/PowerManagerService( 1015): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/SRIB_DCS( 2912): log_dcs ThreadedRenderer::initialize entered! 
,I/Adreno-EGL( 2912): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2912): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2912): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2912): Local Branch: 
I/Adreno-EGL( 2912): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2912): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2912):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/OpenGLRenderer( 2912): Initialized EGL, version 1.4
,W/ResourcesManager( 5825): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5825): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager( 1015): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=5988 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
D/OpenGLRenderer( 2912): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2912): Enabling debug mode 0
,E/Zygote  ( 5988): MountEmulatedStorage(),
E/Zygote  ( 5988): v2
,I/libpersona( 5988): KNOX_SDCARD checking this for 10009
I/libpersona( 5988): KNOX_SDCARD not a persona,
,I/SELinux ( 5988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5988): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/dex2oat ( 5963): ----------------------------------------------------
I/dex2oat ( 5963): <SS>: S T A R T I N G . . .
I/dex2oat ( 5963): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 5963): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads637611181.jar --oat-fd=39 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads637611181.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/TimaKeyStoreProvider( 5988): TimaSignature is unavailable
,D/ActivityThread( 5988): Added TimaKeyStore provider
,D/ActivityManager( 1015): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,V/JNIHelp ( 5825): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5825): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5825): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@389847fa: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5825): Installed default security provider GmsCore_OpenSSL
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5921): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/InitializeManagerStateMachine( 5132): exit::SUCCESS
D/InitializeManagerStateMachine( 5132): entry::IDLE
,I/Babel   ( 5825): Destroying RTCS
,I/System.out( 5132): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 5132): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5132): (HTTPLog)-Static: isShipBuild true
I/System.out( 5132): (HTTPLog)-Thread-876-760302641: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5132): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10010
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10010
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5921): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/dex2oat ( 5963): dex2oat took 317.124ms (threads: 4)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/PeopleSync( 1990): onPerformSync() [5005f081]
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ContextImpl( 5921): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ConnectivityManager( 1990): CallingUid : 10012, CallingPid : 1990
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/ConnectivityService( 1015): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1015): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1015): apparently satisfied.  currentScore=60
,D/ConnectivityService( 1015): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
W/ContextImpl( 5921): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityManager.CallbackHandler( 1990): CM callback handler got msg 524290
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CheckinRequestBuilder( 1990): Checkin reason type: 12 attempt count: 1
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1015): getStreamVolume 3 index 0
,E/ActivityThread( 1990): Failed to find provider info for com.google.android.wearable.settings
,I/System.out( 5132): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 5132): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5132, getuid(): 10010
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/SA      ( 5291): [RC New] Execute method=[GET] start
,E/SMD     (  290): DCD OFF
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 4768:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,I/FOTA_Client( 5988): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/FOTA_Client( 5988): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/WebViewFactory( 5921): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5840): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 5840): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5840): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,I/FOTA_Client( 5988): [IlIlIIllllIllIIIIIll(86/llllIIIllIlIIIIllllI)] Polling time is not vaild
,I/FOTA_Client( 5988): [com.sec.android.fotaclient.FotaUpdaterReceiver(101/onReceive)] Polling time is already passed. Start device init Immediately
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.fotaclient, calleePkgName: com.sec.android.fotaclient
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.fotaclient/com.sec.android.fotaclient.FotaUpdateIntentService; callingUser = 0; userId(target) = 0
,I/LibraryLoader( 5921): Time to load native libraries: 2 ms (timestamps 5699-5701)
I/LibraryLoader( 5921): Expected native library version number "",actual native library version number ""
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.fotaclient, destAppInfo.processName = com.sec.android.fotaclient
,I/System.out( 1778): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1778): Tagging socket 81 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,I/System.out( 1778): (HTTPLog)-Static: isSBSettingEnabled false
,V/WebViewChromiumFactoryProvider( 5921): Binding Chromium to main looper Looper (main, tid 1) {3140ab91}
,I/LibraryLoader( 5921): Expected native library version number "",actual native library version number ""
,I/chromium( 5921): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/System.out( 1778): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1778): Tagging socket 90 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,W/FOTA_Client( 5988): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/SA      ( 5291): [RC New] Security=[true]
,I/System.out( 5291): Thread-910(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5291): Thread-910(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5291): Thread-910(ApacheHTTPLog):isShipBuild true
I/System.out( 5291): Thread-910(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5291): Thread-910(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10041
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10041
,W/libprocessgroup( 1015): failed to open /acct/uid_10032/pid_4768/cgroup.procs: No such file or directory
,I/FOTA_Client( 5988): [com.sec.android.fotaclient.FotaUpdateIntentService(30/onHandleIntent)] Update State: Start update request
,I/BrowserStartupController( 5921): Initializing chromium process, singleProcess=true
,W/art     ( 5921): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5921): ApplicationContext is null in ApplicationStatus
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.cache.DataUpdateListenerCacheService; callingUser = 0; userId(target) = 0
,I/FOTA_Client( 5988): [IIIlIIIIIIlIlllllllI(45/llIIIIlllllIIllIIllI)] Update State: Check condition to decide update type
,W/chromium( 5921): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 5921): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,I/chromium( 5921): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
D/ActivityManager( 1015): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/Adreno-EGL( 5921): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5921): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5921): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5921): Local Branch: 
I/Adreno-EGL( 5921): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5921): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5921):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/FOTA_Client( 5988): [lIllIIIllIIllIIlIllI(143/llIIIIlllllIIllIIllI)] Update State: Checking polling to server
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/FOTA_Client( 5988): [lIllIllllIIIlllIlllI(88/llllIIIllIlIIIIllllI)] WiFi Network is connected
,I/FOTA_Client( 5988): [lIIllIIIIIlllIIlllIl(28/llIIIIlllllIIllIIllI)] Request Network Connection
,I/FOTA_Client( 5988): [lIllIllllIIIlllIlllI(88/llllIIIllIlIIIIllllI)] WiFi Network is connected
,D/AndroidHttpClient( 5840): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
,D/AndroidHttpClient( 5840): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 5840): Thread-1056(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5840): Thread-1056(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5840): Thread-1056(ApacheHTTPLog):isShipBuild true
I/System.out( 5840): Thread-1056(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5840): Thread-1056(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10166
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10166
,I/FOTA_Client( 5988): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(82/llIIIIlllllIIllIIllI)] Server time is zero
,I/FOTA_Client( 5988): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(111/llllIIIllIlIIIIllllI)] Request ServerTime
,W/AudioManagerAndroid( 5921): Requires BLUETOOTH permission
,I/FOTA_Client( 5988): [com.sec.android.fota.osp.http.RestClient(264/llIIIIlllllIIllIIllI)] =====================================================================
,I/NSApplication( 5921): Starting up...
,I/FOTA_Client( 5988): [com.sec.android.fota.osp.http.RestClient(276/llIIIIlllllIIllIIllI)] =====================================================================
,I/System.out( 5988): Thread-1017(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5988): Thread-1017(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5988): Thread-1017(ApacheHTTPLog):isShipBuild true
I/System.out( 5988): Thread-1017(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5988): Thread-1017(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10009
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10009
,I/System.out( 5840): Thread-1040(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5840): Thread-1040(ApacheHTTPLog):isShipBuild true
,I/System.out( 5840): Thread-1040(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5840): Thread-1040(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0,
D/EnterpriseController(  277): uids 10166
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10166
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
I/qtaguid ( 1778): Tagging socket 92 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/System.out( 5840): Thread-1045(ApacheHTTPLog):isSBSettingEnabled false
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/System.out( 5840): Thread-1045(ApacheHTTPLog):isShipBuild true
,I/System.out( 5840): Thread-1045(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5840): Thread-1045(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10166
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10166
,I/DBG_POLICYDM( 5099): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5458): Disconnected process message: 10
,I/DBG_POLICYDM( 5099): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5099): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/DBG_POLICYDM( 5099): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/DBG_POLICYDM( 5099): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/PicasaService( 5798): start picasa sync
,D/PicasaService( 5798): end picasa sync
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,I/PeopleSync( 1990): Setting subscription: result=true [5005f081]
,I/PeopleSync( 1990): Starting sync, feed=null [5005f081]
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 2956(117KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 780us total 24.318ms
,I/art     ( 1629): WaitForGcToComplete blocked for 25.544ms for cause Explicit
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 1305(57KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 767us total 40.411ms
,E/Zygote  ( 6118): MountEmulatedStorage()
E/Zygote  ( 6118): v2
I/libpersona( 6118): KNOX_SDCARD checking this for 10125
I/libpersona( 6118): KNOX_SDCARD not a persona
,I/SELinux ( 6118): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6118 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
I/SELinux ( 6118): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6118): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 4802:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 6118): TimaSignature is unavailable
,D/ActivityThread( 6118): Added TimaKeyStore provider
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1015): Killing 5208:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,W/ResourcesManager( 6118): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6118): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6118): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{38e9e077 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/QuickConnect( 6118): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6118): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6118): PeriphStartReceiver.onReceive - no need to start
,W/art     ( 5825): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 1990): Explicit concurrent mark sweep GC freed 13026(1113KB) AllocSpace objects, 31(496KB) LOS objects, 40% free, 14MB/23MB, paused 1.447ms total 84.972ms
,I/art     ( 1990): WaitForGcToComplete blocked for 85.319ms for cause Explicit
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gm, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.provider.MailSyncAdapterService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6136): MountEmulatedStorage()
E/Zygote  ( 6136): v2
I/libpersona( 6136): KNOX_SDCARD checking this for 10101
I/libpersona( 6136): KNOX_SDCARD not a persona
,I/SELinux ( 6136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6136 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6136): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/qtaguid ( 5840): Tagging socket 53 with tag 0{0,0} for uid -1, pid: 5840, getuid(): 10166
,I/qtaguid ( 5132): Untagging socket 26
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
W/libprocessgroup( 1015): failed to open /acct/uid_10072/pid_5208/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4802/cgroup.procs: No such file or directory
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/qtaguid ( 5840): Tagging socket 48 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 5840, getuid(): 10166
,D/TimaKeyStoreProvider( 6136): TimaSignature is unavailable
,D/ActivityThread( 6136): Added TimaKeyStore provider
,D/SecurityLogAgent( 5592): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5592): KnoxConfiguration : Current State Mapping Found 
I/System.out( 1778): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1778): Tagging socket 81 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
D/SecurityLogAgent( 5592): StateMachine : Current State = 1
,D/Finsky  ( 4857): [835] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4857): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SecurityLogAgent( 5592): StateMachine : Changed Current State = 1
,I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1015): Killing 5026:com.android.mms/u0a46 (adj 15): empty #31
,I/splitIntent( 1015): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=24
,I/splitIntent( 1015): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,I/System.out( 1778): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5988): IntentService[Service[FotaUpdateIntentService]] calls detatch()
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController(  277): uids 10012,
,D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0,
,D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
I/FOTA_Client( 5988): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(139/llllIIIllIlIIIIllllI)] Receive result: success in ServerTime
,I/FOTA_Client( 5988): [com.sec.android.fota.osp.http.RestClient(264/llIIIIlllllIIllIIllI)] =====================================================================
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5053): mConnectivityHandler : connected
,E/Zygote  ( 6156): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6156 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6156): v2
I/libpersona( 6156): KNOX_SDCARD checking this for 10062
I/libpersona( 6156): KNOX_SDCARD not a persona
,I/SELinux ( 6156): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/System.out( 1778): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1778): Tagging socket 54 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,I/SELinux ( 6156): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6156): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6167): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6167 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/Zygote  ( 6167): v2
I/libpersona( 6167): KNOX_SDCARD checking this for 10135
I/SELinux ( 6167): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6167): KNOX_SDCARD not a persona
I/SELinux ( 6167): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6167): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6156): TimaSignature is unavailable
D/ActivityThread( 6156): Added TimaKeyStore provider
,I/FOTA_Client( 5988): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
D/TimaKeyStoreProvider( 6167): TimaSignature is unavailable
D/ActivityThread( 6167): Added TimaKeyStore provider
,W/ResourcesManager( 6167): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6167): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6167): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/FOTA_Client( 5988): [com.sec.android.fota.osp.http.RestClient(276/llIIIIlllllIIllIIllI)] =====================================================================
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/System.out( 5988): Thread-1017(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5988): Thread-1017(ApacheHTTPLog):isShipBuild true
,I/System.out( 5988): Thread-1017(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5988): Thread-1017(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10009
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10009
,I/qtaguid ( 1778): Tagging socket 88 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,D/hcjo    ( 5132): AutoUpdateTriggerManager:REQUEST2:setInterval:345600000
,I/art     ( 1990): Explicit concurrent mark sweep GC freed 4486(185KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 13MB/23MB, paused 1.571ms total 282.209ms
,D/hcjo    ( 5132): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
D/hcjo    ( 5132): AutoUpdateManager:UPD_CHECK_TIMING:onUpdateTime
D/hcjo    ( 5132): SelfUpdateManager:IDLE:execute
,D/hcjo    ( 5132): SelfUpdateManager:CONDITION_CHECK:onUpdateCondition
,W/DriveInitializer( 1990): Awaiting to be initialized
,W/DriveInitializer( 1990): Background init thread started
,I/System.out( 5988): IntentService[Service[FotaUpdateIntentService]] calls detatch()
,D/daemonapp( 1310): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
I/FOTA_Client( 5988): [IIllIIIIlIlIlIlIllII(102/llIIIIlllllIIllIIllI)] result is success
D/daemonapp( 1310): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/libprocessgroup( 1015): failed to kill 1 processes for processgroup 5026
,D/SettingsProvider( 1015): name = FOTA_CLIENT_HEARTBEAT_PERIOD
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
,I/Gmail   ( 6136): getAccountsCursor
,D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10009
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/SettingsProvider( 1015): ret = -1
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 1990): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,I/ExternalOEMControlProvider( 6156): onCreate
,D/SettingsProvider( 1015): name = FOTA_CLIENT_HEARTBEAT_ADD
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10009
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
,D/CountryDetector( 1015): No listener is left
,I/System.out( 5840): Thread-1056 calls detatch()
,E/Zygote  ( 6200): MountEmulatedStorage()
E/Zygote  ( 6200): v2
,I/libpersona( 6200): KNOX_SDCARD checking this for 1000
I/libpersona( 6200): KNOX_SDCARD not a persona
,I/SELinux ( 6200): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
D/EnterpriseController(  277): uids 10104
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10104
,I/SELinux ( 6200): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6200): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=6200 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10009
,I/ActivityManager( 1015): Killing 5225:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 6200): TimaSignature is unavailable
D/ActivityThread( 6200): Added TimaKeyStore provider
,W/PCWCLIENTTRACE_AccountUtil( 5053): [hasSamungAccount] - No Samsung Account
,D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/Volley  ( 5132): RestApi Request Add : 2346
,I/KLMS-2.5.183: ( 3433): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Jan 26 12:26:06 GMT+01:00 2016
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/qtaguid ( 5840): Untagging socket 48
,D/daemonapp( 1310): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1310): [MSC_Daemon]>>> ====================================================================================================================
,I/System.out( 5840): Thread-1040 calls detatch()
D/comsamsunglog( 1310): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1310): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1310): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1310): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5053): [GetString-S]
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/System.out( 5132): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5132): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 5132): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5132, getuid(): 10010
,D/daemonapp( 1310): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,W/GAV2    ( 6136): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/daemonapp( 1310): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1310): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1310): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1310): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,W/libprocessgroup( 1015): failed to open /acct/uid_10047/pid_5225/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/KLMS-2.5.183: ( 3433): KLMSAbstractReciever(): onReceive().END.
,I/FOTA_Client( 5988): [llIllIIlIIIIIIIllllI(191/IllIlIIIIlIIlIIIllIl)] Request NetActionGetPolling
,I/FOTA_Client( 5988): [lIllIIIllIIllIIlIllI(146/llIIIIlllllIIllIIllI)] Receive result: success in NetActionGetPolling
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/FOTA_Client( 5988): [IIllIIIIlIlIlIlIllII(193/IIIIllIlIIlIIIIlllIl)] Find Firmware version in Version List
,I/FOTA_Client( 5988): [IIIlIIllllllIllIlIII(177/llIIIIlllllIIllIIllI)] Update State: success to check polling
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 33346(1650KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 4.827ms total 203.185ms
,W/DriveInitializer( 1990): Background init thread ended
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/SA      ( 5291): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/FOTA_Client( 5988): [IlIlIIllllIllIIIIIll(37/llIIIIlllllIIllIIllI)] Calculate next polling time
,D/comdaemonstockapp( 1310): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1310): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,I/ Time Manager ( 6156): Time Difference not stored. TIME_DIFFERENCE
,E/Gmail   ( 6136): Error finding the version of the Email provider.....
E/Gmail   ( 6136): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6136): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 6136): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 6136): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 6136): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6136): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6136): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 6136): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6136): We do not support migrating this version of the Email provider.
,D/SettingsProvider( 1015): name = FOTA_CLIENT_POLLING_TIME
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10009
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 6136): getAccountsCursor
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10009
,W/Gmail   ( 6136): Sync started for account: account:61035162
,W/DefaultRequestDirector( 5840): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/qtaguid ( 5840): Untagging socket 53
,I/System.out( 5840): Thread-1045 calls detatch()
E/Volley  ( 5840): [1045] abz.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
,I/CheckinService( 1990): Checkin interval check for package: unspecified last checkin: 1453002886666 min interval config: 0 actual interval: 804680590
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/System.out( 5840): Thread-1045(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5840): Thread-1045(ApacheHTTPLog):isShipBuild true
I/System.out( 5840): Thread-1045(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5840): Thread-1045(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5840): Tagging socket 53 with tag 0{0,0} for uid -1, pid: 5840, getuid(): 10166
,I/qtaguid ( 5840): Tagging socket 54 with tag 0{0,0} for uid -1, pid: 5840, getuid(): 10166
,I/ReactiveServiceManager( 5053): Supported : 1
,D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,I/KLMS-2.5.183: ( 3433): KLMSIntentService(): onCreate()
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 10
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/QSEECOMAPI: ( 1015): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1015): QSEECom_shutdown_app, app_id = 10
,E/terrier ( 1015): handleString: Failed to handle string(-4)
E/terrier ( 1015): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5053): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5053): [GetString-E]
I/KLMS-2.5.183: ( 3433): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/FOTA_Client( 5988): [llIllIIIIlllIIlIIllI(238/llIIIIlllllIIllIIllI)] Update State: Initialize polling update
I/FOTA_Client( 5988): [llIllIIlIIIIIIIllllI(248/IlIlIlIlIlIIlllllIlI)] request Polling
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
I/libpersona( 6245): KNOX_SDCARD checking this for 10042
E/Zygote  ( 6245): MountEmulatedStorage()
I/libpersona( 6245): KNOX_SDCARD not a persona,
E/Zygote  ( 6245): v2
I/SELinux ( 6245): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/PCWCLIENTTRACE_PushUtil( 5053): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5053): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5053): getPushTypeList : [SPP, GCM]
W/ResourcesManager( 6200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/PCWCLIENTTRACE_PCWHandler( 5053): [ensureRegistration] - No Samsung account
I/SELinux ( 6245): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6245): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1015): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6245 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
I/KLMS-2.5.183: ( 3433): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/FOTA_Client( 5988): [com.sec.android.fotaclient.FotaUpdateIntentService(36/onHandleIntent)] Update State: Finish update request
,I/KLMS-2.5.183: ( 3433): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
I/KLMS-2.5.183: ( 3433): KLMSIntentService(): TIME_CHANGED
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,I/KLMS-2.5.183: ( 3433): StateImplV2(): dateTimeChanged().START : Tue Jan 26 12:26:07 GMT+01:00 2016
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3433): StateImplV2(): dateTimeChanged().END
,D/TimaKeyStoreProvider( 6245): TimaSignature is unavailable,
D/ActivityThread( 6245): Added TimaKeyStore provider,
,E/Zygote  ( 6262): MountEmulatedStorage(),
I/ActivityManager( 1015): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6262 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/Zygote  ( 6262): v2
,I/libpersona( 6262): KNOX_SDCARD checking this for 10012
I/libpersona( 6262): KNOX_SDCARD not a persona
,I/SELinux ( 6262): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 6262): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6262): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     (  317): Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 690us total 23.670ms
,D/TimaKeyStoreProvider( 6262): TimaSignature is unavailable
,D/ActivityThread( 6262): Added TimaKeyStore provider
,D/SecurityLogAgent( 5592): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5592): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 5592): StateMachine : Current State = 1
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 20.843ms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 18.897ms
,W/ResourcesManager( 6262): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6262): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
D/accuweather( 1711): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1711): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 5666): wlan0: sending IPv6 Router Solicitation,
,E/Zygote  ( 6280): MountEmulatedStorage()
,E/Zygote  ( 6280): v2
I/libpersona( 6280): KNOX_SDCARD checking this for 10157
I/libpersona( 6280): KNOX_SDCARD not a persona
,I/SELinux ( 6280): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6280 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,I/SELinux ( 6280): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6280): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 5242:com.wsomacp/u0a25 (adj 15): empty #31
,I/MultiDex( 6262): VM with version 2.1.0 has multidex support
I/MultiDex( 6262): install
I/MultiDex( 6262): VM has multidex support, MultiDex support library is disabled.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/SA      ( 5291): [RC New] [v2liruge] api execute + 1790
I/SA      ( 5291): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,E/Zygote  ( 6290): MountEmulatedStorage()
E/Zygote  ( 6290): v2
,I/libpersona( 6290): KNOX_SDCARD checking this for 10085
I/System.out( 5291): AsyncTask #1 calls detatch()
I/libpersona( 6290): KNOX_SDCARD not a persona
I/SELinux ( 6290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1015): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6290 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6290): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SA      ( 5291): [ODM] saveOpenData( GEO_IP, PL )
,D/TimaKeyStoreProvider( 6280): TimaSignature is unavailable
,D/ActivityThread( 6280): Added TimaKeyStore provider
,I/SA      ( 5291): [OCP] update openData : PL
,I/SA      ( 5291): [TPMU] getNetworkMcc : 
,I/SA      ( 5291): [SCU] saveMccToPreferece Start
I/SA      ( 5291): [SCU] RegionMCC : 260
I/SA      ( 5291): [SSP] query invoked
,V/JNIHelp ( 6262): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 6280): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6290): TimaSignature is unavailable
,D/ActivityThread( 6290): Added TimaKeyStore provider
,I/SA      ( 5291): [TPMU] GetMccFromDB : null
,I/KLMS-2.5.183: ( 3433): KLMSIntentService(): onDestroy()
,I/SA      ( 5291): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5291): [SCU] saveMccToPreferece End
,I/SA      ( 5291): [RC New] executeRequest [v2liruge] end. 2016
,I/SA      ( 5291): [RC New] Execute end
,W/ResourcesManager( 6290): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6290): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/BaseAppContext( 1990): Using Auth Proxy for data requests.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ActivityThread( 6262): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6262): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16f8a22b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6262): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 1015): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6313 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/ResourcesManager( 6290): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6290): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Killing 5259:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
W/ResourcesManager( 6290): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6290): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,E/Zygote  ( 6313): MountEmulatedStorage()
E/Zygote  ( 6313): v2
I/libpersona( 6313): KNOX_SDCARD checking this for 1000
I/libpersona( 6313): KNOX_SDCARD not a persona
,I/SELinux ( 6313): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6313): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6313): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6313): TimaSignature is unavailable
,D/ActivityThread( 6313): Added TimaKeyStore provider
,W/DefaultRequestDirector( 5840): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/qtaguid ( 5840): Untagging socket 53
,I/System.out( 5840): Thread-1045 calls detatch()
,E/Volley  ( 5840): [1045] abz.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
,I/art     ( 6262): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6262): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/ResourcesManager( 6245): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/BaseAppContext( 1990): Using Auth Proxy for data requests.
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 6136): (283) recovered 83 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 6136): Observing account changes for notifications
,D/NativeLibraryUtils( 6262): Install completed successfully. count=14 extracted=0,
,I/SA      ( 5291): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5291): [OR] GetMyCountryZoneTask Success
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6333): MountEmulatedStorage(),
I/libpersona( 6333): KNOX_SDCARD checking this for 10046
E/Zygote  ( 6333): v2
,I/libpersona( 6333): KNOX_SDCARD not a persona
I/SELinux ( 6333): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6333): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6333): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=6333 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
,I/ActivityManager( 1015): Killing 4725:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31,
,I/CalendarProvider2( 6245): CalendarProvider2.onCreate() called
,W/libprocessgroup( 1015): failed to open /acct/uid_10025/pid_5242/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10053/pid_5259/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6333): TimaSignature is unavailable
,D/ActivityThread( 6333): Added TimaKeyStore provider
,D/SettingsProvider( 1015): name = next_alarm_formatted
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10085
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,E/YouTube ( 5840): apps.youtube.app.task.YouTubeNetworkTaskService.a:124 Failed to fetch settings
E/YouTube ( 5840): gss: java.util.concurrent.ExecutionException: aaw
E/YouTube ( 5840): 	at gsl.a(SourceFile:102)
E/YouTube ( 5840): 	at gsm.b(SourceFile:158)
E/YouTube ( 5840): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:4046)
E/YouTube ( 5840): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:54)
E/YouTube ( 5840): 	at dyr.run(Unknown Source)
E/YouTube ( 5840): Caused by: java.util.concurrent.ExecutionException: aaw
E/YouTube ( 5840): 	at acv.a(SourceFile:117)
E/YouTube ( 5840): 	at acv.get(SourceFile:88)
E/YouTube ( 5840): 	at hoz.get(SourceFile:69)
E/YouTube ( 5840): 	at gsl.a(SourceFile:98)
E/YouTube ( 5840): 	... 4 more
E/YouTube ( 5840): Caused by: aaw
E/YouTube ( 5840): 	at abz.a(SourceFile:159)
E/YouTube ( 5840): 	at hoh.a(SourceFile:72)
E/YouTube ( 5840): 	at abf.run(SourceFile:112)
,W/ResourcesManager( 6333): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6333): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6333): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6333): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6333): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6333): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/WVCdm   (  283): Instantiating CDM.
,W/libprocessgroup( 1015): failed to open /acct/uid_10057/pid_4725/cgroup.procs: No such file or directory
,I/WVCdm   (  283): CdmEngine::OpenSession
,I/WVCdm   (  283): Level3 Library Sep 25 2014 17:10:03
,I/ActivityManager( 1015): Killing 5179:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,W/WVCdm   (  283): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  283): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  283): Service_Initialize: starts!
D/QSEECOMAPI: (  283): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  283): App is not loaded in QSEE
E/QSEECOMAPI: (  283): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  283): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  283): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  283): App is not loaded in QSEE
E/QSEECOMAPI: (  283): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  283): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  283): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  283): App is not loaded in QSEE
,W/BaseAppContext( 1990): Using Auth Proxy for data requests.
,I/ActivityManager( 1015): Killing 5114:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,D/QSEECOMAPI: (  283): Loaded image: APP id = 11
,D/DrmWidevineDash(  283): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  283): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  283): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  283): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1662000
E/DrmWidevineDash(  283): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1662000
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/TimeService( 6313): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453807568110
,D/        ( 6313): TimeServiceNative: User Time to be set is 1453807568112
D/DrmLibTime(  431): got the req here! ret=0
D/DrmLibTime(  431): command id, time_cmd_id = 770
D/DrmLibTime(  431): time_getutcsec starts!
D/DrmLibTime(  431): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  431): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  431): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  431): QSEE Time Listener: Checking if ATS_MODEM is set or not.
D/QC-time-services(  431): Lib:time_genoff_operation: pargs->base = 13
D/QC-time-services(  431): Lib:time_genoff_operation: pargs->operation = 2
D/QC-time-services(  431): Lib:time_genoff_operation: pargs->ts_val = 0
,D/QC-time-services(  431): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  333): Daemon: Connection accepted:time_genoff
D/QC-time-services( 6313): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6313): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6313): Lib:time_genoff_operation: pargs->ts_val = 1453807568112
,D/QC-time-services( 6313): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  333): Daemon:Received base = 13, unit = 1, operation = 2,value = 0
D/QC-time-services(  333): Daemon:genoff_opr: Base = 13, val = 0, operation = 2
D/QC-time-services(  333): offset is: 0 for base: 0
E/QC-time-services(  431): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  431): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  431): QSEE Time Listener: Retrieved Android system time: 1453807568
D/DrmLibTime(  431): time_getutcsec returns 0, sec = 1453807568; nsec = 0
D/DrmLibTime(  431): time_getutcsec finished! 
D/DrmLibTime(  431): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  431): before calling ioctl to read the next time_cmd
E/QC-time-services(  333): Daemon: Time-services: Waiting to acceptconnection
D/QC-time-services(  333): Daemon: Connection accepted:time_genoff
D/QC-time-services(  333): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453807568112
D/QC-time-services(  333): Daemon:genoff_opr: Base = 2, val = 1453807568112, operation = 0
D/QC-time-services(  333): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS6/27/70 9:32:14
D/QC-time-services(  333): Daemon:Value read from RTC seconds = 17919134000
D/QC-time-services(  333): Daemon:new time 1453807568112 
D/QC-time-services(  333): Daemon: delta 1435888434112 genoff 1435888434112 
D/QC-time-services(  333): Daemon:genoff_persistent_update: Writing genoff = 1435888434112 to memory
D/QC-time-services(  333): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  333): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/Mms/MmsApp( 6333): [start]    onCreate() consume time = 0.0,
,D/QC-time-services(  333): Updating the TOD offset
D/QC-time-services(  333): Daemon:genoff_persistent_update: Writing genoff = 1435888434112 to memory,
D/QC-time-services(  333): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  333): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  333): Daemon:Update to modem bit set
D/QC-time-services(  333): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  333): Daemon: Base = 2, Value being sent to MODEM = 1119923634112
E/QC-time-services( 6313): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  333): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  333): Daemon: Time-services: Waiting to acceptconnection
,D/DrmWidevineDash(  283): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  283): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  283): hlos api version =  9
D/DrmWidevineDash(  283): tz api version =  9
D/DrmWidevineDash(  283): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  283): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  283): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  283): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  283): OEMCrypto_OpenSession: starts! SID=0xbee891b0
D/DrmWidevineDash(  283): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  283): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  283): OEMCrypto_GetRandom: starts! randomData=0xb8f3e680, dataLength=8
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  283): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb8f0d760, wrapped_rsa_key_length=1280
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  283): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  283): OEMCrypto_GetDeviceID: starts! deviceID=0xb8f13658, idLength=0xb11c6730
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/ActivityManager( 1015): Killing 5338:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  283): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  283): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  283): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  283): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  283): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  283): OEMCrypto_GetHDCPCapability: starts!, current = 0xb11c6746, maximum = 0xb11c6747
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  283): OEMCrypto_APIVersion: starts!
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  283): hlos api version =  9
D/DrmWidevineDash(  283): tz api version =  9
D/DrmWidevineDash(  283): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  283): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb11c67b4
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  283): PrepareKeyRequest: nonce=2484594108
,D/DrmWidevineDash(  283): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8fab610
D/DrmWidevineDash(  283): message_length=1599, signature=0xb8fa75f8, signature_length=0xb11c6714
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,E/File    ( 6136): fail readDirectory() errno=2
,I/dex2oat ( 6330): ----------------------------------------------------
I/dex2oat ( 6330): <SS>: S T A R T I N G . . .
I/dex2oat ( 6330): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 6330): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads637611181.jar --oat-fd=113 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/cache/ads637611181.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/PeopleSync( 1990): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/art     ( 6333): Verification of com.android.mms.ui.ComposeMessageFragment com.android.mms.ArtClassLoader.createMessage(android.content.Intent) took 146.348ms
,I/GoogleURLConnFactory( 6262): Using platform SSLCertificateSocketFactory
,I/Babel   ( 5825): Creating RTCS
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 6262): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6262): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6262): (HTTPLog)-Static: isShipBuild true
I/System.out( 6262): (HTTPLog)-Thread-1044-242839200: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 6262): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 6262): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6262): Tagging socket 30 with tag 1000180300000000{268441603,0} for uid 10012, pid: 6262, getuid(): 10012
,W/art     ( 6290): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 388.962ms
,I/Gmail   ( 6136): notifyAccountChanged
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/qtaguid ( 6262): Tagging socket 34 with tag 1000180300000000{268441603,0} for uid 10012, pid: 6262, getuid(): 10012
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  283): CdmEngine::CloseSession
,D/DrmWidevineDash(  283): OEMCrypto_CloseSession: starts! SID=1
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  283): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  283): L3 Terminate.
D/DrmWidevineDash(  283): OEMCrypto_Terminate: starts!
,I/Gmail   ( 6136): getAccountsCursor
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  283): Service_Uninitialize: starts!
D/QSEECOMAPI: (  283): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  283): QSEECom_shutdown_app, app_id = 11
,D/DrmWidevineDash(  283): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  283): OEMCrypto_Terminate: ends! returns 0
,I/art     ( 5825): Note: end time exceeds epoch: 
,I/SurfaceFlinger(  257): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1015): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 88419
,D/PowerManagerService( 1015): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
,D/PowerManagerService( 1015): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{1000}) (elapsedTime=3506)
I/Gmail   ( 6136): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/Babel   ( 5825): Account registration complete:Redacted-21
V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,I/Babel   ( 5825): ProcessRegisterDeviceResponse
I/Babel   ( 5825): Perform warm sync in case there are messages missed before the device is registered for account Redacted-21
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 6136): notifyAccountChanged
,I/Gmail   ( 6136): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/dex2oat ( 6330): dex2oat took 252.732ms (threads: 4)
,I/Gmail   ( 6136): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6136): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/libprocessgroup( 1015): failed to kill 1 processes for processgroup 5114
,W/libprocessgroup( 1015): failed to open /acct/uid_10038/pid_5179/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10100/pid_5338/cgroup.procs: No such file or directory
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 6262): Untagging socket 30
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/art     ( 6333): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 373.547ms
,I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6375 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5360:com.samsung.helphub/1000 (adj 15): empty #31
E/Zygote  ( 6375): MountEmulatedStorage()
I/libpersona( 6375): KNOX_SDCARD checking this for 10094
E/Zygote  ( 6375): v2
I/libpersona( 6375): KNOX_SDCARD not a persona
,I/SELinux ( 6375): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6375): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6375): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1778): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1778): Tagging socket 90 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,D/TimaKeyStoreProvider( 6375): TimaSignature is unavailable
,D/ActivityThread( 6375): Added TimaKeyStore provider
,I/Babel   ( 5825): Destroying RTCS
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5825): Creating RTCS
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5360/cgroup.procs: No such file or directory
,I/art     ( 5825): Note: end time exceeds epoch: 
,I/VacuumService( 1778): Vacuum at: now=1453807568858 tag=VacuumService
,W/art     ( 6333): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 194.297ms
,D/Mms/ArtClassLoader( 6333): init before art
,D/Mms/TelephonyPermission( 6333): start operation mode monitor
,W/ResourcesManager( 6333): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/elm:15183( 6375): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/Mms/TelephonyPermission( 6333): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 6333): isDefault true
,D/Mms/MmsApp( 6333): onCreate() com.android.mms
,D/elm:15183( 6375): ELMEngine.ELMEngine( context ).
,D/elm:15183( 6375): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1015): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 6375): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6396): MountEmulatedStorage(),
E/Zygote  ( 6396): v2
I/libpersona( 6396): KNOX_SDCARD checking this for 10134
I/libpersona( 6396): KNOX_SDCARD not a persona
,I/SELinux ( 6396): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6396): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6396): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6396 uid=10134 gids={50134, 9997} abi=armeabi-v7a
,D/elm:15183( 6375): ElmAgentService : onCreate()
,D/elm:15183( 6375): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:15183( 6375): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15183( 6375): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:15183( 6375): ModuleBase.ModifySetAlarm()
D/elm:15183( 6375): MDMBridge.getInstance()
D/elm:15183( 6375): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15183( 6375): ElmAgentService : onDestroy().
,I/ActivityManager( 1015): Killing 5620:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6396): TimaSignature is unavailable
,D/ActivityThread( 6396): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 5643:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,W/ResourcesManager( 6396): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6396): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/Mms/MmsApp( 6333): [start]    initCountryIso consume time = 980.456302
,D/CountryDetector( 1015): The first listener is added
,I/Gmail   ( 6136): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15582, normalSync: true
,D/Mms/MmsApp( 6333): [end]    initCountryIso consume time = 46.419479
,D/Mms/MmsConfig( 6333): [start]    MmsConfig.init() consume time = 1.361875
,D/Mms/MmsConfig( 6333): before partial update
,D/Mms/MmsConfig( 6333): Load Resize quality : 80
,I/Babel   ( 5825): Destroying RTCS
,D/EasySignUpManager_1.0.1( 6333): serviceId : 1, features : -1
,W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_5643/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10068/pid_5620/cgroup.procs: No such file or directory
D/EasySignUpManager_1.0.1( 6333): isAuth is false
D/Mms/MmsConfig( 6333): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1443): query,matched:2117, calling pid = 6333
,D/TP/MmsSmsProvider( 1443): match 2117:Elapsed time : 2.089 ms
,D/EasySignUpManager_1.0.1( 6333): isAuth is false
,D/EasySignUpManager_1.0.1( 6333): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 6333): mps_code.dat does not exist
,E/CscParser( 6333): customer_path =/system/csc/customer.xml
E/CscParser( 6333): fileName + /system/csc/customer.xml
,I/ActivityManager( 1015): Killing 5497:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,E/CscParser( 6333): mps_code.dat does not exist
E/CscParser( 6333): customer_path =/system/csc/customer.xml
E/CscParser( 6333): fileName + /system/csc/customer.xml
,I/Gmail   ( 6136): getAccountsCursor
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CscParser( 6333): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 6333):  enable multiwindow = true
,E/Mms/MessageUtils( 6333): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 6333): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 6333): [end]    init() consume time = 199.183021
,D/Mms/Contact( 6333): [start]    init() consume time = 0.759844
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.appcert.AppCertService; callingUser = 0; userId(target) = 0
,D/Mms/Contact( 6333): [end]    init consume time = 21.444062
,W/libprocessgroup( 1015): failed to open /acct/uid_10003/pid_5497/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1443): query,matched:13, calling pid = 6333
,D/TP/MmsSmsProvider( 1443): match 13:Elapsed time : 1.865 ms
,D/Mms/DraftCache( 6333): [start]    rebuildCache consume time = 17.310886
,D/TP/MmsSmsProvider( 1443): query,matched:12, calling pid = 6333
,D/TP/MmsSmsProvider( 1443): match 12:Elapsed time : 2.204 ms
,D/Mms/DraftCache( 6333): [end]    rebuildCache consume time = 16.544583
,D/Mms/MethodReflector( 6333): getSubId is called
D/Mms/TelephonyUtils( 6333): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 6333): getTelephonyProperty is called
D/Mms/DownloadManager( 6333): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6333): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6333): auto download without roaming -> true
D/Mms/DownloadManager( 6333): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/MethodReflector( 6333): getSubId is called
,D/Mms/MethodReflector( 6333): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 6333): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 6333): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 6333): getTelephonyProperty is called
D/Mms/DownloadManager( 6333): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 6333): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 6333): auto download without roaming -> true
D/Mms/DownloadManager( 6333): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 6333): auto download during roaming secondary -> false
D/Mms/DownloadManager( 6333): mAutoDownload ------> true
,I/CalendarProvider2( 6245): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/qtaguid ( 5132): Untagging socket -1
,I/qtaguid ( 5132): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 5132): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 5132): untagSocket(-1) failed with errno -9
,D/ComposerPerformance( 6333): 1453807569568 ms / [DONE] Composer constructor
,I/dex2oat ( 6419): ----------------------------------------------------
,I/dex2oat ( 6419): <SS>: S T A R T I N G . . .
I/dex2oat ( 6419): <SS>: Zip is absent. Canceled.
I/dex2oat ( 6419): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/CII     ( 6333): CommonIMSInterface: VoLTE CSC feature disabled.
D/Mms/Conversation( 6333): [start]    init() consume time = 175.421406
,I/Mms/ReservationManager( 6333): ReservationManager()
,I/Mms/ReservationManager( 6333): resetAfterConnected()
,D/TP/MmsSmsProvider( 1443): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1443): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1443): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1443): sUpgradeVersion = 0, db.getVersion() = 81
,D/TP/MmsSmsProvider( 1443): query,matched:7, calling pid = 6333
,D/TP/MmsSmsProvider( 1443): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1443): need read changed broadcast:false
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 21520(1080KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 2.639ms total 183.173ms
D/Mms/Conversation( 6333): [end]    init consume time = 18.678021
,D/TP/MmsSmsProvider( 1443): match 7:Elapsed time : 11.473 ms
,D/Mms/MessagingNotification( 6333): [start]    init() consume time = 2.945052
,D/Mms/MessagingNotification( 6333): [end]    init consume time = 7.806563
,I/Mms/ReservationManager( 6333): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/SpamFilter( 6333): [start]    SpamFilter fill() begin consume time = 17.986927
,D/hcjo    ( 5132): SelfUpdateManager:REQUEST_UPD_CHECK:onUpdateCheckSuccessAndNoNeedUpdate
,D/hcjo    ( 5132): AutoUpdateManager:CHECK_SELF_UPD:onSelfUpdateResult:T
,D/hcjo    ( 5132): SellerAppAutoUpdate:clearFlag
,D/Mms/Synchronizer( 6333): [start]    doSync consume time = 6.32302
,D/TP/MmsSmsProvider( 1443): query,matched:400, calling pid = 6333
,D/Mms/MmsApp( 6333): [end]    onCreate() consume time = 7.561563
D/TP/MmsSmsProvider( 1443): query,matched:0, calling pid = 6333
V/TP/MmsSmsProvider( 1443): getSimpleConversations entered.
,D/Mms/SpamFilter( 6333): [end]    SpamFilter fill() finished consume time = 1.939844
,D/TP/MmsSmsProvider( 1443): match 0:Elapsed time : 2.634 ms
,D/TP/MmsSmsProvider( 1443): update, matched:300, calling pid = 6333
,V/TP/MmsSmsProvider( 1443): syncDBData start
,V/TP/MmsSmsProvider( 1443): syncDBData sms end
,I/ActivityManager( 1015): Killing 5525:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,V/TP/MmsSmsProvider( 1443): syncDBData mms end
,V/TP/MmsSmsProvider( 1443): syncDBData end
,D/SellerAppAutoUpdateManagerStateMachine( 5132): execute::IDLE:EXECUTE
,D/SellerAppAutoUpdateManagerStateMachine( 5132): exit::IDLE
D/SellerAppAutoUpdateManagerStateMachine( 5132): entry::TOKENCHECK
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
D/Mms/DownloadManager( 6333): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 6333): roaming ------> false, mSimSlot = 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/Mms/MethodReflector( 6333): getSubId is called
,D/Mms/TelephonyUtils( 6333): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 6333): getTelephonyProperty is called
D/Mms/DownloadManager( 6333): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6333): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6333): auto download without roaming -> true
D/Mms/DownloadManager( 6333): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/DownloadManager( 6333): mAutoDownload ------> true
,I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6429 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/splitIntent( 1015): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
E/Zygote  ( 6429): MountEmulatedStorage()
E/Zygote  ( 6429): v2
I/libpersona( 6429): KNOX_SDCARD checking this for 10072,
D/Mms/Synchronizer( 6333): [end]    doSync consume time = 40.755781
I/libpersona( 6429): KNOX_SDCARD not a persona
,I/SELinux ( 6429): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6429): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6429): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6429): TimaSignature is unavailable
D/SellerAppAutoUpdateManagerStateMachine( 5132): execute::TOKENCHECK:TOKEN_RECEIVED
,D/SellerAppAutoUpdateManagerStateMachine( 5132): exit::TOKENCHECK
D/SellerAppAutoUpdateManagerStateMachine( 5132): entry::FAILED
D/ActivityThread( 6429): Added TimaKeyStore provider
D/hcjo    ( 5132): AutoUpdateManager:SELLER_UPD:onSellerAutoUpdateFailed
,D/SellerAppAutoUpdateManagerStateMachine( 5132): exit::FAILED
D/SellerAppAutoUpdateManagerStateMachine( 5132): entry::IDLE
,I/ActivityManager( 1015): Killing 5053:com.sec.pcw.device/1000 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 5734:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/Mms/ArtClassLoader( 6333): init [DONE] art
,I/ActivityManager( 1015): Killing 5724:com.android.chrome/u0a81 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/dex2oat ( 6419): dex2oat took 180.367ms (threads: 4)
,D/BadgeProvider( 6429): onCreate
,D/BadgeProvider( 6429): DatabaseHelper
,I/Adreno-EGL( 6262): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6262): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6262): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6262): Local Branch: 
I/Adreno-EGL( 6262): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6262): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6262):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 5755:com.sec.android.soagent/u0a34 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,D/Mms/MessagingNotification( 6333): checkBadgeCount unreadCount=0 badgeCount=0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_10107/pid_5525/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5053/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10159/pid_5734/cgroup.procs: No such file or directory
,D/TP/SmsProvider( 1443): query,matched:26, calling pid = 6333
,D/TP/SmsProvider( 1443): match 26:Elapsed time : 2.087 ms
,W/ResourcesManager( 6136): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6136): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 1443): query,matched:6, calling pid = 6333
,D/TP/MmsSmsProvider( 1443): match 6:Elapsed time : 1.562 ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1778): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/Adreno-EGL( 6262): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6262): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6262): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6262): Local Branch: 
I/Adreno-EGL( 6262): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6262): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6262):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6447): MountEmulatedStorage(),
I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6447 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/Zygote  ( 6447): v2
I/libpersona( 6447): KNOX_SDCARD checking this for 10025,
I/libpersona( 6447): KNOX_SDCARD not a persona
,I/SELinux ( 6447): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6447): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6447): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6447): TimaSignature is unavailable
,D/ActivityThread( 6447): Added TimaKeyStore provider
,V/JNIHelp ( 6136): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.fotaclient, destAppInfo.processName = com.wssyncmldm
,W/ResourcesManager( 6447): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 2912): [llIIIllllIIIlIIIlIIl(1846/llIlIIIIlIIIIIlIlIII)] flag is : false
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 6447): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,W/libprocessgroup( 1015): failed to open /acct/uid_10081/pid_5724/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10034/pid_5755/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/Omacp( 6333): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/System.out( 1990): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1990): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1990): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1990): (HTTPLog)-Thread-225-165040478: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1990): (HTTPLog)-Static: isSBSettingEnabled false
,I/OMACP   ( 6447): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
I/OMACP   ( 6447): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 6447): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 6447): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 6447): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/System.out( 1990): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/OMACP   ( 6447): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/qtaguid ( 1990): Tagging socket 114 with tag 1000150000000000{268440832,0} for uid 10012, pid: 1990, getuid(): 10012
,I/OMACP   ( 6447): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 6447): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 6447): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 6447): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 6447): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 6447): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 6447): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,I/DBG_DM  ( 2912): [com.wssyncmldm.DMSecBroadcastReceiver(192/onReceive)] sec.fota.polling.intent.RECEIVE
,I/DBG_DM  ( 2912): [com.wssyncmldm.DMSecBroadcastReceiver(543/llIIIIlllllIIllIIllI)] nMode : 0
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 8
,I/ActivityManager( 1015): Killing 4986:com.android.defcontainer/u0a4 (adj 15): empty #31
,I/qtaguid ( 1990): Tagging socket 118 with tag 1000150000000000{268440832,0} for uid 10012, pid: 1990, getuid(): 10012
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 2912): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(226/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(3800/IllIIlllIllIIIIIllII)] Wifi_Only_flag : true
,I/DBG_DM  ( 2912): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 2912): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(251/llIIIIlllllIIllIIllI)] bWifiOnly flag : true
,I/Adreno-EGL( 6262): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6262): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6262): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6262): Local Branch: 
I/Adreno-EGL( 6262): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6262): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6262):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 2912): [llIIIllllIIIlIIIlIIl(1846/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 2912): [IIllIIIIlIlIlIlIllII(1756/lllllIIlIIIlIlIIIllI)] bUpdateProcessing : false
,I/DBG_DM  ( 2912): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_DM  ( 2912): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1990): Restart initialization of location
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1778): callingUid 10012, callindPid: 1778
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1778): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/libprocessgroup( 1015): failed to open /acct/uid_10004/pid_4986/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onInitialize : 2672
D/WVMDrmPlugIn(  281): WVMDrmPlugin::onSetOnInfoListener : add 2672
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2912): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,I/DBG_DM  ( 2912): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,E/MDM     ( 1778): [222] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onGetSupportInfo : 0
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GAV4    ( 5921): Thread[GAThread,5,main]: No campaign data found.
,I/DBG_DM  ( 2912): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,I/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,W/ActivityThread( 6136): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6136): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ca8d8ad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6136): Installed default security provider GmsCore_OpenSSL
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/WVCdm   (  283): Instantiating CDM.
I/WVCdm   (  283): CdmEngine::OpenSession
I/WVCdm   (  283): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  283): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/GCoreFlp( 1778): No location to return for getLastLocation()
,W/FusedLocationProvider( 1778): location=null
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,D/DrmWidevineDash(  283): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  283): Service_Initialize: starts!
D/QSEECOMAPI: (  283): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  283): App is not loaded in QSEE
E/QSEECOMAPI: (  283): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  283): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  283): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  283): App is not loaded in QSEE
E/QSEECOMAPI: (  283): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  283): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  283): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  283): App is not loaded in QSEE
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/QSEECOMAPI: (  283): Loaded image: APP id = 12
,D/DrmWidevineDash(  283): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  283): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  283): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  283): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1660000
E/DrmWidevineDash(  283): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1660000,
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  431): got the req here! ret=0
D/DrmLibTime(  431): command id, time_cmd_id = 770
D/DrmLibTime(  431): time_getutcsec starts!
D/DrmLibTime(  431): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  431): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  431): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  431): QSEE Time Listener: Checking if ATS_MODEM is set or not.
D/QC-time-services(  431): Lib:time_genoff_operation: pargs->base = 13
D/QC-time-services(  431): Lib:time_genoff_operation: pargs->operation = 2
D/QC-time-services(  431): Lib:time_genoff_operation: pargs->ts_val = 0
D/QC-time-services(  431): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  333): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  333): Daemon:Received base = 13, unit = 1, operation = 2,value = 0,
D/QC-time-services(  333): Daemon:genoff_opr: Base = 13, val = 0, operation = 2
D/QC-time-services(  333): offset is: 0 for base: 0
E/QC-time-services(  431): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
,D/DrmLibTime(  431): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  431): QSEE Time Listener: Retrieved Android system time: 1453807570
D/DrmLibTime(  431): time_getutcsec returns 0, sec = 1453807570; nsec = 0
,D/DrmLibTime(  431): time_getutcsec finished! 
D/DrmLibTime(  431): iotcl_continue_command finished! and return 0 
,D/DrmLibTime(  431): before calling ioctl to read the next time_cmd
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main,
E/QC-time-services(  333): Daemon: Time-services: Waiting to acceptconnection
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false,
,I/DBG_DM  ( 2912): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
I/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,D/DrmWidevineDash(  283): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  283): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): hlos api version =  9
D/DrmWidevineDash(  283): tz api version =  9
D/DrmWidevineDash(  283): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  283): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,E/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,E/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@19290a59
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  283): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  283): OEMCrypto_OpenSession: starts! SID=0xb11c6960
D/DrmWidevineDash(  283): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  283): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  283): OEMCrypto_GetRandom: starts! randomData=0xb8fa71f8, dataLength=8
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  283): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb8f0dc68, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/DBG_DM  ( 2912): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  283): OEMCrypto_GetDeviceID: starts! deviceID=0xb8f13698, idLength=0xb18b6730
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/DBG_DM  ( 2912): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  283): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  283): OEMCrypto_SupportsUsageTable: starts!
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  283): OEMCrypto_SupportsUsageTable: wv_app_version = 24
,D/DrmWidevineDash(  283): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  283): OEMCrypto_GetHDCPCapability: starts!, current = 0xb18b6746, maximum = 0xb18b6747
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): OEMCrypto_GetHDCPCapability: ends! returns 0
,D/DrmWidevineDash(  283): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  283): hlos api version =  9
D/DrmWidevineDash(  283): tz api version =  9
D/DrmWidevineDash(  283): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  283): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb18b67b4
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  283): PrepareKeyRequest: nonce=3616792682
,D/DrmWidevineDash(  283): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8fab120
D/DrmWidevineDash(  283): message_length=1634, signature=0xb8fabdf0, signature_length=0xb18b6714
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/qtaguid ( 1990): Untagging socket 114
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_DM  ( 2912): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/SecContentProvider2( 1015): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1015): mCursor = null
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/SecContentProvider2( 1015): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1015): mCursor = null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=4, Uoast
,I/DBG_DM  ( 2912): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2912): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/DBG_DM  ( 2912): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/PowerManagerService( 1015): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5825): Creating RTCS
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,D/SRIB_DCS( 2912): log_dcs ThreadedRenderer::initialize entered! 
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  283): CdmEngine::CloseSession
D/DrmWidevineDash(  283): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  283): L3 Terminate.
D/DrmWidevineDash(  283): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  283): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  283): Service_Uninitialize: starts!
D/QSEECOMAPI: (  283): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  283): QSEECom_shutdown_app, app_id = 12
D/DrmWidevineDash(  283): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  283): OEMCrypto_Terminate: ends! returns 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,I/CheckinRequestBuilder( 1990): Classify the device as Phone.
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 1465(50KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 750us total 22.898ms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/Babel   ( 5825): Destroying RTCS
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AndroidHttpClient( 6136): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Android-GmailProvider/52000999 (sw360dp; 320dpi) (a5ulte LRX22G); gzip
,D/AndroidHttpClient( 6136): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = POST
,I/System.out( 6136): Thread-1039(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,E/GmsUtils( 5709): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 5709): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/System.out( 6136): Thread-1039(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6136): Thread-1039(ApacheHTTPLog):isShipBuild true
I/System.out( 6136): Thread-1039(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6136): Thread-1039(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10101
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10101
,I/qtaguid ( 6136): Tagging socket 62 with tag 1010000000000000{269484032,0} for uid -1, pid: 6136, getuid(): 10101
,I/qtaguid ( 6136): Tagging socket 61 with tag 1010000000000000{269484032,0} for uid -1, pid: 6136, getuid(): 10101
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.appcert.AppCertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/MusicLeanback( 5709): Conditions not met for autocaching.
I/MusicLeanback( 5709): Stop autocaching.
,I/System.out( 1990): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1990): Tagging socket 114 with tag 1000190000000000{268441856,0} for uid 10012, pid: 1990, getuid(): 10012
,I/System.out( 1990): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1990): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1990): Tagging socket 113 with tag 1000010400000000{268435716,0} for uid -1, pid: 1990, getuid(): 10012
,I/System.out( 1990): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1990): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1990): Tagging socket 119 with tag 1000040800000000{268436488,0} for uid -1, pid: 1990, getuid(): 10012
,I/qtaguid ( 1990): Untagging socket 114
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5825): Creating RTCS
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 5825): Destroying RTCS
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.appcert.AppCertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1990): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1990): Tagging socket 114 with tag 1000150000000000{268440832,0} for uid 10012, pid: 1990, getuid(): 10012
,I/qtaguid ( 1990): Tagging socket 124 with tag 1000040800000000{268436488,0} for uid -1, pid: 1990, getuid(): 10012
,I/CheckinTask( 1990): Sending checkin request (13078 bytes)
,I/qtaguid ( 1990): Untagging socket 114
,I/qtaguid ( 1990): Untagging socket 113
,I/PeopleSync( 1990): Sync finished, successful=true, took 3040ms
,I/PeopleContactsSync( 1990): CP2 sync start [5005f081]
,I/PeopleContactsSync( 1990): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 1990): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PeopleContactsSync( 1990): CP2 cleanup done, kept= duration=76 ms
,I/PeopleContactsSync( 1990): ===CP2 sync finished, success=true, time=94,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5825): Creating RTCS
,I/PeopleSync( 1990): ***Sync finished***, duration: 6130 [5005f081]
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1990): Module APK com.google.android.play.games already loaded
,I/dhcpcd  ( 5666): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 5666): wlan0: no IPv6 Routers available
,W/PlaySystemBroadcastReceiver( 1990): Processed handlePeopleChanged at 91492
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 5825): Destroying RTCS
,D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1990): Module APK com.google.android.play.games already loaded
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,W/DataBroker( 1990): No player ID found and calling context is not the dest app
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  290): DCD OFF,
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.apps.magazines, action: android.content.SyncAdapter
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService; callingUser = 0; userId(target) = 0
,I/Mms/MmsApp( 6333):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 6333): [start]    fillCache consume time = 1954.35802
D/Mms/ComposeMessageFragment( 6333): fillCache, easy = false
,I/SyncAdapterService( 5921): Ignoring sync request for non-current account
,I/art     ( 1990): Explicit concurrent mark sweep GC freed 29214(2MB) AllocSpace objects, 25(832KB) LOS objects, 40% free, 15MB/25MB, paused 1.708ms total 83.694ms
,I/qtaguid ( 1990): Untagging socket 119
,W/SQLiteConnectionPool( 1990): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/CheckinResponseProcessor( 1990): From server: 11 gservices updates and 2 deletes
,D/AbsListView( 6333): Get MotionRecognitionManager
,D/MotionRecognitionService( 1015):  ssp status : false
,D/Mms/ComposeMessageFragment( 6333): [end]    fillCache consume time = 138.854479
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.syncadapters.contacts, action: android.content.SyncAdapter
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterService; callingUser = 0; userId(target) = 0
,E/SQLiteLog( 1990): (284) automatic index on invitations(external_inviter_id)
,F/Babel   ( 5825): wtf
F/Babel   ( 5825): Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
,F/Babel   ( 5825): Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
F/Babel   ( 5825): java.lang.Exception
F/Babel   ( 5825): 	at cvu.h(SourceFile:274)
F/Babel   ( 5825): 	at bri.<init>(SourceFile:95)
F/Babel   ( 5825): 	at bwx.<init>(SourceFile:1866)
F/Babel   ( 5825): 	at bwx.parseFrom(SourceFile:2021)
F/Babel   ( 5825): 	at java.lang.reflect.Method.invoke(Native Method)
F/Babel   ( 5825): 	at java.lang.reflect.Method.invoke(Method.java:372)
F/Babel   ( 5825): 	at bzp.a(SourceFile:372)
F/Babel   ( 5825): 	at bzp.a(SourceFile:117)
F/Babel   ( 5825): 	at bui.a(SourceFile:626)
F/Babel   ( 5825): 	at bui.a(SourceFile:491)
F/Babel   ( 5825): 	at bfq.a(SourceFile:39)
F/Babel   ( 5825): 	at bfr.run(SourceFile:88)
,F/Babel   ( 5825): wtf
F/Babel   ( 5825): Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
,F/Babel   ( 5825): Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
F/Babel   ( 5825): java.lang.Exception
F/Babel   ( 5825): 	at cvu.h(SourceFile:274)
F/Babel   ( 5825): 	at bri.<init>(SourceFile:95)
F/Babel   ( 5825): 	at bwx.<init>(SourceFile:1866)
F/Babel   ( 5825): 	at bwx.parseFrom(SourceFile:2021)
F/Babel   ( 5825): 	at java.lang.reflect.Method.invoke(Native Method)
F/Babel   ( 5825): 	at java.lang.reflect.Method.invoke(Method.java:372)
F/Babel   ( 5825): 	at bzp.a(SourceFile:372)
F/Babel   ( 5825): 	at bzp.a(SourceFile:117)
F/Babel   ( 5825): 	at bui.a(SourceFile:626)
F/Babel   ( 5825): 	at bui.a(SourceFile:491)
F/Babel   ( 5825): 	at bfq.a(SourceFile:39)
F/Babel   ( 5825): 	at bfr.run(SourceFile:88)
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5825): Creating RTCS
,I/art     ( 5825): Note: end time exceeds epoch: 
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/Mms/BubbleViewCache( 6333): fillCache bubble = 1
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 5825): Account selfinfo retrieved: Redacted-21
I/Babel   ( 5825): Retrieved account setting:Redacted-21
,I/Babel   ( 5825): Account sign in complete with state 102account: Redacted-21
,D/AndroidHttpClient( 1629): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Android-GData-Contacts/1.3 (a5ulte LRX22G); gzip
,D/AndroidHttpClient( 1629): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 1629): Thread-142(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 1629): Thread-142(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 1629): Thread-142(ApacheHTTPLog):isShipBuild true
I/System.out( 1629): Thread-142(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 1629): Thread-142(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/qtaguid ( 1629): Tagging socket 38 with tag 1244000400000000{306446340,0} for uid -1, pid: 1629, getuid(): 10012
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1015): name = lockscreen.options
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = serial_blacklist
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = facelock_liveliness_recognition_threshold
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = config_update_certificate
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/qtaguid ( 1629): Tagging socket 42 with tag 1244000400000000{306446340,0} for uid -1, pid: 1629, getuid(): 10012
,D/SettingsProvider( 1015): name = pubkey_blacklist
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = dropbox:data_app_crash
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/CertBlacklister( 1015): Certificate blacklist changed, updating...
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/SettingsProvider( 1015): name = facelock_max_center_movement
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.PeopleRequestProcessor; callingUser = 0; userId(target) = 0
D/SettingsProvider( 1015): name = send_action_app_error
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,I/GAV2    ( 6136): Thread[GAThread,5,main]: No campaign data found.
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1015): name = facelock_detection_threshold
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = dropbox:data_app_anr
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = web_autofill_query_url
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = ssl_session_cache
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = print_service_search_uri
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012,
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/SettingsProvider( 1015): name = masterLocationPackagePrefixBlacklist
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012,
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/SettingsProvider( 1015): name = masterLocationPackagePrefixWhitelist
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = dropbox:data_app_wtf
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = cert_pin_metadata_url
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = cert_pin_content_url
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = sms_short_codes_metadata_url
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = sms_short_codes_content_url
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = send_action_app_error
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10012
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/CertBlacklister( 1015): Certificate blacklist updated
I/GservicesProvider( 1629): main difference update completed
,I/CheckinRequestBuilder( 1990): Checkin reason type: 12 attempt count: 1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.partnersetup
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6530 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 6530): MountEmulatedStorage()
E/Zygote  ( 6530): v2
I/libpersona( 6530): KNOX_SDCARD checking this for 10015
I/libpersona( 6530): KNOX_SDCARD not a persona
,I/SELinux ( 6530): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6530): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6530): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/ActivityThread( 1990): Failed to find provider info for com.google.android.wearable.settings
,D/TimaKeyStoreProvider( 6530): TimaSignature is unavailable
,D/ActivityThread( 6530): Added TimaKeyStore provider
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,I/qtaguid ( 6136): Untagging socket 62
I/System.out( 6136): SyncAdapterThread-1 calls detatch()
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.LauncherConfigService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/splitIntent( 1015): intent=com.google.gservices.intent.action.GSERVICES_CHANGED will be not split. because same process=com.google.android.gms is in other queue. index=10
,I/splitIntent( 1015): base  index=10, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
,I/splitIntent( 1015): other index=24, name=com.google.android.gms com.google.android.gms.backup.GmsBackupStatusChangeReceiver
,I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.gservices.intent.action.GSERVICES_CHANGED !! do not split it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 36837(1836KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 3.753ms total 181.357ms
,I/qtaguid ( 1629): Untagging socket 38
,I/System.out( 1629): GDataFeedFetcher calls detatch()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6555): MountEmulatedStorage(),
,I/libpersona( 6555): KNOX_SDCARD checking this for 10057
E/Zygote  ( 6555): v2
I/libpersona( 6555): KNOX_SDCARD not a persona
I/SELinux ( 6555): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=6555 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,I/SELinux ( 6555): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6555): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/Babel   ( 5825): Destroying RTCS
,D/Mms/Contact( 6333): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 6333): performUpdate:widgetCount=0
,D/Mms/ContactsCache( 6333): [start]    invalidate() consume time = 640.344114
D/Mms/ContactsCache( 6333): [end]    invalidate() consume time = 0.142344
,D/TimaKeyStoreProvider( 6555): TimaSignature is unavailable
,D/ActivityThread( 6555): Added TimaKeyStore provider
,D/SSRM:n  ( 1015): SIOP:: AP = 360
,D/AndroidHttpClient( 1629): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Android-GData-Contacts/1.3 (a5ulte LRX22G); gzip
D/AndroidHttpClient( 1629): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 1629): Thread-145(ApacheHTTPLog):isSBSettingEnabled false
,D/ContactProvider( 5798): getAllContactInfoList Start
,I/System.out( 1629): Thread-145(ApacheHTTPLog):isShipBuild true
I/System.out( 1629): Thread-145(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 1629): Thread-145(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1629): Tagging socket 38 with tag 1144000400000000{289669124,0} for uid -1, pid: 1629, getuid(): 10012
,D/ContactProvider( 5798): getAllContactInfoList End
,I/syncContacts( 5798): thread: 994, onChange
,I/qtaguid ( 1629): Untagging socket 38
,I/System.out( 1629): GDataFeedFetcher calls detatch()
,D/ContactsSyncAdapter( 1629): ForbiddenException, ignoring rest of feed
D/ContactsSyncAdapter( 1629): com.google.wireless.gdata2.client.ForbiddenException: Could not fetch feed https://www.google.com/m8/feeds/contacts/thalitester@gmail.com/base2_property-android_linksto-gprofiles_highresphotos?sz=720&sortorder=ascending&showdeleted=true&max-results=500&requirealldeleted=true&updated-min=2016-01-22T10%3A06%3A25.316Z&orderby=lastmodified com.google.wireless.gdata2.client.HttpException: Received 403 status code: <?xml version="1.0" encoding="UTF-8"?>
D/ContactsSyncAdapter( 1629): <errors xmlns="http://schemas.google.com/g/2005">
D/ContactsSyncAdapter( 1629):  <error>
D/ContactsSyncAdapter( 1629):   <domain>usageLimits</domain>
D/ContactsSyncAdapter( 1629):   <code>rateLimitExceededUnreg</code>
D/ContactsSyncAdapter( 1629):   <internalReason>Rate Limit Exceeded. Please sign up</internalReason>
D/ContactsSyncAdapter( 1629):   <extendedHelp>https://code.google.com/apis/console</extendedHelp>
D/ContactsSyncAdapter( 1629):  </error>
D/ContactsSyncAdapter( 1629): </errors>
D/ContactsSyncAdapter( 1629): 
D/ContactsSyncAdapter( 1629): 	at com.google.wireless.gdata2.client.GDataServiceClient.convertHttpExceptionForFeedReads(GDataServiceClient.java:433)
D/ContactsSyncAdapter( 1629): 	at com.google.wireless.gdata2.client.GDataServiceClient.getParserForFeed(GDataServiceClient.java:111)
D/ContactsSyncAdapter( 1629): 	at com.google.android.syncadapters.contacts.GDataFeedFetcher.fetchFeed(GDataFeedFetcher.java:185)
D/ContactsSyncAdapter( 1629): 	at com.google.android.syncadapters.contacts.GDataFeedFetcher.run(GDataFeedFetcher.java:100)
D/ContactsSyncAdapter( 1629): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter$ContactsGDataFeedFetcher.run(ContactsSyncAdapter.java:1413)
D/ContactsSyncAdapter( 1629): 	at java.lang.Thread.run(Thread.java:818)
D/ContactsSyncAdapter( 1629): Caused by: com.google.wireless.gdata2.client.HttpException: Received 403 status code: <?xml version="1.0" encoding="UTF-8"?>
D/ContactsSyncAdapter( 1629): <errors xmlns="http://schemas.google.com/g/2005">
D/ContactsSyncAdapter( 1629):  <error>
D/ContactsSyncAdapter( 1629):   <domain>usageLimits</domain>
D/ContactsSyncAdapter( 1629):   <code>rateLimitExceededUnreg</code>
D/ContactsSyncAdapter( 1629):   <internalReason>Rate Limit Exceeded. Please sign up</internalReason>
D/ContactsSyncAdapter( 1629):   <extendedHelp>https://code.google.com/apis/console</extendedHelp>
D/ContactsSyncAdapter( 1629):  </error>
D/ContactsSyncAdapter( 1629): </errors>
D/ContactsSyncAdapter( 1629): 
D/ContactsSyncAdapter( 1629): 	at com.google.android.common.gdata2.AndroidGDataClient.createAndExecuteMethod(AndroidGDataClient.java:397)
D/ContactsSyncAdapter( 1629): 	at com.google.android.syncadapters.HttpsOnlyAndroidGDataClient.createAndExecuteMethod(HttpsOnlyAndroidGDataClient.java:32)
D/ContactsSyncAdapter( 1629): 	at com.google.android.common.gdata2.AndroidGDataClient.getFeedAsStream(AndroidGDataClient.java:415)
D/ContactsSyncAdapter( 1629): 	at com.google.wireless.gdata2.client.GDataServiceClient.getParserForFeed(GDataServiceClient.java:108)
D/ContactsSyncAdapter( 1629): 	... 4 more
,D/ContactsSyncAdapter( 1629): getServerDiffs failed
D/ContactsSyncAdapter( 1629): com.google.wireless.gdata2.parser.ParseException: unparsable feed https://www.google.com/m8/feeds/contacts/thalitester@gmail.com/base2_property-android_linksto-gprofiles_highresphotos?sz=720
D/ContactsSyncAdapter( 1629): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.getServerDiffs(ContactsSyncAdapter.java:1218)
D/ContactsSyncAdapter( 1629): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:298)
D/ContactsSyncAdapter( 1629): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1629): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/ContactsSyncAdapter( 1629): FAILURE: processed 0 records in 128 ms from feed https://www.google.com/m8/feeds/contacts/thalitester@gmail.com/base2_property-android_linksto-gprofiles_highresphotos?sz=720, updated time is 2016-01-22T10:06:25.316Z
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 27020(1411KB) AllocSpace objects, 2(55KB) LOS objects, 40% free, 7MB/12MB, paused 1.143ms total 44.159ms
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 23044, reason: Periodic, SyncResult: stats [ numParseExceptions: 1]
,D/SyncManager( 1015): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 123401, reason: Periodic
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.syncadapters.calendar, action: android.content.SyncAdapter
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.syncadapters.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6574): MountEmulatedStorage(),
E/Zygote  ( 6574): v2
I/libpersona( 6574): KNOX_SDCARD checking this for 10102
I/libpersona( 6574): KNOX_SDCARD not a persona
,I/SELinux ( 6574): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6574): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6574): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,I/art     (  317): Explicit concurrent mark sweep GC freed 8683(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 22.139ms
,D/TimaKeyStoreProvider( 6574): TimaSignature is unavailable
,D/ActivityThread( 6574): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 17.511ms
I/ActivityManager( 1015): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=6574 uid=10102 gids={50102, 9997, 3003} abi=armeabi-v7a
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 19.164ms
,W/AbstractGoogleClient( 6574): Application name is not set. Call Builder#setApplicationName.
,D/LocationManagerService( 1015): getProviders()=[passive]
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6601): MountEmulatedStorage()
E/Zygote  ( 6601): v2
I/libpersona( 6601): KNOX_SDCARD checking this for 10086
I/libpersona( 6601): KNOX_SDCARD not a persona
,I/SELinux ( 6601): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6601): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6601 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 6601): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6601): TimaSignature is unavailable
,D/ActivityThread( 6601): Added TimaKeyStore provider
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/art     ( 6136): Explicit concurrent mark sweep GC freed 8638(315KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 10MB/13MB, paused 971us total 94.559ms
,W/TRThreadPoolExecutor( 6555): Task "NotifyOnDoneFutureTask[update_gservices_config]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,I/GservicesUpdateTask( 6555): Updating Gservices keys
,I/CheckinRequestBuilder( 1990): Classify the device as Phone.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,E/UpdateRequestReceiver( 6601): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,E/UpdateRequestReceiver( 6601): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/Gmail   ( 6136): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15722, normalSync: true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,I/jxcore-log( 5378): Test app app.js loaded
I/jxcore-log( 5378): 
,E/UpdateRequestReceiver( 6601): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,E/UpdateRequestReceiver( 6601): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5378): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 5378): BLE advertisement is supported
I/jxcore-log( 5378): 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.apps.plus
,I/chromium( 5378): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/CheckinTask( 1990): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
I/CheckinService( 1990): Checking schedule, now: 1453807573212 next: 1454346836170
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
I/CheckinService( 1990): active receiver: disabled
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.syncadapters.calendar, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.syncadapters.calendar, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 6136): lowestBackward conversation id 0
,D/PreloadUpdateManagerStateMachine( 5132): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5132): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5132): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5132): AutoUpdateTriggerManager:REQUEST2:requestInterval
D/hcjo    ( 5132): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/CheckinService( 1990): Recording last checkin time for package unspecified as 1453807573275
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/hcjo    ( 5132): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PreloadUpdateManagerStateMachine( 5132): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5132): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5132): entry::REQ_UPDATE_CHECK
,I/CheckinService( 1990): Checkin interval check for package: unspecified last checkin: 1453807573275 min interval config: 0 actual interval: 34
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/Volley  ( 5132): RestApi Request Add : 2315
,I/System.out( 5132): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 5132): Tagging socket -1 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5132, getuid(): 10010
,I/qtaguid ( 5132): Failed write_ctrl(t -1 8764893202948816896 -1) res=-1 errno=9,
I/qtaguid ( 5132): Tagging socket -1 with tag 79a327ee00000000(2040735726) for uid -1 failed errno=-9
I/NetworkManagementSocketTagger( 5132): tagSocketFd(-1, 2040735726, -1) failed with errno-9
,I/qtaguid ( 5132): Tagging socket 31 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5132, getuid(): 10010
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/CheckinService( 1990): Checking schedule, now: 1453807573350 next: 1454346836170
,I/CheckinService( 1990): active receiver: disabled
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SystemUpdateService( 1990): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,D/SystemUpdateService( 1990): onCreate
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 1990): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SystemUpdateService( 1990): cancelUpdate (empty URL),
I/SystemUpdateService( 1990): active receiver: disabled
,I/System.out( 1778): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1778): Tagging socket 81 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,I/Gmail   ( 6136): notifyAccountChanged
,I/Gmail   ( 6136): getAccountsCursor
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/Gmail   ( 6136): notifyAccountChanged
,W/Gmail   ( 6136): Sync complete for account: account:61035162
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.plus.service.OfflineActionSyncAdapterService; callingUser = 0; userId(target) = 0
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 5103(217KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 749us total 26.108ms
,I/Gmail   ( 6136): getAccountsCursor
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5132): Untagging socket -1
,I/qtaguid ( 5132): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 5132): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 5132): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 5132): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
D/PreloadUpdateManagerStateMachine( 5132): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 5132): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 5132): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 5132): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 5132): exit::FINISH
D/PreloadUpdateManagerStateMachine( 5132): entry::IDLE
,I/ActivityManager( 1015): Killing 4857:com.android.vending/u0a28 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_10028/pid_4857/cgroup.procs: No such file or directory
,W/BaseAppContext( 1990): Using Auth Proxy for data requests.
,W/BaseAppContext( 1990): Using Auth Proxy for data requests.
,W/BaseAppContext( 1990): Using Auth Proxy for data requests.
,W/BaseAppContext( 1990): Using Auth Proxy for data requests.
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 2993(114KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.224ms total 36.866ms
,W/BaseAppContext( 1990): Using Auth Proxy for data requests.
,W/BaseAppContext( 1990): Using Auth Proxy for data requests.
,W/BaseAppContext( 1990): Using Auth Proxy for data requests.
,D/SystemUpdateService( 1990): onDestroy
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/DynamiteModule( 1990): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1990): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 1990): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1990): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 1990): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 1990): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1990): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1990): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1990): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1990): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1990): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1990): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
E/DynamiteModule( 1990): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
E/DynamiteModule( 1990): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
E/DynamiteModule( 1990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1990): 	at android.os.Looper.loop(Looper.java:145)
E/DynamiteModule( 1990): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/DynamiteModule( 1990): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 1990): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 1990): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/DynamiteModule( 1990): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/DynamiteModule( 1990): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 1990): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 1990): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 1990): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 1990): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 1990): 		... 17 more
E/DynamiteModule( 1990): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 1990): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 1990): Selected local version of com.google.android.gms.flags
I/art     ( 1778): Explicit concurrent mark sweep GC freed 84046(4MB) AllocSpace objects, 56(2MB) LOS objects, 40% free, 13MB/22MB, paused 1.679ms total 103.412ms
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.music, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.sync.SyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5709): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5709): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 5709): Using the GMSCore's GoogleHttpClient
,I/SurfaceFlinger(  257): id=15 Removed Uoast (8/9)
,D/PowerManagerService( 1015): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 94100
,D/PowerManagerService( 1015): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
,D/PowerManagerService( 1015): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{1000}) (elapsedTime=3466)
,I/art     ( 1990): Explicit concurrent mark sweep GC freed 24304(1480KB) AllocSpace objects, 18(436KB) LOS objects, 40% free, 15MB/25MB, paused 1.659ms total 107.210ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SystemEventReceiver( 1990): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1990): Updating ocr activity enabled=false
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 31220(1529KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 2.883ms total 164.838ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6574): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6574): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6574): (HTTPLog)-Static: isShipBuild true
I/System.out( 6574): (HTTPLog)-Thread-1106-1018696699: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6574): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10102
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10102
,I/System.out( 6574): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6574): Tagging socket 28 with tag 1100000000000000{285212672,0} for uid -1, pid: 6574, getuid(): 10102
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.RefreshEnabledStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 5947:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 5897:com.sec.android.cloudagent/u0a2 (adj 15): empty #32
,I/System.out( 5709): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.PlayLogMonitorIntervalService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
I/System.out( 5709): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5709): (HTTPLog)-Static: isShipBuild true
I/System.out( 5709): (HTTPLog)-Thread-988-944761778: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5709): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  277): uids 10111
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10111
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.measurement.service.b; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/OcrModelManager( 1990): Updating downloaded model state (gservices changed)
,E/File    ( 1990): fail readDirectory() errno=2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 5709): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/libprocessgroup( 1015): failed to open /acct/uid_10002/pid_5897/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5947/cgroup.procs: No such file or directory
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 2967(120KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 753us total 22.487ms
,E/SMD     (  290): DCD OFF
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
D/GCM     ( 1778): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.syncadapters.calendar, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.syncadapters.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService; callingUser = 0; userId(target) = 0
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 23044, reason: Periodic, SyncResult: syncAlreadyInProgress: true stats []
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/qtaguid ( 6574): Untagging socket 28
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1778): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/GCoreUlr( 1778): DispatchingService.onCreate()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
,I/System.out( 1778): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1778): Tagging socket 54 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/CalendarSyncAdapter( 6574): Found 0 events marked dirty & lastSynced
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 3434(139KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 1.485ms total 27.506ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1778): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/GCM     ( 1778): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1778): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 5709): (HTTPLog)-Static: isSBSettingEnabled false
,W/GeofencerStateMachine( 1778): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1778): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1778): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1778): Unbound from all location providers
,I/GCoreUlr( 1778): Place inference reporting - stopped
,W/ctxmgr  ( 1778): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10012, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,W/MusicApiClient( 5709): No content in 'data' field in GET sync response for Track
,E/ctxmgr  ( 1778): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
I/GCoreUlr( 1778): DispatchingService.onDestroy()
I/GCoreUlr( 1778): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1778): Unbound from all location providers
,I/GCoreUlr( 1778): Place inference reporting - stopped
,W/art     ( 4835): Attempt to remove local handle scope entry from IRT, ignoring
,I/MusicSyncAdapter( 5709): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
,I/MusicSyncAdapter( 5709): Periodic update
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 1990): Indexing CCCF2610294B0D8C53498F9681259C2D89058ED7 from com.google.android.gm
,E/Zygote  ( 6675): MountEmulatedStorage()
,E/Zygote  ( 6675): v2
I/libpersona( 6675): KNOX_SDCARD checking this for 10028
I/libpersona( 6675): KNOX_SDCARD not a persona
,I/SELinux ( 6675): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=6675 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6675): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6675): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6675): TimaSignature is unavailable
,D/ActivityThread( 6675): Added TimaKeyStore provider
,I/Gmail   ( 6136): Backfilling search sequence table
,D/EnterpriseController(  277): uids 10120
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10120
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,I/art     ( 1778): Explicit concurrent mark sweep GC freed 25397(1481KB) AllocSpace objects, 11(560KB) LOS objects, 39% free, 13MB/22MB, paused 1.397ms total 74.974ms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,W/Icing   ( 1990): Content incarnation mismatch: Expected [6def6ecf0f3d1ba7] found [f77d6ca0121b5a38]
I/Icing   ( 1990): Indexing done CCCF2610294B0D8C53498F9681259C2D89058ED7
E/Icing   ( 1990): Aborting indexing of corpus messages/com.google/thalitester%40gmail.com
,I/Icing   ( 1990): Removing corpus key CCCF2610294B0D8C53498F9681259C2D89058ED7 for package com.google.android.gm
,E/Auth.Api.Credentials( 1990): [CredentialSyncAdapter] Unknown sync event.
,D/Finsky  ( 6675): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.subscribedfeeds.SyncService; callingUser = 0; userId(target) = 0
,I/GoogleURLConnFactory( 1990): Using platform SSLCertificateSocketFactory
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1990): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1990): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1990): Tagging socket 47 with tag 1000210100000000{268443905,0} for uid -1, pid: 1990, getuid(): 10012
,D/Finsky  ( 6675): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6675): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6675): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Icing   ( 1990): Indexing CCCF2610294B0D8C53498F9681259C2D89058ED7 from com.google.android.gm
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/Ads     ( 6675): Skipping gmscore version check
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.KeepOnUpdater$SyncListener; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6675): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6675): [1] Libraries$2.run: Finished loading 1 libraries.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/Icing   ( 1990): Indexing done CCCF2610294B0D8C53498F9681259C2D89058ED7
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/Finsky  ( 6675): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5709): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/File    ( 5709): fail readDirectory() errno=2
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5709): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/Finsky  ( 6675): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.keepon.KeeponSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/qtaguid ( 1990): Tagging socket 126 with tag 1000210100000000{268443905,0} for uid -1, pid: 1990, getuid(): 10012
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 5709): Conditions not met for autocaching.
,I/MusicLeanback( 5709): Stop autocaching.
,E/GmsUtils( 5709): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5709): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,E/GmsUtils( 5709): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/ActivityManager( 1015): Killing 5840:com.google.android.youtube/u0a166 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10166/pid_5840/cgroup.procs: No such file or directory
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5458): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6675): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 38118(1900KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 2.656ms total 153.616ms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 6675): Thread-1122(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6675): Thread-1122(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6675): Thread-1122(ApacheHTTPLog):isShipBuild true
I/System.out( 6675): Thread-1122(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6675): Thread-1122(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
,I/qtaguid ( 6675): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 6675, getuid(): 10028
,I/qtaguid ( 6675): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 6675, getuid(): 10028
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 5099:com.policydm/1000 (adj 15): empty #31
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.photos.service.GooglePhotoDownsyncService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5099/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.sync.RemindersSyncService; callingUser = 0; userId(target) = 0
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 2989(117KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 880us total 34.723ms
,I/RemindersSync( 1990): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=335:priority=5:group=main]
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.ReportingSyncService; callingUser = 0; userId(target) = 0
,E/SMD     (  290): DCD OFF
,I/qtaguid ( 1990): Untagging socket 47
,I/ActivityManager( 1015): Killing 5153:com.sec.spp.push/u0a35 (adj 15): empty #31
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.apps.docs, action: android.content.SyncAdapter
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6743): MountEmulatedStorage(),
E/Zygote  ( 6743): v2
I/libpersona( 6743): KNOX_SDCARD checking this for 10091
I/libpersona( 6743): KNOX_SDCARD not a persona,
I/SELinux ( 6743): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1015): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6743 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6743): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6743): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 5798:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6743): TimaSignature is unavailable
,D/ActivityThread( 6743): Added TimaKeyStore provider
,W/BaseAppContext( 1778): Using Auth Proxy for data requests.
,I/qtaguid ( 6675): Untagging socket 44
,I/System.out( 6675): Thread-1122 calls detatch()
,E/BaseAppContext( 1778): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,E/PhotosPlugin( 6743): Loading PhotosPlugin
,W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_5153/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10044/pid_5798/cgroup.procs: No such file or directory
,I/System.out( 1778): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1778): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1778): Tagging socket 48 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 6675): Thread-1123(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6675): Thread-1123(ApacheHTTPLog):isShipBuild true
I/System.out( 6675): Thread-1123(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6675): Thread-1123(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 6675): Untagging socket 44
I/qtaguid ( 6675): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 6675): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 6675): untagSocket(44) failed with errno -22
I/System.out( 6675): Thread-1123 calls detatch()
,I/qtaguid ( 1778): Tagging socket 102 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,D/Finsky  ( 6675): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 6769): MountEmulatedStorage(),
I/libpersona( 6769): KNOX_SDCARD checking this for 10012
E/Zygote  ( 6769): v2
I/libpersona( 6769): KNOX_SDCARD not a persona,
I/SELinux ( 6769): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6769): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6769): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6769 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 6675): Thread-1122(ApacheHTTPLog):isSBSettingEnabled false
,D/TimaKeyStoreProvider( 6769): TimaSignature is unavailable
,I/System.out( 6675): Thread-1122(ApacheHTTPLog):isShipBuild true
I/System.out( 6675): Thread-1122(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6675): Thread-1122(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/ActivityThread( 6769): Added TimaKeyStore provider
,W/ResourcesManager( 6769): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6769): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6769): VM with version 2.1.0 has multidex support
I/MultiDex( 6769): install
I/MultiDex( 6769): VM has multidex support, MultiDex support library is disabled.
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,V/JNIHelp ( 6769): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/GAV2    ( 4835): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityThread( 6769): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6769): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16f8a22b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6769): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 6743): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6769): Reading stored module config
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
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1990): Restart initialization of location
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1778): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/qtaguid ( 6675): Untagging socket 44
I/qtaguid ( 6675): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 6675): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 6675): untagSocket(44) failed with errno -22
I/System.out( 6675): Thread-1122 calls detatch()
,D/ChimeraCfgMgr( 6769): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1778): [197] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,W/GCoreFlp( 1778): No location to return for getLastLocation()
,W/FusedLocationProvider( 1778): location=null
,D/NativeLibraryUtils( 6769): Install completed successfully. count=14 extracted=0
,W/GAV2    ( 6743): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CAR.SERVICE( 6769): Connecting to CarCallService...
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/AccountFeatureHelper( 6743): Write apps_features disabled false
,I/art     ( 6769): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6769): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6769): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6769): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6769): Creating a new PhoneAdapter instance
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6769): setListener: com.google.android.gms.car.dn@2ff56af6
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
D/CAR.TEL.PhoneAdapter( 6769): Returning an existing PhoneAdapter instance.
W/ActivityManager( 1015): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.Service( 6769): Starting CarCallService with initial phone null
,W/Flag    ( 6743): Duration spec must be at least 2 characters long
,I/System.out( 6743): Thread-1145(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 6743): Thread-1145(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6743): Thread-1145(ApacheHTTPLog):isShipBuild true
I/System.out( 6743): Thread-1145(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6743): Thread-1145(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10091
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10091
,D/CAR.SERVICE( 6769): Package validated; name: com.android.vending
,V/Finsky  ( 6675): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.appcert.AppCertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1778): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1778): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1778): Tagging socket 103 with tag 1000060200000000{268436994,0} for uid 10012, pid: 1778, getuid(): 10012
,I/qtaguid ( 1778): Tagging socket 106 with tag 1000060200000000{268436994,0} for uid 10012, pid: 1778, getuid(): 10012
,I/System.out( 6743): BaseSyncManager calls detatch()
,I/qtaguid ( 1778): Untagging socket 103
,I/GCoreUlr( 1778): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1778): DispatchingService.onCreate()
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.CredentialStateSyncService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/GCoreUlr( 1778): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/System.out( 1778): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1778): Tagging socket 48 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,I/GCoreUlr( 1778): Unbound from all location providers
I/GCoreUlr( 1778): Place inference reporting - stopped
,I/GCoreUlr( 1778): DispatchingService.onDestroy()
,I/GCoreUlr( 1778): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1778): Unbound from all location providers
,I/GCoreUlr( 1778): Place inference reporting - stopped
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1778): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1778): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1778): Tagging socket 107 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,I/qtaguid ( 1778): Tagging socket 110 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1778, getuid(): 10012
,I/System.out( 6743): Thread-1145(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6743): Thread-1145(ApacheHTTPLog):isShipBuild true
I/System.out( 6743): Thread-1145(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6743): Thread-1145(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10091
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10091
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupSyncService; callingUser = 0; userId(target) = 0
,I/System.out( 6675): Thread-1123(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6675): Thread-1123(ApacheHTTPLog):isShipBuild true
I/System.out( 6675): Thread-1123(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6675): Thread-1123(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 36611(1658KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 2.531ms total 154.995ms
,I/qtaguid ( 6675): Untagging socket 44
,I/qtaguid ( 6675): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 6675): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 6675): untagSocket(44) failed with errno -22
I/System.out( 6675): Thread-1123 calls detatch()
,D/Finsky  ( 6675): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.marvin.talkback to true
,D/Finsky  ( 6675): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.marvin.talkback from  to d_AAAAAAADF8w=
,D/Finsky  ( 6675): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for flipboard.app to true
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.cache.DataUpdateListenerCacheService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupSyncService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 6675): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6675): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6675): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/System.out( 6743): BaseSyncManager calls detatch()
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 6675): [1] DailyHygiene.access$600: Logging device features
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1778): client connected with version: 8296000
,D/Finsky  ( 6675): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.vending.verifier.PackageVerificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/GAV2    ( 6743): BaseSyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager( 1015): Killing 6118:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,D/Finsky  ( 6675): [1145] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/Finsky  ( 6675): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,D/Finsky  ( 6675): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6675): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1015): failed to open /acct/uid_10125/pid_6118/cgroup.procs: No such file or directory
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onTerminate : 2672
,I/System.out( 6675): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6675): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6675): (HTTPLog)-Static: isShipBuild true
I/System.out( 6675): (HTTPLog)-Thread-1133-188759253: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6675): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 6675): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  290): DCD OFF
,I/ActivityManager( 1015): Killing 5540:com.android.email/u0a145 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10145/pid_5540/cgroup.procs: No such file or directory
,D/PackageManager( 1015): [MSG] WRITE_SETTINGS
,D/SSRM:n  ( 1015): SIOP:: AP = 340
,I/PowerManagerService( 1015): [PWL] Off : 50s ago
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/PackageManager( 1015): [MSG] SEND_PENDING_BROADCAST
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,I/PageBuddyNotiSvc( 4059): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6854): MountEmulatedStorage()
,I/libpersona( 6854): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6854): v2
I/libpersona( 6854): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6854 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6854): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RegisteredComponentCache( 1434): Collect Tech packages for Knox
,D/PersonaManager( 1434): isKioskContainerExistOnDevice
,D/PersonaManager( 1434): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1434): empty dynamic service
,D/TimaKeyStoreProvider( 6854): TimaSignature is unavailable
,D/ActivityThread( 6854): Added TimaKeyStore provider
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,I/ActivityManager( 1015): Killing 6156:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,W/IntentResolver( 1015): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1015): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1015): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/BackupManagerService( 1015): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1015): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3e053d46
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AASAservice-UpdateReceiver( 6854): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,I/splitIntent( 1015): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
,I/splitIntent( 1015): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
I/splitIntent( 1015): other index=7, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5825): Creating RTCS
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6872): MountEmulatedStorage(),
E/Zygote  ( 6872): v2
I/libpersona( 6872): KNOX_SDCARD checking this for 10032
I/libpersona( 6872): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6872 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 6872): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/Babel   ( 5825): Destroying RTCS
,I/ActivityManager( 1015): Killing 5988:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,I/SELinux ( 6872): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6872): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6872): TimaSignature is unavailable
,D/ActivityThread( 6872): Added TimaKeyStore provider
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/FeatureConfig( 6872): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1015): Killing 5291:com.osp.app.signin/u0a41 (adj 15): empty #31
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,E/SMD     (  290): DCD OFF
,W/ResourcesManager( 6872): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6872): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6872): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  ( 6889): MountEmulatedStorage()
E/Zygote  ( 6889): v2
I/libpersona( 6889): KNOX_SDCARD checking this for 10044
I/libpersona( 6889): KNOX_SDCARD not a persona
,I/SELinux ( 6889): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1015): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6889 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6889): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,E/SELinux ( 6889): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6872): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6872): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,W/ResourcesManager( 6872): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6872): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6889): TimaSignature is unavailable
,D/ActivityThread( 6889): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6872): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6889): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6889): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6889): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6889): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6889): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6889): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6889): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6889): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6872): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_10062/pid_6156/cgroup.procs: No such file or directory
,W/ResourcesManager( 6872): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/libprocessgroup( 1015): failed to open /acct/uid_10009/pid_5988/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1015): applying state to connected service
W/ResourcesManager( 6872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_10041/pid_5291/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 6769): mConnectedToCar = false, abort
,E/ActivityThread( 6769): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1176b61e that was originally bound here
E/ActivityThread( 6769): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1176b61e that was originally bound here
E/ActivityThread( 6769): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6769): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6769): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6769): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6769): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6769): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6769): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6769): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6769): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6769): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6769): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6769): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6769): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6769): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6769): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6769): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6769): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6769): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6769): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6769): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6769): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6769): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ResourcesManager( 6872): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/ActivityThread( 6769): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3140ab91 that was originally bound here
E/ActivityThread( 6769): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3140ab91 that was originally bound here
E/ActivityThread( 6769): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6769): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6769): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6769): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6769): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6769): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6769): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6769): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6769): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6769): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6769): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6769): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6769): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6769): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6769): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6769): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6769): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6769): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6769): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6769): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6769): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1015): Unbind failed: could not find connection for android.os.BinderProxy@226bfc94
,W/ResourcesManager( 6872): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6872): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6872): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6872): system/finder_cp/cpdata.xml file not found
,D/NearbySource( 6889): Nearby Source Create!
,D/NearbyContext( 6889): Nearby Context Create!
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6889): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6889): Samsung link source created
,D/ContactProvider( 6889): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PackagesMonitor( 6889): PackagesMonitor onReceive :com.google.android.gms
,D/ContactProvider( 6889): getAllContactInfoList End
,I/syncContacts( 6889): thread: 1143, sync time = 32
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/UpdateIcingCorporaServi( 6555): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/Zygote  ( 6910): MountEmulatedStorage()
,E/Zygote  ( 6910): v2
I/libpersona( 6910): KNOX_SDCARD checking this for 10069
I/libpersona( 6910): KNOX_SDCARD not a persona
,I/SELinux ( 6910): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6910 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6910): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6910): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/TimaKeyStoreProvider( 6910): TimaSignature is unavailable
,D/ActivityThread( 6910): Added TimaKeyStore provider
,D/FileShare-Server( 6910): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/UpdateIcingCorporaServi( 6555): UpdateCorporaTask done [took 90 ms] updated apps [took 90 ms] ,
,E/Zygote  ( 6925): MountEmulatedStorage()
,E/Zygote  ( 6925): v2
I/libpersona( 6925): KNOX_SDCARD checking this for 1000
I/libpersona( 6925): KNOX_SDCARD not a persona
,I/SELinux ( 6925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6925 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1015): Killing 5592:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/SELinux ( 6925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6925): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 6280:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31,
,D/TimaKeyStoreProvider( 6925): TimaSignature is unavailable
,D/ActivityThread( 6925): Added TimaKeyStore provider
,W/ResourcesManager( 6925): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6940): MountEmulatedStorage()
E/Zygote  ( 6940): v2
I/libpersona( 6940): KNOX_SDCARD checking this for 1000
I/libpersona( 6940): KNOX_SDCARD not a persona
,I/SELinux ( 6940): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=6940 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1015): Killing 6290:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31,
I/SELinux ( 6940): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6940): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6940): TimaSignature is unavailable
,D/ActivityThread( 6940): Added TimaKeyStore provider
,D/KnoxSetupWizardDbHelper( 6940): dbMigrationFlag : false
,D/ShortcutReceiver( 6940):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5592/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10085/pid_6290/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10157/pid_6280/cgroup.procs: No such file or directory
,I/ActivityManager( 1015): Killing 6313:com.qualcomm.timeservice/1000 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageBroadcastService( 1990): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PackageBroadcastService( 1990): Null package name or gms related package.  Ignoreing.
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 1990): updateResources: need to parse f{com.google.android.gms}
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_6313/cgroup.procs: No such file or directory
,I/art     ( 1778): Explicit concurrent mark sweep GC freed 39285(2MB) AllocSpace objects, 29(1088KB) LOS objects, 39% free, 13MB/22MB, paused 1.301ms total 68.578ms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 1990): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,D/Icing   ( 1990): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1990): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5458): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF,
,D/FactoryTest( 4644): Not factory mode
,D/FactoryTest( 4644): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4644): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4644): still no open session command from host, so toast
,W/ContextImpl( 4644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4644): Timeline: Activity_launch_request id:com.android.settings time:107043
,E/PersonaManagerService( 1015): inState():  stateMachine is null !!
,I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): mDVFSHelper.acquire()
,I/UsageStatsService( 1015): User[0] Flushing usage stats to disk
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 5378
,E/MTPRx   ( 4644): started activity for popup
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 4644): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 4644): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4644): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4644): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4644): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4644): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/daily/1453248000000 to /data/system/usagestats/0/daily/1453248002437
,I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/daily/1453334400000 to /data/system/usagestats/0/daily/1453334402437
I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/daily/1453420800000 to /data/system/usagestats/0/daily/1453420802437
,I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/daily/1453507200000 to /data/system/usagestats/0/daily/1453507202437
I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/daily/1453680000000 to /data/system/usagestats/0/daily/1453680002437
I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/daily/1453766400000 to /data/system/usagestats/0/daily/1453766402437
I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/weekly/1451520006823 to /data/system/usagestats/0/weekly/1451520009260
,I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/weekly/1452124800000 to /data/system/usagestats/0/weekly/1452124802437
I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/weekly/1452729600000 to /data/system/usagestats/0/weekly/1452729602437
,I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/weekly/1453334400000 to /data/system/usagestats/0/weekly/1453334402437
I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/monthly/1439783480854 to /data/system/usagestats/0/monthly/1439783483291
I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/monthly/1441152046282 to /data/system/usagestats/0/monthly/1441152048719
,I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/monthly/1443744046282 to /data/system/usagestats/0/monthly/1443744048719
I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/monthly/1446336020968 to /data/system/usagestats/0/monthly/1446336023405
I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/monthly/1448928012906 to /data/system/usagestats/0/monthly/1448928015343
I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/monthly/1451520006823 to /data/system/usagestats/0/monthly/1451520009260
,I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/yearly/1435031480854 to /data/system/usagestats/0/yearly/1435031483291
I/UsageStatsDatabase( 1015): Moving file /data/system/usagestats/0/yearly/1450656010517 to /data/system/usagestats/0/yearly/1450656012954
,E/SettingsReceiverActivity( 4644): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus entered window: 5378
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/UsageStatsService( 1015): User[0] Rollover scheduled @ 2016-01-27 01:00:00(1453852800000)
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1015): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@15ca006 attribute=null, token = android.os.BinderProxy@256647a5
,D/SettingsReceiverActivity( 4644): dev.kiessupport is : TRUE
,D/PhoneWindow( 4644): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4644): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,I/Timeline( 5378): Timeline: Activity_idle id: android.os.BinderProxy@16d7780e time:107218,
V/ActivityThread( 5378): updateVisibility : ActivityRecord{2550c03c token=android.os.BinderProxy@16d7780e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,E/Watchdog( 1015): !@Sync 3
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,W/ActivityManager( 1015): mDVFSHelper.release()
,V/AlarmManager( 1015): waitForAlarm result :4
,D/SSRM:n  ( 1015): SIOP:: AP = 320
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6675): [1135] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6675): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.PeopleRequestProcessor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 1990): getNumBytesRead when not calculated.
,D/SSRM:n  ( 1015): SIOP:: AP = 300
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1015): [PWL] Off : 75s ago,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1015): !@Sync 4
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4
,V/AlarmManager( 1015): ___SyncScheduler (v3) ACTIVATED___,
,V/AlarmManagerEXT( 1015): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1015): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.metadata.ContactMetadataSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.games.chimera.GamesSyncServiceNotificationProxy; callingUser = 0; userId(target) = 0
,D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1990): Module APK com.google.android.play.games already loaded
,E/ActivityThread( 1990): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 114335, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 1015): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 205749, reason: UserStart
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.syncadapters.calendar, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.syncadapters.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService; callingUser = 0; userId(target) = 0
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.syncadapters.calendar, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.syncadapters.calendar, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 6574): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 6574): Tagging socket 28 with tag 1100000000000000{285212672,0} for uid -1, pid: 6574, getuid(): 10102
,I/qtaguid ( 6574): Tagging socket 32 with tag 1100000000000000{285212672,0} for uid -1, pid: 6574, getuid(): 10102
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 65862(3MB) AllocSpace objects, 34(544KB) LOS objects, 33% free, 28MB/42MB, paused 2.462ms total 161.876ms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 1990): 0 accounts found with uca feature
,I/GamesSyncAdapter( 1990): Starting sync for 3a3529a
,I/GamesSyncAdapter( 1990): Sync duration for 3a3529a: 6
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1990): Module APK com.google.android.play.games already loaded
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.apps.docs, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService; callingUser = 0; userId(target) = 0
,I/qtaguid ( 6574): Untagging socket 28
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1990): Module APK com.google.android.play.games already loaded
,D/CalendarSyncAdapter( 6574): Found 0 events marked dirty & lastSynced
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.syncadapters.calendar, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.syncadapters.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService; callingUser = 0; userId(target) = 0
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.syncadapters.calendar, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.syncadapters.calendar, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 6574): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 6574): Tagging socket 28 with tag 1000000400000000{268435460,0} for uid -1, pid: 6574, getuid(): 10102
,V/CalendarSyncAdapter( 6574): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-01-24T00:00:00.000Z, updatedMin=2015-11-18T16:31:02.459Z}
,I/qtaguid ( 6574): Untagging socket 28
,D/CalendarSyncAdapter( 6574): Found 0 events marked dirty & lastSynced,
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.syncadapters.calendar, action: android.content.SyncAdapter
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.syncadapters.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.syncadapters.calendar, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.syncadapters.calendar, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 6574): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 6574): Tagging socket 28 with tag 1000000400000000{268435460,0} for uid -1, pid: 6574, getuid(): 10102
,V/CalendarSyncAdapter( 6574): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-01-24T00:00:00.000Z, timeMin=2017-02-23T00:00:00.000Z}
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 3
,I/qtaguid ( 6574): Untagging socket 28
,D/CalendarSyncAdapter( 6574): Found 0 events marked dirty & lastSynced
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1015): [PWL] Off : 105s ago,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ClearcutLoggerApiImpl( 1778): disconnect managed GoogleApiClient
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1015): stay LED for fully charged
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5458): Disconnected process message: 10,
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 5
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5458): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 140s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,V/AlarmManager( 1015): waitForAlarm result :4
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5458): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 6
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/ClearcutLoggerApiImpl( 1990): disconnect managed GoogleApiClient
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5458): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/BatteryService( 1015): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5458): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/Watchdog( 1015): !@Sync 7
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5458): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5458): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 8
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 1015): [PWL] Off : 225s ago,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5458): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5458): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 9
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5458): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5458): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5458): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/jxcore-log( 5378): --= Surplus to requirements =--
I/jxcore-log( 5378): 
,I/jxcore-log( 5378): ****TEST TOOK:  ms ****
I/jxcore-log( 5378): 
I/jxcore-log( 5378): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5378): 
,D/AndroidRuntime( 7078): 
D/AndroidRuntime( 7078): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7078): CheckJNI is OFF
,D/AndroidRuntime( 7078): readGMSProperty: start
D/AndroidRuntime( 7078): readGMSProperty: already setted!!
D/AndroidRuntime( 7078): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7078): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7078): readGMSProperty: end
D/AndroidRuntime( 7078): addProductProperty: start
,E/AffinityControl( 7078): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 7078): Calling main entry com.android.commands.pm.Pm,
,E/SMD     (  290): DCD OFF,
,D/PersonaManagerService( 1015): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1015): START PACKAGE DELETE: observer{120210770}
D/PackageManager( 1015): pkg{<packageName>}
D/PackageManager( 1015): user{0}
D/PackageManager( 1015): caller{2000}
D/PackageManager( 1015): flags{3}
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1015): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1015): !@killApplicatoin: 10155, uninstall pkg
,I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
I/ActivityManager( 1015): Killing 5378:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{1289b2f u0 com.test.thalitest/.MainActivity t7}
,E/JavaBinder( 1015): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1015): Focus left window: 5378
,I/SurfaceFlinger(  257): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger(  257): id=12 Removed NainActivit (-2/8)
,D/InputDispatcher( 1015): Focused application released,
E/JavaBinder( 1015): !!! FAILED BINDER TRANSACTION !!!
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 3646): Explicit concurrent mark sweep GC freed 3029(186KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 6MB/11MB, paused 772us total 34.340ms
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1788): mOCRHelper is null
,W/GeofencerStateMachine( 1778): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1990): Explicit concurrent mark sweep GC freed 14833(864KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 15MB/20MB, paused 1.393ms total 79.822ms
,D/RegisteredComponentCache( 1434): Collect Tech packages for Knox
,D/PersonaManager( 1434): isKioskContainerExistOnDevice
,I/KLMS-2.5.183: ( 3433): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 26 12:29:53 GMT+01:00 2016
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3433): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1015): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1015): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/elm:15183( 6375): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/PackagesMonitor( 6889): PackagesMonitor onReceive :com.test.thalitest
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3433): KLMSIntentService(): onCreate()
,E/Zygote  ( 7092): MountEmulatedStorage()
E/Zygote  ( 7092): v2
I/libpersona( 7092): KNOX_SDCARD checking this for 10149
I/libpersona( 7092): KNOX_SDCARD not a persona
,I/SELinux ( 7092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/KLMS-2.5.183: ( 3433): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/SELinux ( 7092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 7092): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3433): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/ActivityManager( 1015): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7092 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1015): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3433): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 6375): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.5.183: ( 3433): KLMSIntentService(): PACKAGE_REMOVED
,D/elm:15183( 6375): ElmAgentService : onCreate()
,D/elm:15183( 6375): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
I/art     (  317): Explicit concurrent mark sweep GC freed 8727(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 902us total 23.239ms
,D/elm:15183( 6375): MainReceiver.listeningToPackageRemoved()
,D/elm:15183( 6375): MDMBridge.getInstance()
,D/elm:15183( 6375): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15183( 6375): MDMBridge.getAllLicenseInfoFromSDK()
,D/TimaKeyStoreProvider( 7092): TimaSignature is unavailable
,D/ActivityThread( 7092): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.030ms
I/KLMS-2.5.183: ( 3433): KLMSIntentService(): listeningToPackageRemoved().START
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 41250(3MB) AllocSpace objects, 73(1168KB) LOS objects, 33% free, 27MB/41MB, paused 2.865ms total 221.430ms
I/art     ( 1015): WaitForGcToComplete blocked for 214.608ms for cause Explicit
,I/KLMS-2.5.183: ( 3433): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 17.066ms
,E/SQLiteLog( 6200): (284) automatic index on crash_info_summary(package_name_touched)
,D/Mms/FreeMessageStatusReceiver( 6333): onReceive, action : android.intent.action.PACKAGE_REMOVED
,D/ActivityManager( 1015): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/elm:15183( 6375): ElmAgentService : onDestroy().
,D/PersonaManager( 1434): isKioskContainerExistOnDevice
,D/AASAservice-UpdateReceiver( 6854): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,W/System.err( 6854): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 6854): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6854): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6854): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6854): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6854): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6854): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6854): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6854): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6854): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6854): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6854): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6854): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/art     ( 6200): Explicit concurrent mark sweep GC freed 618(48KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 694us total 51.385ms
,D/BadgeProvider( 6429): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6429): sendNotify, [notify] : null
D/BadgeProvider( 6429): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6429): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 6429): update, [UpdateCount] : 1
,D/RegisteredServicesCache( 1434): empty dynamic service
,D/Mms/FreeMessageReceiverService( 6333): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 6333): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 1015): enable value -1
I/TactileAssist( 1015): internal enable value -1
I/TactileAssist( 1015): intensity value -1
I/TactileAssist( 1015): saveAppList value true
,D/ThemeInfoUtil( 7092): getCurrentFestivalName is [null]
,D/ThemeInfoUtil( 7092): isCurrentFestival = false,
,I/TactileAssist( 1015): List of disabled apps :
,I/KLMS-2.5.183: ( 3433): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.183: ( 3433): KLMSIntentService(): onDestroy()
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7112): MountEmulatedStorage(),
E/Zygote  ( 7112): v2
,I/libpersona( 7112): KNOX_SDCARD checking this for 10152
I/libpersona( 7112): KNOX_SDCARD not a persona
,I/SELinux ( 7112): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 7112): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 7112): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7112 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7126): MountEmulatedStorage()
,E/Zygote  ( 7126): v2
I/libpersona( 7126): KNOX_SDCARD checking this for 1000
I/libpersona( 7126): KNOX_SDCARD not a persona
,I/SELinux ( 7126): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 7126): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 7126): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/RCPManagerService( 1015): PackageReceiver onReceive()
I/HarmonyEASService( 1015): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/ActivityManager( 1015): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7126 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 6447:com.wsomacp/u0a25 (adj 15): empty #31
,D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1015): PackageRemovalReceiver::onReceive Enter
,D/TimaKeyStoreProvider( 7112): TimaSignature is unavailable
,D/OTPFW   ( 1015): OtpDbHelper::getInstance New instance created
,D/ActivityThread( 7112): Added TimaKeyStore provider
,D/OTPFW   ( 1015): DBIntegrity::getInstance - New instance created
,D/TimaKeyStoreProvider( 7126): TimaSignature is unavailable
,D/ActivityThread( 7126): Added TimaKeyStore provider
,D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
,D/OTPFW   ( 1015): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
W/TextServicesManagerService( 1015): no available spell checker services found
,I/OTPFW   ( 1015): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1015): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 9211(502KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 28MB/42MB, paused 6.641ms total 219.760ms
,D/JobSchedulerService( 1015): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10155
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7142): MountEmulatedStorage()
,E/Zygote  ( 7142): v2
I/libpersona( 7142): KNOX_SDCARD checking this for 10053
I/libpersona( 7142): KNOX_SDCARD not a persona
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 7142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 7142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7142 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
,E/SELinux ( 7142): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TaskPersister( 1015): removeObsoleteFile: deleting file=7_task.xml
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/SSRM:aZ ( 1015): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1015): uID is 10155
V/AlarmManagerEXT( 1015): com.test.thalitest(10155) is removed.
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7150): MountEmulatedStorage(),
E/Zygote  ( 7150): v2
I/libpersona( 7150): KNOX_SDCARD checking this for 1000
I/SELinux ( 7150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 7150): KNOX_SDCARD not a persona
I/SELinux ( 7150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7150): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7150 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SQLiteLog( 7112): (284) automatic index on shooting_modes(title_id)
,D/PackageManager( 1015): delete codoeFile: 
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,D/AASAuninstall( 1015): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
I/AASA_removePackage( 1015): UID=10155 Target=com.test.thalitest,
D/TimaKeyStoreProvider( 7142): TimaSignature is unavailable
D/PackageManager( 1015): result of delete: 1{120210770}
,D/ActivityThread( 7142): Added TimaKeyStore provider
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 7150): TimaSignature is unavailable
,D/ActivityThread( 7150): Added TimaKeyStore provider
,D/AndroidRuntime( 7078): Shutting down VM
,E/Zygote  ( 7172): MountEmulatedStorage()
E/Zygote  ( 7172): v2
I/libpersona( 7172): KNOX_SDCARD checking this for 10156
I/libpersona( 7172): KNOX_SDCARD not a persona
,I/SELinux ( 7172): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 7172): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7172 uid=10156 gids={50156, 9997} abi=armeabi-v7a
E/SELinux ( 7172): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7172): TimaSignature is unavailable
,D/ActivityThread( 7172): Added TimaKeyStore provider
,W/ResourcesManager( 7142): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/ActivityManager( 1015): Killing 6396:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,I/PCWCLIENTTRACE_LOG( 7150): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7150): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7150): new DMDBOpenHelper instance
,D/Compatibility( 7142): onReceive() it will make start service
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ContextImpl( 7126): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,I/PCWCLIENTTRACE_PushUtil( 7150): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7150): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7150): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7150): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/Compatibility( 7142): onHandleIntent()
,D/Compatibility( 7142): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 7142): found: 2
,I/TapandpayWidget:TapandpayAppWidgetProvider( 7172): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 7172): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/TapandpayWidget:Utils( 7172): Clear T&P info.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManager( 6925):  in createShortcut() for packageName: com.test.thalitest userId0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,D/Compatibility( 7142): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/RCPManagerService( 1015):  in createShortcut() for packageName: com.test.thalitest userId0
,D/Compatibility( 7142): skipping ResolveInfo{32f4639d com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7142): considering ResolveInfo{10d67012 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7142): default: com.sec.android.app.soundalive.SAControlPanelActivity
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 7142): enabling receiver ResolveInfo{15f63e3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000},
D/RCPManagerService( 1015): queryAllProviders():  providerCallBack is not register for 0
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Compatibility( 7142): enabling receiver ResolveInfo{a9ee1e0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/Zygote  ( 7193): MountEmulatedStorage()
E/Zygote  ( 7193): v2
I/libpersona( 7193): KNOX_SDCARD checking this for 10035
I/libpersona( 7193): KNOX_SDCARD not a persona
,I/SELinux ( 7193): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TapandpayWidget:TapandpayAppWidgetProvider( 7172): Widget is not attached.
,I/UpdateIcingCorporaServi( 6555): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/SELinux ( 7193): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 7193): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7193 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Compatibility( 7142): enabling receiver ResolveInfo{1b89c99 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/Compatibility( 7142): enabling receiver ResolveInfo{32a77b5e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/TimaKeyStoreProvider( 7193): TimaSignature is unavailable
,D/ActivityThread( 7193): Added TimaKeyStore provider
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Compatibility( 7142): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 7208): MountEmulatedStorage()
E/Zygote  ( 7208): v2
I/libpersona( 7208): KNOX_SDCARD checking this for 10160
I/libpersona( 7208): KNOX_SDCARD not a persona
I/SELinux ( 7208): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 7208): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 7208): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=7208 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,W/ResourcesManager( 6872): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6872): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/art     ( 7078): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ResourcesManager( 6872): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6872): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 7208): TimaSignature is unavailable
,D/ActivityThread( 7208): Added TimaKeyStore provider
E/Zygote  ( 7222): MountEmulatedStorage()
E/Zygote  ( 7222): v2
I/libpersona( 7222): KNOX_SDCARD checking this for 10003
I/libpersona( 7222): KNOX_SDCARD not a persona
I/SELinux ( 7222): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7222 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 7222): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 7222): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6872): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 7222): TimaSignature is unavailable
,D/ActivityThread( 7222): Added TimaKeyStore provider
,W/ResourcesManager( 6872): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/Zygote  ( 7234): MountEmulatedStorage()
W/ResourcesManager( 6872): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/Zygote  ( 7234): v2
I/libpersona( 7234): KNOX_SDCARD checking this for 10100
I/libpersona( 7234): KNOX_SDCARD not a persona
,I/SELinux ( 7234): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 7234): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 7234): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7234 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5921:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
I/ActivityManager( 1015): Killing 6167:com.android.calendar/u0a135 (adj 15): empty #32
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 6872): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6872): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 6200): (284) automatic index on crash_info_summary(package_name_touched)
,W/ResourcesManager( 6872): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 7234): TimaSignature is unavailable
D/ActivityThread( 7234): Added TimaKeyStore provider
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 7208): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/UsbSettingsManager( 1015): clearDefaults: com.test.thalitest
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/CrashAnrDetector( 1015): onPackageRemoved : com.test.thalitest
,D/BadgeProvider( 6429): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6429): sendNotify, [notify] : null
D/BadgeProvider( 6429): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6429): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6429): update, [UpdateCount] : 1
,W/libprocessgroup( 1015): failed to open /acct/uid_10025/pid_6447/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10134/pid_6396/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SPPClientService( 7193): ============PushLog. commonIsShipBuild. stop!
W/ResourcesManager( 6872): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
E/SPPClientService( 7193): [PushClientApplication] Push log off : This is Ship build version
W/ResourcesManager( 6872): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SPPClientService( 7193): PushLog.txt file is not deleted.
D/SPPClientService( 7193): PushLog.txt file is not deleted.
D/SPPClientService( 7193): ============PushLog. stop!
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,D/UserAnalysis.PlaceProvider( 7222): PlaceProvider onCreate()
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 6872): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 7257): MountEmulatedStorage()
E/Zygote  ( 7257): v2
I/libpersona( 7257): KNOX_SDCARD checking this for 10035
I/libpersona( 7257): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7257 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Killing 6530:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/SELinux ( 7257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7257): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6872): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6872): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/UserAnalysis.SecureDbManager( 7222): Key for secure DB is newly created
E/SQLiteLog( 6200): (10) unixWrite() File Descriptor : 36 gets errno : 9
,D/UserAnalysis.SecurePlaceDbHelper( 7222): SecurePlaceDbHelper() 
D/UserAnalysis( 7222): Create SecureDbHelper
,E/SQLiteDatabase( 6200): Error inserting name=status value=successfully initialized
E/SQLiteDatabase( 6200): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 6200): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6200): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6200): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6200): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6200): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6200): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6200): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6200): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6200): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:193)
E/SQLiteDatabase( 6200): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6200): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6200): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6200): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6200): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6200): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6200): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6200): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6200): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6200): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,D/TimaKeyStoreProvider( 7257): TimaSignature is unavailable
D/ActivityThread( 7257): Added TimaKeyStore provider
,E/Zygote  ( 7273): MountEmulatedStorage()
,E/Zygote  ( 7273): v2
I/libpersona( 7273): KNOX_SDCARD checking this for 1000
I/libpersona( 7273): KNOX_SDCARD not a persona
I/SELinux ( 7273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7273 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 6601:com.google.android.configupdater/u0a86 (adj 15): empty #31,
I/SELinux ( 7273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 7273): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/IntelligenceServiceApplication( 7222): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 7222): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,I/TLC_TIMA_PKM_initialize( 1015): initializing...
I/TLC_TIMA_PKM_initialize( 1015): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,I/ActivityManager( 1015): Killing 5132:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10135/pid_6167/cgroup.procs: No such file or directory
,E/SQLiteLog( 7222): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/SQLiteDatabase( 7222): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7222): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7222): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7222): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7222): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 7222): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 7222): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7222): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 7222): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7222): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7222): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7222): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteDatabase( 7222): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteDatabase( 7222): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7222): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7222): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7222): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 7222): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7222): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7222): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 7222): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 7222): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7222): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7222): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7222): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7222): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 7222): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 7222): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabas,e.java:699)
E/SQLiteOpenHelper( 7222): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 7222): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7222): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7222): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7222): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteOpenHelper( 7222): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteOpenHelper( 7222): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 7222): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 7222): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 7222): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 7222): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 7222): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 7222): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 7222): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/SQLiteOpenHelper( 7222): Opened privacy in read-only mode
,D/TimaKeyStoreProvider( 7273): TimaSignature is unavailable
,D/ActivityThread( 7273): Added TimaKeyStore provider
W/ResourcesManager( 6872): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/art     (  317): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 39.885ms
W/ResourcesManager( 6872): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/IntelligenceServiceApplication( 7222): no applications having user consent for prediction
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 7222): [PlaceDetection::stopService] Service stopped.
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 17.782ms
,W/ResourcesManager( 6872): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Launcher.Model( 1467): reloadBadges entered.
D/Launcher.Model( 1467): reloadBadges entered.
,I/UpdateIcingCorporaServi( 6555): UpdateCorporaTask done [took 371 ms] updated apps [took 371 ms] 
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 738us total 17.221ms
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 13,

```
