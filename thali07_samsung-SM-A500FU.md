#### Test 55613145c131883_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/TP/MmsSmsProvider( 1460): query,matched:0, calling pid = 5789
V/TP/MmsSmsProvider( 1460): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1460): match 0:Elapsed time : 0.871 ms
D/Mms/DownloadManager( 5789): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/Synchronizer( 5789): [start]    doSync consume time = 16.956458
D/Mms/DownloadManager( 5789): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5789): getSubId is called
D/Mms/TelephonyUtils( 5789): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5789): getTelephonyProperty is called
D/Mms/DownloadManager( 5789): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5789): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5789): auto download without roaming -> true
D/Mms/DownloadManager( 5789): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5789): mAutoDownload ------> true
D/Mms/SpamFilter( 5789): [start]    SpamFilter fill() begin consume time = 4.897761
D/TP/MmsSmsProvider( 1460): update, matched:300, calling pid = 5789
V/TP/MmsSmsProvider( 1460): syncDBData start
V/TP/MmsSmsProvider( 1460): syncDBData sms end
V/TP/MmsSmsProvider( 1460): syncDBData mms end
V/TP/MmsSmsProvider( 1460): syncDBData end
D/Mms/Synchronizer( 5789): [end]    doSync consume time = 4.575364
D/TP/MmsSmsProvider( 1460): query,matched:400, calling pid = 5789
I/DBG_POLICYDM( 5851): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 5851): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
D/Mms/FreeMessageStatusReceiver( 5789): onReceive, action : android.intent.action.PACKAGE_ADDED
--------- beginning of system
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5851): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
D/Mms/ArtClassLoader( 5789): init [DONE] art
I/DBG_POLICYDM( 5851): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/DBG_POLICYDM( 5851): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
E/Zygote  ( 5945): MountEmulatedStorage()
E/Zygote  ( 5945): v2
I/SELinux ( 5945): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 5945): KNOX_SDCARD checking this for 10072
I/libpersona( 5945): KNOX_SDCARD not a persona
I/DBG_POLICYDM( 5851): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/Mms/SpamFilter( 5789): [end]    SpamFilter fill() finished consume time = 33.588594
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5945 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
I/SELinux ( 5945): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/DBG_POLICYDM( 5851): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
E/SELinux ( 5945): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5851): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 5851): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5959 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
E/Zygote  ( 5959): MountEmulatedStorage()
E/Zygote  ( 5959): v2
I/DBG_POLICYDM( 5851): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/SELinux ( 5959): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/Mms/FreeMessageReceiverService( 5789): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5789): onHandleIntent: ACTION_PACKAGE_ADDED
I/SELinux ( 5959): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/DBG_POLICYDM( 5851): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
E/SELinux ( 5959): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/libpersona( 5959): KNOX_SDCARD checking this for 10047
I/libpersona( 5959): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Killing 5327:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
I/DBG_POLICYDM( 5851): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 5851): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 5851): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
I/DBG_POLICYDM( 5851): [com.policydm.XSPPReceiver(53/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 5945): TimaSignature is unavailable
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 5945): Added TimaKeyStore provider
E/Zygote  ( 5980): MountEmulatedStorage()
I/libpersona( 5980): KNOX_SDCARD checking this for 10038
E/Zygote  ( 5980): v2
I/libpersona( 5980): KNOX_SDCARD not a persona
I/SELinux ( 5980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5980): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5959): TimaSignature is unavailable
D/ActivityThread( 5959): Added TimaKeyStore provider
I/ActivityManager( 1015): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5980 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5228:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
I/ActivityManager( 1015): Killing 3715:com.android.providers.calendar/u0a42 (adj 15): empty #31
D/TimaKeyStoreProvider( 5980): TimaSignature is unavailable
D/ActivityThread( 5980): Added TimaKeyStore provider
W/ResourcesManager( 5959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5959): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5959): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5980): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5980): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/BadgeProvider( 5945): onCreate
D/BadgeProvider( 5945): DatabaseHelper
D/Mms/MessagingNotification( 5789): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1460): query,matched:26, calling pid = 5789
D/TP/SmsProvider( 1460): match 26:Elapsed time : 1.704 ms
D/TP/MmsSmsProvider( 1460): query,matched:6, calling pid = 5789
D/TP/MmsSmsProvider( 1460): match 6:Elapsed time : 1.507 ms
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5851): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
E/Zygote  ( 5996): MountEmulatedStorage()
I/libpersona( 5996): KNOX_SDCARD checking this for 10025
E/Zygote  ( 5996): v2
I/libpersona( 5996): KNOX_SDCARD not a persona
I/DBG_POLICYDM( 5851): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/SELinux ( 5996): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5996): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5996): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5851): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 5851): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5996 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/DBG_POLICYDM( 5851): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_5327/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5228/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_3715/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 5851): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
D/TimaKeyStoreProvider( 5996): TimaSignature is unavailable
D/ActivityThread( 5996): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
I/ConfigFetchService( 1858): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ActivityManager( 1015): Killing 3932:com.google.android.talk/u0a104 (adj 15): empty #31
I/ConfigFetchService( 1858): launchTask
I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
I/DBG_POLICYDM( 5851): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 5851): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 5851): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 5851): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/01/18/17:26:23
I/DBG_POLICYDM( 5851): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/01/14/13:17:13
I/DBG_POLICYDM( 5851): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5851): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
I/ServiceManager(  317): Waiting for service AtCmdFwd...
I/DBG_POLICYDM( 5851): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
D/ChimeraCfgMgr( 1858): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1858): Module APK com.google.android.play.games already loaded
I/DBG_POLICYDM( 5851): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5851): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5851): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 5851): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 5851): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5851): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
D/MyFiles ( 5959): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
W/ResourcesManager( 5996): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5851): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
I/ActivityManager( 1015): Killing 5485:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
V/ConfigFetchTask( 1858): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VnUzRysUPPPXWr8cOc5NUCJSTyHRVAzQWaeay-hXKPCQT0Lf7czAHvE7FOxCJOKw39misaRLyRB8uwXJFzlhPrEMcaLIGfzDi1ApbyP6dPdetfR4jFw4cNOYOCLW-5FJ8ree0j3AHkxZucLwTDuEWCuUHXbT2iXx1xPF7250Jh9YbpMZ-kN87Pr7cLXomlU4oGYQ5h8HwQ3WO6MtTx-l5YdbBPjZwfuyOQ6Nq1B6xeqaMz_XM
E/installd(  282): system dir 0 : /system/app/
E/installd(  282): system dir 1 : /system/priv-app/
E/installd(  282): system dir 2 : /vendor/app/
E/installd(  282): system dir 3 : /oem/app/
I/PeopleContactsSync( 1858): CP2 sync disabled
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 5996): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
I/DBG_POLICYDM( 5851): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
D/ChimeraCfgMgr( 1858): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1858): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1858): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1858): No vision deps
D/Mms/Omacp( 5789): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/TactileAssist( 1015): enable value -1
I/TactileAssist( 1015): internal enable value -1
I/TactileAssist( 1015): intensity value -1
I/TactileAssist( 1015): saveAppList value true
I/TactileAssist( 1015): List of disabled apps :
I/OMACP   ( 5996): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5996): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5996): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/OMACP   ( 5996): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5996): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5996): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5996): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5996): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5996): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5996): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_5485/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10104/pid_3932/cgroup.procs: No such file or directory
I/OMACP   ( 5996): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/libpersona( 6019): KNOX_SDCARD checking this for 10053
I/OMACP   ( 5996): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/libpersona( 6019): KNOX_SDCARD not a persona
I/OMACP   ( 5996): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
E/Zygote  ( 6019): MountEmulatedStorage()
E/Zygote  ( 6019): v2
I/SELinux ( 6019): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6019): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6019): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6019 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6019): TimaSignature is unavailable
D/ActivityThread( 6019): Added TimaKeyStore provider
I/DBG_POLICYDM( 5851): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
I/DBG_POLICYDM( 5851): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
W/ResourcesManager( 6019): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/PackageManager( 1015): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
I/GAv4    ( 5801): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5801):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5801):   adb logcat -s GAv4
W/GAv4    ( 5801): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/Compatibility( 6019): onReceive() it will make start service
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Compatibility( 6019): onHandleIntent()
E/Zygote  ( 6037): MountEmulatedStorage()
E/Zygote  ( 6037): v2
I/libpersona( 6037): KNOX_SDCARD checking this for 1000
D/Compatibility( 6019): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10174, android.intent.extra.user_handle=0}]
I/libpersona( 6037): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6037 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/Compatibility( 6019): found: 2
D/Compatibility( 6019): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6019): skipping ResolveInfo{33231f08 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6019): considering ResolveInfo{198d6a1 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6019): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6019): enabling receiver ResolveInfo{20fea0c6 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6019): enabling receiver ResolveInfo{8af887 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/GoogleURLConnFactory( 1858): Using platform SSLCertificateSocketFactory
D/Compatibility( 6019): enabling receiver ResolveInfo{124f23b4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 6019): enabling receiver ResolveInfo{39cb3bdd com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/SELinux ( 6037): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6037): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6037): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 6019): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
W/GAv4    ( 5801): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/DBG_POLICYDM( 5851): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
D/TimaKeyStoreProvider( 6037): TimaSignature is unavailable
D/ActivityThread( 6037): Added TimaKeyStore provider
W/BaseAppContext( 1858): Using Auth Proxy for data requests.
W/BaseAppContext( 1858): Using Auth Proxy for data requests.
W/AnalyticsTrackerProxyImpl( 5801): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
W/GAv4    ( 5801): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/System.out( 1858): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1858): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1858): (HTTPLog)-Static: isShipBuild true
W/ContextImpl( 6037): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
I/System.out( 1858): (HTTPLog)-Thread-266-865767374: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1858): (HTTPLog)-Static: isSBSettingEnabled false
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 502 for uid 10012
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6062): MountEmulatedStorage()
I/libpersona( 6062): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6062): v2
I/libpersona( 6062): KNOX_SDCARD not a persona
I/SELinux ( 6062): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6062 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6062): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/BaseAppContext( 1858): Using Auth Proxy for data requests.
I/ActivityManager( 1015): Killing 5500:com.sec.knox.bridge/1000 (adj 15): empty #31
E/SELinux ( 6062): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/art     ( 5801): Suspending all threads took: 25.310ms
I/System.out( 1858): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1858): Tagging socket 98 with tag 40b00000000{1035,0} for uid -1, pid: 1858, getuid(): 10012
D/TimaKeyStoreProvider( 6062): TimaSignature is unavailable
D/ActivityThread( 6062): Added TimaKeyStore provider
I/art     ( 1684): Explicit concurrent mark sweep GC freed 20254(1210KB) AllocSpace objects, 3(108KB) LOS objects, 40% free, 10MB/17MB, paused 1.082ms total 51.326ms
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5500/cgroup.procs: No such file or directory
W/ResourcesManager( 6062): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
W/BaseAppContext( 1858): Using Auth Proxy for data requests.
W/BaseAppContext( 1858): Using Auth Proxy for data requests.
I/SL_DEBUG( 5980): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5980): isLoggable:: SL_DEBUG_EXIST = false
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6080): MountEmulatedStorage()
E/Zygote  ( 6080): v2
I/libpersona( 6080): KNOX_SDCARD checking this for 1000
I/libpersona( 6080): KNOX_SDCARD not a persona
I/SELinux ( 6080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6080 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6080): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 5516:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/DBG_POLICYDM( 5851): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
W/BaseAppContext( 1858): Using Auth Proxy for data requests.
D/TimaKeyStoreProvider( 6080): TimaSignature is unavailable
D/ActivityThread( 6080): Added TimaKeyStore provider
I/DBG_POLICYDM( 5851): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/qtaguid ( 1858): Tagging socket 104 with tag 40b00000000{1035,0} for uid -1, pid: 1858, getuid(): 10012
W/ResourcesManager( 6080): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Killing 5576:com.google.android.apps.plus/u0a120 (adj 15): empty #31
I/DBG_POLICYDM( 5851): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5980): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5980): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/ActivityManager( 1015): Killing 5420:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
E/JavaBinder( 1015): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue( 1015): Exception when sending broadcast to ComponentInfo{com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor}
W/BroadcastQueue( 1015): android.os.TransactionTooLargeException
W/BroadcastQueue( 1015): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1015): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1015): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1015): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1015): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1015): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1015): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1015): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1015): 	at android.os.Binder.execTransact(Binder.java:461)
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6103): MountEmulatedStorage()
E/Zygote  ( 6103): v2
I/libpersona( 6103): KNOX_SDCARD checking this for 10120
I/libpersona( 6103): KNOX_SDCARD not a persona
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5516/cgroup.procs: No such file or directory
I/SELinux ( 6103): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6103): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6103): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6103 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/AcmsKeyStoreHelper( 5866):  getKeyStoreForApplication Enter
I/art     (  307): Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 667us total 25.324ms
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5801): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5801): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5801): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 17.109ms
D/TimaKeyStoreProvider( 6103): TimaSignature is unavailable
D/ActivityThread( 6103): Added TimaKeyStore provider
I/qtaguid ( 1858): Untagging socket 98
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 17.582ms
I/ConfigFetchService( 1858): fetch service done; releasing wakelock
I/ConfigFetchService( 1858): stopping self
I/AcmsKeyStoreHelper( 5866): Key Store exist
I/AcmsKeyStoreHelper( 5866): Hence loading the keystore file
,W/libprocessgroup( 1015): failed to open /acct/uid_10120/pid_5576/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10057/pid_5420/cgroup.procs: No such file or directory
W/ResourcesManager( 6103): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/JNIHelp ( 5801): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6121): MountEmulatedStorage()
E/Zygote  ( 6121): v2
I/libpersona( 6121): KNOX_SDCARD checking this for 10041
I/libpersona( 6121): KNOX_SDCARD not a persona
I/SELinux ( 6121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6121 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6121): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AcmsKeyStoreHelper( 5866):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5866): getKeyStoreForApplication success 
D/AcmsCore( 5866): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5866): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5866): Decrementing - Counter value: 1
D/AcmsCore( 5866): AcmsCore: ACMS_APP_INSTALLED
D/AcmsCore( 5866): This is NOT a valid MirrorLink app
D/AcmsCore( 5866): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5866): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5866): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5866): Counter value is 0: Stopping ACMS service
D/AcmsServiceMonitor( 5866): getSvcCounter - Counter value: 0
D/AcmsService( 5866): Enter onDestroy
I/AcmsService( 5866): cleanUp(): inside service clean up
D/AcmsCore( 5866): AcmsCore: inside DeInit
D/AcmsCore( 5866): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5866): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5866): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5866): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5866): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5866): getSvcCounter - Counter value: 0
D/AcmsService( 5866): killing acms process
I/Process ( 5866): Sending signal. PID: 5866 SIG: 9
I/ActivityManager( 1015): Killing 4993:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 6121): TimaSignature is unavailable
D/ActivityThread( 6121): Added TimaKeyStore provider
W/System  ( 5801): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@347eb22: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 5801): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 5801): Installed default security provider GmsCore_OpenSSL
E/SMD     (  287): DCD OFF
I/ActivityManager( 1015): Process ACMS.Process (pid 5866)(adj 0) has died(52,1078)
I/ServiceManager(  317): Waiting for service AtCmdFwd...
I/art     ( 1015): Explicit concurrent mark sweep GC freed 222083(14MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/40MB, paused 12.349ms total 255.575ms
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4993/cgroup.procs: No such file or directory
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/AlarmManager( 1015): waitForAlarm result :4
V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SA      ( 6121): [SSP] onCreated
D/AndroidRuntime( 6132): 
D/AndroidRuntime( 6132): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6132): CheckJNI is OFF
D/AndroidRuntime( 6132): readGMSProperty: start
D/AndroidRuntime( 6132): readGMSProperty: already setted!!
D/AndroidRuntime( 6132): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6132): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6132): readGMSProperty: end
D/AndroidRuntime( 6132): addProductProperty: start
I/SA      ( 6121): [TPM] There is no property file
I/SA      ( 6121): [SCU] isHaveSA() - false
I/SA      ( 6121): [TPM] getModelProperty : null
I/SA      ( 6121): [TPM] getCSCProperty : null
I/SA      ( 6121): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6121): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6121): [DM] TFT FEATURE: false
I/SA      ( 6121): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6121): [DM] init START
I/SA      ( 6121): [DM] This device is not a Vodafone
W/ResourceType( 6121): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6121): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6121): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6121): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6121): [SCU] isHaveSA() - false
I/SA      ( 6121): support phone number id : false
I/SA      ( 6121): [DM] Supports Ref Jpn : true
I/SA      ( 6121): [DM] init END
I/SA      ( 6121): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 6121): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10174 extra.user_handle.:0 ]
I/ActivityManager( 1015): Killing 5011:com.google.android.gms:car/u0a12 (adj 15): empty #31
E/AffinityControl( 6132): AffinityControl: registerfunction enter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/AndroidRuntime( 6132): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1015): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/libprocessgroup( 1015): failed to open /acct/uid_10012/pid_5011/cgroup.procs: No such file or directory
W/ActivityManager( 1015): mDVFSHelper.acquire()
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
E/Zygote  ( 6162): MountEmulatedStorage()
E/Zygote  ( 6162): v2
I/libpersona( 6162): KNOX_SDCARD checking this for 10174
I/libpersona( 6162): KNOX_SDCARD not a persona
I/SELinux ( 6162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6162 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 3054
I/SELinux ( 6162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
D/AndroidRuntime( 6132): Shutting down VM
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
E/SELinux ( 6162): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=13 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 6162): TimaSignature is unavailable
D/ActivityThread( 6162): Added TimaKeyStore provider
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
V/ActivityManager( 1015): Display changed displayId=0
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1015): isKioskContainerExistOnDevice
V/ActivityThread( 3054): updateVisibility : ActivityRecord{3f2db424 token=android.os.BinderProxy@7003bc5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6180): MountEmulatedStorage()
I/libpersona( 6180): KNOX_SDCARD checking this for 10057
E/Zygote  ( 6180): v2
I/libpersona( 6180): KNOX_SDCARD not a persona
I/SELinux ( 6180): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6180): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6180 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/SELinux ( 6180): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  256): id=11 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  256): id=11 Removed YUIInstallC (-2/9)
I/ActivityManager( 1015): Killing 5627:com.sec.android.diagmonagent/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 6180): TimaSignature is unavailable
D/ActivityThread( 6180): Added TimaKeyStore provider
D/ChimeraCfgMgr( 1858): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1858): Module APK com.google.android.play.games already loaded
I/WebViewFactory( 6162): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
W/art     ( 6132): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/LibraryLoader( 6162): Time to load native libraries: 2 ms (timestamps 2769-2771)
I/LibraryLoader( 6162): Expected native library version number "",actual native library version number ""
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5627/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,V/WebViewChromiumFactoryProvider( 6162): Binding Chromium to main looper Looper (main, tid 1) {124f23b4}
,I/LibraryLoader( 6162): Expected native library version number "",actual native library version number ""
,I/chromium( 6162): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6201): MountEmulatedStorage()
,E/Zygote  ( 6201): v2
I/libpersona( 6201): KNOX_SDCARD checking this for 10010
I/libpersona( 6201): KNOX_SDCARD not a persona
,I/SELinux ( 6201): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6201 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6201): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6201): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/BrowserStartupController( 6162): Initializing chromium process, singleProcess=true
,W/art     ( 6162): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6162): ApplicationContext is null in ApplicationStatus,
,D/TimaKeyStoreProvider( 6201): TimaSignature is unavailable
,D/ActivityThread( 6201): Added TimaKeyStore provider
,W/chromium( 6162): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/PowerManagerService( 1015): [PWL] Off : 5s ago
,I/PowerManagerService( 1015): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1015): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1858, ws=null) (elapsedTime=47178)
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1015, ws=WorkSource{10054}) (elapsedTime=582)
,E/libEGL  ( 6162): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6162): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6162): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6162): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6162): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6162): Local Branch: 
I/Adreno-EGL( 6162): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6162): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6162):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/Mms/MmsApp( 5789):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5789): [start]    fillCache consume time = 1936.832603
,D/Mms/ComposeMessageFragment( 5789): fillCache, easy = false
,I/splitIntent( 1015): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1015): Killing 5244:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/KeyguardViewMediator( 1168): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1168): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1168): *** Keyguard wallpaper service already unbounded
,D/AbsListView( 5789): Get MotionRecognitionManager
,D/MotionRecognitionService( 1015):  ssp status : false
,D/Mms/ComposeMessageFragment( 5789): [end]    fillCache consume time = 74.599219
,D/LocationManagerService( 1015): getProviders()=[passive]
,W/libprocessgroup( 1015): failed to open /acct/uid_10150/pid_5244/cgroup.procs: No such file or directory
,D/Mms/BubbleViewCache( 5789): fillCache bubble = 1
,I/UpdateIcingCorporaServi( 6180): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/ActivityManager( 1015): Activity pause timeout for ActivityRecord{530bd79 u0 com.test.thalitest/.MainActivity t234}
,W/art     ( 6162): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6162): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6162): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6162): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6162): CordovaWebView is running on device made by: samsung
,W/art     ( 6162): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6162): Attempt to remove local handle scope entry from IRT, ignoring
,I/UpdateIcingCorporaServi( 6180): UpdateCorporaTask done [took 114 ms] updated apps [took 114 ms] 
,I/ActivityManager( 1015): Killing 5653:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/OpenGLRenderer( 6162): Render dirty regions requested: true
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
,D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,W/chromium( 6162): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6162): updateVisibility : ActivityRecord{22388a49 token=android.os.BinderProxy@9674e13 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6162): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6162): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  256): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1015): Focus entered window: 6162
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 6162): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6162): Initialized EGL, version 1.4
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 6162): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6162): Enabling debug mode 0
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1168): There is/are notification(s) 
,I/SamsungIME( 1792): getCurrentCandidateView
,I/ActivityManager( 1015): Displayed Component not be shown by security: +725ms (total +808ms)
,W/ActivityManager( 1015): mDVFSHelper.release()
,I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{530bd79 u0 com.test.thalitest/.MainActivity t234} time:83334
,I/SurfaceFlinger(  256): id=13 Removed uhalitest (7/9)
,W/IInputConnectionWrapper( 6162): showStatusIcon on inactive InputConnection
,I/Timeline( 6162): Timeline: Activity_idle id: android.os.BinderProxy@9674e13 time:83351
,D/SamsungIME( 1792): Dismiss ExpandCandiate
,I/SamsungIME( 1792): getDebugLevel  : 0x4f4c
,W/libprocessgroup( 1015): failed to open /acct/uid_10142/pid_5653/cgroup.procs: No such file or directory
,W/BindingManager( 6162): Cannot call determinedVisibility() - never saw a connection for the pid: 6162,
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/SamsungIME( 1792): getDebugLevel  : 0x4f4c,
E/Zygote  ( 6253): MountEmulatedStorage(),
,E/Zygote  ( 6253): v2
I/libpersona( 6253): KNOX_SDCARD checking this for 10012
I/libpersona( 6253): KNOX_SDCARD not a persona
I/SELinux ( 6253): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=6253 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
I/SELinux ( 6253): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6253): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/SamsungIME( 1792): KeybaordView init() : load resources
,D/TimaKeyStoreProvider( 6253): TimaSignature is unavailable
,D/ActivityThread( 6253): Added TimaKeyStore provider
,I/SamsungIME( 1792): getCurrentKeyboard
I/SamsungIME( 1792): getTextKeyboard
,W/ResourcesManager( 6253): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6253): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SamsungIME( 1792): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/MultiDex( 6253): VM with version 2.1.0 has multidex support
,I/MultiDex( 6253): install
I/MultiDex( 6253): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6253): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/JsMessageQueue( 6162): Set native->JS mode to OnlineEventsBridgeMode
,W/ActivityThread( 6253): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6253): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13b00447: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6253): Installed default security provider GmsCore_OpenSSL,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1684): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1684): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/ActivityManager( 1015): Killing 5137:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1858): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4475): callingUid 10012, callindPid: 4475
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/jxcore_app_log( 6162): JniHelper::setJavaVM(0xb8f08450), pthread_self() = -1186581568
,D/JX-Cordova( 6162): jxcore cordova android initializing
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/MDM     ( 1653): [178] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1858): Restart initialization of location
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_10040/pid_5137/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5851): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5851): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,W/jxcore-log( 6162): Initializing JXcore engine
,W/jxcore-log( 6162): JXcore engine is ready
,W/jxcore-log( 6162): Starting JXcore engine
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/audit   ( 1841): type=1400 msg=audit(1452773837.375:205): avc:  denied  { ioctl } for  pid=6162 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1841):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1841): type=1300 msg=audit(1452773837.375:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=be921d58 items=0 ppid=307 ppcomm=main pid=6162 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1841): type=1320 msg=audit(1452773837.375:205): 
,W/jxcore-log( 6162): Platform android
W/jxcore-log( 6162): 
W/jxcore-log( 6162): Process ARCH arm
W/jxcore-log( 6162): 
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6162): JXcore Cordova bridge is ready!
I/jxcore-log( 6162): 
,W/jxcore-log( 6162): JXcore engine is started
I/Choreographer( 6162): Skipped 128 frames!  The application may be doing too much work on its main thread.
I/chromium( 6162): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1015): stay LED for charging
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2622): Disconnected process message: 10
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/jxcore-log( 6162): Toggling radios to true
I/jxcore-log( 6162): 
,D/BluetoothAdapter( 6162): enable()
,D/BluetoothAdapter( 6162): enable(): BT is already enabled..!
,D/SecContentProvider( 1015): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1015): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1015): mCursor = null
,D/WifiService( 1015): setWifiEnabled: true pid=6162, uid=10174
,W/ActivityManager( 1015): Permission Denial: getCurrentUser() from pid=6162, uid=10174 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1015): Failed getting userId using ActivityManagerNative
W/WifiService( 1015): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6162, uid=10174 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1015): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1015): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1015): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1015): name = wifi_on
,I/WifiService( 1015): disconnect: pid=6162, uid=10174
,I/jxcore-log( 6162): Radios toggled
I/jxcore-log( 6162): 
I/wpa_supplicant( 2155): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6162): My device name is: samsung-SM-A500FU
I/jxcore-log( 6162): 
,I/wpa_supplicant( 2155): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
,I/wpa_supplicant( 2155): wlan0: State: COMPLETED -> DISCONNECTED
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2155): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 2155): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2155): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/wpa_supplicant( 2155): Cmd 35605 not handled
D/Tethering( 1015): InitialState.processMessage what=4
E/WifiStateMachine( 1015): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 2155): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2155): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2155): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2155): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 2155): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 2155): First Scan Start
,I/wpa_supplicant( 2155): Scan requested (ret=0) - scan timeout 30 seconds
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Tethering( 1015): No numeric data
,D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering( 1015): clearTetheredNotification()
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/HotspotTile( 1168): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1168): updateTetherState():false, false
,V/NetworkStats( 1015): performPollLocked() took 5ms
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1015): do suspend true
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/CommandListener(  276): Clearing all IP addresses on wlan0,
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1168): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NativeCrypto( 1684): Read error: ssl=0xb94960f0: I/O error during system call, Connection timed out
,E/WifiStateMachine( 1015): Start Disconnecting Watchdog 1
E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,V/NativeCrypto( 1684): SSL shutdown failed: ssl=0xb94960f0: I/O error during system call, Broken pipe
,I/wpa_supplicant( 2155): wlan0: Setting scan request: 0 sec 0 usec,
,D/ConnectivityService( 1015): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1015): Tagging socket 360 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1015, getuid(): 1000
I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14949 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6950 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1168): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/qtaguid ( 1015): Untagging socket 360
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,E/WifiNative-wlan0( 1015): do suspend true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3619): Starting #8
D/WifiP2pService( 1015): InactiveState{ what=143375 }
D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 3619): Message received 5007
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1168): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1324): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1324): MountReceiver.mPrefHandler - 7002
,D/EnterpriseController(  276): uids 1000
,D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  276): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
D/ConnectivityService( 1015): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
D/ConnectivityService( 1015): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1015): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524292
,D/CSLegacyTypeTracker( 1015): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
D/CSLegacyTypeTracker( 1015): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1460): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1460): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1168): onWifiSignalChanged enabled=true enabledDesc:null
D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1015): MasterInitialState.processMessage what=3
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,V/NetworkStats( 1015): updateIfacesLocked()
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1168): EthernetConnected: false
D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1168): updateDataNetType()
D/StatusBar.NetworkController( 1168): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1168): updateLTEICONDataNetType:0
,D/WifiNetworkAgent( 1015): NetworkAgent: NetworkAgent channel lost
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,V/NetworkStats( 1015): performPollLocked() took 8ms
D/ConnectivityService( 1015): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): doQuit - quitNow()
,D/StatusBar.NetworkController( 1168): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1168): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6280): MountEmulatedStorage(),
I/libpersona( 6280): KNOX_SDCARD checking this for 10104
E/Zygote  ( 6280): v2
I/libpersona( 6280): KNOX_SDCARD not a persona
,I/SELinux ( 6280): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6280 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 6280): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6280): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6280): TimaSignature is unavailable
,D/ActivityThread( 6280): Added TimaKeyStore provider
,W/ResourcesManager( 6280): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3,
D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/PhoneApp( 1460): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,I/Babel_SMS( 6280): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 6280): MmsConfig.loadMmsSettings
I/Babel_SMS( 6280): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 6280): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6280): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6280): MmsConfig.loadFromResources
,E/Babel_SMS( 6280): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6280): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  281): getCameraInfo: X
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  281): getCameraInfo: X
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6280): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6280): startup - clean
,I/Babel   ( 6280): deleted: false for 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3619): Starting #9
,I/Hs20UtilService( 3619): Message received 5007
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1324): MountReceiver.onReceive - Set preference state off
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/NearbySettings( 1324): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6280): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6280): Unsupported mime audio/evrc
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/AudioCapabilities( 6280): Unsupported mime audio/qcelp
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/DBG_DM  ( 3054): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ApplicationPolicy( 1015): updateDataUsageMap
,W/AudioCapabilities( 6280): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6280): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6280): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6280): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6280): Unsupported mime audio/qcelp
,I/DBG_DM  ( 3054): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,W/AudioCapabilities( 6280): Unsupported mime audio/evrc
,W/VideoCapabilities( 6280): Unsupported mime video/wvc1
,W/VideoCapabilities( 6280): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6280): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6280): Unsupported mime video/wvc1
,W/VideoCapabilities( 6280): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6280): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6280): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6280): Unsupported mime video/mp43
,W/VideoCapabilities( 6280): Unsupported mime video/sorenson
,W/VideoCapabilities( 6280): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6280): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6280): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6280): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6280): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6280): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1015): Killing 5043:com.google.android.music:main/u0a111 (adj 15): empty #31
,I/vclib   ( 6280): onServiceConnected
,W/Babel   ( 6280): Attempted to change video mute state without an active call.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/libprocessgroup( 1015): failed to open /acct/uid_10111/pid_5043/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ConfigService( 1684): onDestroy
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
,I/PCWCLIENTTRACE_PushUtil( 5821): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5821): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5821): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5821): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
I/splitIntent( 1015): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1015): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5821): noConnectivity : true
,E/Zygote  ( 6323): MountEmulatedStorage(),
,I/libpersona( 6323): KNOX_SDCARD checking this for 10111,
E/Zygote  ( 6323): v2
I/libpersona( 6323): KNOX_SDCARD not a persona
I/SELinux ( 6323): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6323 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6323): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6323): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 2155): nl80211: Received scan results (14 BSSes)
I/wpa_supplicant( 2155): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 2155): Trying to associate with SSID '4E47373030'
,I/wpa_supplicant( 2155): Trying to associate with  'G700'
I/wpa_supplicant( 2155): Re-associate with C0.AA.48
I/wpa_supplicant( 2155): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 2155): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1015): didn't find BSSID Trying to associate with SSID 'NG700'
,D/TimaKeyStoreProvider( 6323): TimaSignature is unavailable
,D/ActivityThread( 6323): Added TimaKeyStore provider
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,I/MusicStore( 6323): Database version: 120
,E/wpa_supplicant( 2155): Cmd 35605 not handled
,I/wpa_supplicant( 2155): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2155): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
I/wpa_supplicant( 2155): wlan0: State: ASSOCIATING -> ASSOCIATED
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2155): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 2155): Associated with C0.AA.48
I/wpa_supplicant( 2155): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2155): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2155): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceStatusChanged wlan0, false
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,I/wpa_supplicant( 2155): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 2155): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 2155): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 2155): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 2155): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2155): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2155): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 2155): Blacklist: Clear (temp) 
I/wpa_supplicant( 2155): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
D/Tethering( 1015): interfaceStatusChanged wlan0, true
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceStatusChanged wlan0, true
,E/Tethering( 1015): No numeric data
,D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1015): clearTetheredNotification()
,D/WifiNative-wlan0( 1015): callSECApiVoid - ID [50]
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/HotspotTile( 1168): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1168): updateTetherState():false, false
,V/NetworkStats( 1015): performPollLocked() took 4ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,E/WifiConfigStore( 1015): setLastSelectedConfiguration -1
,D/ConnectivityService( 1015): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1015): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1015): updateNetworkInfo()
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1168): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  276): Setting iface cfg
,E/WifiStateMachine( 1015): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1015): mCursor = null
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6323): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/WifiNative-wlan0( 1015): do suspend false
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6323): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6323): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6323): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6323): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6323): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6323): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6323): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12d28cca: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6323): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6323): GMSCore installation verified
,I/ConfigStore( 6323): Config Database version: 1
,E/SQLiteLog( 1684): (10) POSIX Error : 11 SQLite Error : 3850
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/dhcpcd  ( 6348): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6348): version 5.5.6 starting
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,E/dhcpcd  ( 6348): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/dhcpcd  ( 6348): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6348): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6348): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6348): bssid match
,I/dhcpcd  ( 6348): wlan0: rebinding lease of 192.168.1.137
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1015): getStreamVolume 3 index 0
,I/MediaRouter( 6323): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6323): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6357): MountEmulatedStorage()
E/Zygote  ( 6357): v2
I/libpersona( 6357): KNOX_SDCARD checking this for 10002
I/libpersona( 6357): KNOX_SDCARD not a persona
I/SELinux ( 6357): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6357): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1015): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6357 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6357): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SSRM:n  ( 1015): SIOP:: AP = 360
,I/GHttpClientFactory( 6323): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GoogleURLConnFactory( 6323): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6357): TimaSignature is unavailable
,D/ActivityThread( 6357): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1015): Killing 5372:com.google.android.gm/u0a101 (adj 15): empty #31
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6376): MountEmulatedStorage()
E/Zygote  ( 6376): v2
I/libpersona( 6376): KNOX_SDCARD checking this for 1000
I/libpersona( 6376): KNOX_SDCARD not a persona
,I/SELinux ( 6376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6376 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/dhcpcd  ( 6348): wlan0: acknowledged 192.168.1.137 from 192.168.1.1
,D/TimaKeyStoreProvider( 6376): TimaSignature is unavailable
,D/ActivityThread( 6376): Added TimaKeyStore provider
,I/dhcpcd  ( 6348): wlan0: leased 192.168.1.137 for 86400 seconds
,I/DIAGMON_AGENT( 6376): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] ,
,W/libprocessgroup( 1015): failed to open /acct/uid_10101/pid_5372/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6376): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,I/DIAGMON_AGENT( 6376): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,I/DIAGMON_AGENT( 6376): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
,I/DIAGMON_AGENT( 6376): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6376): ./extraInfo: <unknown ssid>
W/DIAGMON_AGENT( 6376): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6411): MountEmulatedStorage()
,E/Zygote  ( 6411): v2
I/libpersona( 6411): KNOX_SDCARD checking this for 10009
I/libpersona( 6411): KNOX_SDCARD not a persona
,I/SELinux ( 6411): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6411): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6411): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1015): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6411 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5155:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6411): TimaSignature is unavailable
,D/ActivityThread( 6411): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 4199:com.sec.spp.push/u0a35 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3639): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 14 13:17:20 GMT+01:00 2016
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3639): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3639): KLMSIntentService(): onCreate()
,E/WifiNative-wlan0( 1015): do suspend true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3639): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3639): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3639): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/Zygote  ( 6428): MountEmulatedStorage(),
E/Zygote  ( 6428): v2
I/libpersona( 6428): KNOX_SDCARD checking this for 10034
I/libpersona( 6428): KNOX_SDCARD not a persona
,I/SELinux ( 6428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1015): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6428 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,I/KLMS-2.5.183: ( 3639): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/SELinux ( 6428): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3639): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3639): StateImplV2(): networkChangeListener().END
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1015): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1015): VerifyingLinkState enter
,D/WifiNative-wlan0( 1015): callSECApiInt - ID [210]
,E/ConnectivityService( 1015): updateNetworkInfo()
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1015): Adding iface wlan0 to network 503
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1168): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/art     (  307): Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 756us total 27.577ms
,D/WifiWatchdogStateMachine( 1015): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
D/WifiWatchdogStateMachine.DnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1168): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1015): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 721us total 20.594ms
,I/KLMS-2.5.183: ( 3639): KLMSIntentService(): onDestroy()
,E/WifiStateMachine( 1015): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 1015): Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
,D/ConnectivityService( 1015): Adding Route [fe80::/64 -> :: wlan0] to network 503
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
D/ConnectivityService( 1015): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1015): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1015): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1015): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1015): LTETest block dns file not exists
,D/TimaKeyStoreProvider( 6428): TimaSignature is unavailable
D/ActivityThread( 6428): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1168): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1015): mBoosterFLAG : 0
I/WifiTrafficPoller( 1015): current booster mode : FullMode
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 19.165ms
,D/WifiNative-wlan0( 1015): callSECApiVoid - ID [212]
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1015): updateNetworkInfo()
E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1015): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 503]
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
D/STATUSBAR-WifiQuickSettingButton( 1168): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService( 1015):    accepting network in place of null
D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1460): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1460): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EnterpriseController(  276): uids 1000
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 1000
,E/CSLegacyTypeTracker( 1015): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1015): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 1015): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1015): MasterInitialState.processMessage what=3
D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524290
,V/NetworkStats( 1015): updateIfacesLocked()
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1168): EthernetConnected: false
D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1168): updateDataNetType()
D/StatusBar.NetworkController( 1168): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1168): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked() took 6ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1168): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1168): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF,
,W/libprocessgroup( 1015): failed to open /acct/uid_10044/pid_5155/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_4199/cgroup.procs: No such file or directory
,I/SO_AGENT( 6428): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5851): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5851): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 6121): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6121): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6121): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6121): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5851): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5851): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 6121): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6121): [OR] == isSIMCardReady false ==
,I/SA      ( 6121): [SCU] == networkStateCheck == true
I/SA      ( 6121): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6121): isChinaCountryCode : false
I/SA      ( 6121): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6121): [OR] == networkStateCheck true ==
,I/SA      ( 6121): [OR] GetMyCountryZoneTask
,I/SA      ( 6121): [OR] onReceive END
,I/DBG_POLICYDM( 5851): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/System.out( 1015): KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,I/ActivityManager( 1015): Killing 5773:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,V/DownloadManager( 1224): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 6121): [SRS] prepareGetMyCountryZone
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 6121): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6121): [SSP] query invoked
,D/accuweather( 1600): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5851): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5851): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 14 Jan 2016 12:17:20 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452773840680], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452773840658]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
,D/ConnectivityService( 1015): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1015): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1168): EthernetConnected: false
,D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1168): updateDataNetType()
D/StatusBar.NetworkController( 1168): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1168): updateLTEICONDataNetType:0
E/DBG_POLICYDM( 5851): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/StatusBar.NetworkController( 1168): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1168): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/daemonapp( 1288): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 16
,D/accuweather( 1600): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1600): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1600): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1600): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5851): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,W/libprocessgroup( 1015): failed to open /acct/uid_10100/pid_5773/cgroup.procs: No such file or directory
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 69789(3MB) AllocSpace objects, 8(176KB) LOS objects, 33% free, 27MB/41MB, paused 2.613ms total 165.842ms
,I/SA      ( 6121): [TPMU] GetMccFromDB : null
I/SA      ( 6121): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6121): [TPM] isNoProxy(default) : true
,D/accuweather( 1600): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1600): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/File    ( 6121): fail readDirectory() errno=2
,E/Zygote  ( 6454): MountEmulatedStorage()
E/Zygote  ( 6454): v2
,I/libpersona( 6454): KNOX_SDCARD checking this for 10125
I/libpersona( 6454): KNOX_SDCARD not a persona
,I/SELinux ( 6454): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6454 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6454): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6454): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1015): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1015): mCursor = null
,D/TimaKeyStoreProvider( 6454): TimaSignature is unavailable
,D/ActivityThread( 6454): Added TimaKeyStore provider
,W/ResourcesManager( 6454): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6454): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6454): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6454): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6454): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6454): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6469): MountEmulatedStorage()
E/Zygote  ( 6469): v2
I/libpersona( 6469): KNOX_SDCARD checking this for 10145
I/libpersona( 6469): KNOX_SDCARD not a persona
I/SELinux ( 6469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 6469): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6469 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5350:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6469): TimaSignature is unavailable
,D/ActivityThread( 6469): Added TimaKeyStore provider
,W/ResourcesManager( 6469): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6469): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6469): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_5350/cgroup.procs: No such file or directory
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/DBG_DM  ( 3054): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 6323): type=WIFI subType= reason=null isConnected=true
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6488): MountEmulatedStorage()
E/Zygote  ( 6488): v2
I/libpersona( 6488): KNOX_SDCARD checking this for 10075
I/libpersona( 6488): KNOX_SDCARD not a persona
,I/SELinux ( 6488): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1015): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6488 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6488): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6488): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 5451:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 6488): TimaSignature is unavailable
,D/ActivityThread( 6488): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 5801:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/BadgeProvider( 5945): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 1483): reloadBadges entered.
,D/BadgeProvider( 5945): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5945): sendNotify, [notify] : null
,D/BadgeProvider( 5945): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5945): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5945): update, [UpdateCount] : 1
,W/libprocessgroup( 1015): failed to open /acct/uid_10015/pid_5451/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10091/pid_5801/cgroup.procs: No such file or directory
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6508 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1015): Killing 5833:com.samsung.helphub/1000 (adj 15): empty #31
,E/Zygote  ( 6508): MountEmulatedStorage(),
E/Zygote  ( 6508): v2,
I/libpersona( 6508): KNOX_SDCARD checking this for 1000
I/libpersona( 6508): KNOX_SDCARD not a persona,
,I/SELinux ( 6508): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6508): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6508): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6508): TimaSignature is unavailable
,D/ActivityThread( 6508): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/SA      ( 6121): [RC New] Execute method=[GET] start,
,D/SecurityLogAgent( 6508): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6508): KnoxConfiguration : Current State Mapping Found ,
,D/SecurityLogAgent( 6508): StateMachine : Current State = 1
,D/SecurityLogAgent( 6508): StateMachine : Changed Current State = 1
,I/SA      ( 6121): [RC New] Security=[true]
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/System.out( 6121): Thread-1060(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/System.out( 6121): Thread-1060(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6121): Thread-1060(ApacheHTTPLog):isShipBuild true
I/System.out( 6121): Thread-1060(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6121): Thread-1060(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController(  276): uids 10041
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 10041
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5833/cgroup.procs: No such file or directory,
,E/Zygote  ( 6529): MountEmulatedStorage()
E/Zygote  ( 6529): v2
I/libpersona( 6529): KNOX_SDCARD checking this for 10159
I/libpersona( 6529): KNOX_SDCARD not a persona
,I/SELinux ( 6529): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1015): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6529 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5466:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,I/SELinux ( 6529): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6529): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6529): TimaSignature is unavailable
,D/ActivityThread( 6529): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1015): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/GAV2    ( 6488): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6488): Created application version: 3.6.9 (30609)
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1858): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_10032/pid_5466/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1858): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6550 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6550): MountEmulatedStorage()
,I/libpersona( 6550): KNOX_SDCARD checking this for 10035
E/Zygote  ( 6550): v2
,I/libpersona( 6550): KNOX_SDCARD not a persona
I/SELinux ( 6550): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 6550): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 6550): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6550): TimaSignature is unavailable
,D/ActivityThread( 6550): Added TimaKeyStore provider
,I/System.out( 6280): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6280): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6280): (HTTPLog)-Static: isShipBuild true
I/System.out( 6280): (HTTPLog)-Thread-1091-160751913: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6280): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10104
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 10104
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksSync( 6488): Starting books sync for 61035162, extras: ade
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6280): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 1858): [AccountUtils] Account not ready
W/Kids    ( 1858): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1858): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1858): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1858): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1858): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1858): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1858): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1858): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1858): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1858): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1858): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1858): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
,E/SPPClientService( 6550): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6550): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6550): [SystemStateMoniter] Current Time : 89432
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PanelView( 1168): There is/are notification(s) 
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
E/SPPClientService( 6550): [PushClientApplication] Push log off : This is Ship build version
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SPPClientService( 6550): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/Babel   ( 6280): connection state changed from UNKNOWN to CONNECTED
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6550): PushLog.txt file is not deleted.
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/SPPClientService( 6550): PushLog.txt file is not deleted.
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/SPPClientService( 6550): ============PushLog. stop!
,E/Zygote  ( 6571): MountEmulatedStorage()
E/Zygote  ( 6571): v2
I/libpersona( 6571): KNOX_SDCARD checking this for 10113
I/libpersona( 6571): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6571 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6571): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6571): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6571): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SPPClientService( 6550): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 6571): TimaSignature is unavailable
D/ActivityThread( 6571): Added TimaKeyStore provider
,D/PanelView( 1168): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ActivityManager( 1015): Killing 5889:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 6488): (284) automatic index on view_volumes(volume_id)
,I/BooksConfig( 6488): GmsCore Version = 7.8.99 (2134222-436)
,W/libprocessgroup( 1015): failed to open /acct/uid_10152/pid_5889/cgroup.procs: No such file or directory
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6571): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6571): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6571):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6571):   adb logcat -s GAv4
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6571): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 6571): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ContextImpl( 6571): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6571): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/GAv4    ( 6571): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 6571): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/SA      ( 6121): [RC New] [v2liruge] api execute + 676
I/SA      ( 6121): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6121): AsyncTask #1 calls detatch()
I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SA      ( 6121): [ODM] saveOpenData( GEO_IP, PL )
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/SA      ( 6121): [OCP] update openData : PL
,I/SA      ( 6121): [TPMU] getNetworkMcc : 
,E/BooksAccountManager( 6488): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,I/SA      ( 6121): [SCU] saveMccToPreferece Start
I/SA      ( 6121): [SCU] RegionMCC : 260
I/SA      ( 6121): [SSP] query invoked
,E/BooksSync( 6488): Soft error
E/BooksSync( 6488): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6488): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/SA      ( 6121): [TPMU] GetMccFromDB : null
I/SA      ( 6121): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6121): [SCU] saveMccToPreferece End
,I/SA      ( 6121): [RC New] executeRequest [v2liruge] end. 734
I/SA      ( 6121): [RC New] Execute end
I/SA      ( 6121): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6121): [OR] GetMyCountryZoneTask Success
,E/BooksSync( 6488): Sync error
E/BooksSync( 6488): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6488): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6488): Finished books sync
,D/PanelView( 1168): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ActivityManager( 1015): Killing 5909:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 64158, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,I/ActivityManager( 1015): Killing 5532:com.android.vending/u0a28 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10156/pid_5909/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6571): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6571): Time to load native libraries: 2 ms (timestamps 9963-9965)
I/LibraryLoader( 6571): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6571): Binding Chromium to main looper Looper (main, tid 1) {1d7693e0}
,I/LibraryLoader( 6571): Expected native library version number "",actual native library version number ""
,I/chromium( 6571): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6571): Initializing chromium process, singleProcess=true
,W/art     ( 6571): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6571): ApplicationContext is null in ApplicationStatus
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/chromium( 6571): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6571): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6571): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6571): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6571): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6571): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6571): Local Branch: 
I/Adreno-EGL( 6571): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6571): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6571):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/libprocessgroup( 1015): failed to open /acct/uid_10028/pid_5532/cgroup.procs: No such file or directory
,W/AudioManagerAndroid( 6571): Requires BLUETOOTH permission
,I/NSApplication( 6571): Starting up...
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6631 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1015): Killing 5789:com.android.mms/u0a46 (adj 15): empty #31
,E/Zygote  ( 6631): MountEmulatedStorage()
E/Zygote  ( 6631): v2
I/libpersona( 6631): KNOX_SDCARD checking this for 10081
I/libpersona( 6631): KNOX_SDCARD not a persona
,I/SELinux ( 6631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6631): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6631): TimaSignature is unavailable
,D/ActivityThread( 6631): Added TimaKeyStore provider
,D/CountryDetector( 1015): No listener is left
,W/libprocessgroup( 1015): failed to open /acct/uid_10046/pid_5789/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 6201): notifyNetworkActivated
,W/ContextImpl( 6201): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6201): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6201): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6201): exit::IDLE
D/InitializeManagerStateMachine( 6201): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6201): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6201): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6201): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6201): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6201): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6201): entry::SUCCESS
D/hcjo    ( 6201): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3619): Starting #10
I/Hs20UtilService( 3619): Message received 5007
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
D/hcjo    ( 6201): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6201): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6201): exit::SUCCESS
D/InitializeManagerStateMachine( 6201): entry::IDLE
,I/ActivityManager( 1015): Killing 5959:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3619): Starting #11
D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3619): Message received 5007
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3619): Starting #12
,I/Hs20UtilService( 3619): Message received 5007
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3619): Starting #13
,I/Hs20UtilService( 3619): Message received 5007
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1015): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1015): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5821): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5821): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5821): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5821): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
I/splitIntent( 1015): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1015): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6323): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/libprocessgroup( 1015): failed to open /acct/uid_10047/pid_5959/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  256): id=15 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6376): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6376): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6376): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6376): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService( 1015): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,D/SRIB_DCS( 1168): log_dcs ThreadedRenderer::initialize entered! 
,I/DBG_POLICYDM( 5851): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5851): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5851): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5851): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5851): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6411): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6411): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.183: ( 3639): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 14 13:17:23 GMT+01:00 2016
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3639): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3639): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3639): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3639): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3639): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3639): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3639): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3639): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3639): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.183: ( 3639): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3639): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3639): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5851): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5851): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 6121): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6121): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6121): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/DBG_POLICYDM( 5851): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 6121): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6121): [OR] == isSIMCardReady false ==
,I/SA      ( 6121): [SCU] == networkStateCheck == true
I/SA      ( 6121): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 6121): isChinaCountryCode : false
I/SA      ( 6121): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6121): [OR] == networkStateCheck true ==
,I/SA      ( 6121): [OR] GetMyCountryZoneTask
,I/SA      ( 6121): [OR] onReceive END
,I/SA      ( 6121): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1224): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 6121): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6121): [SSP] query invoked
,D/accuweather( 1600): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 28744(1578KB) AllocSpace objects, 3(88KB) LOS objects, 33% free, 27MB/40MB, paused 2.610ms total 139.889ms
,D/SecContentProvider2( 1015): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1015): mCursor = null
,I/SA      ( 6121): [TPMU] GetMccFromDB : null
I/SA      ( 6121): [SCU] getMccFromPreferece mcc = 260
,D/daemonapp( 1288): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
I/SA      ( 6121): [TPM] isNoProxy(default) : true
I/SA      ( 6121): [RC New] Execute method=[GET] start
,D/accuweather( 1600): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1600): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1600): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1600): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1600): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1600): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6454): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6454): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6454): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6508): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6508): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6508): StateMachine : Current State = 1
,D/SecurityLogAgent( 6508): StateMachine : Changed Current State = 1
,I/SA      ( 6121): [RC New] Security=[true]
,I/System.out( 6121): Thread-1062(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6121): Thread-1062(ApacheHTTPLog):isShipBuild true
I/System.out( 6121): Thread-1062(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6121): Thread-1062(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1858): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1858): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6550): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6550): [SystemStateMoniter] Current Time : 91024
,E/SPPClientService( 6550): [SystemStateMoniter] No Connect : false
,I/System.out( 6280): (HTTPLog)-Static: isSBSettingEnabled false
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/hcjo    ( 6201): AutoUpdateManager:IDLE:execute
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,D/InitializeManagerStateMachine( 6201): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6201): exit::IDLE
D/InitializeManagerStateMachine( 6201): entry::NETWORK_CHECK
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/InitializeManagerStateMachine( 6201): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6201): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6201): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6201): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6201): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6201): entry::SUCCESS
D/hcjo    ( 6201): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6201): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6201): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6201): exit::SUCCESS
D/InitializeManagerStateMachine( 6201): entry::IDLE
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 1858): [AccountUtils] Account not ready
W/Kids    ( 1858): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1858): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1858): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1858): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1858): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1858): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1858): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1858): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1858): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1858): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1858): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1858): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1168): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/SA      ( 6121): [RC New] [v2liruge] api execute + 578
,I/SA      ( 6121): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6121): AsyncTask #2 calls detatch()
,I/SA      ( 6121): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6121): [OCP] update openData : PL
,I/SA      ( 6121): [TPMU] getNetworkMcc : 
,I/SA      ( 6121): [SCU] saveMccToPreferece Start
,I/SA      ( 6121): [SCU] RegionMCC : 260
I/SA      ( 6121): [SSP] query invoked
,I/SA      ( 6121): [TPMU] GetMccFromDB : null
,I/SA      ( 6121): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6121): [SCU] saveMccToPreferece End
,I/SA      ( 6121): [RC New] executeRequest [v2liruge] end. 628
I/SA      ( 6121): [RC New] Execute end
,I/SA      ( 6121): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6121): [OR] GetMyCountryZoneTask Success
,I/ActivityManager( 1015): Killing 5996:com.wsomacp/u0a25 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10025/pid_5996/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6348): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6348): wlan0: sendmsg: Cannot assign requested address
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524295
,V/AlarmManager( 1015): waitForAlarm result :4
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 10012
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
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
,D/WearableService( 4475): callingUid 10012, callindPid: 4475
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6323): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6323): Stop autocaching.
,E/GmsUtils( 6323): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6323): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/GCM     ( 1684): Connected
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1684): Message class com.google.f.a.a.p
,I/PowerManagerService( 1015): [PWL] Off : 15s ago
,I/PowerManagerService( 1015): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1015): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1858, ws=null) (elapsedTime=57179)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  256): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  256): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1015): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 94043
,D/PowerManagerService( 1015): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
,D/PowerManagerService( 1015): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{10054}) (elapsedTime=3483)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6488): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5821): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5821): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5821): [GetString-S]
,I/ReactiveServiceManager( 5821): Supported : 1
,D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 12
,D/QSEECOMAPI: ( 1015): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1015): QSEECom_shutdown_app, app_id = 12
,E/terrier ( 1015): handleString: Failed to handle string(-4)
E/terrier ( 1015): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5821): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5821): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5821): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5821): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5821): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5821): [ensureRegistration] - No Samsung account
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{2efcdffe u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/dhcpcd  ( 6348): wlan0: sending IPv6 Router Solicitation
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/jxcore-log( 6162): Test app app.js loaded
I/jxcore-log( 6162): 
,I/Choreographer( 6162): Skipped 653 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6162): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 360
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6692): MountEmulatedStorage()
I/libpersona( 6692): KNOX_SDCARD checking this for 10028
E/Zygote  ( 6692): v2
I/libpersona( 6692): KNOX_SDCARD not a persona
,I/SELinux ( 6692): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6692): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6692 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6692): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6692): TimaSignature is unavailable
,D/ActivityThread( 6692): Added TimaKeyStore provider
,D/Finsky  ( 6692): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6692): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/Settings( 6692): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6692): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 6692): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6692): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6692): [1145] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/Finsky  ( 6692): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6692): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 6348): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 6348): wlan0: no IPv6 Routers available
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6692): [1145] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/ActivityManager( 1015): Killing 6019:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,I/art     ( 1684): Explicit concurrent mark sweep GC freed 17751(980KB) AllocSpace objects, 8(288KB) LOS objects, 39% free, 10MB/17MB, paused 985us total 39.440ms
,V/Finsky  ( 6692): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/libprocessgroup( 1015): failed to open /acct/uid_10053/pid_6019/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6201): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6201): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6201): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6201): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6201): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6201): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6201): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6201): entry::IDLE
,V/AlarmManager( 1015): waitForAlarm result :4
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6692): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6692): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6692): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6201): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6201): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6201): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6201): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6201): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PreloadUpdateManagerStateMachine( 6201): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6201): entry::IDLE
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6692): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6692): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6692): [1] 5.onFinished: Scheduling replication attempt 2.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6692): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6692): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6692): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6692): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1653): client connected with version: 7571000
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4271, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 27112(1317KB) AllocSpace objects, 6(116KB) LOS objects, 33% free, 27MB/40MB, paused 2.569ms total 174.533ms
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/SSRM:n  ( 1015): SIOP:: AP = 330
,I/PowerManagerService( 1015): [PWL] Off : 30s ago
,E/Watchdog( 1015): !@Sync 3
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/FactoryTest( 5606): Not factory mode
,D/FactoryTest( 5606): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5606): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5606): still no open session command from host, so toast
,W/ContextImpl( 5606): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5606): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5606): Timeline: Activity_launch_request id:com.android.settings time:115986
,E/PersonaManagerService( 1015): inState():  stateMachine is null !!
,I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): mDVFSHelper.acquire()
,D/PersonaManager( 1015): isKioskContainerExistOnDevice,
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus left window: 6162
,E/MTPRx   ( 5606): started activity for popup
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5606): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5606): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5606): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5606): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5606): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5606): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5606): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus entered window: 6162
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1015): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@243f2c53 attribute=null, token = android.os.BinderProxy@3ecbe1b
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4275, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SettingsReceiverActivity( 5606): dev.kiessupport is : TRUE,
,D/PhoneWindow( 5606): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5606): *FMB* installDecor flags : 8388610
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
,D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,V/ActivityThread( 6162): updateVisibility : ActivityRecord{22388a49 token=android.os.BinderProxy@9674e13 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6162): Timeline: Activity_idle id: android.os.BinderProxy@9674e13 time:116168
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 310
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,W/ActivityManager( 1015): mDVFSHelper.release()
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/BooksSync( 6488): Starting books sync for 61035162, extras: ade
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/BooksConfig( 6488): GmsCore Version = 7.8.99 (2134222-436)
,D/Finsky  ( 6692): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6692): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6692): [1] 5.onFinished: Scheduling replication attempt 3.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1168): isKioskContainerExistOnDevice
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,D/PanelView( 1168): There is/are notification(s) ,
D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6488): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6488): Soft error
E/BooksSync( 6488): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6488): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6488): Sync error
E/BooksSync( 6488): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6488): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6488): Finished books sync
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 120131, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1168): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 300
,I/PowerManagerService( 1015): [PWL] Off : 50s ago
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4278, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 300
,E/Watchdog( 1015): !@Sync 4
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1015): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1015): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1015): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/SecKeyguardClockView( 1168): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1168): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6692): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6692): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6692): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/PowerManagerService( 1015): [PWL] Off : 75s ago
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4281, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6692): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6692): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6692): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/Watchdog( 1015): !@Sync 5
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 290,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6488): Starting books sync for 61035162, extras: ade
V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,I/BooksConfig( 6488): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6488): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6488): Soft error
E/BooksSync( 6488): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6488): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6488): Sync error
E/BooksSync( 6488): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6488): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6488): Finished books sync
,D/PanelView( 1168): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 182173, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6692): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6692): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6692): [1] 5.onFinished: Giving up after 6 failures.
,I/PowerManagerService( 1015): [PWL] Off : 105s ago
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/Watchdog( 1015): !@Sync 6
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/SecKeyguardClockView( 1168): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1168): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecKeyguardStatusUtils( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1684): Vacuum at: now=1452773955124 tag=VacuumService
,I/GoogleURLConnFactory( 1684): Using platform SSLCertificateSocketFactory
,W/Uploader( 1684): No account for auth token provided
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1684): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1684): (HTTPLog)-Static: isShipBuild true
I/System.out( 1684): (HTTPLog)-Thread-195-584564959: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1684): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1684): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,I/qtaguid ( 1684): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 45140(2MB) AllocSpace objects, 45(760KB) LOS objects, 33% free, 27MB/41MB, paused 2.533ms total 145.066ms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
,E/Uploader( 1684): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1684): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1684): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1684): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1684): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1684): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1684): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1684): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1684): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1684): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1684): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1684): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1684): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1684): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,W/Uploader( 1684): No account for auth token provided
,I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1684): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,D/PanelView( 1168): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/Uploader( 1684): No account for auth token provided
,I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1684): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,W/Uploader( 1684): No account for auth token provided
,I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1684): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,W/Uploader( 1684):  no longer exists, so no auth token.
,I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1684): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,E/SQLiteLog( 1684): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,V/AlarmManager( 1015): waitForAlarm result :4
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/PowerManagerService( 1015): [PWL] Off : 140s ago
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/Watchdog( 1015): !@Sync 7
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4285, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4281, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PowerManagerService( 1015): [PWL] Off : 180s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/Watchdog( 1015): !@Sync 8
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4285, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4285, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 280
,E/Watchdog( 1015): !@Sync 9
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 280
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 225s ago
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/SecKeyguardClockView( 1168): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1168): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6488): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6488): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/art     ( 1684): Explicit concurrent mark sweep GC freed 47937(2MB) AllocSpace objects, 43(2MB) LOS objects, 39% free, 10MB/17MB, paused 1.250ms total 54.506ms
,D/PanelView( 1168): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6488): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6488): Soft error
E/BooksSync( 6488): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6488): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6488): Sync error
E/BooksSync( 6488): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6488): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6488): Finished books sync
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 303564, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4285, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1015): initializing...
,I/TLC_TIMA_PKM_initialize( 1015): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 13
,I/TZ: qc_tlc_communication( 1015): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1015): Trustlet response is completed
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10,
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/Watchdog( 1015): !@Sync 10
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6162): --= Surplus to requirements =--
I/jxcore-log( 6162): 
,I/jxcore-log( 6162): ****TEST TOOK:  ms ****
I/jxcore-log( 6162): 
I/jxcore-log( 6162): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6162): 
,D/AndroidRuntime( 6864): 
D/AndroidRuntime( 6864): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6864): CheckJNI is OFF
D/AndroidRuntime( 6864): readGMSProperty: start
D/AndroidRuntime( 6864): readGMSProperty: already setted!!
D/AndroidRuntime( 6864): propertySet: couldn't set property (it is from app),
D/AndroidRuntime( 6864): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6864): readGMSProperty: end
D/AndroidRuntime( 6864): addProductProperty: start
,E/AffinityControl( 6864): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6864): Calling main entry com.android.commands.pm.Pm,
,D/PackageManager( 1015): START PACKAGE DELETE: observer{266383620},
D/PackageManager( 1015): pkg{<packageName>}
D/PackageManager( 1015): user{0}
D/PackageManager( 1015): caller{2000}
D/PackageManager( 1015): flags{3}
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1015): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1015): !@killApplicatoin: 10174, uninstall pkg
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled,
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled :  enabled true
,I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10174 user=-1: uninstall pkg
,I/ActivityManager( 1015): Killing 6162:com.test.thalitest/u0a174 (adj 0): stop com.test.thalitest cause uninstall pkg
,I/WindowState( 1015): WIN DEATH: Window{319b5bb8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (6/8)
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (-2/8)
,D/InputDispatcher( 1015): Focus left window: 6162
I/ActivityManager( 1015):   Force finishing activity ActivityRecord{530bd79 u0 com.test.thalitest/.MainActivity t234}
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (-2/8)
,W/ActivityManager( 1015): mDVFSHelper.acquire()
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1015): Spurious death for ProcessRecord{25b2c6ed 6162:com.test.thalitest/u0a174}, curProc for 6162: null
I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10174 user=0: pkg removed
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{530bd79 u0 com.test.thalitest/.MainActivity t234 f}
,W/ActivityManager( 1015): Duplicate finish request for ActivityRecord{530bd79 u0 com.test.thalitest/.MainActivity t234 f}
,W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
,D/InputDispatcher( 1015): Focused application released
,I/DBG_DM  ( 3054): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/art     ( 5120): Explicit concurrent mark sweep GC freed 2369(132KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.115ms total 30.500ms
,I/DBG_DM  ( 3054): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 13
,E/SamsungIME( 1792): mOCRHelper is null
,I/DBG_DM  ( 3054): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,W/GeofencerStateMachine( 1653): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 3054): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3054): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 13
,D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,I/DBG_DM  ( 3054): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3054): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/KLMS-2.5.183: ( 3639): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 14 13:21:18 GMT+01:00 2016
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/DBG_DM  ( 3054): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 3054): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/KLMS-2.5.183: ( 3639): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1015): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
I/splitIntent( 1015): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1015): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,I/KLMS-2.5.183: ( 3639): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3639): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/art     ( 6180): Explicit concurrent mark sweep GC freed 22999(1798KB) AllocSpace objects, 1(18KB) LOS objects, 25% free, 8MB/11MB, paused 809us total 119.081ms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6878): MountEmulatedStorage()
E/Zygote  ( 6878): v2
I/libpersona( 6878): KNOX_SDCARD checking this for 10094
,I/libpersona( 6878): KNOX_SDCARD not a persona
,I/SELinux ( 6878): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6878 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/SELinux ( 6878): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6878): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3639): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3639): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/DBG_DM  ( 3054): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 13
,I/DBG_DM  ( 3054): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/KLMS-2.5.183: ( 3639): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.183: ( 3639): KLMSIntentService(): listeningToPackageRemoved().START
,I/DBG_DM  ( 3054): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3054): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false,
I/KLMS-2.5.183: ( 3639): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,I/DBG_DM  ( 3054): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3054): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,I/DBG_DM  ( 3054): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/SurfaceFlinger(  256): id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/TimaKeyStoreProvider( 6878): TimaSignature is unavailable
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ActivityThread( 6878): Added TimaKeyStore provider
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,D/InputDispatcher( 1015): Focus entered window: 3054
,D/RegisteredServicesCache( 1439): empty dynamic service
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3054): log_dcs ThreadedRenderer::initialize entered! 
,V/ActivityThread( 3054): updateVisibility : ActivityRecord{3f2db424 token=android.os.BinderProxy@7003bc5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1015): Got RemoteException sending setActive(false) notification to pid 6162 uid 10174
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 31578(2MB) AllocSpace objects, 55(920KB) LOS objects, 33% free, 27MB/41MB, paused 4.620ms total 228.389ms
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     ( 1015): WaitForGcToComplete blocked for 214.237ms for cause Explicit
,D/SamsungIME( 1792): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,I/Timeline( 3054): Timeline: Activity_idle id: android.os.BinderProxy@7003bc5 time:326476
,D/elm:15183( 6878): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 6878): ELMEngine.ELMEngine( context ).
,W/ActivityManager( 1015): mDVFSHelper.release()
I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{38a57ce8 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t233} time:326501
,D/elm:15183( 6878): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 6878): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1015): no available spell checker services found
,D/elm:15183( 6878): ElmAgentService : onCreate()
,D/elm:15183( 6878): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6878): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6878): MDMBridge.getInstance()
D/elm:15183( 6878): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15183( 6878): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.183: ( 3639): KLMSIntentService(): listeningToPackageRemoved().END
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.183: ( 3639): KLMSIntentService(): onDestroy()
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15183( 6878): ElmAgentService : onDestroy().
,I/ActivityManager( 1015): Killing 6037:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 11746(557KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 3.383ms total 180.229ms
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1015): delete codoeFile: 
,D/AASAuninstall( 1015): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.test.thalitest
I/AASA_removePackage( 1015): UID=10174 Target=com.test.thalitest
,D/PackageManager( 1015): result of delete: 1{266383620}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AndroidRuntime( 6864): Shutting down VM
,W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1015): PackageReceiver onReceive()
I/HarmonyEASService( 1015): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1015): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1015): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1015): DBIntegrity::getInstance - New instance created
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/OTPFW   ( 1015): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10174 container id = 0
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/OTPFW   ( 1015): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1015): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1015): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10174
,V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10174
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
,D/SSRM:aZ ( 1015): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/PanelView( 1168): There is/are notification(s) 
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/PCWCLIENTTRACE_PushUtil( 5821): SPPPushClient is installed : true
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PCWCLIENTTRACE_PushUtil( 5821): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5821): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5821): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/UsbSettingsManager( 1015): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1015): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_6037/cgroup.procs: No such file or directory
,E/Zygote  ( 6898): MountEmulatedStorage()
,E/Zygote  ( 6898): v2
I/libpersona( 6898): KNOX_SDCARD checking this for 10032
I/libpersona( 6898): KNOX_SDCARD not a persona
,I/SELinux ( 6898): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1015): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6898 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/TaskPersister( 1015): removeObsoleteFile: deleting file=234_task.xml
,I/SELinux ( 6898): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/TaskPersister( 1015): removeObsoleteFile: deleting file=233_task.xml
,E/SELinux ( 6898): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  307): Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 21.702ms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1168): isKioskContainerExistOnDevice
D/PersonaManager( 1168): isKioskContainerExistOnDevice
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): kidsfalse mQsExpansionEnabled:true
,D/TimaKeyStoreProvider( 6898): TimaSignature is unavailable
,D/ActivityThread( 6898): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 701us total 17.765ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 17.341ms
,I/FeatureConfig( 6898): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/SA      ( 6121): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6121): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10174 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1015): Killing 6062:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ResourcesManager( 6898): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/PanelView( 1168): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ResourcesManager( 6898): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  ( 6916): MountEmulatedStorage()
E/Zygote  ( 6916): v2
I/libpersona( 6916): KNOX_SDCARD checking this for 10044
I/libpersona( 6916): KNOX_SDCARD not a persona
W/art     ( 6864): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/SELinux ( 6916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6916 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ResourcesManager( 6898): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SELinux ( 6916): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6898): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6916): TimaSignature is unavailable
,D/ActivityThread( 6916): Added TimaKeyStore provider
,W/ResourcesManager( 6898): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.,
,W/ResourcesManager( 6898): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.,
,W/ResourcesManager( 6916): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6916): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6916): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6916): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6916): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6916): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6916): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6916): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_6062/cgroup.procs: No such file or directory
,W/ResourcesManager( 6898): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6898): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6898): system/finder_cp/cpdata.xml file not found
,E/SQLiteLog( 6916): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6916): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase( 6916): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6916): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6916): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6916): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6916): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6916): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6916): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6916): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6916): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6916): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6916): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase( 6916): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase( 6916): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6916): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6916): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6916): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6916): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6916): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6916): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6916): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6916): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6916): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)

```
