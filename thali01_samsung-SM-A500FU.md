#### Test 50650278c17c777_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Mms/DownloadManager( 5109): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5109): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5109): getSubId is called
D/Mms/TelephonyUtils( 5109): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5109): getTelephonyProperty is called
D/Mms/DownloadManager( 5109): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5109): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5109): auto download without roaming -> true
D/Mms/DownloadManager( 5109): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5109): mAutoDownload ------> true
--------- beginning of system
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/Mms/ArtClassLoader( 5109): init [DONE] art
E/Zygote  ( 5285): MountEmulatedStorage()
E/Zygote  ( 5285): v2
I/SELinux ( 5285): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/Mms/Synchronizer( 5109): [end]    doSync consume time = 20.472136
I/libpersona( 5285): KNOX_SDCARD checking this for 10072
I/libpersona( 5285): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5285 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/SELinux ( 5285): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5285): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/Mms/FreeMessageStatusReceiver( 5109): onReceive, action : android.intent.action.PACKAGE_ADDED
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
D/Mms/FreeMessageReceiverService( 5109): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5109): onHandleIntent: ACTION_PACKAGE_ADDED
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 5285): TimaSignature is unavailable
D/ActivityThread( 5285): Added TimaKeyStore provider
E/Zygote  ( 5301): MountEmulatedStorage()
E/Zygote  ( 5301): v2
I/SELinux ( 5301): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5301): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5301): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/libpersona( 5301): KNOX_SDCARD checking this for 10047
I/libpersona( 5301): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5301 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 4440:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/TimaKeyStoreProvider( 5301): TimaSignature is unavailable
D/ActivityThread( 5301): Added TimaKeyStore provider
D/BadgeProvider( 5285): onCreate
D/BadgeProvider( 5285): DatabaseHelper
W/ResourcesManager( 5301): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5301): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5301): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/Mms/MessagingNotification( 5109): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1439): query,matched:26, calling pid = 5109
D/TP/SmsProvider( 1439): match 26:Elapsed time : 1.596 ms
W/libprocessgroup( 1014): failed to open /acct/uid_10150/pid_4440/cgroup.procs: No such file or directory
D/TP/MmsSmsProvider( 1439): query,matched:6, calling pid = 5109
D/TP/MmsSmsProvider( 1439): match 6:Elapsed time : 1.681 ms
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5318): MountEmulatedStorage()
E/Zygote  ( 5318): v2
I/libpersona( 5318): KNOX_SDCARD checking this for 10025
I/libpersona( 5318): KNOX_SDCARD not a persona
I/SELinux ( 5318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5318 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/SELinux ( 5318): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SMD     (  288): DCD OFF
D/MyFiles ( 5301): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
E/installd(  284): system dir 0 : /system/app/
E/installd(  284): system dir 1 : /system/priv-app/
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
I/TactileAssist( 1014): enable value -1
I/TactileAssist( 1014): internal enable value -1
I/TactileAssist( 1014): intensity value -1
I/TactileAssist( 1014): saveAppList value true
I/TactileAssist( 1014): List of disabled apps :
D/TimaKeyStoreProvider( 5318): TimaSignature is unavailable
D/ActivityThread( 5318): Added TimaKeyStore provider
I/ActivityManager( 1014): Killing 3983:com.android.providers.calendar/u0a42 (adj 15): empty #31
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1014): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 5335): MountEmulatedStorage()
E/Zygote  ( 5335): v2
I/libpersona( 5335): KNOX_SDCARD checking this for 10053
I/libpersona( 5335): KNOX_SDCARD not a persona
I/SELinux ( 5335): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5335): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5335 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 5335): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 5318): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 5335): TimaSignature is unavailable
D/ActivityThread( 5335): Added TimaKeyStore provider
W/ResourcesManager( 5335): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/OMACP   ( 5318): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/Mms/Omacp( 5109): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/OMACP   ( 5318): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5318): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5318): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5318): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5318): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5318): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5318): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5318): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5318): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5318): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5318): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5318): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5318): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
W/libprocessgroup( 1014): failed to open /acct/uid_10042/pid_3983/cgroup.procs: No such file or directory
D/Compatibility( 5335): onReceive() it will make start service
D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 5335): onHandleIntent()
D/Compatibility( 5335): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
D/Compatibility( 5335): found: 2
I/UpdateIcingCorporaServi( 4780): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/Compatibility( 5335): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5335): skipping ResolveInfo{36dab597 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5335): considering ResolveInfo{83d8384 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5335): default: com.sec.android.app.soundalive.SAControlPanelActivity
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/Compatibility( 5335): enabling receiver ResolveInfo{3c5b676d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 5335): enabling receiver ResolveInfo{37bc6fa2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 5335): enabling receiver ResolveInfo{1e8b1433 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5335): enabling receiver ResolveInfo{33d153f0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5335): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1999): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1999): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1999): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/UpdateIcingCorporaServi( 4780): UpdateCorporaTask done [took 92 ms] updated apps [took 92 ms] 
D/AsyncTaskServiceImpl( 1999): Submit a task: k
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1014): Killing 4476:com.google.android.gm/u0a101 (adj 15): empty #31
D/ChimeraCfgMgr( 1999): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ChimeraCfgMgr( 1999): Loading module com.google.android.gms.vision from APK com.google.android.gms
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/k       ( 1999): Processing package: com.test.thalitest
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SL_DEBUG( 5259): isLoggable:: isProductShip = 1
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SL_DEBUG( 5259): isLoggable:: SL_DEBUG_EXIST = false
D/GassUtils( 1999): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 1999): Found info for package com.test.thalitest in db.
W/BaseAppContext( 1999): Using Auth Proxy for data requests.
W/BaseAppContext( 1999): Using Auth Proxy for data requests.
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/PeopleDatabaseHelper( 1999): cleanUpNonGplusAccounts done.
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1014): failed to open /acct/uid_10101/pid_4476/cgroup.procs: No such file or directory
W/BaseAppContext( 1999): Using Auth Proxy for data requests.
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 1999): Using Auth Proxy for data requests.
W/BaseAppContext( 1999): Using Auth Proxy for data requests.
W/BaseAppContext( 1999): Using Auth Proxy for data requests.
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5259): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5259): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/art     ( 5192): Suspending all threads took: 5.194ms
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5378): MountEmulatedStorage()
E/Zygote  ( 5378): v2
I/libpersona( 5378): KNOX_SDCARD checking this for 10041
I/libpersona( 5378): KNOX_SDCARD not a persona
I/SELinux ( 5378): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5378): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5378 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5378): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5378): TimaSignature is unavailable
D/ActivityThread( 5378): Added TimaKeyStore provider
I/SA      ( 5378): [SSP] onCreated
I/ActivityManager( 1014): Killing 4344:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
I/SA      ( 5378): [TPM] There is no property file
I/SA      ( 5378): [SCU] isHaveSA() - false
I/SA      ( 5378): [TPM] getModelProperty : null
I/SA      ( 5378): [TPM] getCSCProperty : null
I/SA      ( 5378): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5378): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5378): [DM] TFT FEATURE: false
I/SA      ( 5378): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5378): [DM] init START
W/GAV2    ( 5192): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SA      ( 5378): [DM] This device is not a Vodafone
W/ResourceType( 5378): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 5378): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 5378): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5378): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 5378): [SCU] isHaveSA() - false
I/SA      ( 5378): support phone number id : false
I/SA      ( 5378): [DM] Supports Ref Jpn : true
I/SA      ( 5378): [DM] init END
I/SA      ( 5378): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 5378): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
I/ActivityManager( 1014): Killing 4247:com.google.android.music:main/u0a111 (adj 15): empty #31
W/libprocessgroup( 1014): failed to open /acct/uid_10040/pid_4344/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10111/pid_4247/cgroup.procs: No such file or directory
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5409): MountEmulatedStorage()
E/Zygote  ( 5409): v2
I/libpersona( 5409): KNOX_SDCARD checking this for 10100
I/libpersona( 5409): KNOX_SDCARD not a persona
I/SELinux ( 5409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5409): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5409 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 4618:com.google.android.talk/u0a104 (adj 15): empty #31
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5192): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/TimaKeyStoreProvider( 5409): TimaSignature is unavailable
D/ActivityThread( 5409): Added TimaKeyStore provider
W/AccountFeatureHelper( 5192): Write apps_features disabled false
D/PackageIntentReceiver( 5409): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5409): Not GearManger package! 
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1014): failed to open /acct/uid_10104/pid_4618/cgroup.procs: No such file or directory
E/Zygote  ( 5429): MountEmulatedStorage()
E/Zygote  ( 5429): v2
I/libpersona( 5429): KNOX_SDCARD checking this for 1000
I/libpersona( 5429): KNOX_SDCARD not a persona
I/SELinux ( 5429): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5429 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5429): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5429): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5429): TimaSignature is unavailable
D/ActivityThread( 5429): Added TimaKeyStore provider
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5444): MountEmulatedStorage()
E/Zygote  ( 5444): v2
I/libpersona( 5444): KNOX_SDCARD checking this for 1000
I/libpersona( 5444): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5444 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 4844:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/SELinux ( 5444): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5444): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5444): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ChimeraCfgMgr( 1999): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1999): Module APK com.google.android.play.games already loaded
D/TimaKeyStoreProvider( 5444): TimaSignature is unavailable
D/ActivityThread( 5444): Added TimaKeyStore provider
D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/AcmsPackageEventListener( 5444): Received: android.intent.action.PACKAGE_ADDED
W/ContextImpl( 5444): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
W/libprocessgroup( 1014): failed to open /acct/uid_10069/pid_4844/cgroup.procs: No such file or directory
W/GAV2    ( 5192): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 220919(14MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/40MB, paused 2.621ms total 189.587ms
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/AcmsService( 5444): Enter Oncreate
D/AcmsServiceMonitor( 5444): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5444): creating AcmsCore
D/AcmsCore( 5444): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5444): AcmsCore
D/AcmsCore( 5444): init
D/AcmsCore( 5444): Looper handler is not null
D/AcmsCore( 5444): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5444): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5444): Incrementing - Counter value: 1
D/AcmsCore( 5444): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 5444): onStartCommand
D/AcmsService( 5444): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5444): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5444): Incrementing - Counter value: 2
D/AcmsService( 5444): Incremented Counter Value : onStartCommand
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/AcmsCertificateMngr( 5444): AcmsCertificateMngr
D/ActivityThread( 5444): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/AcmsRevocationMngr( 5444): AcmsRevocationMngr
I/Icing   ( 1999): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
D/AcmsService( 5444): Inside handle Intent
D/AcmsService( 5444): App added - package name: com.test.thalitest
D/AcmsCore( 5444): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5444): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5444): Incrementing - Counter value: 3
D/AcmsCore( 5444): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5444): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5444): Decrementing - Counter value: 2
I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 1014): Killing 4877:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/Icing   ( 1999): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 5465): 
D/AndroidRuntime( 5465): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5465): CheckJNI is OFF
D/AndroidRuntime( 5465): readGMSProperty: start
D/AndroidRuntime( 5465): readGMSProperty: already setted!!
D/AndroidRuntime( 5465): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5465): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5465): readGMSProperty: end
D/AndroidRuntime( 5465): addProductProperty: start
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4877/cgroup.procs: No such file or directory
I/Mms/MmsApp( 5109):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5109): [start]    fillCache consume time = 1966.909739
D/Mms/ComposeMessageFragment( 5109): fillCache, easy = false
E/AffinityControl( 5465): AffinityControl: registerfunction enter
D/AndroidRuntime( 5465): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/AbsListView( 5109): Get MotionRecognitionManager
D/MotionRecognitionService( 1014):  ssp status : false
D/Mms/ComposeMessageFragment( 5109): [end]    fillCache consume time = 80.370885
W/ActivityManager( 1014): mDVFSHelper.acquire()
I/SurfaceFlinger(  258): id=9 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  258): id=10 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1014): Set to : 0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1014): *FMB* installDecor flags : 25362712
E/Zygote  ( 5479): MountEmulatedStorage()
E/Zygote  ( 5479): v2
I/libpersona( 5479): KNOX_SDCARD checking this for 10175
I/SELinux ( 5479): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5479): KNOX_SDCARD not a persona
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 5479): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5479): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, uhalitest
I/ActivityManager( 1014): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5479 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/art     (  303): Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 19.942ms
D/TimaKeyStoreProvider( 5479): TimaSignature is unavailable
D/InputDispatcher( 1014): Focused application set to: xxxx
D/ActivityThread( 5479): Added TimaKeyStore provider
D/InputDispatcher( 1014): Focus left window: 1468
D/AndroidRuntime( 5465): Shutting down VM
V/WindowManager( 1014): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
V/ActivityManager( 1014): Display changed displayId=0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 31.131ms
D/PersonaManager( 1014): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 18.598ms
I/ActivityManager( 1014): Killing 4975:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
I/SurfaceFlinger(  258): id=6 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=6 Removed Mauncher (-2/9)
V/ActivityThread( 1468): updateVisibility : ActivityRecord{2dda30a token=android.os.BinderProxy@39d73192 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1468): onTrimMemory. Level: 20
D/Mms/BubbleViewCache( 5109): fillCache bubble = 1
I/WebViewFactory( 5479): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
W/libprocessgroup( 1014): failed to open /acct/uid_10142/pid_4975/cgroup.procs: No such file or directory
I/LibraryLoader( 5479): Time to load native libraries: 1 ms (timestamps 7811-7812)
I/LibraryLoader( 5479): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5479): Binding Chromium to main looper Looper (main, tid 1) {3c5b676d}
I/LibraryLoader( 5479): Expected native library version number "",actual native library version number ""
I/chromium( 5479): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 5465): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/BrowserStartupController( 5479): Initializing chromium process, singleProcess=true
,W/art     ( 5479): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5479): ApplicationContext is null in ApplicationStatus
,W/chromium( 5479): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,W/chromium( 5479): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 5479): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 5479): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
I/Adreno-EGL( 5479): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5479): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5479): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5479): Local Branch: 
I/Adreno-EGL( 5479): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5479): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5479):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5479): 1058399214: getState() :  mService = null. Returning STATE_OFF
,W/chromium( 5479): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/art     ( 5479): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5479): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5479): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5479): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5479): CordovaWebView is running on device made by: samsung
,W/art     ( 5479): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5479): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5479): Render dirty regions requested: true
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/PhoneWindow( 5479): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5479): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1014): Focus entered window: 5479
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5479): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5479): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5479): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5479): Enabling debug mode 0
,V/ActivityThread( 5479): updateVisibility : ActivityRecord{2139249e token=android.os.BinderProxy@32999920 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1014): Displayed Component not be shown by security: +562ms (total +657ms)
,W/ActivityManager( 1014): mDVFSHelper.release()
I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{228ca4f3 u0 com.test.thalitest/.MainActivity t2} time:88229
,I/SurfaceFlinger(  258): id=11 Removed uhalitest (7/9)
,I/SurfaceFlinger(  258): id=11 Removed uhalitest (-2/9)
,I/SamsungIME( 1777): getCurrentCandidateView
,W/IInputConnectionWrapper( 5479): showStatusIcon on inactive InputConnection
,I/Timeline( 5479): Timeline: Activity_idle id: android.os.BinderProxy@32999920 time:88240
,D/SamsungIME( 1777): Dismiss ExpandCandiate
,W/BindingManager( 5479): Cannot call determinedVisibility() - never saw a connection for the pid: 5479
,I/SamsungIME( 1777): getDebugLevel  : 0x4f4c
,D/JsMessageQueue( 5479): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1777): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1777): KeybaordView init() : load resources
,I/SamsungIME( 1777): getCurrentKeyboard
I/SamsungIME( 1777): getTextKeyboard
,D/SamsungIME( 1777): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 5479): JniHelper::setJavaVM(0xb787f450), pthread_self() = -1210286584
,D/JX-Cordova( 5479): jxcore cordova android initializing
,E/SMD     (  288): DCD OFF
,D/SamsungIME( 1777): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/jxcore-log( 5479): Initializing JXcore engine
W/jxcore-log( 5479): JXcore engine is ready
,W/jxcore-log( 5479): Starting JXcore engine
,E/audit   ( 1880): type=1400 msg=audit(1449746249.141:203): avc:  denied  { ioctl } for  pid=5479 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1880):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1880): type=1300 msg=audit(1449746249.141:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=bea46d58 items=0 ppid=303 ppcomm=main pid=5479 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1880): type=1320 msg=audit(1449746249.141:203): 
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AcmsKeyStoreHelper( 5444):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5444): Key Store exist
I/AcmsKeyStoreHelper( 5444): Hence loading the keystore file
,W/jxcore-log( 5479): Platform android
W/jxcore-log( 5479): 
,W/jxcore-log( 5479): Process ARCH arm
W/jxcore-log( 5479): 
,D/AcmsKeyStoreHelper( 5444):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5444): getKeyStoreForApplication success 
D/AcmsCore( 5444): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5444): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5444): Decrementing - Counter value: 1
D/AcmsCore( 5444): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5444): This is NOT a valid MirrorLink app
D/AcmsCore( 5444): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5444): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5444): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5444): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5444): getSvcCounter - Counter value: 0
,D/AcmsService( 5444): Enter onDestroy
,I/AcmsService( 5444): cleanUp(): inside service clean up
,D/AcmsCore( 5444): AcmsCore: inside DeInit
D/AcmsCore( 5444): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5444): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5444): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5444): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5444): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5444): getSvcCounter - Counter value: 0
D/AcmsService( 5444): killing acms process
I/Process ( 5444): Sending signal. PID: 5444 SIG: 9
,I/ActivityManager( 1014): Process ACMS.Process (pid 5444)(adj 0) has died(64,1171)
,I/jxcore-log( 5479): JXcore Cordova bridge is ready!
I/jxcore-log( 5479): 
,W/jxcore-log( 5479): JXcore engine is started
,I/chromium( 5479): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 5479): Skipped 130 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 5479): Toggling radios to true
I/jxcore-log( 5479): 
,D/BluetoothAdapter( 5479): enable()
,W/ActivityManager( 1014): Permission Denial: getCurrentUser() from pid=5479, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 1014): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 1014): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5479, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 1014): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/BluetoothManagerService( 1014): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
W/BluetoothManagerService( 1014): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
W/BluetoothManagerService( 1014): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/BluetoothManagerService( 1014): 	at android.os.Binder.execTransact(Binder.java:461)
,E/DevicePolicyManagerService( 1014): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1014): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 1014): name = bluetooth_on
,E/DevicePolicyManagerService( 1014): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1014): getAllowBluetoothMode - value retunrs : 2
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider( 1014): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1014): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1014): mCursor = null
,D/WifiService( 1014): setWifiEnabled: true pid=5479, uid=10175
,E/Zygote  ( 5531): MountEmulatedStorage()
I/libpersona( 5531): KNOX_SDCARD checking this for 1002
E/Zygote  ( 5531): v2
I/libpersona( 5531): KNOX_SDCARD not a persona
W/ActivityManager( 1014): Permission Denial: getCurrentUser() from pid=5479, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5531): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/WifiService( 1014): Failed getting userId using ActivityManagerNative
W/WifiService( 1014): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5479, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1014): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1014): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1014): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
,W/WifiService( 1014): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1014): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1014): name = wifi_on
,I/ActivityManager( 1014): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5531 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/SELinux ( 5531): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/WifiHW  ( 1014): ##################### set firmware type 0 #####################
I/WifiService( 1014): disconnect: pid=5479, uid=10175
I/jxcore-log( 5479): Radios toggled
I/jxcore-log( 5479): 
,E/SELinux ( 5531): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5531): TimaSignature is unavailable
,D/ActivityThread( 5531): Added TimaKeyStore provider
,W/ResourcesManager( 5531): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.,
W/ResourcesManager( 5531): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni( 5531): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 5531): Adding GattService
,D/BtSettings.ProfileConfig( 5531): Adding HeadsetService
,D/BtSettings.ProfileConfig( 5531): Adding A2dpService
,D/BtSettings.ProfileConfig( 5531): Adding HidService
,D/BtSettings.ProfileConfig( 5531): Adding HealthService
,D/BtSettings.ProfileConfig( 5531): Adding PanService
,D/BtSettings.ProfileConfig( 5531): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 5531): Adding SapService
,D/BtSettings.ProfileConfig( 5531): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 5531): Adding A2dpSinkService
,D/BtSettings.ProfileConfig( 5531): Adding SapClientService
,D/BtSettings.ProfileConfig( 5531): Adding HidDevService
,I/BtSettings.ProfileConfig( 5531): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService,
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002,
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1014): name = bt_svcst_com.broadcom.bt.service.sap.SapService
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
,D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
,D/SettingsProvider( 1014): selectionArgs: 1002
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.hid.HidDevService
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
,D/SettingsProvider( 1014): selectionArgs: 1002
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/BluetoothAdapterState( 5531): make
,I/bluedroid( 5531): init
,I/BluetoothAdapterState( 5531): Entering OffState
,I/bte_conf( 5531): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5531): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5531): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,I/bte_conf( 5531): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 5531): btif_fetch_local_ble_random_bdaddr,
I/bluedroid( 5531): get_profile_interface socket
,I/bluedroid( 5531): get_profile_interface map_client
,D/BluetoothAdapterService( 5531): checkAddrForIOP: Loading from conf
,I/GKI_LINUX( 5531): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothA2dp( 5531): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1014): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
D/BluetoothAdapterProperties( 5531): Address is:7C:F9:0E:37:96:AB
E/BluetoothServiceJni( 5531): populateRssiValuesNative
I/bluedroid( 5531): getModelRssiValues
E/BluetoothServiceJni( 5531): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5531): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/SettingsProvider( 1014): name = bluetooth_name
,D/BluetoothAdapterProperties( 5531): Name is: A5-1
,I/bluedroid( 5531): config_hci_snoop_log
,D/BluetoothManagerService( 1014): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothManagerService( 1014): Ble is always on enable gatt
,I/BluetoothManagerService( 1014): enableGattForLeMode, doBind called
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,E/DevicePolicyManagerService( 1014): getAllowBluetoothMode - value retunrs : 2
,I/BtGatt.JNI( 5531): classInitNative(L900): classInitNative: Success!
,E/DevicePolicyManagerService( 1014): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 1014): uri = 3 selection = isBluetoothEnabled
,D/BluetoothManagerService( 1014): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/BluetoothAdapterState( 5531): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 5531): Setting state to 11
I/BluetoothAdapterState( 5531): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5531): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5531): updateAdapterState state is 11
,D/BluetoothAdapterService( 5531): Autoconnection is available 
,D/BluetoothAdapterService( 5531): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager( 5531): getInstant: null
D/BluetoothSecureManager( 5531): calling getMethod for getService
,D/BluetoothSecureManager( 5531): calling getService
,W/InputMethodManagerService( 1014): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothSecureManager( 5531): getService return binder: android.os.BinderProxy@1d4700a1
,D/BluetoothSecureManagerService( 1014): isSecureModeEnabled
I/InputMethodManagerService( 1014): [BT Setting State] State =11,
D/BluetoothSecureManagerService( 1014): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 5531): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5531): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5531): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5531): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5531): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5531): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
W/BluetoothAdapterService( 5531): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5531): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BluetoothTile( 1174): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothTile( 1174):  getBluetoothState : 11
,W/BluetoothAdapterService( 5531): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5531): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5531): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5531): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5531): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/StatusBarManagerService( 1014): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,I/SamsungIME( 1777): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/StatusBarManagerService( 1014): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1174): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/STATUSBAR-QSTileView( 1174): onStateChanged: Bluetooth
,D/BluetoothNotiBroadcastReceiver( 1281): onReceive
,D/BluetoothBondStateMachine( 5531): make
,V/BluetoothStatusReceiver( 1174): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1174): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/BluetoothAdapterService( 5531): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5531): Not skipping com.android.bluetooth.gatt.GattService
,I/BluetoothBondStateMachine( 5531): StableState(): Entering Off State
,E/Zygote  ( 5571): MountEmulatedStorage(),
E/Zygote  ( 5571): v2
I/libpersona( 5571): KNOX_SDCARD checking this for 10003
I/libpersona( 5571): KNOX_SDCARD not a persona
,I/SELinux ( 5571): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5571): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5571): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5571 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5531): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5531): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 5531): handleDebugAction() action=null
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,D/BtGatt.GattService( 5531): Received start request. Starting profile...
D/BtGatt.GattService( 5531): start()
D/BtGatt.GattService( 5531): start()
I/bluedroid( 5531): get_profile_interface gatt
,D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
,D/BtGatt.AdvertiseManager( 5531): advertise manager created
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5531): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5531): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5531): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5531): Not skipping com.android.bluetooth.hid.HidService
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,D/BtGatt.GattService( 5531): mStartError = false
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/TimaKeyStoreProvider( 5571): TimaSignature is unavailable
,W/BluetoothAdapterService( 5531): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5531): Not skipping com.android.bluetooth.hdp.HealthService
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
D/HeadsetService( 5531): Received start request. Starting profile...
D/HeadsetService( 5531): start()
,I/BluetoothHeadsetServiceJni( 5531): classInitNative: succeeds
D/ActivityThread( 5571): Added TimaKeyStore provider
D/Tethering( 1014): interfaceAdded wlan0
D/HeadsetStateMachine( 5531): make
,E/HeadsetStateMachine( 5531): # of Max HF connection is 2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
,W/BluetoothAdapterService( 5531): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,D/Tethering( 1014): interfaceStatusChanged wlan0, false
,W/BluetoothAdapterService( 5531): Not skipping com.android.bluetooth.pan.PanService
I/WifiHW  (  278): wifi_change_fw_path(): fwpath = sta
,D/SoftapController(  278): Softap fwReload - Ok
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/Tethering( 1014): No numeric data
,D/ActivityManager( 1014): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/BluetoothAdapterService( 5531): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5531): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,D/Tethering( 1014): interfaceAdded p2p0
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
D/CommandListener(  278): Setting iface cfg
D/CommandListener(  278): Trying to bring down wlan0
D/Tethering( 1014): p2p0 is not a tetherable iface, ignoring
,D/Tethering( 1014): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged p2p0, false
D/Tethering( 1014): interfaceStatusChanged p2p0, false
D/Tethering( 1014): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1014): clearTetheredNotification()
,D/CommandListener(  278): Clearing all IP addresses on wlan0
D/Tethering( 1014): InitialState.processMessage what=4
,E/Tethering( 1014): No numeric data
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,D/EnterpriseController(  278): uids 1000
D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/HotspotTile( 1174): updateTetherState():false, false
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  278): uids 1000,
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1014): forceRefresh Fail.
,V/NetworkStats( 1014): performPollLocked(flags=0x1)
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,V/NetworkStats( 1014): performPollLocked() took 2ms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5531): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5531): Not skipping com.broadcom.bt.service.sap.SapService
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1014): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
W/BluetoothAdapterService( 5531): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5531): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
W/BluetoothAdapterService( 5531): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5531): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5531): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5531): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5531): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5531): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 5531): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/bluedroid( 5531): get_profile_interface handsfree
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,D/Tethering( 1014): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1014): clearTetheredNotification()
,D/NtpTrustedTime( 1014): forceRefresh Fail.
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
V/NetworkStats( 1014): performPollLocked(flags=0x1)
D/UserAnalysis.PlaceProvider( 5571): PlaceProvider onCreate()
D/NtpTrustedTime( 1014): forceRefresh Fail.
D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1174): updateTetherState():false, false
,V/NetworkStats( 1014): performPollLocked() took 4ms
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,D/NtpTrustedTime( 1014): forceRefresh Fail.
,I/DualScoManager( 5531): Instantiating Dual Sco Manager
,I/DualScoManager( 5531): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 5531): createCMTIContentObservers
,D/SettingsProvider( 1014): name = bluetooth_hfp_allowed_bvra
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 5531): Enter Disconnected: -2
D/HeadsetService( 5531): mStartError = false
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
,D/UserAnalysis.SecureDbManager( 5571): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5571): SecurePlaceDbHelper() 
D/BluetoothA2dp( 1014): Proxy object connected
D/UserAnalysis( 5571): Create SecureDbHelper
,D/A2dpService( 5531): Received start request. Starting profile...
,D/A2dpService( 5531): start()
D/BluetoothA2dp( 2689): Proxy object connected
,D/HeadsetStateMachine( 5531): Clear mHeadsetBrsf
,D/HeadsetStateMachine( 5531): map size, before remove : 0
,D/HeadsetStateMachine( 5531): map size, after remove: 0
,I/BluetoothAvrcpServiceJni( 5531): classInitNative: succeeds
,I/bluedroid( 5531): get_profile_interface avrcp
,D/IntelligenceServiceApplication( 5571): onCreate()
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/ActivityManager( 1014): Killing 5011:com.google.android.gms:car/u0a12 (adj 15): empty #31
,E/RemoteController( 5531): Cannot set synchronization mode on an unregistered RemoteController
,D/IntelligenceServiceApplication( 5571): no applications having user consent for prediction
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 5571): [PlaceDetection::stopService] Service stopped.
,I/Avrcp   ( 5531):  Updating now playing list upon AVRCP Start
,V/PlaceDetection v1.0.19 ( 5571): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,I/BluetoothA2dpServiceJni( 5531): classInitNative: succeeds
D/A2dpStateMachine( 5531): make
,I/bluedroid( 5531): get_profile_interface a2dp
,I/GKI_LINUX( 5531): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 5531): warning : media task started media_task_refcnt 1 
E/WifiHW  ( 1014): supplicant_name : p2p_supplicant
,D/WifiMonitor( 1014): startMonitoring(wlan0) with mConnected = false
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/A2dpService( 5531): mStartError = false
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/BluetoothMediaBrowser( 5531):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,D/A2dpStateMachine( 5531): Enter Disconnected: -2
,E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,I/BluetoothHidServiceJni( 5531): classInitNative: succeeds
D/STATUSBAR-WifiQuickSettingButton( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1174): Wifi onReceive(2)
,D/HotspotTile( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1174): onStateChanged: Wi-Fi
,D/WifiCredService( 1281): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1174): onReceive : 2, 0
,D/BluetoothMediaBrowser( 5531): no now playing list
D/BluetoothMediaBrowser( 5531):  getNowPlayingId now playing id : -1
,D/HidService( 5531): Received start request. Starting profile...
D/HidService( 5531): start()
I/bluedroid( 5531): get_profile_interface hidhost
D/HidService( 5531): setHidService(): set to: null
D/HidService( 5531): mStartError = false
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
,I/BluetoothHealthServiceJni( 5531): classInitNative: succeeds
,D/HealthService( 5531): Received start request. Starting profile...
,D/HealthService( 5531): start()
,I/bluedroid( 5531): get_profile_interface health,
D/HealthService( 5531): mStartError = false
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
,I/BluetoothPanServiceJni( 5531): classInitNative(L105): succeeds
,D/BluetoothPan( 1014): BluetoothPAN Proxy object connected
,D/PanService( 5531): Received start request. Starting profile...
D/PanService( 5531): start()
D/BluetoothPanServiceJni( 5531): initializeNative(L110): pan
I/bluedroid( 5531): get_profile_interface pan
,I/wpa_supplicant( 5596): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 5596): Successfully initialized wpa_supplicant
,I/SecureStorage( 5596): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,D/PanService( 5531): mStartError = false
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
,D/HeadsetStateMachine( 5531): Try to query the phonestate on bind
,I/Telecom ( 1419): BluetoothPhoneService: queryPhoneState
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
I/Telecom ( 1419): BluetoothPhoneService: handleMessage(7) / param 0
I/Telecom ( 1419): BluetoothPhoneService: updateHeadsetWithCallState
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,I/SecureStorage( 5596): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/Telecom ( 1419): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/SecureStorage(  353): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5596
I/Telecom ( 1419): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/SecureStorage(  353): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5596): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 5596): ssSupport state is = 1
I/wpa_supplicant( 5596): >>>>> GET KEY, IV <<<<<
I/SecureStorage( 5596): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  353): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5596
I/SecureStorage(  353): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,I/Telecom ( 1419): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1419): Proxy not attached to service
,I/Telecom ( 1419): BluetoothPhoneService: Result of Message : true
,D/BluetoothMapService( 5531): Received start request. Starting profile...,
D/BluetoothMapService( 5531): start()
,W/libprocessgroup( 1014): failed to open /acct/uid_10012/pid_5011/cgroup.procs: No such file or directory
D/BluetoothMapService( 5531): mStartError = false
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
,I/BluetoothSAPServiceJni( 5531): classInitNative(L204): succeeds
,D/SapService( 5531): Received start request. Starting profile...
,D/SapService( 5531): start()
D/BluetoothSAPServiceJni( 5531): initializeNative(L209): sap
I/bluedroid( 5531): get_profile_interface sap
D/SapService( 5531): mStartError = false
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
D/HeadsetStateMachine( 5531): Proxy object connected
,D/HeadsetPhoneState( 5531): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 5531): sendDeviceDataStateChanged
,D/HeadsetPhoneState( 5531): Signal level : previous=0 curr=0
D/HeadsetStateMachine( 5531): Disconnected process message: 11
E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5531): Disconnected process message: 18
D/HeadsetStateMachine( 5531): Disconnected process message: 10
D/BluetoothA2dp( 5531): Proxy object connected
D/BluetoothAdapterService( 5531): Bluetooth A2dp source service connected
,D/HeadsetPhoneState( 5531): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5531): Disconnected process message: 11
E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5603): MountEmulatedStorage(),
I/ActivityManager( 1014): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=5603 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/Zygote  ( 5603): v2
I/libpersona( 5603): KNOX_SDCARD checking this for 10107,
I/libpersona( 5603): KNOX_SDCARD not a persona
,I/SELinux ( 5603): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,I/SELinux ( 5603): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5603): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5614): MountEmulatedStorage(),
I/libpersona( 5614): KNOX_SDCARD checking this for 10145
E/Zygote  ( 5614): v2
I/libpersona( 5614): KNOX_SDCARD not a persona
,I/SELinux ( 5614): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5614 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 5614): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5614): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5603): TimaSignature is unavailable
,D/ActivityThread( 5603): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 5614): TimaSignature is unavailable
,D/ActivityThread( 5614): Added TimaKeyStore provider
,E/SMD     (  288): DCD OFF
,W/ResourcesManager( 5614): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
W/ResourcesManager( 5614): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5614): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.,
W/ResourcesManager( 5614): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5614): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SecureStorage(  353): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,I/SecureStorage( 5596): [INFO]: SPID(0x00000002)Processing data has been completed,
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/wpa_supplicant( 5596): Ctrl_iface: loading cred from phone
,I/SecureStorage( 5596): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,I/SecureStorage( 5596): [INFO]: SPID(0x00000002)This device supports Secure Storage
,I/SecureStorage(  353): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5596
I/SecureStorage(  353): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 5596): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5596): ssSupport state is = 1
,I/wpa_supplicant( 5596): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5596): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5596): SIM READ ERROR
I/wpa_supplicant( 5596): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5596): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5596): SIM READ ERROR
I/wpa_supplicant( 5596): Blacklist: Clear (all) 
,I/wpa_supplicant( 5596): wpa_default_ap_write_once
I/wpa_supplicant( 5596): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5596): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5596): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 5596): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5596): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant( 5596): rfkill: Cannot open RFKILL control device
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,I/ActivityManager( 1014): Killing 4764:com.samsung.aasaservice/1000 (adj 15): empty #31
,D/BluetoothAdapterState( 5531): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5531): enable
,I/bt_hci_bdroid( 5531): init
,D/BadgeProvider( 5285): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/GKI_LINUX( 5531): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor( 5531): bt-vendor : init
I/bt_vendor( 5531): bt-vendor : get_bt_soc_type
E/bt_vendor( 5531): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 5531): init: Local BD Address : ab:96:37:0e:f9:7c
D/bt_userial_mct( 5531): userial_init
,I/bt_vendor( 5531): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 5531): Starting hciattach daemon
I/bt_vendor( 5531): try to set false
,I/bt_vendor( 5531): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 5531): Starting hciattach daemon
I/bt_vendor( 5531): try to set true
,I/wpa_supplicant( 5596): wlan0: Setting scan request: 0 sec 100000 usec
,I/qcom-bluetooth( 5649): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/Launcher.Model( 1468): reloadBadges entered.
,D/BadgeProvider( 5285): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5285): sendNotify, [notify] : null
D/BadgeProvider( 5285): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5285): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5285): update, [UpdateCount] : 1
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/qcom-bluetooth( 5658): /system/etc/init.qcom.bt.sh: Transport : smd ,
,I/qcom-bluetooth( 5659): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,I/qcom-bluetooth( 5662): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4764/cgroup.procs: No such file or directory
,I/qcom-bluetooth( 5663): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,I/wpa_supplicant( 5596): wlan0: State: DISCONNECTED -> DISCONNECTED,
,I/qcom-bluetooth( 5664): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/SecureStorage( 5596): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,I/qcom-bluetooth( 5665): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/SecureStorage( 5596): [INFO]: SPID(0x00000002)This device supports Secure Storage,
I/SecureStorage(  353): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5596
I/SecureStorage(  353): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,I/SecureStorage( 5596): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5596): ssSupport state is = 1
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/wpa_supplicant( 5596): Ctrl_iface: loading cred from phone
I/SecureStorage( 5596): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,I/SecureStorage( 5596): [INFO]: SPID(0x00000002)This device supports Secure Storage
,I/SecureStorage(  353): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5596
I/SecureStorage(  353): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 5596): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5596): ssSupport state is = 1
I/wpa_supplicant( 5596): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5596): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5596): SIM READ ERROR
I/wpa_supplicant( 5596): wpa_default_ap_write_once
I/wpa_supplicant( 5596): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5596): rfkill: Cannot open RFKILL control device
I/Nat464Xlat( 1014): interfaceLinkStateChanged p2p0, false
D/Tethering( 1014): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1014): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1014): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1014): interfaceLinkStateChanged p2p0, false
D/Tethering( 1014): interfaceStatusChanged p2p0, false
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/StrictMode( 5603): StrictMode policy violation; ~duration=404 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5603): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5603): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5603): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 5603): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 5603): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 5603): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 5603): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 5603): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 5603): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5603): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5603): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5603): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5603): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5603): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5603): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5603): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5603): StrictMode policy violation; ~duration=397 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5603): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5603): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5603): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 5603): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 5603): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 5603): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 5603): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5603): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5603): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5603): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5603): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5603): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5603): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5603): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5603): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5603): StrictMode policy violation; ~duration=311 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5603): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5603): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5603): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5603): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5603): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 5603): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 5603): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 5603): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5603): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5603): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5603): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5603): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5603): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5603): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5603): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5603): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5603): StrictMode policy violation; ~duration=310 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5603): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5603): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5603): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 5603): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 5603): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 5603): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5603): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5603): 	at android.app.Instrumentation.callApplicationOnCreate(Instrume,ntation.java:1020)
D/StrictMode( 5603): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5603): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5603): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5603): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5603): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5603): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5603): StrictMode policy violation; ~duration=309 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5603): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5603): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 5603): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 5603): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 5603): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 5603): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5603): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5603): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5603): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5603): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5603): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5603): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5603): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5603): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5603): StrictMode policy violation; ~duration=301 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5603): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5603): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 5603): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 5603): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 5603): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 5603): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 5603): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 5603): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 5603): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 5603): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 5603): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 5603): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 5603): 	at com.google.r.e.b(PG:170)
D/StrictMode( 5603): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5603): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5603): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5603): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5603): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5603): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5603): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5603): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5603): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5603): StrictMode policy violation; ~duration=298 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5603): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5603): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 5603): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 5603): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 5603): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 5603): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 5603): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 5603): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 5603): 	at com.google.r.k.c(PG:583)
D/StrictMode( 5603): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 5603): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 5603): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 5603): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 5603): 	at com.google.r.e.b(PG:170)
D/StrictMode( 5603): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5603): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5603): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5603): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5603): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5603): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5603): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5603): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5603): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5603): StrictMode policy violation; ~duration=250 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5603): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5603): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5603): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5603): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5603): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 5603): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 5603): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 5603): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 5603): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5603): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5603): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5603): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5603): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5603): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5603): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5603): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5603): StrictMode policy violation; ~duration=249 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5603): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5603): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5603): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5603): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 5603): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5603): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5603): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5603): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5603): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5603): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5603): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5603): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5603): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5603): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5603): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/ActivityManager( 1014): Killing 4360:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
D/AuthorizationBluetoothService( 1789): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/wpa_supplicant( 5596): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 5596): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3452): Starting #2
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
I/Hs20UtilService( 3452): Message received 5011
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5673): MountEmulatedStorage()
I/ActivityManager( 1014): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5673 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 5673): v2
I/libpersona( 5673): KNOX_SDCARD checking this for 1000
I/libpersona( 5673): KNOX_SDCARD not a persona
I/SELinux ( 5673): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5673): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5673): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/wpa_supplicant( 5596): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 5596): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5596): Skip scan - bUseNetwork false
,E/WifiStateMachine( 1014): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-wlan0( 1014): callSECApiBoolean - ID [21]
I/wpa_supplicant( 5596): HOTSPOT20_ENABLE called
I/wpa_supplicant( 5596): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5596): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5596): SIM READ ERROR
I/wpa_supplicant( 5596): Blacklist: Clear (all) 
,D/TimaKeyStoreProvider( 5673): TimaSignature is unavailable
,D/ActivityThread( 5673): Added TimaKeyStore provider
,I/wpa_supplicant( 5596): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 5596): Skip scan - bUseNetwork false,
,I/qcom-bluetooth( 5689): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,I/qcom-bluetooth( 5690): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,W/ProcessCpuTracker( 1014): Skipping unknown process pid 5667
,W/ProcessCpuTracker( 1014): Skipping unknown process pid 5669
,I/bt_vendor( 5531): bluetooth satus is on,
,D/bt_userial_mct( 5531): userial_open(port:0)
,I/bt_vendor( 5531): bt-vendor : BT_VND_OP_USERIAL_OPEN
,D/WifiNative-wlan0( 1014): callSECApiInt - ID [210]
,D/Tethering( 1014): interfaceLinkStateChanged p2p0, false,
I/Nat464Xlat( 1014): interfaceLinkStateChanged p2p0, false
D/Tethering( 1014): interfaceStatusChanged p2p0, false
,I/bt_vendor( 5531): Done intiailizing UART
,I/bt_vendor( 5531): Done intiailizing UART
,I/bt_userial_mct( 5531): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
,I/bt_vendor( 5531): Bluetooth Firmware and transport layer are initialized
D/WifiConfigStore( 1014): Loading config and enabling all networks 
,D/bt_userial_mct( 5531): Entering userial_read_thread()
,I/        ( 5531): BTE_InitTraceLevels -- TRC_HCI
I/        ( 5531): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5531): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5531): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5531): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5531): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5531): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5531): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5531): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5531): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5531): BTE_InitTraceLevels -- TRC_SAP
I/        ( 5531): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5531): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5531): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5531): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5531): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 5531): BTE_InitTraceLevels -- TRC_PROTOCOL
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1174): Wifi onReceive(3)
D/HotspotTile( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1174): onStateChanged: Wi-Fi
,D/HotspotTile( 1174): onReceive : 3, 0
,E/WifiConfigStore( 1014): Not a HS20
,E/WifiConfigStore( 1014): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/SSRM:n  ( 1014): SIOP:: AP = 330
,D/WifiNative-wlan0( 1014): callSECApiInt - ID [65]
,D/WifiNative-wlan0( 1014): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 5596): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 5596): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 5596): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5596): P2P: Current p2p state = IDLE
I/wpa_supplicant( 5596): wlan0: State: DISCONNECTED -> SCANNING
,I/wpa_supplicant( 5596): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5596): First Scan Start
I/wpa_supplicant( 5596): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-wlan0( 1014): Setting external_sim to 1
,D/WifiStateMachine( 1014): Setting OUI to DA-A1-19
,I/WifiNative-HAL( 1014): startHal
E/wifi    ( 1014): getStaticLongField sWifiHalHandle 0x9e84388c
I/WifiNative-HAL( 1014): Could not start hal
,D/WifiCredService( 1281): Action received :android.net.wifi.WIFI_STATE_CHANGED
,E/WifiNative-wlan0( 1014): do suspend true
,D/WifiP2pService( 1014): P2pDisabledState{ what=131203 }
,E/WifiStateMachine( 1014): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,W/libprocessgroup( 1014): failed to open /acct/uid_10044/pid_4360/cgroup.procs: No such file or directory
,D/WifiScanningService( 1014): SCAN_AVAILABLE : 3
D/WifiScanningService( 1014): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1014): SCAN_AVAILABLE : 3
,D/RttService( 1014): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1014): startHal
D/CommandListener(  278): Setting iface cfg
D/CommandListener(  278): Trying to bring up p2p0
,E/wifi    ( 1014): getStaticLongField sWifiHalHandle 0x9d8039bc
I/WifiNative-HAL( 1014): Could not start hal
,D/WifiMonitor( 1014): startMonitoring(p2p0) with mConnected = true
E/WifiScanningService( 1014): could not start HAL
,D/WifiP2pService( 1014): P2pEnablingState
D/WifiP2pService( 1014): P2pEnablingState{ what=147457 }
,D/WifiP2pService( 1014): P2p socket connection successful
D/WifiP2pService( 1014): P2pEnabledState
,D/SecurityLogAgent( 5673): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5673): KnoxConfiguration : Current State Mapping Found 
,I/wpa_supplicant( 5596): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/SecurityLogAgent( 5673): StateMachine : Current State = 1
I/wpa_supplicant( 5596): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/WifiP2pService( 1014): sending p2p connection changed broadcast: IDLE
,E/WifiStateMachine( 1014): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,I/wpa_supplicant( 5596): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiP2pService( 1014): create mNetworkAgent
,E/WifiStateMachine( 1014): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1014): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1014): invaild command id : 215
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,W/bt-l2cap( 5531): l2c_link_processs_ble_num_bufs 16
,E/bt-btm  ( 5531): BTM_SecRegister:p_cb_info->p_le_callback == 0xa40ca6e9 
,E/bt-btm  ( 5531): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40ca6e9 
,D/ConnectivityService( 1014): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1014): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 1014): updateNetworkInfo()
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/CSLegacyTypeTracker( 1014): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,D/WifiDisplayController( 1014): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/WifiDisplayController( 1014): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayController( 1014): disconnect
,D/WifiDisplayController( 1014): updateConnection
,D/WifiDisplayController( 1014): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/BluetoothAdapterProperties( 5531): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,D/SecurityLogAgent( 5673): StateMachine : Changed Current State = 1
,E/bt-btif ( 5531): Calling BTA_HhEnable
E/bt-btif ( 5531): BTM_SEC_REG[6]: id 43, is_orig 1, psm 0x001b, proto_id 0
D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/BluetoothAdapterProperties( 5531): Address is:7C:F9:0E:37:96:AB
E/BluetoothServiceJni( 5531): populateRssiValuesNative
I/bluedroid( 5531): getModelRssiValues
E/BluetoothServiceJni( 5531): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5531): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 5531): Name is: A5-1
,D/WifiNative-p2p0( 1014): p2pGetDeviceAddress
,D/WifiNative-p2p0( 1014): p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1014): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/com.google.a.a.b.d.a( 5603): Application name is not set. Call Builder#setApplicationName.
,D/AllShareCastTile( 1174): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1174): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,I/ActivityManager( 1014): Killing 5094:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/SettingsProvider( 1014): name = bluetooth_name
,D/WifiP2pService( 1014): DeviceAddress: 7e:96:ac
,D/BluetoothUtils( 5531): getBtEnabledContainers(): btContainers = []
,D/WifiDisplayController( 1014): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
D/WifiDisplayController( 1014):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1014):  primary type: 10-0050F204-5
D/WifiDisplayController( 1014):  secondary type: null
D/WifiDisplayController( 1014):  wps: 0
D/WifiDisplayController( 1014):  grpcapab: 0
D/WifiDisplayController( 1014):  devcapab: 0
D/WifiDisplayController( 1014):  status: 3
D/WifiDisplayController( 1014):  wfdInfo: null
D/WifiDisplayController( 1014):  groupownerAddress: null
D/WifiDisplayController( 1014):  GOdeviceName: null
D/WifiDisplayController( 1014):  interfaceAddress: 
D/WifiDisplayController( 1014):  SConnectInfo : null
,D/BluetoothAdapterProperties( 5531): Scan Mode:20
D/BluetoothAdapterProperties( 5531): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5531): LE Address is:FC:F3:1C:6E:2D:57
,E/bt-btif ( 5531): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 5531): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif ( 5531): btif_sock_init: !radio_req && !rfc_init
,E/bt-btif ( 5531): btif_sock_init: !vhci_init
E/bt_mct  ( 5531): hci lib postload completed
,D/IOP_DB_BT( 5531): db_open: file /etc/bluetooth/iop_bt.db
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3452): Starting #3
,I/Hs20UtilService( 3452): Message received 5011
,D/IOP_DB_BT( 5531): db_open: db_open : handle 3028606992l, read 13894 bytes onto local cache
D/IOP_DB_BT( 5531): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT( 5531): db_query: result 1
I/        ( 5531): iop_db_open: iop_db_open status 0
,E/WifiStateMachine( 1014): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1014): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1014): invaild command id : 215
,D/bte_conf( 5531): Device ID record 1 : primary
D/bte_conf( 5531):   vendorId            = 0075
D/bte_conf( 5531):   vendorIdSource      = 0001
D/bte_conf( 5531):   product             = 0100
D/bte_conf( 5531):   version             = 0200
D/bte_conf( 5531):   clientExecutableURL = 
D/bte_conf( 5531):   serviceDescription  = 
D/bte_conf( 5531):   documentationURL    = 
D/bte_conf( 5531): bte_load_did_conf no section named DID2.
,D/BluetoothPanServiceJni( 5531): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState( 5531): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 5531): ScanMode =  20
D/BluetoothAdapterProperties( 5531): State =  11
D/SecurityLogAgent( 5673): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5673): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5673): StateMachine : Current State = 1
D/SecurityLogAgent( 5673): StateMachine : Changed Current State = 1
,D/SecContentProvider( 1014): uri = 3 selection = isDiscoverableEnabled
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BluetoothAdapterProperties( 5531): Setting state to 12
,I/BluetoothAdapterState( 5531): Bluetooth adapter state changed: 11-> 12
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/WifiP2pService( 1014): sending p2p persistent groups changed broadcast
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/BluetoothUtils( 5531): getBtEnabledContainers(): btContainers = []
D/BluetoothAdapterProperties( 5531): Scan Mode:21
,D/BluetoothAdapterProperties( 5531): Discoverable Timeout:120
,D/SettingsProvider( 1014): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/WifiP2pService( 1014): InactiveState
,D/WifiP2pService( 1014): InactiveState{ what=143376 }
,V/NearbySettings( 1281): DMSUtil.isNetworkConnected - flag-null, state-null
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 5531): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5531): updateAdapterState state is 12
,D/WifiP2pService( 1014): P2pEnabledState{ what=143376 }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/wpa_supplicant( 5596): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ConnectivityService( 1014): updateNetworkInfo()
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,D/WifiP2pService( 1014): InactiveState{ what=143376 }
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/WifiP2pService( 1014): P2pEnabledState{ what=143376 }
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1281): MountReceiver.onReceive - Set preference state off
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,V/NearbySettings( 1281): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/BluetoothAdapterService( 5531): Autoconnection is available 
D/BluetoothAdapterService( 5531): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 5531): starting service from this receiver
,D/BluetoothA2dp( 5531): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1014): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1014): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1430): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1430): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 2689): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2689): onBluetoothStateChange: Bluetooth is on
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/BluetoothAdapter( 1174): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1174): onBluetoothStateChange: Bluetooth is on
D/BluetoothA2dp( 2689): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 5479): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 5479): onBluetoothStateChange: Bluetooth is on
,I/BluetoothPbapService( 5531): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
I/BluetoothPbapService( 5531): Handler(): got msg=1
D/BluetoothAdapter( 1419): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1419): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 5531): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5531): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1439): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1439): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1789): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1789): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 5603): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5603): onBluetoothStateChange: Bluetooth is on
D/BluetoothA2dp( 1014): onBluetoothStateChange: up=true
,E/Zygote  ( 5704): MountEmulatedStorage()
I/libpersona( 5704): KNOX_SDCARD checking this for 10068
E/Zygote  ( 5704): v2
I/libpersona( 5704): KNOX_SDCARD not a persona
I/SELinux ( 5704): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5704): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5704): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5704 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
W/InputMethodManagerService( 1014): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1014): [BT Setting State] State =12
I/InputMethodManagerService( 1014): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothTile( 1174):  onBluetoothStateChange:
,D/BluetoothHeadset( 1419): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@38ed6381, true
D/BluetoothHeadset( 1419): registerMessageListener
D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1174): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1174):  getBluetoothState : 12
,I/SamsungIME( 1777): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/TimaKeyStoreProvider( 5704): TimaSignature is unavailable
,D/ActivityThread( 5704): Added TimaKeyStore provider
,D/StatusBarManagerService( 1014): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/HeadsetService( 5531): registerMessageListener
,D/StatusBarManagerService( 1014): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 1174): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/HeadsetService( 5531): registerMessageListener
,D/HeadsetStateMachine( 5531): Disconnected process message: 70
D/HeadsetStateMachine( 5531): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@23b1bc03
,I/Telecom ( 1419): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1419): BluetoothPhoneService: updateHeadsetWithCallState
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,I/Telecom ( 1419): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1419): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
W/libprocessgroup( 1014): failed to open /acct/uid_10152/pid_5094/cgroup.procs: No such file or directory
,I/Telecom ( 1419): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/HeadsetStateMachine( 5531): Disconnected process message: 9,
D/HeadsetStateMachine( 5531): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/audio_hw_primary(  283): adev_set_parameters: enter: A2dpSuspended=false
,V/voice   (  283): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  283): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  283): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
,E/HeadsetStateMachine( 5531): terminateScoUsingVirtualVoiceCall:No present call to terminate
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 40638(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 2.779ms total 164.131ms
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
D/SecContentProvider( 1014): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothAdapterState( 5531): Entering On State from state = 11
,V/BluetoothPbapService( 5531): PBAP Service initSocket try: 0
,D/BluetoothSocket( 5531): bindListen(): myUserId = 0
,W/BluetoothAdapter( 5531): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5531): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 5531): bindListen(), new LocalSocket 
D/BluetoothSocket( 5531): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5531): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@eba080a
,D/BluetoothSocket( 5531): channel: 19
,D/BluetoothPbapService( 5531): PBAP Socket is BluetoothServerSocket
,D/BluetoothMapMasInstance( 5531): set MAP SDP message type : 1
,W/ResourcesManager( 5704): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/BluetoothSocket( 5531): bindListen(): myUserId = 0
,W/BluetoothAdapter( 5531): getBluetoothService() called with no BluetoothManagerCallback
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/BluetoothSocket( 5531): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 5531): bindListen(), new LocalSocket 
D/BluetoothSocket( 5531): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5531): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3564a87b
D/BluetoothSocket( 5531): channel: 5
,D/FileShare-Client( 5704): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 5704): ClientBroadcastReceiver.onReceive - disconnected
,D/FileShare-Client( 5704): Outbound.stopDelayTimer - 
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5723): MountEmulatedStorage(),
E/Zygote  ( 5723): v2
I/libpersona( 5723): KNOX_SDCARD checking this for 10069
I/SELinux ( 5723): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5723): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5723 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5723): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Killing 4677:com.samsung.android.sm/1000 (adj 15): empty #31
E/SELinux ( 5723): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 1789): Explicit concurrent mark sweep GC freed 33026(2002KB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 12MB/21MB, paused 1.200ms total 63.419ms
,D/TimaKeyStoreProvider( 5723): TimaSignature is unavailable
,D/ActivityThread( 5723): Added TimaKeyStore provider
,D/FileShare-Server( 5723): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1014): Killing 4800:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,W/ContextImpl( 1281): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/ActivityManager( 1014): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/LocalBluetoothProfileManager( 1281): Adding local A2DP profile
,D/BluetoothA2dp( 1281): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1014): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1281): Adding local HEADSET profile
,E/BluetoothHeadset( 1281): BTStateChangeCB is registed
,D/BluetoothHeadset( 1281): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1014): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 1281): BluetoothHeadset service is binded
,D/BluetoothMap( 1281): Create BluetoothMap proxy object
,D/ActivityManager( 1014): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1014): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ContextImpl( 1281): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/ActivityManager( 1014): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/Bluetoothsap( 1281): bindService called to Bluetooth SAP Service
,D/ActivityManager( 1014): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1014): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4677/cgroup.procs: No such file or directory
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/libprocessgroup( 1014): failed to open /acct/uid_10015/pid_4800/cgroup.procs: No such file or directory
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1281): PANU : true
,W/LocalBluetoothProfileManager( 1281): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1281): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1281): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1281): onReceive
,D/BluetoothA2dp( 1281): Proxy object connected
,D/A2dpProfile( 1281): Bluetooth service connected
,V/BluetoothStatusReceiver( 1174): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1174): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,D/HeadsetProfile( 1281): Bluetooth service connected
,D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
,D/BtConfig.SecureMode( 5531): isSecureModeOn:false
D/BluetoothMap( 1281): Proxy object connected
D/MapProfile( 1281): Bluetooth service connected
D/BluetoothMap( 1281): getConnectedDevices()
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothPbap( 1281): Proxy object connected
D/PbapServerProfile( 1281): Bluetooth service connected
D/Bluetoothsap( 1281): BluetoothSAP Proxy object connected
,D/SapProfile( 1281): Bluetooth service connected
D/Bluetoothsap( 1281): getConnectedDevices()
,D/BluetoothInputDevice( 1281): Proxy object connected
D/HidProfile( 1281): Bluetooth service connected
,D/BluetoothPan( 1281): BluetoothPAN Proxy object connected
D/PanProfile( 1281): Bluetooth service connected
,D/AuthorizationBluetoothService( 1789): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/SecContentProvider( 1014): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/BluetoothSocket( 5531): bindListen(): myUserId = 0
W/BluetoothAdapter( 5531): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5531): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
D/BluetoothSocket( 5531): bindListen(), new LocalSocket 
D/BluetoothSocket( 5531): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5531): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10fcc92d
,D/BluetoothSocket( 5531): channel: 12
I/BtOppRfcommListener( 5531): Accept thread started.
,I/wpa_supplicant( 5596): nl80211: Received scan results (4 BSSes),
I/wpa_supplicant( 5596): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5596): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 5596): Trying to associate with  'G700'
I/wpa_supplicant( 5596): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 5596): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1014): didn't find BSSID Trying to associate with SSID 'NG700'
I/WifiNative-HAL( 1014): startHal,
E/wifi    ( 1014): getStaticLongField sWifiHalHandle 0x9e8438ac
I/WifiNative-HAL( 1014): Could not start hal
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1014): mCursor = null
,E/wpa_supplicant( 5596): Cmd 35605 not handled
,I/wpa_supplicant( 5596): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5596): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
I/wpa_supplicant( 5596): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 5596): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 5596): Associated with C0.AA.48
I/wpa_supplicant( 5596): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 5596): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 5596): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false,
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, true
D/Tethering( 1014): interfaceStatusChanged wlan0, true
,E/Tethering( 1014): No numeric data
D/Tethering( 1014): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1014): clearTetheredNotification()
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,I/wpa_supplicant( 5596): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5596): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,I/wpa_supplicant( 5596): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 5596): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 5596): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5596): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 5596): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 5596): Blacklist: Clear (temp) 
D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
I/wpa_supplicant( 5596): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/HotspotTile( 1174): updateTetherState():false, false
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, true
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, true
D/Tethering( 1014): interfaceStatusChanged wlan0, true
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1014): forceRefresh Fail.
V/NetworkStats( 1014): performPollLocked(flags=0x1)
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,V/NetworkStats( 1014): performPollLocked() took 3ms
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,D/NtpTrustedTime( 1014): forceRefresh Fail.
,D/WifiNative-wlan0( 1014): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1014): setLastSelectedConfiguration -1
,D/ConnectivityService( 1014): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1014): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 1014): updateNetworkInfo()
,D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3452): Starting #4
I/Hs20UtilService( 3452): Message received 5007
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1281): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1281): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1281): MountReceiver.mPrefHandler - 7002
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  278): Setting iface cfg
,E/WifiStateMachine( 1014): Start Dhcp Watchdog 1
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1014): mCursor = null
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1014): mCursor = null
,E/WifiNative-wlan0( 1014): do suspend false
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,E/dhcpcd  ( 5748): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5748): version 5.5.6 starting,
,E/dhcpcd  ( 5748): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5748): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 5748): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 5748): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5748): bssid match
,I/dhcpcd  ( 5748): wlan0: rebinding lease of 192.168.1.129
,I/dhcpcd  ( 5748): wlan0: acknowledged 192.168.1.129 from 192.168.1.1
,I/dhcpcd  ( 5748): wlan0: leased 192.168.1.129 for 86400 seconds
,E/WifiNative-wlan0( 1014): do suspend true
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1014): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1014): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1014): callSECApiInt - ID [210]
,E/ConnectivityService( 1014): updateNetworkInfo()
,D/ConnectivityService( 1014): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1014): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 1014): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
D/WifiWatchdogStateMachine.DnsResolver( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ConnectivityService( 1014): Adding Route [fe80::/64 -> :: wlan0] to network 502
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3452): Starting #5
,E/WifiStateMachine( 1014): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1014): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,I/Hs20UtilService( 3452): Message received 5007
I/NearbySettings( 1281): MountReceiver.onReceive - Keep current state
D/ConnectivityService( 1014): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,E/ConnectivityService( 1014): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1014): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService( 1014): LTETest block dns file not exists
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,E/ConnectivityService( 1014): updateNetworkInfo()
E/ConnectivityService( 1014): updateNetworkInfo()
,D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1014): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1014): rematching NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,D/ConnectivityService( 1014):    accepting network in place of null
D/WIFI_P2P( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1014): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,D/TelephonyNetworkFactory( 1439): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/TelephonyNetworkFactory( 1439): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1014): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1014): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1014): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1014): (HTTPLog)-Static: isShipBuild true
I/System.out( 1014): (HTTPLog)-Thread-170-924795775: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 1000
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ConnectivityService( 1014): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/WIFI    ( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,I/Hs20UtilService( 3452): Starting #6
,D/Tethering( 1014): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1014): MasterInitialState.processMessage what=3
,V/NetworkStats( 1014): updateIfacesLocked()
V/NetworkStats( 1014): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
I/Hs20UtilService( 3452): Message received 5007
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
D/EntConnectivity( 1014): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityService( 1014): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 1000
,V/NetworkStats( 1014): performPollLocked() took 4ms
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1014): mBoosterFLAG : 0
I/WifiTrafficPoller( 1014): current booster mode : FullMode
D/WifiNative-wlan0( 1014): callSECApiVoid - ID [212]
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1174): EthernetConnected: false
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NearbySettings( 1281): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1281): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3452): Starting #7
,I/Hs20UtilService( 3452): Message received 5007
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1281): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1014): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravity,
D/SecContentProvider2( 1014): mCursor = null
D/NtpTrustedTime( 1014): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449746254467 mCachedNtpElapsedRealtime : 94359 mCachedNtpCertainty : 9
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1014): mCursor = null
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,I/System.out( 1014): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SecContentProvider2( 1014): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1014): mCursor = null
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=4, Uoast
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 11:17:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449746253733], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449746253708]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Validated
D/ConnectivityService( 1014): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1014): rematching NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1014): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 1014): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
,D/PowerManagerService( 1014): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,D/SRIB_DCS( 1174): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
,D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  288): DCD OFF
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/AlarmManagerService( 1014): Setting time of day to sec=1449746254
D/AlarmManagerService( 1014): Trying to open a file
,D/AlarmManagerService( 1014): File Open Success,
D/AlarmManagerService( 1014): File Close Success
I/AlarmManagerService( 1014): DRM_TIME_PATH CHMOD 666 for resetState done 
W/AlarmManagerService( 1014): Unable to set rtc to 1449746254: Invalid argument
,I/DBG_DM  ( 2940): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
V/AlarmManager( 1014): waitForAlarm result :65536
I/DBG_DM  ( 2940): [com.wssyncmldm.llllIIIllIlIIIIllllI(230/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 2940): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,V/AlarmManager( 1014): No more alarm at this time.nowELAPSED=94815 batch.start=99031
,D/OTPFW   ( 1014): OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1449746254919
,D/WifiStateMachine( 1014): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,I/PCWCLIENTTRACE_PushUtil( 5129): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5129): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5129): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5129): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DowntimeConditions( 1014): android.intent.action.TIME_SET ignored because schedule turned off.
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_SET
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/Settings( 1014): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DBG_DM  ( 2940): [IlIlllIlllllIlIllllI(403/llIIllllIIlllIIIIlll)] Check completed.
D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DBG_DM  ( 2940): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/splitIntent( 1014): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
I/splitIntent( 1014): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = lockscreen_zoom_panning_effect
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10054
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1014): ret = -1
,D/KeyguardEffectViewUtil( 1174): isStrongPowerSavingMode() :false
,E/Zygote  ( 5791): MountEmulatedStorage()
E/Zygote  ( 5791): v2
I/libpersona( 5791): KNOX_SDCARD checking this for 10111
I/libpersona( 5791): KNOX_SDCARD not a persona
,I/SELinux ( 5791): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5791 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5791): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,I/DBG_DM  ( 2940): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,E/SELinux ( 5791): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 2940): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,D/KeyguardEffectViewController( 1174): isPreloadedWallpaper=true
I/GeometricMosaic_Keyguard( 1174): update
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/KeyguardEffectViewUtil( 1174): getCurrentWallpaper() mWallpaperPath :null
,W/SEC_DRM_PLUGIN_Playready(  282): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1449746254 after conversion: 1449746254
W/SEC_DRM_PLUGIN_Playready(  282): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1449746254 after conversion: 1449746254
,E/Zygote  ( 5799): MountEmulatedStorage()
I/libpersona( 5799): KNOX_SDCARD checking this for 10009
E/Zygote  ( 5799): v2
I/libpersona( 5799): KNOX_SDCARD not a persona
I/SELinux ( 5799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=5799 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5799): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/accuweather( 1705): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_DM  ( 2940): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1332): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/TimaKeyStoreProvider( 5799): TimaSignature is unavailable
,D/ActivityThread( 5799): Added TimaKeyStore provider
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 5791): TimaSignature is unavailable
,D/ActivityThread( 5791): Added TimaKeyStore provider
,D/accuweather( 1705): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1705): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1705): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1705): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/DBG_DM  ( 2940): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 8
,I/GoogleURLConnFactory( 1789): Using platform SSLCertificateSocketFactory
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/accuweather( 1705): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2940): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,D/accuweather( 1705): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/DBG_DM  ( 2940): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/KeyguardEffectViewUtil( 1174): set current wallpaper info
,D/SettingsProvider( 1014): name = keyguard_current_wallpaper_type
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
,I/DBG_DM  ( 2940): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [8]
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/SettingsProvider( 1014): selectionArgs: 10054
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 1014): name = keyguard_current_wallpaper_file_path
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1014): selectionArgs: false
,D/SettingsProvider( 1014): selectionArgs: 10054
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
D/SettingsProvider( 1014): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10054
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,E/Zygote  ( 5825): MountEmulatedStorage(),
I/libpersona( 5825): KNOX_SDCARD checking this for 10081
E/Zygote  ( 5825): v2,
I/libpersona( 5825): KNOX_SDCARD not a persona
,I/SELinux ( 5825): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5825): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5825): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5825 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SecurityLogAgent( 5673): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5673): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5673): StateMachine : Current State = 1
,D/SecurityLogAgent( 5673): StateMachine : Changed Current State = 1
,D/TimaKeyStoreProvider( 5825): TimaSignature is unavailable
,D/ActivityThread( 5825): Added TimaKeyStore provider
,I/DBG_DM  ( 2940): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 0
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2940): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 2940): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 2940): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 2940): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] ,
I/DBG_DM  ( 2940): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
I/DBG_DM  ( 2940): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/DBG_DM  ( 2940): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,I/DBG_DM  ( 2940): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5841): MountEmulatedStorage()
,E/Zygote  ( 5841): v2
I/libpersona( 5841): KNOX_SDCARD checking this for 10159
,I/libpersona( 5841): KNOX_SDCARD not a persona
,I/SELinux ( 5841): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=5841 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TEST    ( 1174): run!!!
I/SELinux ( 5841): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5841): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 2940): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,I/GeometricMosaic_Renderer( 1174): setBackgroundBitmap,
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,I/art     (  303): Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 6.189ms total 38.466ms,
,I/DBG_DM  ( 2940): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 671us total 17.279ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 21.112ms
,I/DBG_DM  ( 2940): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,D/TimaKeyStoreProvider( 5841): TimaSignature is unavailable
,I/DBG_DM  ( 2940): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
D/ActivityThread( 5841): Added TimaKeyStore provider
,I/FOTA_Client( 5799): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/MusicStore( 5791): Database version: 108
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.metadata.ContactMetadataSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,I/FOTA_Client( 5799): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 5799): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 5799): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.183: ( 3491): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 12:17:35 GMT+01:00 2015
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3491): KLMSAbstractReciever(): onReceive().END.
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/KLMS-2.5.183: ( 3491): KLMSIntentService(): onCreate()
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,I/KLMS-2.5.183: ( 3491): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3491): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3491): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3491): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  ( 5864): MountEmulatedStorage()
I/libpersona( 5864): KNOX_SDCARD checking this for 10034
E/Zygote  ( 5864): v2
I/libpersona( 5864): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5864 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 5864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5864): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
I/KLMS-2.5.183: ( 3491): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
I/KLMS-2.5.183: ( 3491): StateImplV2(): networkChangeListener().START
,I/DBG_DM  ( 2940): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,D/TimaKeyStoreProvider( 5864): TimaSignature is unavailable
,D/ActivityThread( 5864): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3491): NetworkChangeOperations(): uploadRequestLog().START 
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/WaitQueueForNetworkActivate( 5177): notifyNetworkActivated
,E/Zygote  ( 5886): MountEmulatedStorage()
E/Zygote  ( 5886): v2
I/libpersona( 5886): KNOX_SDCARD checking this for 10044
I/libpersona( 5886): KNOX_SDCARD not a persona
,I/SELinux ( 5886): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/KLMS-2.5.183: ( 3491): NetworkChangeOperations(): uploadRequestLog().END 
I/SELinux ( 5886): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=5886 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
E/SELinux ( 5886): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3491): StateImplV2(): networkChangeListener().END
,I/DBG_DM  ( 2940): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 2940): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,I/DBG_DM  ( 2940): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/DBG_DM  ( 2940): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
I/DBG_DM  ( 2940): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,E/DBG_DM  ( 2940): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,E/DBG_DM  ( 2940): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@2a09144f
,I/PhenotypeConfigurator( 1789): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/KLMS-2.5.183: ( 3491): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 5886): TimaSignature is unavailable
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityThread( 5886): Added TimaKeyStore provider
I/DBG_DM  ( 2940): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/DBG_DM  ( 2940): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,W/ResourcesManager( 5886): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5886): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5886): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5886): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5886): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5886): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5886): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5886): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityThread( 1999): Failed to find provider info for com.android.contacts.metadata
,W/ResourcesManager( 5791): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5791): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ContextImpl( 5177): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/JNIHelp ( 5791): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...,
,E/GpsLocationProvider( 1014): No APN found to select.
,I/DBG_DM  ( 2940): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_POLICYDM( 5204): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5204): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5204): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,E/DBG_POLICYDM( 5204): [com.policydm.XDMBroadcastReceiver(240/xdmNotInitSetResume)] DM Not Init
,I/DBG_POLICYDM( 5204): [com.policydm.XDMApplication(286/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_POLICYDM( 5204): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/SyncManager( 1014): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 23198, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 1014): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 128193, reason: UserStart
,I/DBG_POLICYDM( 5204): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_DM  ( 2940): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,E/SPPClientService( 5234): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/DBG_POLICYDM( 5204): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 9
,I/DBG_POLICYDM( 5204): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 9
,W/ActivityThread( 5791): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5791): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34645444: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5791): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5791): GMSCore installation verified
,I/SA      ( 5378): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5378): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5378): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5378): [SLFUCHKMGR] constructor called
,D/NearbySource( 5886): Nearby Source Create!
,D/NearbyContext( 5886): Nearby Context Create!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5915 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/Zygote  ( 5915): MountEmulatedStorage()
I/libpersona( 5915): KNOX_SDCARD checking this for 10104
E/Zygote  ( 5915): v2
I/libpersona( 5915): KNOX_SDCARD not a persona
I/SELinux ( 5915): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5915): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5915): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1014): mCursor = null
,I/DBG_POLICYDM( 5204): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 9,
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/,
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5886): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 5886): Samsung link source created
,D/PackageManager( 1014): [MSG] MCS_UNBIND
,I/ActivityManager( 1014): Killing 4425:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5915): TimaSignature is unavailable
,D/ActivityThread( 5915): Added TimaKeyStore provider
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1014): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager( 1174): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_DM  ( 2940): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1014): mCursor = null
,W/ResourcesManager( 5915): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1014): mCursor = null
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1014): mCursor = null
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 48224(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 5.409ms total 230.133ms
,D/ContactProvider( 5886): getAllContactInfoList Start,
,I/DBG_POLICYDM( 5204): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,I/DBG_DM  ( 2940): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/KnoxNotification( 1174): ----- inflateViews : modified publicViewLocal -----
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,D/SecContentProvider2( 1014): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1014): mCursor = null
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/SecContentProvider2( 1014): uri = 15 selection = getToastShowPackageNameState
I/SA      ( 5378): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5378): [OR] == isSIMCardReady false ==
,D/SecContentProvider2( 1014): mCursor = null
,I/SA      ( 5378): [SCU] == networkStateCheck == true
D/KnoxNotification( 1174): ----- inflateViews : modified KnoxViewLocal -----
,I/SA      ( 5378): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5378): isChinaCountryCode : false
I/SA      ( 5378): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5378): [OR] == networkStateCheck true ==
,D/PersonaManager( 1174): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/SA      ( 5378): [OR] GetMyCountryZoneTask
,I/SA      ( 5378): [OR] onReceive END
,I/PhoneStatusBar( 1174): Icon Only
,I/ActivityManager( 1014): Killing 5146:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
I/DBG_POLICYDM( 5204): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,V/DownloadManager( 1230): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5204): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5204): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5204): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5204): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 5204): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2015/12/15/14:49:36
,I/DBG_POLICYDM( 5204): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2015/12/10/12:17:36
,I/DBG_POLICYDM( 5204): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5204): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/SA      ( 5378): [SRS] prepareGetMyCountryZone
,I/DBG_POLICYDM( 5204): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_DM  ( 2940): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 2940): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 2940): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,I/DBG_POLICYDM( 5204): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5204): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 5204): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5204): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5204): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 5204): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5204): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5204): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 5204): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,I/SA      ( 5378): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5378): [SSP] query invoked
,I/ConfigStore( 5791): Config Database version: 1
,I/DBG_POLICYDM( 5204): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4425/cgroup.procs: No such file or directory
,D/SecContentProvider2( 1014): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1014): mCursor = null
,W/libprocessgroup( 1014): failed to open /acct/uid_10156/pid_5146/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5204): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,I/SA      ( 5378): [TPMU] GetMccFromDB : null
,D/ContactProvider( 5886): getAllContactInfoList End
,I/SA      ( 5378): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5378): [TPM] isNoProxy(default) : true
,I/syncContacts( 5886): thread: 1008, sync time = 302
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 5204): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/File    ( 5378): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5204): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/Auth.Api.Credentials( 1999): [CredentialSyncAdapter] Unknown sync event.
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/hcjo    ( 5177): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5177): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5177): exit::IDLE
D/InitializeManagerStateMachine( 5177): entry::NETWORK_CHECK
,I/ActivityManager( 1014): Killing 5160:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/InitializeManagerStateMachine( 5177): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5177): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5177): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5177): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5177): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5177): entry::SUCCESS
D/hcjo    ( 5177): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5177): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 5177): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5177): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5177): exit::SUCCESS
,D/InitializeManagerStateMachine( 5177): entry::IDLE
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 5204): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/System.out( 1789): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
,I/ActivityManager( 1014): Killing 4916:com.android.vending/u0a28 (adj 15): empty #31
,I/DBG_POLICYDM( 5204): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5791): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5160/cgroup.procs: No such file or directory
,D/NetworkLogImpl( 1999): Loaded NetworkSpeedPredictor
,I/System.out( 1789): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,I/iu.SyncManager( 1999): SYNC; picasa accounts
,W/ContextImpl( 5791): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,I/iu.Environment( 1999): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/ContextImpl( 5791): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,I/iu.UploadsManager( 1999): num queued entries: 0
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/iu.UploadsManager( 1999): num updated entries: 0
,I/iu.SyncManager( 1999): NEXT; no task
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 1789): Tagging socket 52 with tag 1000120300000000{268440067,0} for uid -1, pid: 1789, getuid(): 10012
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/art     ( 1618): Explicit concurrent mark sweep GC freed 1639(57KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 803us total 51.510ms
,I/AudioService( 1014): getStreamVolume 3 index 0
,I/MediaRouter( 5791): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/Babel   ( 5915): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 5915): MmsConfig.loadMmsSettings
I/Babel   ( 5915): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 5915): MmsConfig.loadFromDatabase
,V/MusicLeanback( 5791): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/Babel   ( 5915): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5915): MmsConfig.loadFromResources
,E/Babel   ( 5915): canonicalizeMccMnc: invalid mccmnc nullnull
I/NetworkMonitor( 5791): type=WIFI subType= reason=null isConnected=true
,I/Babel   ( 5915): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/Settings( 5915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/ConnectivityChangeReceiver( 1999): Ignoring connectivity change
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/qtaguid ( 1789): Tagging socket 79 with tag 1000120300000000{268440067,0} for uid -1, pid: 1789, getuid(): 10012
,D/ConnectivityManager( 1999): CallingUid : 10012, CallingPid : 1999
,I/NetworkMonitor( 5791): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService( 1014): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService( 1014): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1014): apparently satisfied.  currentScore=60
,D/ConnectivityService( 1014): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,D/ConnectivityManager.CallbackHandler( 1999): CM callback handler got msg 524290,
,E/Zygote  ( 5964): MountEmulatedStorage()
I/libpersona( 5964): KNOX_SDCARD checking this for 10002
E/Zygote  ( 5964): v2
I/libpersona( 5964): KNOX_SDCARD not a persona
I/SELinux ( 5964): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=5964 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5964): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5964): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5964): TimaSignature is unavailable
,D/ActivityThread( 5964): Added TimaKeyStore provider
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/Babel_StickerModule( 5915): App launched.
,W/libprocessgroup( 1014): failed to open /acct/uid_10028/pid_4916/cgroup.procs: No such file or directory
,W/ResourcesManager( 5791): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5791): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,I/GCM     ( 1789): GCM config loaded
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5985): MountEmulatedStorage()
E/Zygote  ( 5985): v2
I/libpersona( 5985): KNOX_SDCARD checking this for 10113
I/libpersona( 5985): KNOX_SDCARD not a persona
,I/SELinux ( 5985): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5985): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5985 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5985): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/GHttpClientFactory( 5791): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/PicasaService( 5886): start picasa sync
D/TimaKeyStoreProvider( 5985): TimaSignature is unavailable
,D/ActivityThread( 5985): Added TimaKeyStore provider
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
D/PicasaService( 5886): end picasa sync
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  283): getCameraInfo: X
,W/VideoCapabilities( 5915): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1014): Killing 4860:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/AudioCapabilities( 5915): Unsupported mime audio/evrc,
,W/AudioCapabilities( 5915): Unsupported mime audio/qcelp,
,I/ActivityManager( 1014): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6009 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 6009): MountEmulatedStorage(),
E/Zygote  ( 6009): v2
I/libpersona( 6009): KNOX_SDCARD checking this for 1000
I/libpersona( 6009): KNOX_SDCARD not a persona
,I/SELinux ( 6009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6009): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6009): TimaSignature is unavailable
,D/ActivityThread( 6009): Added TimaKeyStore provider
,W/AudioCapabilities( 5915): Unsupported mime audio/mpeg-L1
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4860/cgroup.procs: No such file or directory
,W/AudioCapabilities( 5915): Unsupported mime audio/mpeg-L2
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/AudioCapabilities( 5915): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5915): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5915): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5915): Unsupported mime audio/evrc
,W/VideoCapabilities( 5915): Unsupported mime video/wvc1
,W/VideoCapabilities( 5915): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5915): Unrecognized profile/level 32768/2 for video/mp4v-es
,I/DIAGMON_AGENT( 6009): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/VideoCapabilities( 5915): Unsupported mime video/wvc1
,W/VideoCapabilities( 5915): Unsupported mime video/x-ms-wmv
,I/ActivityManager( 1014): Killing 4825:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,W/VideoCapabilities( 5915): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5915): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5915): Unsupported mime video/mp43
,W/VideoCapabilities( 5915): Unsupported mime video/sorenson
,W/VideoCapabilities( 5915): Unsupported mime video/mp4v-esdp
,W/PhenotypeConfigurator( 1789): Server returned 404
,W/libprocessgroup( 1014): failed to open /acct/uid_10032/pid_4825/cgroup.procs: No such file or directory
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/VideoCapabilities( 5915): Unsupported profile 4 for video/mp4v-es
,I/DIAGMON_AGENT( 6009): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 6009): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6009): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6009): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6009): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6009): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/System.out( 1789): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1789): (HTTPLog)-Static: isSBSettingEnabled false
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1789): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1789): Tagging socket 55 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1789, getuid(): 10012
,I/System.out( 1789): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1789): Tagging socket 83 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1789, getuid(): 10012
,I/qtaguid ( 1789): Tagging socket 88 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1789, getuid(): 10012
,I/qtaguid ( 1789): Tagging socket 89 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1789, getuid(): 10012
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ContextImpl( 5985): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5985): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager( 1014): Killing 5109:com.android.mms/u0a46 (adj 15): empty #31
,D/CountryDetector( 1014): No listener is left
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5985): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5985): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager( 1014): Killing 5301:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,E/SMD     (  288): DCD OFF
,W/DriveInitializer( 1999): Awaiting to be initialized
,W/DriveInitializer( 1999): Background init thread started
,W/libprocessgroup( 1014): failed to open /acct/uid_10046/pid_5109/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.cache.DataUpdateListenerCacheService; callingUser = 0; userId(target) = 0
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1999): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 5985): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/VacuumService( 1789): Vacuum at: now=1449746257958 tag=VacuumService
,W/libprocessgroup( 1014): failed to open /acct/uid_10047/pid_5301/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  258): id=13 Removed Uoast (8/9)
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/SurfaceFlinger(  258): id=13 Removed Uoast (-2/9)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/PowerManagerService( 1014): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1014) eventTime = 97907
D/PowerManagerService( 1014): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014 (0x0)
D/PowerManagerService( 1014): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1014, ws=WorkSource{10054}) (elapsedTime=3489)
,I/LibraryLoader( 5985): Time to load native libraries: 1 ms (timestamps 7916-7917)
,I/LibraryLoader( 5985): Expected native library version number "",actual native library version number ""
,D/OpenGLRenderer( 2940): Render dirty regions requested: true
,V/WebViewChromiumFactoryProvider( 5985): Binding Chromium to main looper Looper (main, tid 1) {deca66b}
,I/LibraryLoader( 5985): Expected native library version number "",actual native library version number ""
,I/chromium( 5985): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 32529(1642KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 5.479ms total 174.934ms
,W/art     ( 4894): Attempt to remove local handle scope entry from IRT, ignoring
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1014): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,D/SRIB_DCS( 2940): log_dcs ThreadedRenderer::initialize entered! 
I/BrowserStartupController( 5985): Initializing chromium process, singleProcess=true
,W/art     ( 5985): Attempt to remove local handle scope entry from IRT, ignoring
,I/Adreno-EGL( 2940): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2940): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2940): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2940): Local Branch: 
I/Adreno-EGL( 2940): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2940): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2940):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/SysUtils( 5985): ApplicationContext is null in ApplicationStatus
,I/dhcpcd  ( 5748): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 5748): wlan0: sendmsg: Cannot assign requested address
,I/OpenGLRenderer( 2940): Initialized EGL, version 1.4
,W/chromium( 5985): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 5985): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 5985): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,W/DriveInitializer( 1999): Background init thread ended
,D/OpenGLRenderer( 2940): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,I/Adreno-EGL( 5985): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5985): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5985): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5985): Local Branch: 
I/Adreno-EGL( 5985): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5985): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5985):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/OpenGLRenderer( 2940): Enabling debug mode 0
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  278): uids 10120
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10120
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/AudioManagerAndroid( 5985): Requires BLUETOOTH permission
,I/SA      ( 5378): [RC New] Execute method=[GET] start
,I/NSApplication( 5985): Starting up...
,I/SA      ( 5378): [RC New] Security=[true]
,I/System.out( 5378): Thread-925(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5378): Thread-925(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5378): Thread-925(ApacheHTTPLog):isShipBuild true
I/System.out( 5378): Thread-925(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5378): Thread-925(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): uids 10041
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10041
,I/ActivityManager( 1014): Killing 5318:com.wsomacp/u0a25 (adj 15): empty #31
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/dex2oat ( 6104): ----------------------------------------------------
I/dex2oat ( 6104): <SS>: S T A R T I N G . . .
I/dex2oat ( 6104): <SS>: Zip is absent. Canceled.
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/dex2oat ( 6104): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads1581586684.jar --oat-fd=111 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/cache/ads1581586684.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6107): MountEmulatedStorage()
,E/Zygote  ( 6107): v2,
I/libpersona( 6107): KNOX_SDCARD checking this for 10125
I/libpersona( 6107): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6107 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 6107): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6107): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6107): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6107): TimaSignature is unavailable
,D/ActivityThread( 6107): Added TimaKeyStore provider
,W/ResourcesManager( 6107): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6107): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6107): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1014): failed to open /acct/uid_10025/pid_5318/cgroup.procs: No such file or directory
,D/QuickConnect( 6107): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6107): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6107): PeriphStartReceiver.onReceive - no need to start
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/dex2oat ( 6104): dex2oat took 91.875ms (threads: 4)
,I/ActivityManager( 1014): Killing 5335:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,I/splitIntent( 1014): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=24
,I/splitIntent( 1014): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6128): MountEmulatedStorage()
I/libpersona( 6128): KNOX_SDCARD checking this for 10062
E/Zygote  ( 6128): v2
I/libpersona( 6128): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6128 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6128): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,I/SELinux ( 6128): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6128): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6136): MountEmulatedStorage()
E/Zygote  ( 6136): v2
I/libpersona( 6136): KNOX_SDCARD checking this for 10135
I/libpersona( 6136): KNOX_SDCARD not a persona
,I/SELinux ( 6136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6136): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6136 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/FOTA_Client( 5799): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6128): TimaSignature is unavailable
,D/ActivityThread( 6128): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6136): TimaSignature is unavailable
,D/ActivityThread( 6136): Added TimaKeyStore provider
,D/daemonapp( 1332): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1332): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1332): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1332): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/FOTA_Client( 5799): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/daemonapp( 1332): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1332): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1332): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1332): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1332): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1332): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1332): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,W/ResourcesManager( 6136): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/daemonapp( 1332): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/ResourcesManager( 6136): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6136): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1332): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/KLMS-2.5.183: ( 3491): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Dec 10 12:17:38 GMT+01:00 2015
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/daemonapp( 1332): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,I/KLMS-2.5.183: ( 3491): KLMSAbstractReciever(): onReceive().END.
,D/daemonapp( 1332): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1332): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,I/SA      ( 5378): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/btif_config_util( 5531): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/libprocessgroup( 1014): failed to open /acct/uid_10053/pid_5335/cgroup.procs: No such file or directory
,I/KLMS-2.5.183: ( 3491): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3491): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3491): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/daemonapp( 1332): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.5.183: ( 3491): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupSyncService; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3491): KLMSIntentService(): TIME_CHANGED
,E/daemonapp( 1332): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/KLMS-2.5.183: ( 3491): StateImplV2(): dateTimeChanged().START : Thu Dec 10 12:17:38 GMT+01:00 2015
,I/KLMS-2.5.183: ( 3491): StateImplV2(): dateTimeChanged().END
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,D/comdaemonstockapp( 1332): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
I/ExternalOEMControlProvider( 6128): onCreate
D/comdaemonstockapp( 1332): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6166): MountEmulatedStorage(),
,E/Zygote  ( 6166): v2
I/libpersona( 6166): KNOX_SDCARD checking this for 10046
,I/libpersona( 6166): KNOX_SDCARD not a persona
,I/SELinux ( 6166): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6166): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1014): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=6166 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
,E/SELinux ( 6166): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,I/KLMS-2.5.183: ( 3491): KLMSIntentService(): onDestroy()
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1332): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/Zygote  ( 6178): MountEmulatedStorage(),
,E/Zygote  ( 6178): v2
I/libpersona( 6178): KNOX_SDCARD checking this for 1000
,I/libpersona( 6178): KNOX_SDCARD not a persona
,I/SELinux ( 6178): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6178): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6178): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=6178 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1014): Killing 4780:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6166): TimaSignature is unavailable
,D/ActivityThread( 6166): Added TimaKeyStore provider
,I/art     (  303): Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 27.091ms,
,D/ActivityManager( 1014): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 6178): TimaSignature is unavailable
,D/ActivityThread( 6178): Added TimaKeyStore provider
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 17.781ms
,I/ Time Manager ( 6128): Time Difference not stored. TIME_DIFFERENCE
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/CheckinService( 1999): Checkin interval check for package: unspecified last checkin: 1449470940712 min interval config: 0 actual interval: 275318103
,W/ResourcesManager( 6166): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6166): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6166): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6166): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6166): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6166): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 16.911ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6178): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6203 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6203): MountEmulatedStorage(),
D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
E/Zygote  ( 6203): v2,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
I/libpersona( 6203): KNOX_SDCARD checking this for 10042,
I/libpersona( 6203): KNOX_SDCARD not a persona
,I/SELinux ( 6203): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6203): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6203): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/Mms/MmsApp( 6166): [start]    onCreate() consume time = 0.0
,D/SecurityLogAgent( 5673): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5673): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5673): StateMachine : Current State = 1
,D/TimaKeyStoreProvider( 6203): TimaSignature is unavailable
,D/ActivityThread( 6203): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_10057/pid_4780/cgroup.procs: No such file or directory
,D/accuweather( 1705): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,D/accuweather( 1705): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6219 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 5259:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31,
,E/Zygote  ( 6219): MountEmulatedStorage()
I/libpersona( 6219): KNOX_SDCARD checking this for 10157
E/Zygote  ( 6219): v2
I/libpersona( 6219): KNOX_SDCARD not a persona
I/SELinux ( 6219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6219): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6229): MountEmulatedStorage(),
E/Zygote  ( 6229): v2
I/ActivityManager( 1014): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6229 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 6229): KNOX_SDCARD checking this for 10085
,I/libpersona( 6229): KNOX_SDCARD not a persona
,I/SELinux ( 6229): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,D/TimaKeyStoreProvider( 6219): TimaSignature is unavailable,
D/ActivityThread( 6219): Added TimaKeyStore provider
,I/SELinux ( 6229): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6229): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/ResourcesManager( 6219): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6229): TimaSignature is unavailable
,D/ActivityThread( 6229): Added TimaKeyStore provider
,W/ResourcesManager( 6203): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6250 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
E/Zygote  ( 6250): MountEmulatedStorage()
E/Zygote  ( 6250): v2
I/ActivityManager( 1014): Killing 5192:com.google.android.apps.docs/u0a91 (adj 15): empty #31,
I/libpersona( 6250): KNOX_SDCARD checking this for 1000
I/libpersona( 6250): KNOX_SDCARD not a persona
,I/SELinux ( 6250): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6250): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6250): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6250): TimaSignature is unavailable
,D/ActivityThread( 6250): Added TimaKeyStore provider
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6229): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6229): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6229): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6229): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6229): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6229): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6203): CalendarProvider2.onCreate() called,
,E/Zygote  ( 6265): MountEmulatedStorage(),
E/Zygote  ( 6265): v2
I/libpersona( 6265): KNOX_SDCARD checking this for 10028
I/libpersona( 6265): KNOX_SDCARD not a persona,
,I/SELinux ( 6265): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6265 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6265): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6265): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6265): TimaSignature is unavailable
,D/ActivityThread( 6265): Added TimaKeyStore provider
,D/TimeService( 6250): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449746259209
,D/        ( 6250): TimeServiceNative: User Time to be set is 1449746259210
D/QC-time-services( 6250): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6250): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 6250): Lib:time_genoff_operation: pargs->ts_val = 1449746259210
,D/QC-time-services(  314): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  314): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449746259210
D/QC-time-services(  314): Daemon:genoff_opr: Base = 2, val = 1449746259210, operation = 0
D/QC-time-services(  314): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/10/70 9:24:33
D/QC-time-services(  314): Daemon:Value read from RTC seconds = 13857873000
D/QC-time-services(  314): Daemon:new time 1449746259210 
D/QC-time-services(  314): Daemon: delta 1435888386210 genoff 1435888386210 
D/QC-time-services(  314): Daemon:genoff_persistent_update: Writing genoff = 1435888386210 to memory
D/QC-time-services(  314): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  314): Daemon:time_persistent_memory_opr:Genoff write operation 
I/SA      ( 5378): [RC New] [v2liruge] api execute + 902
,D/QC-time-services( 6250): Lib:time_genoff_operation: Send to server  passed!!
,I/SA      ( 5378): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,W/art     ( 6166): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 223.471ms
,I/System.out( 5378): AsyncTask #1 calls detatch()
,I/SA      ( 5378): [ODM] saveOpenData( GEO_IP, PL )
,W/libprocessgroup( 1014): failed to open /acct/uid_10038/pid_5259/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10091/pid_5192/cgroup.procs: No such file or directory
,D/QC-time-services(  314): Updating the TOD offset
D/QC-time-services(  314): Daemon:genoff_persistent_update: Writing genoff = 1435888386210 to memory
D/QC-time-services(  314): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  314): Daemon:time_persistent_memory_opr:Genoff write operation 
,I/SA      ( 5378): [OCP] update openData : PL
,E/QC-time-services(  314): Daemon:Update to modem bit set
D/QC-time-services(  314): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  314): Daemon: Base = 2, Value being sent to MODEM = 1119923586210
,E/QC-time-services( 6250): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  314): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  314): Daemon: Time-services: Waiting to acceptconnection
,I/SA      ( 5378): [TPMU] getNetworkMcc : 
,I/SA      ( 5378): [SCU] saveMccToPreferece Start
I/SA      ( 5378): [SCU] RegionMCC : 260
I/SA      ( 5378): [SSP] query invoked
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/DBG_POLICYDM( 5204): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/SA      ( 5378): [TPMU] GetMccFromDB : null
I/SA      ( 5378): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5378): [SCU] saveMccToPreferece End
,I/SA      ( 5378): [RC New] executeRequest [v2liruge] end. 1087
,I/SA      ( 5378): [RC New] Execute end
,I/SA      ( 5378): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5378): [OR] GetMyCountryZoneTask Success
,I/DBG_POLICYDM( 5204): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5204): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5204): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5204): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5204): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb87687c8
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
D/Finsky  ( 6265): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1200192200)
I/DBG_POLICYDM( 5204): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
W/art     ( 6166): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 138.792ms
D/Mms/ArtClassLoader( 6166): init before art
,I/DBG_POLICYDM( 5204): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/Mms/TelephonyPermission( 6166): start operation mode monitor
,D/SettingsProvider( 1014): name = next_alarm_formatted
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10085
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,E/DBG_POLICYDM( 5204): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1200192200) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
,I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb87687c8
,W/ResourcesManager( 6166): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5204): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/Mms/TelephonyPermission( 6166): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 6166): isDefault true
,D/Mms/MmsApp( 6166): onCreate() com.android.mms
,D/Finsky  ( 6265): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/ConnectivityService( 1014): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524295
W/art     ( 6229): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 162.371ms
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 1999): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1999): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524295
,W/Settings( 6265): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6265): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager( 1014): Killing 5409:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/Ads     ( 6265): Skipping gmscore version check
,I/ActivityManager( 1014): Killing 5429:com.samsung.helphub/1000 (adj 15): empty #31
,D/Finsky  ( 6265): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6265): [1] Libraries$2.run: Finished loading 1 libraries.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 6265): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/Zygote  ( 6312): MountEmulatedStorage()
,E/Zygote  ( 6312): v2
I/libpersona( 6312): KNOX_SDCARD checking this for 10094
,I/libpersona( 6312): KNOX_SDCARD not a persona
,I/SELinux ( 6312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6312): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6312): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6312 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,W/libprocessgroup( 1014): failed to open /acct/uid_10100/pid_5409/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6312): TimaSignature is unavailable
I/ActivityManager( 1014): Killing 5285:com.sec.android.provider.badge/u0a72 (adj 15): empty #31,
D/ActivityThread( 6312): Added TimaKeyStore provider
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 6265): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5129): mConnectivityHandler : connected
,D/Mms/MmsApp( 6166): [start]    initCountryIso consume time = 1004.961771
,D/CountryDetector( 1014): The first listener is added
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5429/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10072/pid_5285/cgroup.procs: No such file or directory
,D/elm:15183( 6312): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15183( 6312): ELMEngine.ELMEngine( context ).
,D/elm:15183( 6312): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1014): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 25046(1124KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 7.136ms total 213.254ms
,D/elm:15183( 6312): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,D/Mms/MmsApp( 6166): [end]    initCountryIso consume time = 39.13401
D/Mms/MmsConfig( 6166): [start]    MmsConfig.init() consume time = 0.13625
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/elm:15183( 6312): ElmAgentService : onCreate(),
D/elm:15183( 6312): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/Mms/MmsConfig( 6166): before partial update,
,E/Zygote  ( 6333): MountEmulatedStorage(),
E/Zygote  ( 6333): v2
I/libpersona( 6333): KNOX_SDCARD checking this for 10134
,I/libpersona( 6333): KNOX_SDCARD not a persona
,I/SELinux ( 6333): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6333): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/elm:15183( 6312): ELMAgentService.listeningToTimeDateChanges( context, intent ).,
I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6333 uid=10134 gids={50134, 9997} abi=armeabi-v7a
,D/elm:15183( 6312): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:15183( 6312): ModuleBase.ModifySetAlarm()
D/elm:15183( 6312): MDMBridge.getInstance()
D/elm:15183( 6312): MDMBridge.getAllLicenseInfoFromSDK()
,E/SELinux ( 6333): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,D/Mms/ArtClassLoader( 6166): init [DONE] art
,D/elm:15183( 6312): ElmAgentService : onDestroy().
,I/ActivityManager( 1014): Killing 5704:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
W/PCWCLIENTTRACE_AccountUtil( 5129): [hasSamungAccount] - No Samsung Account
,D/TimaKeyStoreProvider( 6333): TimaSignature is unavailable
,D/ActivityThread( 6333): Added TimaKeyStore provider
,D/Mms/MmsConfig( 6166): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 6166): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 6166): isAuth is false
D/Mms/MmsConfig( 6166): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1439): query,matched:2117, calling pid = 6166
,D/TP/MmsSmsProvider( 1439): match 2117:Elapsed time : 1.426 ms
,D/EasySignUpManager_1.0.1( 6166): isAuth is false
D/EasySignUpManager_1.0.1( 6166): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 6166): mps_code.dat does not exist
E/CscParser( 6166): customer_path =/system/csc/customer.xml
E/CscParser( 6166): fileName + /system/csc/customer.xml
,W/ResourcesManager( 6333): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6333): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5129): [GetString-S]
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/CscParser( 6166): mps_code.dat does not exist
E/CscParser( 6166): customer_path =/system/csc/customer.xml
E/CscParser( 6166): fileName + /system/csc/customer.xml
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ReactiveServiceManager( 5129): Supported : 1
,W/libprocessgroup( 1014): failed to open /acct/uid_10068/pid_5704/cgroup.procs: No such file or directory
,D/CscParser( 6166): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 6166):  enable multiwindow = true
,D/QSEECOMAPI: ( 1014): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1014): App is not loaded in QSEE
,E/Mms/MessageUtils( 6166): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 6166): updateCountryIso : update country iso info 
,I/ActivityManager( 1014): Killing 5723:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,D/Mms/MmsConfig( 6166): [end]    init() consume time = 191.614896
,D/Mms/Contact( 6166): [start]    init() consume time = 1.353958
,D/QSEECOMAPI: ( 1014): Loaded image: APP id = 10
,D/QSEECOMAPI: ( 1014): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1014): QSEECom_shutdown_app, app_id = 10
,E/terrier ( 1014): handleString: Failed to handle string(-4)
,E/terrier ( 1014): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5129): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5129): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5129): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5129): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5129): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5129): [ensureRegistration] - No Samsung account
,D/TP/MmsSmsProvider( 1439): query,matched:13, calling pid = 6166
,D/TP/MmsSmsProvider( 1439): match 13:Elapsed time : 3.151 ms
,D/Mms/Contact( 6166): [end]    init consume time = 37.053333
,D/Mms/DraftCache( 6166): [start]    rebuildCache consume time = 11.623698
,D/TP/MmsSmsProvider( 1439): query,matched:12, calling pid = 6166
,D/TP/MmsSmsProvider( 1439): match 12:Elapsed time : 2.046 ms
,D/Mms/MethodReflector( 6166): getSubId is called
D/Mms/TelephonyUtils( 6166): getLongSubId from simSlot 0, return Value = -1
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{177e07b5 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/Mms/MethodReflector( 6166): getTelephonyProperty is called
D/Mms/DownloadManager( 6166): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6166): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6166): auto download without roaming -> true
D/Mms/DownloadManager( 6166): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DraftCache( 6166): [end]    rebuildCache consume time = 19.64323
D/Mms/MethodReflector( 6166): getSubId is called
,D/Mms/MethodReflector( 6166): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 6166): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 6166): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 6166): getTelephonyProperty is called
D/Mms/DownloadManager( 6166): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 6166): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 6166): auto download without roaming -> true
D/Mms/DownloadManager( 6166): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 6166): auto download during roaming secondary -> false
D/Mms/DownloadManager( 6166): mAutoDownload ------> true
,D/ComposerPerformance( 6166): 1449746260302 ms / [DONE] Composer constructor
,E/CII     ( 6166): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 6166): ReservationManager()
,I/Mms/ReservationManager( 6166): resetAfterConnected()
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1439): query,matched:7, calling pid = 6166
,D/TP/MmsSmsProvider( 1439): match 7:Elapsed time : 2.463 ms
,D/Mms/Conversation( 6166): [start]    init() consume time = 71.293906
,W/libprocessgroup( 1014): failed to open /acct/uid_10069/pid_5723/cgroup.procs: No such file or directory
,D/TP/MmsSmsProvider( 1439): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1439): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1439): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1439): sUpgradeVersion = 0, db.getVersion() = 81
,D/TP/MmsSmsProvider( 1439): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1439): need read changed broadcast:false
,I/CalendarProvider2( 6203): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
D/Mms/Conversation( 6166): [end]    init consume time = 24.267969
,I/Mms/ReservationManager( 6166): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/MmsApp( 6166): [end]    onCreate() consume time = 6.992552
,I/ActivityManager( 1014): Killing 5571:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,D/Mms/MessagingNotification( 6166): [start]    init() consume time = 6.042604
,D/Mms/MessagingNotification( 6166): [end]    init consume time = 5.689271
,D/TP/MmsSmsProvider( 1439): query,matched:0, calling pid = 6166
V/TP/MmsSmsProvider( 1439): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1439): match 0:Elapsed time : 1.558 ms
,D/Mms/Synchronizer( 6166): [start]    doSync consume time = 8.731927
,D/TP/MmsSmsProvider( 1439): update, matched:300, calling pid = 6166
,V/TP/MmsSmsProvider( 1439): syncDBData start
,V/TP/MmsSmsProvider( 1439): syncDBData sms end
,V/TP/MmsSmsProvider( 1439): syncDBData mms end
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,V/TP/MmsSmsProvider( 1439): syncDBData end
,D/Mms/SpamFilter( 6166): [start]    SpamFilter fill() begin consume time = 15.850573
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/Mms/DownloadManager( 6166): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 6166): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 6166): getSubId is called
D/Mms/TelephonyUtils( 6166): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 6166): getTelephonyProperty is called
D/Mms/DownloadManager( 6166): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6166): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6166): auto download without roaming -> true
D/Mms/DownloadManager( 6166): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 6166): mAutoDownload ------> true
,E/Zygote  ( 6362): MountEmulatedStorage()
E/Zygote  ( 6362): v2
I/libpersona( 6362): KNOX_SDCARD checking this for 10072
I/libpersona( 6362): KNOX_SDCARD not a persona
,I/SELinux ( 6362): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6362 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/splitIntent( 1014): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
I/SELinux ( 6362): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6362): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 5603:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,D/Mms/Synchronizer( 6166): [end]    doSync consume time = 35.636822
,D/TP/MmsSmsProvider( 1439): query,matched:400, calling pid = 6166
,D/Mms/SpamFilter( 6166): [end]    SpamFilter fill() finished consume time = 6.363646
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,D/TimaKeyStoreProvider( 6362): TimaSignature is unavailable
,D/ActivityThread( 6362): Added TimaKeyStore provider
,D/BadgeProvider( 6362): onCreate
,D/BadgeProvider( 6362): DatabaseHelper
,D/Mms/MessagingNotification( 6166): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1439): query,matched:26, calling pid = 6166
,D/TP/SmsProvider( 1439): match 26:Elapsed time : 2.032 ms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/TP/MmsSmsProvider( 1439): query,matched:6, calling pid = 6166
,D/TP/MmsSmsProvider( 1439): match 6:Elapsed time : 2.094 ms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,I/ActivityManager( 1014): Killing 5129:com.sec.pcw.device/1000 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/ActivityManager( 1014): Killing 5614:com.android.email/u0a145 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10003/pid_5571/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10107/pid_5603/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6379): MountEmulatedStorage()
,E/Zygote  ( 6379): v2
I/libpersona( 6379): KNOX_SDCARD checking this for 10025
I/libpersona( 6379): KNOX_SDCARD not a persona
,I/SELinux ( 6379): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6379 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,I/SELinux ( 6379): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6379): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6379): TimaSignature is unavailable
,D/ActivityThread( 6379): Added TimaKeyStore provider
,I/ActivityManager( 1014): Killing 5825:com.android.chrome/u0a81 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5129/cgroup.procs: No such file or directory
,W/ResourcesManager( 6379): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/OMACP   ( 6379): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 6166): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/OMACP   ( 6379): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 6379): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 6379): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 6379): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 6379): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 6379): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 6379): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,W/libprocessgroup( 1014): failed to open /acct/uid_10145/pid_5614/cgroup.procs: No such file or directory
,I/OMACP   ( 6379): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
W/libprocessgroup( 1014): failed to open /acct/uid_10081/pid_5825/cgroup.procs: No such file or directory
,I/OMACP   ( 6379): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 6379): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 6379): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 6379): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 6379): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,I/art     ( 1618): Explicit concurrent mark sweep GC freed 3121(129KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.462ms total 38.290ms
,E/SMD     (  288): DCD OFF
,I/System.out( 1999): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1999): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1999): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1999): (HTTPLog)-Thread-274-493500234: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1999): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1999): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1999): Tagging socket 111 with tag 1000010400000000{268435716,0} for uid -1, pid: 1999, getuid(): 10012
,D/Finsky  ( 6265): [1095] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6265): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager( 1014): Killing 5841:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10159/pid_5841/cgroup.procs: No such file or directory
,I/qtaguid ( 1999): Untagging socket 111
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1014): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1014) eventTime = 101389
,D/PowerManagerService( 1014): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014 (0x0)
D/PowerManagerService( 1014): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1014, ws=WorkSource{1000}) (elapsedTime=3407)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
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
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1789): callingUid 10012, callindPid: 1789
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 5791): Conditions not met for autocaching.
,I/MusicLeanback( 5791): Stop autocaching.
,E/GmsUtils( 5791): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 5791): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/ActivityManager( 1014): Killing 5864:com.sec.android.soagent/u0a34 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10034/pid_5864/cgroup.procs: No such file or directory
,I/dhcpcd  ( 5748): wlan0: sending IPv6 Router Solicitation
,I/Mms/MmsApp( 6166):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 6166): [start]    fillCache consume time = 1923.267187
,D/Mms/ComposeMessageFragment( 6166): fillCache, easy = false
,D/AbsListView( 6166): Get MotionRecognitionManager
,D/MotionRecognitionService( 1014):  ssp status : false
,D/Mms/ComposeMessageFragment( 6166): [end]    fillCache consume time = 94.899323
,W/art     ( 6166): Suspending all threads took: 5.007ms
,D/SSRM:n  ( 1014): SIOP:: AP = 340
,D/Mms/BubbleViewCache( 6166): fillCache bubble = 1
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/GAV4    ( 5985): Thread[GAThread,5,main]: No campaign data found.
,I/PowerManagerService( 1014): [PWL] Off : 50s ago
,I/PowerManagerService( 1014): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1014): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1014): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10085, pid=6229, ws=null) (elapsedTime=3348)
,I/jxcore-log( 5479): Test app app.js loaded
I/jxcore-log( 5479): 
,I/chromium( 5479): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  288): DCD OFF
,D/FactoryTest( 4695): Not factory mode
,D/FactoryTest( 4695): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4695): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4695): still no open session command from host, so toast
,W/ContextImpl( 4695): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4695): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4695): Timeline: Activity_launch_request id:com.android.settings time:105938
,E/PersonaManagerService( 1014): inState():  stateMachine is null !!,
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1014): mDVFSHelper.acquire()
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1014): Focused application set to: xxxx
,D/InputDispatcher( 1014): Focus left window: 5479
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,E/MTPRx   ( 4695): started activity for popup
,I/dhcpcd  ( 5748): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 5748): wlan0: no IPv6 Routers available
,W/ResourcesManager( 4695): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 4695): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4695): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4695): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4695): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4695): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 4695): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1014): Focused application set to: xxxx
,D/InputDispatcher( 1014): Focus entered window: 5479
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1014): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@294b3f75 attribute=null, token = android.os.BinderProxy@3fa179a4
,D/SettingsReceiverActivity( 4695): dev.kiessupport is : TRUE
,D/PhoneWindow( 4695): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4695): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,V/ActivityThread( 5479): updateVisibility : ActivityRecord{2139249e token=android.os.BinderProxy@32999920 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 5479): Timeline: Activity_idle id: android.os.BinderProxy@32999920 time:106126
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PreloadUpdateManagerStateMachine( 5177): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5177): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5177): entry::CHECK_TIMEOUT_FOR_UPDATE
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/hcjo    ( 5177): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5177): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5177): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5177): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5177): entry::IDLE
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 3
,I/Atfwd_Sendcmd(  312): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  312): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ActivityManager( 1014): mDVFSHelper.release()
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 320
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 300
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,V/AlarmManager( 1014): waitForAlarm result :4
,V/AlarmManager( 1014): ___SyncScheduler (v3) ACTIVATED___
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
V/AlarmManagerEXT( 1014): <AppSync3 Whitelist>
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
V/AlarmManagerEXT( 1014): (AppSync) ### 0 added ###
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1014): [PWL] Off : 75s ago
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 2
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
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
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
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
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
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/Watchdog( 1014): !@Sync 4
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 290,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.metadata.ContactMetadataSyncService; callingUser = 0; userId(target) = 0
,E/ActivityThread( 1999): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 1014): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 128193, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 1014): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 221098, reason: UserStart
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1014): mCursor = null
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/PowerManagerService( 1014): [PWL] Off : 105s ago
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ClearcutLoggerApiImpl( 1789): disconnect managed GoogleApiClient
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 270
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 5
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 290,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/PowerManagerService( 1014): [PWL] Off : 140s ago,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/Watchdog( 1014): !@Sync 6
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1014): waitForAlarm result :4,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/Atfwd_Sendcmd(  312): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  312): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/Watchdog( 1014): !@Sync 7
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/Watchdog( 1014): !@Sync 8
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1014): [PWL] Off : 225s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1014): !@Sync 9
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
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
,D/QSEECOMAPI: ( 1014): App is not loaded in QSEE
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/QSEECOMAPI: ( 1014): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1014): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1014): Trustlet response is completed
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/Watchdog( 1014): !@Sync 10
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/Atfwd_Sendcmd(  312): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  312): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 275s ago
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1014): !@Sync 11
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1014): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
D/BatteryService( 1014): stay LED for fully charged,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/Watchdog( 1014): !@Sync 12
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 330s ago
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 6265): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6265): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6265): (HTTPLog)-Static: isShipBuild true
I/System.out( 6265): (HTTPLog)-Thread-1093-986130806: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 6265): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 6265): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 13
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 5531): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5531): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/jxcore-log( 5479): Toggling radios to false
I/jxcore-log( 5479): 
,D/BluetoothAdapter( 5479): disable()
,D/SettingsProvider( 1014): name = bluetooth_on,
,D/BluetoothAdapterState( 5531): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 5531): Setting state to 13
,I/BluetoothAdapterState( 5531): Bluetooth adapter state changed: 12-> 13
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/BluetoothAdapterService( 5531): Bluetooth PBAP supproted is true
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
D/BluetoothAdapterService( 5531): updateAdapterState state is 13
D/SecContentProvider( 1014): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1014): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1014): mCursor = null
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 5531): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
D/WifiService( 1014): setWifiEnabled: false pid=5479, uid=10175
,D/BluetoothAdapterService( 5531): Autoconnection is available 
D/BluetoothAdapterService( 5531): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 5531): terminating service from this receiver
D/BluetoothSocket( 5531): close() in, this: android.bluetooth.BluetoothSocket@6bb8e62, channel: 19, state: LISTENING
D/BluetoothSocket( 5531): close() this: android.bluetooth.BluetoothSocket@6bb8e62, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@eba080a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@509abf3mSocket: android.net.LocalSocket@87470b0 impl:android.net.LocalSocketImpl@2c09cb29 fd:FileDescriptor[74]
D/BluetoothSocket( 5531): Closing mSocket: android.net.LocalSocket@87470b0 impl:android.net.LocalSocketImpl@2c09cb29 fd:FileDescriptor[74]
D/SettingsProvider( 1014): name = wifi_on
,W/InputMethodManagerService( 1014): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1014): [BT Setting State] State =13
,I/jxcore-log( 5479): Radios toggled
I/jxcore-log( 5479): 
E/WifiStateMachine( 1014): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 5596): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5596): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 5596): P2P: Current p2p state = IDLE
I/wpa_supplicant( 5596): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BluetoothTile( 1174):  onBluetoothStateChange:
,I/SamsungIME( 1777): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1174): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1174):  getBluetoothState : 13
,V/BluetoothEventManager( 1281): Received android.bluetooth.adapter.action.STATE_CHANGED
,E/WifiNative-wlan0( 1014): do suspend true
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/StatusBarManagerService( 1014): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1014): setIconVisibility slot=bluetooth visible=false
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,D/PhoneStatusBar( 1174): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/PhoneStatusBar( 1174): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
D/BluetoothTile( 1174):  handleUpdatestate:false name:null
W/ContextImpl( 1281): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/STATUSBAR-QSTileView( 1174): onStateChanged: Bluetooth
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/ActivityManager( 1014): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
D/BluetoothSocket( 5531): close() in, this: android.bluetooth.BluetoothSocket@6c82eae, channel: 5, state: LISTENING
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
D/BluetoothSocket( 5531): close() this: android.bluetooth.BluetoothSocket@6c82eae, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3564a87b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a09144fmSocket: android.net.LocalSocket@2e27e7dc impl:android.net.LocalSocketImpl@3fcaf0e5 fd:FileDescriptor[76]
D/BluetoothSocket( 5531): Closing mSocket: android.net.LocalSocket@2e27e7dc impl:android.net.LocalSocketImpl@3fcaf0e5 fd:FileDescriptor[76]
I/BtOppRfcommListener( 5531): stopping Accept Thread
D/BluetoothSocket( 5531): close() in, this: android.bluetooth.BluetoothSocket@34ec87ba, channel: 12, state: LISTENING
D/BluetoothSocket( 5531): close() this: android.bluetooth.BluetoothSocket@34ec87ba, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10fcc92d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@deca66bmSocket: android.net.LocalSocket@2a39a5c8 impl:android.net.LocalSocketImpl@bbeb661 fd:FileDescriptor[80]
D/BluetoothSocket( 5531): Closing mSocket: android.net.LocalSocket@2a39a5c8 impl:android.net.LocalSocketImpl@bbeb661 fd:FileDescriptor[80]
D/BluetoothAdapterProperties( 5531): onBluetoothDisable()
D/BluetoothAdapterProperties( 5531): mDiscovering is false
,D/SecContentProvider( 1014): uri = 3 selection = isDiscoverableEnabled
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/BluetoothAdapterState( 5531): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
E/BtOppRfcommListener( 5531): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 5531): BluetoothSocket listen thread finished
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/BluetoothPbap( 1281): Proxy object disconnected
D/PbapServerProfile( 1281): Bluetooth service disconnected
,D/DockEventReceiver( 1281): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1281): onReceive
,D/BluetoothUtils( 5531): getBtEnabledContainers(): btContainers = []
D/BluetoothAdapterProperties( 5531): Scan Mode:20
,D/BluetoothAdapterState( 5531): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 5531): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1,
E/bt-btif ( 5531): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
E/bt-btif ( 5531): cmd socket is not created
D/btif_config_util( 5531): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 5531): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 5531): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,V/BluetoothStatusReceiver( 1174): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1174): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
W/bt-l2cap( 5531): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5531): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5531): L2CAP - PSM: 0x001b not found for deregistration
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6559): MountEmulatedStorage(),
I/libpersona( 6559): KNOX_SDCARD checking this for 10003
E/Zygote  ( 6559): v2
I/libpersona( 6559): KNOX_SDCARD not a persona
I/SELinux ( 6559): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6559 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
I/SELinux ( 6559): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6559): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/BluetoothOppManager( 5531): cleanUp...
,D/TimaKeyStoreProvider( 6559): TimaSignature is unavailable
,D/ActivityThread( 6559): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider( 6559): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager( 6559): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 6559): SecurePlaceDbHelper() 
D/UserAnalysis( 6559): Create SecureDbHelper
,D/IntelligenceServiceApplication( 6559): onCreate()
,I/ActivityManager( 1014): Killing 5059:com.android.defcontainer/u0a4 (adj 15): empty #31
,D/IntelligenceServiceApplication( 6559): no applications having user consent for prediction
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6574): MountEmulatedStorage(),
E/Zygote  ( 6574): v2
I/libpersona( 6574): KNOX_SDCARD checking this for 10107
I/libpersona( 6574): KNOX_SDCARD not a persona
,I/SELinux ( 6574): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6574 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 6559): [PlaceDetection::stopService] Service stopped.
,I/SELinux ( 6574): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6574): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/PlaceDetection v1.0.19 ( 6559): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,W/bt-l2cap( 5531): btif_mce_execute_se not  enable:0
,W/bt-l2cap( 5531): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5531): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5531): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5531): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5531): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5531): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 5531): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5531): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 5531): ag scb idx 1 not allocated
W/bt-btif ( 5531): ag scb idx 2 not allocated
E/bt-btif ( 5531): BTA AG is already disabled, ignoring ...
I/bt_userial_mct( 5531): exiting userial_read_thread
D/bt_userial_mct( 5531): Leaving userial_evt_read_thread()
D/bt_userial_mct( 5531): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 5531): hw_epilog_process,
I/art     (  303): Explicit concurrent mark sweep GC freed 8682(369KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 990us total 40.039ms
D/bt_userial_mct( 5531): userial_close
I/bt_vendor( 5531): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/TimaKeyStoreProvider( 6574): TimaSignature is unavailable
,D/ActivityThread( 6574): Added TimaKeyStore provider
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 734us total 34.007ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 859us total 20.858ms
,W/libprocessgroup( 1014): failed to open /acct/uid_10004/pid_5059/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/StrictMode( 6574): StrictMode policy violation; ~duration=193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6574): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6574): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 6574): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 6574): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 6574): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 6574): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 6574): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 6574): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 6574): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6574): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6574): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 6574): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 6574): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 6574): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6574): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6574): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 6574): StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6574): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6574): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 6574): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 6574): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 6574): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 6574): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 6574): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6574): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6574): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 6574): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 6574): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 6574): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6574): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6574): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 6574): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 6574): StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6574): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6574): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 6574): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 6574): 	at java.io.File.exists(File.java:363)
D/StrictMode( 6574): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 6574): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 6574): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 6574): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 6574): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6574): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6574): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 6574): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 6574): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 6574): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6574): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6574): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 6574): StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6574): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6574): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 6574): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 6574): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 6574): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 6574): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 6574): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6574): 	at android.app.Instrumentation.callApplicationOnCreate(Instrume,ntation.java:1020)
D/StrictMode( 6574): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 6574): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 6574): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 6574): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6574): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6574): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 6574): StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6574): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6574): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 6574): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 6574): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 6574): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 6574): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 6574): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6574): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6574): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 6574): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 6574): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 6574): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6574): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6574): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 6574): StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6574): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6574): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 6574): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 6574): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 6574): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 6574): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 6574): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 6574): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 6574): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 6574): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 6574): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 6574): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 6574): 	at com.google.r.e.b(PG:170)
D/StrictMode( 6574): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 6574): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6574): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6574): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 6574): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 6574): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 6574): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6574): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6574): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/ActivityManager( 1014): Killing 5964:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
D/StrictMode( 6574): StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6574): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6574): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 6574): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 6574): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 6574): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 6574): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 6574): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 6574): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 6574): 	at com.google.r.k.c(PG:583)
D/StrictMode( 6574): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 6574): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 6574): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 6574): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 6574): 	at com.google.r.e.b(PG:170)
D/StrictMode( 6574): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 6574): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6574): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6574): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 6574): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 6574): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 6574): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6574): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6574): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 6574): StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6574): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6574): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 6574): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 6574): 	at java.io.File.exists(File.java:363)
D/StrictMode( 6574): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 6574): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 6574): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 6574): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 6574): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6574): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6574): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 6574): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 6574): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 6574): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6574): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6574): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 6574): StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6574): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6574): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 6574): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 6574): 	at java.io.File.exists(File.java:363)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 6574): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6574): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6574): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6574): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 6574): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 6574): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 6574): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6574): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6574): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6574): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 6574): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/bt_vendor( 5531): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 5531): bluetooth satus is on
I/bt_vendor( 5531): bt-vendor : resetting BT status
I/bt_vendor( 5531): Starting hciattach daemon
I/bt_vendor( 5531): try to set false
D/AuthorizationBluetoothService( 1789): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/bt_vendor( 5531): Starting hciattach daemon
I/bt_vendor( 5531): try to set false
I/bt_vendor( 5531): cleanup
I/GKI_LINUX( 5531): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 5531): GKI_exit_task 0 done
I/GKI_LINUX( 5531): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 5531): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 5531): isSecureModeOn:false
D/BluetoothAdapterService( 5531): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 5531): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5531): Not skipping com.android.bluetooth.gatt.GattService
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5531): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 5531): handleDebugAction() action=null
D/BtGatt.GattService( 5531): Received stop request...Stopping profile...
D/BtGatt.GattService( 5531): stop()
D/BtGatt.AdvertiseManager( 5531): advertise clients cleared
W/BluetoothAdapterService( 5531): Not skipping com.android.bluetooth.hfp.HeadsetService
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
W/BluetoothAdapterService( 5531): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5531): Not skipping com.android.bluetooth.a2dp.A2dpService
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/HeadsetService( 5531): Received stop request...Stopping profile...
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5531): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
D/AudioService( 1014): onServiceDisconnected: Bluetooth profile: 1
W/BluetoothAdapterService( 5531): Not skipping com.android.bluetooth.hid.HidService
D/HeadsetProfile( 1281): Bluetooth service disconnected
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5531): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5531): Not skipping com.android.bluetooth.hdp.HealthService
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5531): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5531): Not skipping com.android.bluetooth.pan.PanService
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5531): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityThread( 6574): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/BluetoothAdapterService( 5531): Not skipping com.android.bluetooth.map.BluetoothMapService
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5531): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/libprocessgroup( 1014): failed to open /acct/uid_10002/pid_5964/cgroup.procs: No such file or directory
W/BluetoothAdapterService( 5531): Not skipping com.broadcom.bt.service.sap.SapService
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
I/System.out( 6574): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/System.out( 6574): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6574): (HTTPLog)-Static: isShipBuild true
I/System.out( 6574): (HTTPLog)-Thread-1114-798181609: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6574): (HTTPLog)-Static: isSBSettingEnabled false
W/BluetoothAdapterService( 5531): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5531): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5531): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5531): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5531): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5531): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5531): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5531): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 5531): Stopping profile services that were post enabled
E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/A2dpService( 5531): Received stop request...Stopping profile...
D/A2dpStateMachine( 5531): Exit Disconnected: -1
D/EnterpriseController(  278): uids 10107
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10107
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
D/BluetoothA2dp( 1014): Proxy object disconnected
D/AudioService( 1014): onServiceDisconnected: Bluetooth profile: 2
D/BluetoothA2dp( 2689): Proxy object disconnected
D/BluetoothA2dp( 1281): Proxy object disconnected
D/A2dpProfile( 1281): Bluetooth service disconnected
E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5531): Profile still running: com.android.bluetooth.hid.HidService
W/BluetoothHeadsetServiceJni( 5531): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 5531): Cleaning up Bluetooth Handsfree callback object
D/HidService( 5531): Received stop request...Stopping profile...
D/HidService( 5531): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 5531): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 5531): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5531): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
D/HealthService( 5531): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
D/PanService( 5531): Received stop request...Stopping profile...
D/BluetoothInputDevice( 1281): Proxy object disconnected
D/HidProfile( 1281): Bluetooth service disconnected
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
D/BluetoothPan( 1014): BluetoothPAN Proxy object disconnected
D/BluetoothMapService( 5531): Received stop request...Stopping profile...
D/BluetoothPan( 1281): BluetoothPAN Proxy object disconnected
D/PanProfile( 1281): Bluetooth service disconnected
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
,D/SapService( 5531): Received stop request...Stopping profile...
,D/SapService( 5531): Stopping Bluetooth SapService
D/BluetoothAdapterService( 5531): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d153f0
,E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5531): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 5531): Proxy object disconnected
D/BluetoothAdapterService( 5531): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 5531): gki_task task_id=2 [A2DP-MEDIA] terminating
D/BluetoothMap( 1281): Proxy object disconnected
D/MapProfile( 1281): Bluetooth service disconnected
,I/GKI_LINUX( 5531): GKI_exit_task 2 done
I/GKI_LINUX( 5531): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/Bluetoothsap( 1281): BluetoothSAP Proxy object disconnected
D/SapProfile( 1281): Bluetooth service disconnected
E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5531): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5531): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 5531): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 5531): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5531): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 5531): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5531): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5531): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5531): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(869356528)( 5531): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 5531): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 5531): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/BluetoothAdapterState( 5531): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 5531): Setting state to 10
I/BluetoothAdapterState( 5531): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 5531): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5531): updateAdapterState state is 10
,D/BluetoothAdapterService( 5531): Autoconnection is available 
D/BluetoothAdapterService( 5531): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 5531): Entering OffState
D/BluetoothInputDevice( 1281): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1281): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1281): Bluetooth is turned off, stop adv and scan
,W/com.google.a.a.b.d.a( 6574): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothA2dp( 5531): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1014): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1014): Bluetooth is turned off, stop adv and scan
D/Bluetoothsap( 1281): onBluetoothStateChange: up=false
D/Bluetoothsap( 1281): Unbinding service...
,D/BluetoothAdapter( 1430): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1430): Bluetooth is turned off, stop adv and scan
D/BluetoothPbap( 1281): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 2689): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 2689): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1174): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1174): Bluetooth is turned off, stop adv and scan
D/BluetoothA2dp( 2689): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 5479): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 5479): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1419): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1419): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 5531): onBluetoothStateChange: up=false
D/BluetoothAdapter( 5531): Bluetooth is turned off, stop adv and scan
,D/BluetoothA2dp( 1281): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1439): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1439): Bluetooth is turned off, stop adv and scan
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/BluetoothAdapter( 1789): onBluetoothStateChange: up=false
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/BluetoothAdapter( 1789): Bluetooth is turned off, stop adv and scan
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/BluetoothA2dp( 1014): onBluetoothStateChange: up=false
,D/BluetoothMap( 1281): onBluetoothStateChange: up=false
,D/BluetoothManagerService( 1014): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService( 1014): Broadcasting onBluetoothServiceUp() to 0 receivers.
,W/InputMethodManagerService( 1014): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1014): [BT Setting State] State =10
I/InputMethodManagerService( 1014): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothAdapter( 1174): 902071433: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,D/BluetoothAdapter( 1174): 902071433: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1174): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1174):  getBluetoothState : 10
D/BluetoothAdapter( 1174): 902071433: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1174): 902071433: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService( 1014): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/BluetoothAdapter( 1174): 902071433: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 1014): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1174): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,I/SamsungIME( 1777): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,V/BluetoothEventManager( 1281): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter( 1789): 793361640: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1789): 793361640: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 5531): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 5531): GKI_exit_task 1 done
I/GKI_LINUX( 5531): GKI_shutdown(): task [BTIF] terminated
W/ContextImpl( 1281): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/BluetoothServiceJni( 5531): cleanupNative: return from cleanup
D/ActivityManager( 1014): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,I/art     ( 5531): System.exit called, status: 0
I/AndroidRuntime( 5531): VM exiting with result code 0, cleanup skipped.
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/DockEventReceiver( 1281): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1281): onReceive
,V/BluetoothStatusReceiver( 1174): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1174): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/CommandListener(  278): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1789): Read error: ssl=0xb7df5d90: I/O error during system call, Connection timed out
V/NativeCrypto( 1789): SSL shutdown failed: ssl=0xb7df5d90: I/O error during system call, Broken pipe
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): ValidatedState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1014): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): DefaultState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 1000
,I/ActivityManager( 1014): Process com.android.bluetooth (pid 5531)(adj 0) has died(55,1102)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1014): updateNetworkInfo()
,D/ConnectivityService( 1014): Validated NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Validated
D/ConnectivityService( 1014): rematching NetworkAgentInfo [WIFI () - 502]
E/ConnectivityService( 1014): updateNetworkInfo()
,D/ConnectivityService( 1014): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 1014): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
,D/EntConnectivity( 1014): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/BluetoothAdapter( 6574): 
E/BluetoothAdapter( 6574): android.os.DeadObjectException
E/BluetoothAdapter( 6574): 	at android.os.BinderProxy.transactNative(Native Method)
E/BluetoothAdapter( 6574): 	at android.os.BinderProxy.transact(Binder.java:511)
E/BluetoothAdapter( 6574): 	at android.bluetooth.IBluetooth$Stub$Proxy.isEnabled(IBluetooth.java:1218)
E/BluetoothAdapter( 6574): 	at android.bluetooth.BluetoothAdapter.isEnabled(BluetoothAdapter.java:702)
E/BluetoothAdapter( 6574): 	at com.google.android.apps.gmm.iamhere.ble.m.b(PG:7267)
E/BluetoothAdapter( 6574): 	at com.google.android.apps.gmm.iamhere.ble.x.run(PG:38)
E/BluetoothAdapter( 6574): 	at com.google.android.apps.gmm.shared.f.a.k.run(PG:29)
E/BluetoothAdapter( 6574): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BluetoothAdapter( 6574): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BluetoothAdapter( 6574): 	at java.lang.Thread.run(Thread.java:818)
,D/ConnectivityManager.CallbackHandler( 1999): CM callback handler got msg 524290
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiScanningService( 1014): SCAN_AVAILABLE : 1
D/WifiP2pService( 1014): InactiveState{ what=131204 }
D/WifiScanningService( 1014): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1014): P2pEnabledState{ what=131204 }
D/RttService( 1014): SCAN_AVAILABLE : 1
D/RttService( 1014): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/BluetoothAdapter( 6574): 
E/BluetoothAdapter( 6574): android.os.DeadObjectException
E/BluetoothAdapter( 6574): 	at android.os.BinderProxy.transactNative(Native Method)
E/BluetoothAdapter( 6574): 	at android.os.BinderProxy.transact(Binder.java:511)
E/BluetoothAdapter( 6574): 	at android.bluetooth.IBluetooth$Stub$Proxy.isEnabled(IBluetooth.java:1218)
E/BluetoothAdapter( 6574): 	at android.bluetooth.BluetoothAdapter.isEnabled(BluetoothAdapter.java:702)
E/BluetoothAdapter( 6574): 	at com.google.android.apps.gmm.iamhere.ble.m.b(PG:7267)
E/BluetoothAdapter( 6574): 	at com.google.android.apps.gmm.iamhere.ble.x.run(PG:38)
E/BluetoothAdapter( 6574): 	at com.google.android.apps.gmm.shared.f.a.k.run(PG:29)
E/BluetoothAdapter( 6574): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BluetoothAdapter( 6574): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BluetoothAdapter( 6574): 	at java.lang.Thread.run(Thread.java:818)
,D/WifiP2pService( 1014): sending p2p connection changed broadcast: FAILED
,D/WifiNetworkAgent( 1014): NetworkAgent: NetworkAgent channel lost
,D/AuthorizationBluetoothService( 1789): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/WifiDisplayController( 1014): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/WifiDisplayAdapter( 1014): onP2pDisconnected
D/IpRemoteDisplayController( 1014): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1014): WfdBridgeServer is already null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/WifiP2pService( 1014): sending p2p connection changed broadcast: DISCONNECTED
I/Hs20UtilService( 3452): Starting #8
,I/Hs20UtilService( 3452): Message received 5007
,E/WifiStateMachine( 1014): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 1014): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1014): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1014): disconnect
D/WifiDisplayController( 1014): updateConnection
D/WifiDisplayController( 1014): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1281): DMSUtil.isNetworkConnected - flag-null, state-null
D/AllShareCastTile( 1174): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/AllShareCastTile( 1174): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
I/NearbySettings( 1281): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1281): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1281): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService( 1014): P2pDisablingState
,D/WifiP2pService( 1014): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1014): p2p socket connection lost
,E/WifiNative-wlan0( 1014): do suspend true
D/WifiP2pService( 1014): P2pDisabledState
D/ConnectivityService( 1014): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1014): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1014): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI_P2P( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1014): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1439): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1014): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityManager.CallbackHandler( 1999): CM callback handler got msg 524292
D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1439): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiDisplayController( 1014): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1014): onP2pDisconnected
D/IpRemoteDisplayController( 1014): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1014): WfdBridgeServer is already null
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524292
,D/ConnectivityService( 1014): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): doQuit - quitNow()
E/ConnectivityService( 1014): updateNetworkInfo()
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1014): updateNetworkInfo()
,D/Tethering( 1014): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1014): MasterInitialState.processMessage what=3
D/EntConnectivity( 1014): Not allowed due to - mEnabled false - primarySimSlot false
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): updateIfacesLocked()
D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
V/NetworkStats( 1014): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): performPollLocked() took 8ms
D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1281): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1281): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1281): MountReceiver.mPrefHandler - 7002
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6613): MountEmulatedStorage(),
,I/libpersona( 6613): KNOX_SDCARD checking this for 10068
E/Zygote  ( 6613): v2
I/libpersona( 6613): KNOX_SDCARD not a persona
I/SELinux ( 6613): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6613 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6613): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6613): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6613): TimaSignature is unavailable
,D/ActivityThread( 6613): Added TimaKeyStore provider
,W/ResourcesManager( 6613): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3
,D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3
,D/FileShare-Client( 6613): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3
,D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3
D/FileShare-Client( 6613): ClientBroadcastReceiver.onReceive - disconnected
D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3
,D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3
,D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3
D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3
,D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3
D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3
,D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3
,D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3
,D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3,
D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3
,D/PhoneApp( 1439): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1439): FileWriteThread : threadType = 3
,D/FileShare-Client( 6613): Outbound.stopDelayTimer - 
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6643): MountEmulatedStorage(),
E/Zygote  ( 6643): v2
I/libpersona( 6643): KNOX_SDCARD checking this for 10069
I/libpersona( 6643): KNOX_SDCARD not a persona
I/SELinux ( 6643): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6643): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6643 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6643): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 5985:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6643): TimaSignature is unavailable
D/ActivityThread( 6643): Added TimaKeyStore provider
,D/FileShare-Server( 6643): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1014): Killing 5886:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/libprocessgroup( 1014): failed to open /acct/uid_10113/pid_5985/cgroup.procs: No such file or directory,
W/libprocessgroup( 1014): failed to open /acct/uid_10044/pid_5886/cgroup.procs: No such file or directory
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1014): updateDataUsageMap
,I/DBG_DM  ( 2940): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 2940): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6658): MountEmulatedStorage(),
E/Zygote  ( 6658): v2
I/libpersona( 6658): KNOX_SDCARD checking this for 1000
I/libpersona( 6658): KNOX_SDCARD not a persona
,I/SELinux ( 6658): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6658 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6658): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6658): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6658): TimaSignature is unavailable
,D/ActivityThread( 6658): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 6658): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 6658): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6658): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 6658): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6658): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6658): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6658): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1014): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,I/splitIntent( 1014): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6658): noConnectivity : true
,V/MusicLeanback( 5791): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
D/accuweather( 1705): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6675): MountEmulatedStorage()
,E/Zygote  ( 6675): v2
I/libpersona( 6675): KNOX_SDCARD checking this for 10145
I/libpersona( 6675): KNOX_SDCARD not a persona
I/SELinux ( 6675): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6675): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6675): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6675 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/daemonapp( 1332): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,I/ActivityManager( 1014): Killing 6009:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/accuweather( 1705): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1705): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1705): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1705): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.183: ( 3491): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 12:22:53 GMT+01:00 2015
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/TimaKeyStoreProvider( 6675): TimaSignature is unavailable
,D/ActivityThread( 6675): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3491): KLMSAbstractReciever(): onReceive().END.
,D/accuweather( 1705): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1705): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,I/KLMS-2.5.183: ( 3491): KLMSIntentService(): onCreate()
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3491): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/ResourcesManager( 6675): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6675): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6675): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6675): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6675): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/KLMS-2.5.183: ( 3491): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3491): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3491): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  ( 6691): MountEmulatedStorage()
E/Zygote  ( 6691): v2
I/libpersona( 6691): KNOX_SDCARD checking this for 10081
I/libpersona( 6691): KNOX_SDCARD not a persona
,I/SELinux ( 6691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6691 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast,
I/SELinux ( 6691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 6691): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3491): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3491): StateImplV2(): networkChangeListener().END
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 5
,E/Zygote  ( 6700): MountEmulatedStorage(),
E/Zygote  ( 6700): v2
I/libpersona( 6700): KNOX_SDCARD checking this for 10034
I/libpersona( 6700): KNOX_SDCARD not a persona
I/SELinux ( 6700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6700): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6700 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6691): TimaSignature is unavailable
,D/ActivityThread( 6691): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3491): KLMSIntentService(): onDestroy()
,D/WifiP2pService( 1014): P2pDisabledState{ what=143375 }
,D/WifiP2pService( 1014): DefaultState{ what=143375 }
,D/TimaKeyStoreProvider( 6700): TimaSignature is unavailable
,D/ActivityThread( 6700): Added TimaKeyStore provider
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/wpa_supplicant( 5596): p2p0: State: DISCONNECTED -> DISCONNECTED
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_6009/cgroup.procs: No such file or directory
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
D/WIFI    ( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1174): Wifi onReceive(0)
D/HotspotTile( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1174): onStateChanged: Wi-Fi
D/HotspotTile( 1174): onReceive : 0, 0
,D/WifiCredService( 1281): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/wpa_supplicant( 5596): Blacklist: Clear (all) 
,I/SO_AGENT( 6700): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,E/SPPClientService( 5234): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 5378): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5378): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5378): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/ActivityManager( 1014): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 5204): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
I/DBG_POLICYDM( 5204): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5204): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,I/SA      ( 5378): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/DBG_POLICYDM( 5204): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 2, current network is 0
I/SA      ( 5378): [OR] == isSIMCardReady false ==
,E/DBG_POLICYDM( 5204): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,I/SA      ( 5378): [SCU] == networkStateCheck == false
I/SA      ( 5378): [OR] onReceive END
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,V/DownloadManager( 1230): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/SPPClientService( 5234): [[SystemStateMonitorService]] No Active Internet
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6729): MountEmulatedStorage()
,E/Zygote  ( 6729): v2
I/libpersona( 6729): KNOX_SDCARD checking this for 10002
I/libpersona( 6729): KNOX_SDCARD not a persona
,I/SELinux ( 6729): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6729 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/SELinux ( 6729): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6729): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 6107:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,I/wpa_supplicant( 5596): p2p0: CTRL-EVENT-TERMINATING 
,I/Nat464Xlat( 1014): interfaceLinkStateChanged p2p0, false
D/Tethering( 1014): interfaceLinkStateChanged p2p0, false
D/Tethering( 1014): interfaceStatusChanged p2p0, false
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6729): TimaSignature is unavailable
,D/ActivityThread( 6729): Added TimaKeyStore provider
,E/Zygote  ( 6746): MountEmulatedStorage()
E/Zygote  ( 6746): v2
I/libpersona( 6746): KNOX_SDCARD checking this for 10113
I/libpersona( 6746): KNOX_SDCARD not a persona
,I/SELinux ( 6746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/wpa_supplicant( 5596): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 5596): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 5596): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 5596): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 5596): wlan0: State: DISCONNECTED -> DISCONNECTED
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
I/SELinux ( 6746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
D/Tethering( 1014): InitialState.processMessage what=4
,E/Tethering( 1014): No numeric data
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
I/ActivityManager( 1014): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6746 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6746): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 6128:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,D/Tethering( 1014): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1014): clearTetheredNotification()
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1174): updateTetherState():false, false
,V/NetworkStats( 1014): performPollLocked() took 3ms
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 6746): TimaSignature is unavailable
,D/ActivityThread( 6746): Added TimaKeyStore provider
,D/BadgeProvider( 6362): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/BadgeProvider( 6362): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6362): sendNotify, [notify] : null
D/BadgeProvider( 6362): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6362): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6362): update, [UpdateCount] : 1
,D/Launcher.Model( 1468): reloadBadges entered.
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,W/libprocessgroup( 1014): failed to open /acct/uid_10125/pid_6107/cgroup.procs: No such file or directory
,E/Zygote  ( 6766): MountEmulatedStorage()
I/libpersona( 6766): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6766): v2
I/libpersona( 6766): KNOX_SDCARD not a persona
I/SELinux ( 6766): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6766): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6766): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6766 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/libprocessgroup( 1014): failed to open /acct/uid_10062/pid_6128/cgroup.procs: No such file or directory
,D/SecurityLogAgent( 5673): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5673): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5673): StateMachine : Current State = 1
,D/SecurityLogAgent( 5673): StateMachine : Changed Current State = 1
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,D/TimaKeyStoreProvider( 6766): TimaSignature is unavailable
,D/ActivityThread( 6766): Added TimaKeyStore provider
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 5596): Blacklist: Clear (all) 
,E/Zygote  ( 6781): MountEmulatedStorage()
,E/Zygote  ( 6781): v2
I/libpersona( 6781): KNOX_SDCARD checking this for 10159
I/libpersona( 6781): KNOX_SDCARD not a persona
,I/SELinux ( 6781): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6781 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 6166:com.android.mms/u0a46 (adj 15): empty #31,
,I/SELinux ( 6781): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6781): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6781): TimaSignature is unavailable
,D/ActivityThread( 6781): Added TimaKeyStore provider
,I/wpa_supplicant( 5596): wlan0: CTRL-EVENT-TERMINATING 
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,I/DIAGMON_AGENT( 6766): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/CountryDetector( 1014): No listener is left
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 85663(5MB) AllocSpace objects, 130(2MB) LOS objects, 33% free, 27MB/41MB, paused 4.105ms total 185.358ms
,W/libprocessgroup( 1014): failed to open /acct/uid_10046/pid_6166/cgroup.procs: No such file or directory
,I/iu.Environment( 1999): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1999): num queued entries: 0
I/ActivityManager( 1014): Killing 6178:com.samsung.android.sm/1000 (adj 15): empty #31
,I/iu.UploadsManager( 1999): num updated entries: 0
,I/iu.SyncManager( 1999): NEXT; no task
,I/ActivityManager( 1014): Killing 6219:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/WifiStateMachine( 1014): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,W/Settings( 5915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-wlan0( 1014): callSECApiBoolean - ID [21]
E/WifiConfigStore( 1014): setLastSelectedConfiguration -1
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1174): Wifi onReceive(1)
,D/HotspotTile( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/WifiCredService( 1281): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1174): onStateChanged: Wi-Fi
,D/HotspotTile( 1174): onReceive : 1, 0
,W/Settings( 1789): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DIAGMON_AGENT( 6766): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6766): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6766): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6766): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6766): ./extraInfo: <unknown ssid>
W/DIAGMON_AGENT( 6766): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,I/ActivityManager( 1014): Killing 6229:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_6178/cgroup.procs: No such file or directory
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6746): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6746): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6746): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6746): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1014): failed to open /acct/uid_10157/pid_6219/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10085/pid_6229/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6746): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/LibraryLoader( 6746): Time to load native libraries: 2 ms (timestamps 4539-4541)
,I/LibraryLoader( 6746): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6746): Binding Chromium to main looper Looper (main, tid 1) {3fcaf0e5}
,I/LibraryLoader( 6746): Expected native library version number "",actual native library version number ""
,I/chromium( 6746): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6746): Initializing chromium process, singleProcess=true
,W/art     ( 6746): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6746): ApplicationContext is null in ApplicationStatus
,W/chromium( 6746): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6746): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,I/chromium( 6746): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,I/Adreno-EGL( 6746): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6746): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6746): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6746): Local Branch: 
I/Adreno-EGL( 6746): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6746): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6746):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6746): Requires BLUETOOTH permission
,I/NSApplication( 6746): Starting up...
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6837): MountEmulatedStorage()
I/libpersona( 6837): KNOX_SDCARD checking this for 10125
E/Zygote  ( 6837): v2
I/libpersona( 6837): KNOX_SDCARD not a persona
,I/SELinux ( 6837): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6837): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6837): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6837 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
I/ActivityManager( 1014): Killing 6250:com.qualcomm.timeservice/1000 (adj 15): empty #31
,I/art     (  303): Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.046ms total 40.356ms,
,D/TimaKeyStoreProvider( 6837): TimaSignature is unavailable
,D/ActivityThread( 6837): Added TimaKeyStore provider
,W/ResourcesManager( 6837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 724us total 23.253ms
,D/QuickConnect( 6837): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6837): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 783us total 20.652ms
,I/QuickConnect( 6837): PeriphStartReceiver.onReceive - no need to start
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1014): Killing 6203:com.android.providers.calendar/u0a42 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3452): Starting #9
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1281): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 3452): Message received 5007
I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1281): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1281): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1281): MountReceiver.mPrefHandler - 7002
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/Tethering( 1014): interfaceRemoved wlan0
,E/Tethering( 1014): attempting to remove unknown iface (wlan0), ignoring
D/SecurityLogAgent( 5673): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5673): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5673): StateMachine : Current State = 1
D/SecurityLogAgent( 5673): StateMachine : Changed Current State = 1
I/Hs20UtilService( 3452): Starting #10
,I/Hs20UtilService( 3452): Message received 5011
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3452): Starting #11
I/Hs20UtilService( 3452): Message received 5011
,D/SecurityLogAgent( 5673): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5673): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5673): StateMachine : Current State = 1
D/SecurityLogAgent( 5673): StateMachine : Changed Current State = 1
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_6250/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10042/pid_6203/cgroup.procs: No such file or directory
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/Tethering( 1014): interfaceRemoved p2p0
E/Tethering( 1014): attempting to remove unknown iface (p2p0), ignoring
,E/SMD     (  288): DCD OFF
,E/WifiStateMachine( 1014): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/GAV4    ( 6746): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 14,
,I/Atfwd_Sendcmd(  312): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  312): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 390s ago,
I/PowerManagerService( 1014): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1014): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1014): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1014, ws=null) (elapsedTime=29655)
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 15
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/ConnectivityService( 1014): Failed to find a new network - expiring NetTransition Wakelock
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/bootchecker(  309): bootchecker wake up!!
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 16
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1014): [PWL] Off : 455s ago
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 17
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/ServiceManager(  312): Waiting for service AtCmdFwd...,
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1014): !@Sync 18
,I/Atfwd_Sendcmd(  312): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  312): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1014): [PWL] Off : 525s ago,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/Atfwd_Daemon(  312): Stop the daemon....,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 19
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
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
,E/Watchdog( 1014): !@Sync 20
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1014): !@Sync 21
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1014): [PWL] Off : 600s ago
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 22
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
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
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 23
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1014): [PWL] Off : 680s ago
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 24
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 25
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
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
,E/Watchdog( 1014): !@Sync 26
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1999): Aggregate from 1449744720479 (log), 1449744720479 (data)
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7017): MountEmulatedStorage()
I/libpersona( 7017): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7017): v2
I/libpersona( 7017): KNOX_SDCARD not a persona
,I/SELinux ( 7017): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 7017): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7017 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 7017): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7017): TimaSignature is unavailable
,D/ActivityThread( 7017): Added TimaKeyStore provider
,W/ResourcesManager( 7017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1014): Killing 6265:com.android.vending/u0a28 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10028/pid_6265/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 765s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 27
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :8
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
,E/Watchdog( 1014): !@Sync 28
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 29
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 855s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 30
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
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
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 31
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): stay LED for fully charged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 32
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 950s ago
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 33,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 34,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1014): stay LED for fully charged,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 35
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 36
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 1050s ago,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 37
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 38
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1014): !@Sync 39
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 1155s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1014): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1014): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1014): Updating Usage Statistics in DB @ 1449747375828
,I/NetworkDataUsageDb( 1014): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1014): ::isTableExists: Table exists 
,I/ApplicationUsage( 1014): Done Updating Usage Statistics in DB @ 1449747375855
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 40
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 41
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/SMD     (  288): DCD OFF,
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 42
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 43
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 1265s ago
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
,E/Watchdog( 1014): !@Sync 44
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 45,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 46
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
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
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 47
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 1380s ago,
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
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 48
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 49
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 50
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
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
,E/Watchdog( 1014): !@Sync 51
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 1500s ago
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 52
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
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
,E/Watchdog( 1014): !@Sync 53
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 54
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 55
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 1625s ago
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
,E/Watchdog( 1014): !@Sync 56
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 57
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 58
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 59,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 1755s ago,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 60
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 61
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,I/ActivityManager( 1014): Killing 6379:com.wsomacp/u0a25 (adj 15): empty #31
I/ActivityManager( 1014): Killing 6136:com.android.calendar/u0a135 (adj 15): empty #32
I/ActivityManager( 1014): Killing 6333:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #33
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
I/ActivityManager( 1014): Killing 6312:com.sec.esdk.elm/u0a94 (adj 15): empty #34
D/SecKeyguardClockView( 1174): HomeTimezone(): 1
I/ActivityManager( 1014): Killing 2940:com.wssyncmldm/1000 (adj 15): SPC_empty #35
I/ActivityManager( 1014): Killing 4021:com.sec.android.pagebuddynotisvc/u0a116 (adj 15): SPC_empty #36
I/ActivityManager( 1014): Killing 2576:com.sec.phone/1001 (adj 15): SPC_empty #37
I/ActivityManager( 1014): Killing 3776:com.sec.bcservice/1000 (adj 15): SPC_empty #38
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): performPollLocked(flags=0x3)
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,V/NetworkStats( 1014): performPollLocked() took 13ms
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,I/ProcessStatsService( 1014): Prepared write state in 14ms
,I/ProcessStatsService( 1014): Prepared write state in 7ms
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,W/ActivityManager( 1014): Scheduling restart of crashed service com.wssyncmldm/.XDMService in 1000ms
,W/ActivityManager( 1014): Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 1000ms
,I/BatteryStatsDumper( 1014): In refreshStats isReason Screen ON/OFF: false
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,W/ActivityManager( 1014): ProcessRecord{30562c39 2576:com.sec.phone/1001} is already killed
E/lowmemorykiller(  255): Error opening /proc/2576/oom_score_adj; errno=2
,W/ActivityManager( 1014): Exception when unbinding service com.sec.phone/.SecPhoneService
W/ActivityManager( 1014): android.os.DeadObjectException
W/ActivityManager( 1014): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 1014): 	at android.os.BinderProxy.transact(Binder.java:511)
W/ActivityManager( 1014): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:1029)
W/ActivityManager( 1014): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1997)
W/ActivityManager( 1014): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2381)
W/ActivityManager( 1014): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:18687)
W/ActivityManager( 1014): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6654)
W/ActivityManager( 1014): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:6867)
W/ActivityManager( 1014): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1629)
W/ActivityManager( 1014): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:566)
,W/ActivityManager( 1014): ProcessRecord{30562c39 2576:com.sec.phone/1001} is already killed
,W/ActivityManager( 1014): Scheduling restart of crashed service com.sec.bcservice/.BroadcastService in 10943ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.analytics.CoreAnalyticsIntentService; callingUser = 0; userId(target) = 0
,I/BatteryStatsDumper( 1014): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1014): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1014): Previous Battery Level: 100 Current Level: 100 Delta: 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1789): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,E/Auth    ( 1789): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2: email
,V/NativeCrypto( 1789): SSL shutdown failed: ssl=0xb7d83908: I/O error during system call, Connection timed out
,V/NativeCrypto( 1789): SSL shutdown failed: ssl=0xb7d7f900: I/O error during system call, Connection timed out
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BatteryStatsDumper( 1014): Writing to database completed
,I/ProcessStatsService( 1014): Pruning old procstats: /data/system/procstats/state-2015-12-09-15-58-00.bin
,W/libprocessgroup( 1014): failed to open /acct/uid_10025/pid_6379/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2940/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10094/pid_6312/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10134/pid_6333/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10116/pid_4021/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10135/pid_6136/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3776/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1001/pid_2576/cgroup.procs: No such file or directory
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7466): MountEmulatedStorage()
E/Zygote  ( 7466): v2,
I/libpersona( 7466): KNOX_SDCARD checking this for 10116
I/libpersona( 7466): KNOX_SDCARD not a persona
,I/SELinux ( 7466): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 7466): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.pagebuddynotisvc for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc: pid=7466 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,E/SELinux ( 7466): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7466): TimaSignature is unavailable
,D/ActivityThread( 7466): Added TimaKeyStore provider
,I/PageBuddyNotiSvc( 7466): onCreate mCpBitFlag=0
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7487): MountEmulatedStorage(),
E/Zygote  ( 7487): v2
I/libpersona( 7487): KNOX_SDCARD checking this for 1000
I/libpersona( 7487): KNOX_SDCARD not a persona,
I/ActivityManager( 1014): Start proc com.sec.bcservice for service com.sec.bcservice/.BroadcastService: pid=7487 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 7487): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 7487): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 7487): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7487): TimaSignature is unavailable
,D/ActivityThread( 7487): Added TimaKeyStore provider
,W/ResourcesManager( 7487): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/F_PHONE ( 7487): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 7487): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,D/ActivityManager( 1014): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7502): MountEmulatedStorage()
,E/Zygote  ( 7502): v2
I/libpersona( 7502): KNOX_SDCARD checking this for 1001
I/libpersona( 7502): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.sec.phone for service com.sec.phone/.SecPhoneService: pid=7502 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,I/SELinux ( 7502): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 7502): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 7502): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 7502): TimaSignature is unavailable
,D/ActivityThread( 7502): Added TimaKeyStore provider
,W/ResourcesManager( 7502): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/F_PHONE ( 7487): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 7487): default registerAction()
I/F_PHONE ( 7487): [[com.sec.bcservice]] sendPendingMessage()
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1014): !@Sync 62,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  288): DCD OFF
D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): stay LED for fully charged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/SMD     (  288): DCD OFF
D/AndroidRuntime( 7535): 
D/AndroidRuntime( 7535): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7535): CheckJNI is OFF
D/AndroidRuntime( 7535): readGMSProperty: start
D/AndroidRuntime( 7535): readGMSProperty: already setted!!
D/AndroidRuntime( 7535): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7535): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7535): readGMSProperty: end
D/AndroidRuntime( 7535): addProductProperty: start
E/AffinityControl( 7535): AffinityControl: registerfunction enter
D/AndroidRuntime( 7535): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1014): START PACKAGE DELETE: observer{168771171}
D/PackageManager( 1014): pkg{<packageName>}
D/PackageManager( 1014): user{0}
D/PackageManager( 1014): caller{2000}
D/PackageManager( 1014): flags{3}
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1014): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1014): !@killApplicatoin: 10175, uninstall pkg
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
I/ActivityManager( 1014): Killing 5479:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1014): Skipping PackageSetting{196a1ff5 com.example.hello/10174} due to missing metadata
I/WindowState( 1014): WIN DEATH: Window{3a8f30d u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  258): id=12 Removed NainActivit (6/8)
I/SurfaceFlinger(  258): id=12 Removed NainActivit (-2/8)
D/InputDispatcher( 1014): Focus left window: 5479
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1014):   Force finishing activity ActivityRecord{228ca4f3 u0 com.test.thalitest/.MainActivity t2}
D/InputDispatcher( 1014): Focused application released
D/FocusedStackFrame( 1014): Set to : 0
W/ActivityManager( 1014): mDVFSHelper.acquire()
V/WindowManager( 1014): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
W/ActivityManager( 1014): Spurious death for ProcessRecord{1111ea60 5479:com.test.thalitest/u0a175}, curProc for 5479: null
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
D/Launcher( 1468): onRestart, Launcher: 932167452
W/ActivityManager( 1014): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3709): Explicit concurrent mark sweep GC freed 2941(182KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 6MB/11MB, paused 1.065ms total 41.289ms
I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1789): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1777): mOCRHelper is null
I/art     ( 1999): Explicit concurrent mark sweep GC freed 10707(556KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 14MB/19MB, paused 2.493ms total 88.072ms
D/Launcher( 1468): onStart, Launcher: 932167452
D/Launcher.HomeView( 1468): onStart
D/Launcher( 1468): onResume, Launcher: 932167452
D/SettingsProvider( 1014): name = kids_home_mode
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10007
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
D/Launcher.HomeView( 1468): onResume
D/RegisteredComponentCache( 1430): Collect Tech packages for Knox
D/PersonaManager( 1430): isKioskContainerExistOnDevice
D/Launcher( 1468): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/MenuAppsGridFragment( 1468): onResume
D/WallpaperManager( 1468): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/WallpaperManager( 1468): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/WallpaperManager( 1468): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
I/KLMS-2.5.183: ( 3491): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 12:47:42 GMT+01:00 2015
D/ActivityManager( 1014): handle home activity for 0
I/WallpaperManagerService( 1014): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1014): post home show event for user 0
D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
W/SQLiteConnectionPool( 1999): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
D/Launcher.HomeView( 1468): onPause
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/Launcher( 1468): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/KLMS-2.5.183: ( 3491): KLMSAbstractReciever(): onReceive().END.
I/SurfaceFlinger(  258): id=15 createSurf (720x1280),1 flag=4, Mauncher
I/splitIntent( 1014): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1014): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
E/Zygote  ( 7551): MountEmulatedStorage()
I/libpersona( 7551): KNOX_SDCARD checking this for 10094
E/Zygote  ( 7551): v2
I/libpersona( 7551): KNOX_SDCARD not a persona
I/SELinux ( 7551): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7551): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/InputDispatcher( 1014): Focus entered window: 1468
E/SELinux ( 7551): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/ActivityManager( 1014): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7551 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
D/SRIB_DCS( 1468): log_dcs ThreadedRenderer::initialize entered! 
I/KLMS-2.5.183: ( 3491): KLMSIntentService(): onCreate()
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
V/ActivityThread( 1468): updateVisibility : ActivityRecord{2dda30a token=android.os.BinderProxy@39d73192 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1468): onStop
D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/KLMS-2.5.183: ( 3491): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/Zygote  ( 7563): MountEmulatedStorage()
E/Zygote  ( 7563): v2
I/libpersona( 7563): KNOX_SDCARD checking this for 10044
I/SELinux ( 7563): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 7563): KNOX_SDCARD not a persona
I/KLMS-2.5.183: ( 3491): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/ActivityManager( 1014): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7563 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 7563): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7563): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/InputMethodManagerService( 1014): Got RemoteException sending setActive(false) notification to pid 5479 uid 10175
D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
D/TimaKeyStoreProvider( 7551): TimaSignature is unavailable
D/ActivityThread( 7551): Added TimaKeyStore provider
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3491): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/SamsungIME( 1777): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/Zygote  ( 7584): MountEmulatedStorage()
I/libpersona( 7584): KNOX_SDCARD checking this for 10149
E/Zygote  ( 7584): v2
I/libpersona( 7584): KNOX_SDCARD not a persona
I/SELinux ( 7584): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7584 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7584): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7584): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7563): TimaSignature is unavailable
D/ActivityThread( 7563): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3491): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3491): KLMSIntentService(): listeningToPackageRemoved().START
D/TimaKeyStoreProvider( 7584): TimaSignature is unavailable
D/ActivityThread( 7584): Added TimaKeyStore provider
E/SQLiteLog( 7017): (284) automatic index on crash_info_summary(package_name_touched)
I/KLMS-2.5.183: ( 3491): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/art     ( 1014): Explicit concurrent mark sweep GC freed 64417(6MB) AllocSpace objects, 205(3MB) LOS objects, 33% free, 27MB/41MB, paused 4.667ms total 284.636ms
I/art     ( 1014): WaitForGcToComplete blocked for 212.918ms for cause Explicit
W/ResourcesManager( 7563): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7563): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7563): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7563): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7563): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7563): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7563): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7563): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ActivityManager( 1014): mDVFSHelper.release()
I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{1103843a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1902745
D/PersonaManager( 1430): isKioskContainerExistOnDevice
D/RegisteredServicesCache( 1430): empty dynamic service
I/art     ( 7017): Explicit concurrent mark sweep GC freed 622(47KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 25.801ms total 71.894ms
D/BadgeProvider( 6362): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6362): sendNotify, [notify] : null
D/BadgeProvider( 6362): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6362): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6362): update, [UpdateCount] : 1
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1014): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7602 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/elm:15183( 7551): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/libpersona( 7602): KNOX_SDCARD checking this for 1000
I/KLMS-2.5.183: ( 3491): KLMSIntentService(): listeningToPackageRemoved().END
I/libpersona( 7602): KNOX_SDCARD not a persona
E/Zygote  ( 7602): MountEmulatedStorage()
E/Zygote  ( 7602): v2
I/SELinux ( 7602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/elm:15183( 7551): ELMEngine.ELMEngine( context ).
I/SELinux ( 7602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/elm:15183( 7551): MDMBridge.setEnterpriseBridge()
E/SELinux ( 7602): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7602): TimaSignature is unavailable
D/ActivityThread( 7602): Added TimaKeyStore provider
D/ActivityManager( 1014): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15183( 7551): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/KLMS-2.5.183: ( 3491): KLMSIntentService(): onDestroy()
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
D/ThemeInfoUtil( 7584): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 7584): isCurrentFestival = false
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 1014): PackageReceiver onReceive()
I/HarmonyEASService( 1014): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1014): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1014): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1014): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1014): DBIntegrity::getInstance - New instance created
E/Zygote  ( 7618): MountEmulatedStorage()
E/Zygote  ( 7618): v2
I/libpersona( 7618): KNOX_SDCARD checking this for 1000
I/libpersona( 7618): KNOX_SDCARD not a persona
I/SELinux ( 7618): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/OTPFW   ( 1014): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
I/SELinux ( 7618): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7618): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/OTPFW   ( 1014): ProvisionData::getAllEntries Enter
I/ActivityManager( 1014): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=7618 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/OTPFW   ( 1014): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1014): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1014): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
V/EnterpriseBillingPolicy( 1014): uID is 10175
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/elm:15183( 7551): ElmAgentService : onCreate()
D/elm:15183( 7551): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 7551): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 7551): MDMBridge.getInstance()
D/elm:15183( 7551): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 7551): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 7634): MountEmulatedStorage()
E/Zygote  ( 7634): v2
I/libpersona( 7634): KNOX_SDCARD checking this for 10152
I/libpersona( 7634): KNOX_SDCARD not a persona
I/SELinux ( 7634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/TimaKeyStoreProvider( 7618): TimaSignature is unavailable
D/ActivityThread( 7618): Added TimaKeyStore provider
I/SELinux ( 7634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7634 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
E/SELinux ( 7634): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 6559:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10175
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
D/SSRM:aZ ( 1014): MSG_TYPE_APP_REMOVED::
D/TaskPersister( 1014): removeObsoleteFile: deleting file=2_task.xml
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
W/ContextImpl( 7602): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/WallpaperManagerService( 1014):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1014): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
V/AlarmManagerEXT( 1014): com.test.thalitest(10175) is removed.
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 7634): TimaSignature is unavailable
D/ActivityThread( 7634): Added TimaKeyStore provider
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
D/elm:15183( 7551): ElmAgentService : onDestroy().
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/StatusBar( 1174): Icon Only
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/PanelView( 1174): There is/are notification(s) 
E/Zygote  ( 7652): MountEmulatedStorage()
E/Zygote  ( 7652): v2
I/libpersona( 7652): KNOX_SDCARD checking this for 1000
I/libpersona( 7652): KNOX_SDCARD not a persona
I/SELinux ( 7652): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7652 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 6574:com.google.android.apps.maps/u0a107 (adj 15): empty #31
I/SELinux ( 7652): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/AASAservice-UpdateReceiver( 7618): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
E/SELinux ( 7652): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  303): Explicit concurrent mark sweep GC freed 8752(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 30.372ms
W/System.err( 7618): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 7618): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 7618): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 7618): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 7618): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 7618): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 7618): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7618): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7618): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 7618): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7618): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7618): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7618): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 19.116ms
D/PersonaManager( 1014): isKioskContainerExistOnDevice
D/TimaKeyStoreProvider( 7652): TimaSignature is unavailable
D/ActivityThread( 7652): Added TimaKeyStore provider
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 17.065ms
I/ActivityManager( 1014): Killing 6613:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
I/ActivityManager( 1014): Killing 6643:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/art     ( 1014): Explicit concurrent mark sweep GC freed 17200(917KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 4.544ms total 382.943ms
I/PCWCLIENTTRACE_PushUtil( 6658): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6658): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6658): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6658): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/ResourcesManager( 7652): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 7634): (284) automatic index on shooting_modes(title_id)
E/Zygote  ( 7668): MountEmulatedStorage()
E/Zygote  ( 7668): v2
I/libpersona( 7668): KNOX_SDCARD checking this for 10032
I/libpersona( 7668): KNOX_SDCARD not a persona
I/SELinux ( 7668): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7668 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 7668): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7668): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/NearbySource( 7563): Nearby Source Create!
D/NearbyContext( 7563): Nearby Context Create!
D/TimaKeyStoreProvider( 7668): TimaSignature is unavailable
D/ActivityThread( 7668): Added TimaKeyStore provider
D/RCPManager( 7652):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1014):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1014): queryAllProviders():  providerCallBack is not register for 0
E/Zygote  ( 7686): MountEmulatedStorage()
E/Zygote  ( 7686): v2
I/libpersona( 7686): KNOX_SDCARD checking this for 10156
I/libpersona( 7686): KNOX_SDCARD not a persona
I/SELinux ( 7686): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7686): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7686): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7686 uid=10156 gids={50156, 9997} abi=armeabi-v7a
W/ContextImpl( 7563): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 7563): Samsung link source created

```
