#### Test 55902202f27eba5_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Mms/DownloadManager( 5733): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5733): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5733): getSubId is called
D/Mms/TelephonyUtils( 5733): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5733): getTelephonyProperty is called
D/Mms/DownloadManager( 5733): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5733): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/TP/MmsSmsProvider( 1459): query,matched:400, calling pid = 5733
D/Mms/DownloadManager( 5733): auto download without roaming -> true
D/Mms/DownloadManager( 5733): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5733): mAutoDownload ------> true
--------- beginning of system
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5896): MountEmulatedStorage()
E/Zygote  ( 5896): v2
I/SELinux ( 5896): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 5896): KNOX_SDCARD checking this for 10072
I/libpersona( 5896): KNOX_SDCARD not a persona
D/Mms/FreeMessageStatusReceiver( 5733): onReceive, action : android.intent.action.PACKAGE_ADDED
I/SELinux ( 5896): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5896): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/Mms/Synchronizer( 5733): [end]    doSync consume time = 51.472968
D/Mms/SpamFilter( 5733): [end]    SpamFilter fill() finished consume time = 1.602969
I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5896 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 5896): TimaSignature is unavailable
D/ActivityThread( 5896): Added TimaKeyStore provider
I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/DBG_POLICYDM( 5802): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 5802): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
D/Mms/FreeMessageReceiverService( 5733): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5733): onHandleIntent: ACTION_PACKAGE_ADDED
I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 5802): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
E/Zygote  ( 5914): MountEmulatedStorage()
I/libpersona( 5914): KNOX_SDCARD checking this for 10047
E/Zygote  ( 5914): v2
I/libpersona( 5914): KNOX_SDCARD not a persona
I/SELinux ( 5914): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5914 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 5914): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5914): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/ActivityManager( 1018): Killing 5154:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
D/BadgeProvider( 5896): onCreate
D/BadgeProvider( 5896): DatabaseHelper
I/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ConfigFetchService( 1932): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/TimaKeyStoreProvider( 5914): TimaSignature is unavailable
D/ActivityThread( 5914): Added TimaKeyStore provider
I/ConfigFetchService( 1932): launchTask
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
D/ChimeraCfgMgr( 1932): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1932): Module APK com.google.android.play.games already loaded
D/Mms/MessagingNotification( 5733): checkBadgeCount unreadCount=0 badgeCount=0
I/PeopleContactsSync( 1932): CP2 sync disabled
W/ResourcesManager( 5914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5914): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5914): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/TP/SmsProvider( 1459): query,matched:26, calling pid = 5733
D/TP/SmsProvider( 1459): match 26:Elapsed time : 3.075 ms
I/DBG_POLICYDM( 5802): [com.policydm.XSPPReceiver(53/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
V/ConfigFetchTask( 1932): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VnUzRysUPPPXWr8cOc5NUCJSTyHRVAzQWaeay-hXKPCQT0Lf7czAHvE7FOxCJOKw39misaRLyRB8uwXJFzlhPrEMcaLIGfzDi1ApbyP6dPdetfR4jFw4cNOYOCLW-5FJ8ree0j3AHkxZucLwTDuEWCuUHXbT2iXx1xPF7250Jh9YbpMZ-kN87Pr7cLXomlU4oGYQ5h8HwQ3WO6MtTx-l5YdbBPjZwfuyOQ6Nq1B6xeqaMz_XM
D/ChimeraCfgMgr( 1932): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/ActivityManager( 1018): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5932 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
E/Zygote  ( 5932): MountEmulatedStorage()
I/libpersona( 5932): KNOX_SDCARD checking this for 10038
E/Zygote  ( 5932): v2
I/libpersona( 5932): KNOX_SDCARD not a persona
I/SELinux ( 5932): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Killing 3615:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/SELinux ( 5932): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5932): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Vision  ( 1932): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1932): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1932): No vision deps
I/GoogleURLConnFactory( 1932): Using platform SSLCertificateSocketFactory
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5932): TimaSignature is unavailable
D/TP/MmsSmsProvider( 1459): query,matched:6, calling pid = 5733
D/TP/MmsSmsProvider( 1459): match 6:Elapsed time : 1.595 ms
D/ActivityThread( 5932): Added TimaKeyStore provider
W/ResourcesManager( 5932): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5932): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5802): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
E/Zygote  ( 5948): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5948 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/Zygote  ( 5948): v2
I/libpersona( 5948): KNOX_SDCARD checking this for 10025
I/SELinux ( 5948): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 5948): KNOX_SDCARD not a persona
I/DBG_POLICYDM( 5802): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/SELinux ( 5948): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5948): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 5802): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5154/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_3615/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
D/TimaKeyStoreProvider( 5948): TimaSignature is unavailable
D/ActivityThread( 5948): Added TimaKeyStore provider
I/ActivityManager( 1018): Killing 3920:com.google.android.talk/u0a104 (adj 15): empty #31
I/DBG_POLICYDM( 5802): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
W/ResourcesManager( 5948): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
I/System.out( 1932): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1932): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1932): (HTTPLog)-Static: isShipBuild true
I/System.out( 1932): (HTTPLog)-Thread-274-530847520: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1932): (HTTPLog)-Static: isSBSettingEnabled false
I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
I/DBG_POLICYDM( 5802): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 5802): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
I/DBG_POLICYDM( 5802): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
D/MyFiles ( 5914): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager( 1018): Killing 5430:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
I/OMACP   ( 5948): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 5802): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/01/18/17:26:23
I/DBG_POLICYDM( 5802): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/Mms/Omacp( 5733): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
E/installd(  284): system dir 0 : /system/app/
E/installd(  284): system dir 1 : /system/priv-app/
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
I/TactileAssist( 1018): enable value -1
I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
I/TactileAssist( 1018): List of disabled apps :
I/DBG_POLICYDM( 5802): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/01/13/16:35:30
I/DBG_POLICYDM( 5802): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
I/DBG_POLICYDM( 5802): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5802): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
E/Zygote  ( 5970): MountEmulatedStorage()
E/Zygote  ( 5970): v2
I/libpersona( 5970): KNOX_SDCARD checking this for 10053
I/libpersona( 5970): KNOX_SDCARD not a persona
I/DBG_POLICYDM( 5802): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/SELinux ( 5970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/DBG_POLICYDM( 5802): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 5802): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5802): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
I/ActivityManager( 1018): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5970 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 5970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5970): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5802): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
I/OMACP   ( 5948): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5948): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5948): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
V/AlarmManager( 1018): waitForAlarm result :4
E/SMD     (  291): DCD OFF
D/PackageManager( 1018): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
D/TimaKeyStoreProvider( 5970): TimaSignature is unavailable
D/ActivityThread( 5970): Added TimaKeyStore provider
I/OMACP   ( 5948): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5948): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5948): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/System.out( 1932): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/ServiceManager(  315): Waiting for service AtCmdFwd...
I/qtaguid ( 1932): Tagging socket 95 with tag 40b00000000{1035,0} for uid -1, pid: 1932, getuid(): 10012
I/DBG_POLICYDM( 5802): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
W/ResourcesManager( 5970): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/OMACP   ( 5948): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5948): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5948): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5948): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5948): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5948): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5948): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
W/BaseAppContext( 1932): Using Auth Proxy for data requests.
W/BaseAppContext( 1932): Using Auth Proxy for data requests.
W/libprocessgroup( 1018): failed to open /acct/uid_10104/pid_3920/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10069/pid_5430/cgroup.procs: No such file or directory
I/qtaguid ( 1932): Tagging socket 110 with tag 40b00000000{1035,0} for uid -1, pid: 1932, getuid(): 10012
D/Compatibility( 5970): onReceive() it will make start service
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5970): onHandleIntent()
D/Compatibility( 5970): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10174, android.intent.extra.user_handle=0}]
E/Zygote  ( 5991): MountEmulatedStorage()
E/Zygote  ( 5991): v2
I/libpersona( 5991): KNOX_SDCARD checking this for 1000
I/libpersona( 5991): KNOX_SDCARD not a persona
I/SELinux ( 5991): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/Compatibility( 5970): found: 2
I/SELinux ( 5991): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5991): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5802): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=5991 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/Compatibility( 5970): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5970): skipping ResolveInfo{2327e596 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5970): considering ResolveInfo{7f4a517 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5970): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5970): enabling receiver ResolveInfo{34417d04 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5970): enabling receiver ResolveInfo{2911a2ed com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/TimaKeyStoreProvider( 5991): TimaSignature is unavailable
D/ActivityThread( 5991): Added TimaKeyStore provider
D/Compatibility( 5970): enabling receiver ResolveInfo{c74c522 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5970): enabling receiver ResolveInfo{3c147bb3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/GAv4    ( 5755): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5755):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5755):   adb logcat -s GAv4
D/Compatibility( 5970): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
I/DBG_POLICYDM( 5802): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
W/ContextImpl( 5991): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
I/art     ( 1667): Explicit concurrent mark sweep GC freed 20739(1237KB) AllocSpace objects, 3(108KB) LOS objects, 40% free, 10MB/17MB, paused 1.136ms total 57.044ms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6011): MountEmulatedStorage()
I/libpersona( 6011): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6011): v2
I/libpersona( 6011): KNOX_SDCARD not a persona
I/SELinux ( 6011): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6011 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6011): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Killing 5445:com.sec.knox.bridge/1000 (adj 15): empty #31
W/GAv4    ( 5755): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/SELinux ( 6011): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/BaseAppContext( 1932): Using Auth Proxy for data requests.
W/GAv4    ( 5755): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
D/TimaKeyStoreProvider( 6011): TimaSignature is unavailable
D/ActivityThread( 6011): Added TimaKeyStore provider
W/BaseAppContext( 1932): Using Auth Proxy for data requests.
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5445/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 5802): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
W/BaseAppContext( 1932): Using Auth Proxy for data requests.
W/ResourcesManager( 6011): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
W/AnalyticsTrackerProxyImpl( 5755): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
I/SL_DEBUG( 5932): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5932): isLoggable:: SL_DEBUG_EXIST = false
I/DBG_POLICYDM( 5802): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/qtaguid ( 1932): Untagging socket 95
I/ConfigFetchService( 1932): fetch service done; releasing wakelock
I/ConfigFetchService( 1932): stopping self
W/BaseAppContext( 1932): Using Auth Proxy for data requests.
I/DBG_POLICYDM( 5802): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/GAv4    ( 5755): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/Zygote  ( 6032): MountEmulatedStorage()
E/Zygote  ( 6032): v2
I/libpersona( 6032): KNOX_SDCARD checking this for 1000
I/libpersona( 6032): KNOX_SDCARD not a persona
I/SELinux ( 6032): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6032): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6032): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6032 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5460:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 6032): TimaSignature is unavailable
D/ActivityThread( 6032): Added TimaKeyStore provider
W/ResourcesManager( 6032): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 1018): Killing 5520:com.google.android.apps.plus/u0a120 (adj 15): empty #31
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5932): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
D/AcmsKeyStoreHelper( 5819):  getKeyStoreForApplication Enter
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5932): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/AcmsKeyStoreHelper( 5819): Key Store exist
I/AcmsKeyStoreHelper( 5819): Hence loading the keystore file
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5460/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10120/pid_5520/cgroup.procs: No such file or directory
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6056): MountEmulatedStorage()
E/Zygote  ( 6056): v2
I/libpersona( 6056): KNOX_SDCARD checking this for 10041
I/libpersona( 6056): KNOX_SDCARD not a persona
I/PowerManagerService( 1018): [PWL] Off : 5s ago
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1932, ws=null) (elapsedTime=47358)
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1018, ws=WorkSource{10054}) (elapsedTime=621)
I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6056 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6056): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6056): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6056): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6071 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5365:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
E/Zygote  ( 6071): MountEmulatedStorage()
E/Zygote  ( 6071): v2
I/libpersona( 6071): KNOX_SDCARD checking this for 10120
I/libpersona( 6071): KNOX_SDCARD not a persona
I/SELinux ( 6071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6071): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/AcmsKeyStoreHelper( 5819):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5819): getKeyStoreForApplication success 
D/AcmsCore( 5819): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5819): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5819): Decrementing - Counter value: 1
D/AcmsCore( 5819): AcmsCore: ACMS_APP_INSTALLED
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
D/AcmsCore( 5819): This is NOT a valid MirrorLink app
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
D/AcmsCore( 5819): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5819): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5819): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5819): Counter value is 0: Stopping ACMS service
W/ContextImpl( 5755): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
D/TimaKeyStoreProvider( 6056): TimaSignature is unavailable
D/ActivityThread( 6056): Added TimaKeyStore provider
D/AcmsServiceMonitor( 5819): getSvcCounter - Counter value: 0
D/AcmsService( 5819): Enter onDestroy
I/AcmsService( 5819): cleanUp(): inside service clean up
D/AcmsCore( 5819): AcmsCore: inside DeInit
D/AcmsCore( 5819): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5819): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5819): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5819): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5819): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5819): getSvcCounter - Counter value: 0
D/AcmsService( 5819): killing acms process
I/Process ( 5819): Sending signal. PID: 5819 SIG: 9
D/TimaKeyStoreProvider( 6071): TimaSignature is unavailable
D/ActivityThread( 6071): Added TimaKeyStore provider
W/ResourcesManager( 6071): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/SA      ( 6056): [SSP] onCreated
I/ActivityManager( 1018): Process ACMS.Process (pid 5819)(adj 0) has died(48,1080)
I/SA      ( 6056): [TPM] There is no property file
I/art     ( 1018): Explicit concurrent mark sweep GC freed 220790(14MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/40MB, paused 3.038ms total 199.357ms
I/SA      ( 6056): [SCU] isHaveSA() - false
W/ResourcesManager( 5755): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5755): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/SA      ( 6056): [TPM] getModelProperty : null
I/SA      ( 6056): [TPM] getCSCProperty : null
I/SA      ( 6056): [DM] FLOATING AMOLED FEATURE: true
W/libprocessgroup( 1018): failed to open /acct/uid_10057/pid_5365/cgroup.procs: No such file or directory
I/SA      ( 6056): [DM] PRODUCT AMOLED FEATURE: false
I/ActivityManager( 1018): Killing 4955:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
I/SA      ( 6056): [DM] TFT FEATURE: false
I/SA      ( 6056): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6056): [DM] init START
I/SA      ( 6056): [DM] This device is not a Vodafone
W/ResourceType( 6056): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6056): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6056): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6056): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6056): [SCU] isHaveSA() - false
I/SA      ( 6056): support phone number id : false
I/SA      ( 6056): [DM] Supports Ref Jpn : true
I/SA      ( 6056): [DM] init END
I/SA      ( 6056): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 6056): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10174 extra.user_handle.:0 ]
I/ActivityManager( 1018): Killing 4990:com.google.android.gms:car/u0a12 (adj 15): empty #31
D/AndroidRuntime( 6069): 
D/AndroidRuntime( 6069): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6069): CheckJNI is OFF
D/AndroidRuntime( 6069): readGMSProperty: start
D/AndroidRuntime( 6069): readGMSProperty: already setted!!
D/AndroidRuntime( 6069): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6069): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6069): readGMSProperty: end
D/AndroidRuntime( 6069): addProductProperty: start
V/JNIHelp ( 5755): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/System  ( 5755): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b0705c0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 5755): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 5755): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4955/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10012/pid_4990/cgroup.procs: No such file or directory
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
E/AffinityControl( 6069): AffinityControl: registerfunction enter
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/AndroidRuntime( 6069): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1018): mDVFSHelper.acquire()
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/Zygote  ( 6116): MountEmulatedStorage()
E/Zygote  ( 6116): v2
I/libpersona( 6116): KNOX_SDCARD checking this for 10174
I/libpersona( 6116): KNOX_SDCARD not a persona
I/SELinux ( 6116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6116 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
E/SELinux ( 6116): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 2995
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, uhalitest
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 6069): Shutting down VM
I/art     (  306): Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 22.269ms
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6116): TimaSignature is unavailable
D/ActivityThread( 6116): Added TimaKeyStore provider
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 16.919ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.040ms total 18.050ms
E/Zygote  ( 6131): MountEmulatedStorage()
I/libpersona( 6131): KNOX_SDCARD checking this for 10057
E/Zygote  ( 6131): v2
I/libpersona( 6131): KNOX_SDCARD not a persona
I/SELinux ( 6131): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6131): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6131): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ChimeraCfgMgr( 1932): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1932): Module APK com.google.android.play.games already loaded
I/ActivityManager( 1018): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6131 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
V/ActivityManager( 1018): Display changed displayId=0
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/TimaKeyStoreProvider( 6131): TimaSignature is unavailable
D/ActivityThread( 6131): Added TimaKeyStore provider
D/PersonaManager( 1018): isKioskContainerExistOnDevice
I/ActivityManager( 1018): Killing 5580:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/SurfaceFlinger(  257): id=11 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  257): id=11 Removed YUIInstallC (-2/9)
V/ActivityThread( 2995): updateVisibility : ActivityRecord{5e46712 token=android.os.BinderProxy@3eef37db {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5580/cgroup.procs: No such file or directory
W/art     ( 6069): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/WebViewFactory( 6116): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,E/Zygote  ( 6150): MountEmulatedStorage(),
E/Zygote  ( 6150): v2
I/libpersona( 6150): KNOX_SDCARD checking this for 10010
I/libpersona( 6150): KNOX_SDCARD not a persona
,I/SELinux ( 6150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6150 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6150): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/LibraryLoader( 6116): Time to load native libraries: 2 ms (timestamps 3565-3567)
I/LibraryLoader( 6116): Expected native library version number "",actual native library version number ""
,D/TimaKeyStoreProvider( 6150): TimaSignature is unavailable
,D/ActivityThread( 6150): Added TimaKeyStore provider
,V/WebViewChromiumFactoryProvider( 6116): Binding Chromium to main looper Looper (main, tid 1) {c74c522}
,I/LibraryLoader( 6116): Expected native library version number "",actual native library version number ""
,I/chromium( 6116): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6116): Initializing chromium process, singleProcess=true
,W/art     ( 6116): Attempt to remove local handle scope entry from IRT, ignoring
I/splitIntent( 1018): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1018): Killing 5604:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,E/SysUtils( 6116): ApplicationContext is null in ApplicationStatus
,D/KeyguardViewMediator( 1177): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1177): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1177): *** Keyguard wallpaper service already unbounded
,I/Mms/MmsApp( 5733):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5733): [start]    fillCache consume time = 1934.799426
D/Mms/ComposeMessageFragment( 5733): fillCache, easy = false
,W/chromium( 6116): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6116): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6116): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6116): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6116): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6116): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6116): Local Branch: 
I/Adreno-EGL( 6116): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6116): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6116):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/LocationManagerService( 1018): getProviders()=[passive]
,D/AbsListView( 5733): Get MotionRecognitionManager
,D/MotionRecognitionService( 1018):  ssp status : false
,D/Mms/ComposeMessageFragment( 5733): [end]    fillCache consume time = 72.031146
,W/libprocessgroup( 1018): failed to open /acct/uid_10142/pid_5604/cgroup.procs: No such file or directory
,D/Mms/BubbleViewCache( 5733): fillCache bubble = 1
,I/UpdateIcingCorporaServi( 6131): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 6131): UpdateCorporaTask done [took 102 ms] updated apps [took 102 ms] 
,I/ActivityManager( 1018): Killing 5170:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{3f4ec6bf u0 com.test.thalitest/.MainActivity t234}
,W/art     ( 6116): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6116): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6116): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6116): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6116): CordovaWebView is running on device made by: samsung
,W/art     ( 6116): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6116): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup( 1018): failed to open /acct/uid_10150/pid_5170/cgroup.procs: No such file or directory
,D/OpenGLRenderer( 6116): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,W/chromium( 6116): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6116): updateVisibility : ActivityRecord{10c02aff token=android.os.BinderProxy@1fb07659 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6116): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6116): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1018): Focus entered window: 6116
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 6116): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6116): Initialized EGL, version 1.4
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 6116): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6116): Enabling debug mode 0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  ( 6199): MountEmulatedStorage()
,E/Zygote  ( 6199): v2
I/libpersona( 6199): KNOX_SDCARD checking this for 10012
I/libpersona( 6199): KNOX_SDCARD not a persona
I/SELinux ( 6199): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6199): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=6199 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
D/PanelView( 1177): There is/are notification(s) 
E/SELinux ( 6199): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/SamsungIME( 1786): getCurrentCandidateView
,I/ActivityManager( 1018): Displayed Component not be shown by security: +787ms (total +922ms)
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{3f4ec6bf u0 com.test.thalitest/.MainActivity t234} time:84198
,W/IInputConnectionWrapper( 6116): showStatusIcon on inactive InputConnection
,I/Timeline( 6116): Timeline: Activity_idle id: android.os.BinderProxy@1fb07659 time:84203
,I/SurfaceFlinger(  257): id=13 Removed uhalitest (7/9)
I/SurfaceFlinger(  257): id=13 Removed uhalitest (-2/9)
,D/TimaKeyStoreProvider( 6199): TimaSignature is unavailable
,D/ActivityThread( 6199): Added TimaKeyStore provider
,W/ResourcesManager( 6199): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6199): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6199): VM with version 2.1.0 has multidex support
I/MultiDex( 6199): install
I/MultiDex( 6199): VM has multidex support, MultiDex support library is disabled.
,D/SamsungIME( 1786): Dismiss ExpandCandiate
,V/JNIHelp ( 6199): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/SamsungIME( 1786): getDebugLevel  : 0x4f4c
,W/BindingManager( 6116): Cannot call determinedVisibility() - never saw a connection for the pid: 6116,
,W/ActivityThread( 6199): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6199): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c1a84ad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6199): Installed default security provider GmsCore_OpenSSL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SamsungIME( 1786): getDebugLevel  : 0x4f4c
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
D/GCM     ( 1667): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/SamsungIME( 1786): KeybaordView init() : load resources
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1667): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/ActivityManager( 1018): Killing 5060:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1932): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1786): getCurrentKeyboard
I/SamsungIME( 1786): getTextKeyboard
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1786): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4484): callingUid 10012, callindPid: 4484
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1725): [191] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/JsMessageQueue( 6116): Set native->JS mode to OnlineEventsBridgeMode
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1932): Restart initialization of location
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10040/pid_5060/cgroup.procs: No such file or directory
,D/jxcore_app_log( 6116): JniHelper::setJavaVM(0xb7e48450), pthread_self() = -1204146848
,D/JX-Cordova( 6116): jxcore cordova android initializing
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5802): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,W/jxcore-log( 6116): Initializing JXcore engine
W/jxcore-log( 6116): JXcore engine is ready
,W/jxcore-log( 6116): Starting JXcore engine
,E/audit   ( 1836): type=1400 msg=audit(1452699333.812:205): avc:  denied  { ioctl } for  pid=6116 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1836):  SEPF_SM-A500FU_5.0.2_0027
,E/audit   ( 1836): type=1300 msg=audit(1452699333.812:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=beb88d58 items=0 ppid=306 ppcomm=main pid=6116 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1836): type=1320 msg=audit(1452699333.812:205): 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4183, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/jxcore-log( 6116): Platform android
W/jxcore-log( 6116): 
,W/jxcore-log( 6116): Process ARCH arm
W/jxcore-log( 6116): 
,I/jxcore-log( 6116): JXcore Cordova bridge is ready!
I/jxcore-log( 6116): 
,W/jxcore-log( 6116): JXcore engine is started
I/Choreographer( 6116): Skipped 130 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6116): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6116): Toggling radios to true
I/jxcore-log( 6116): 
,D/BluetoothAdapter( 6116): enable()
,D/BluetoothAdapter( 6116): enable(): BT is already enabled..!
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1018): mCursor = null
,D/WifiService( 1018): setWifiEnabled: true pid=6116, uid=10174
,W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=6116, uid=10174 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1018): Failed getting userId using ActivityManagerNative,
W/WifiService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6116, uid=10174 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1018): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1018): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1018): name = wifi_on
,I/WifiService( 1018): disconnect: pid=6116, uid=10174
,I/wpa_supplicant( 1907): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6116): Radios toggled
I/jxcore-log( 6116): 
,I/jxcore-log( 6116): My device name is: samsung-SM-A500FU
I/jxcore-log( 6116): 
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false,
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1907): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
D/Tethering( 1018): InitialState.processMessage what=4
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1907): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1907): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1907): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1907): wlan0: State: DISCONNECTED -> DISCONNECTED,
E/wpa_supplicant( 1907): Cmd 35605 not handled,
,E/WifiStateMachine( 1018): WifiStateMachine: Leaving Connected state
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1907): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 1907): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1907): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1907): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1907): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1907): First Scan Start
I/wpa_supplicant( 1907): Scan requested (ret=0) - scan timeout 30 seconds
,E/Tethering( 1018): No numeric data,
D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/Tethering( 1018): clearTetheredNotification()
E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1667): Read error: ssl=0xb83d4928: I/O error during system call, Connection timed out
V/NetworkStats( 1018): performPollLocked() took 13ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NativeCrypto( 1667): SSL shutdown failed: ssl=0xb83d4928: I/O error during system call, Broken pipe
,E/WifiStateMachine( 1018): Start Disconnecting Watchdog 1
,E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
I/wpa_supplicant( 1907): wlan0: Setting scan request: 0 sec 0 usec
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14949 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6950 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1018): Tagging socket 358 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1018, getuid(): 1000
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 1018): Untagging socket 358
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 },
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1018): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService( 1018): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
,D/ConnectivityService( 1018): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,D/CSLegacyTypeTracker( 1018): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1018): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1459): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1459): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524292
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/Hs20UtilService( 3603): Starting #8
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
I/Hs20UtilService( 3603): Message received 5007
D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1018): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): doQuit - quitNow()
,V/NetworkStats( 1018): updateIfacesLocked()
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 4ms
D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/NearbySettings( 1327): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1327): DMSUtil.isNetworkConnected - flag-null, state-null
,D/WifiNetworkAgent( 1018): NetworkAgent: NetworkAgent channel lost
,I/NearbySettings( 1327): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1327): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1327): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1327): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1327): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6232 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/Zygote  ( 6232): MountEmulatedStorage()
E/Zygote  ( 6232): v2
I/libpersona( 6232): KNOX_SDCARD checking this for 10104
I/libpersona( 6232): KNOX_SDCARD not a persona
,I/SELinux ( 6232): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6232): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6232): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6232): TimaSignature is unavailable
,D/ActivityThread( 6232): Added TimaKeyStore provider
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6232): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel_SMS( 6232): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6232): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6232): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 6232): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6232): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6232): MmsConfig.loadFromResources
,E/Babel_SMS( 6232): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6232): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  283): getCameraInfo: X
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6232): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6232): startup - clean
,I/Babel   ( 6232): deleted: false for 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1018): updateDataUsageMap
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 2995): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 2995): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1327): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1327): DMSUtil.isNetworkConnected - flag-null, state-null
,D/SSRM:n  ( 1018): SIOP:: AP = 360
,I/Hs20UtilService( 3603): Starting #9
,I/Hs20UtilService( 3603): Message received 5007
,I/ConfigService( 1667): onDestroy
,I/NearbySettings( 1327): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1327): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1327): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1327): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1327): MountReceiver.mPrefHandler - 7002
,W/VideoCapabilities( 6232): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6232): Unsupported mime audio/evrc
,W/AudioCapabilities( 6232): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6232): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6232): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6232): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6232): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6232): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6232): Unsupported mime audio/evrc
,W/VideoCapabilities( 6232): Unsupported mime video/wvc1
,W/VideoCapabilities( 6232): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6232): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6232): Unsupported mime video/wvc1
,W/VideoCapabilities( 6232): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6232): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6232): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6232): Unsupported mime video/mp43
,W/VideoCapabilities( 6232): Unsupported mime video/sorenson
,W/VideoCapabilities( 6232): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6232): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6232): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6232): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6232): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6232): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1018): Killing 5008:com.google.android.music:main/u0a111 (adj 15): empty #31
,I/vclib   ( 6232): onServiceConnected
,W/Babel   ( 6232): Attempted to change video mute state without an active call.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/PCWCLIENTTRACE_PushUtil( 5772): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5772): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5772): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5772): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
,I/splitIntent( 1018): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/PCWCLIENTTRACE_SYSTEMReceiver( 5772): noConnectivity : true
,I/splitIntent( 1018): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 1018): Exception when sending broadcast to ComponentInfo{com.google.android.music/com.google.android.music.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver}
W/BroadcastQueue( 1018): android.os.TransactionTooLargeException
W/BroadcastQueue( 1018): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1018): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1018): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1018): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1018): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1018): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1018): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1018): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6277): MountEmulatedStorage()
E/Zygote  ( 6277): v2
I/libpersona( 6277): KNOX_SDCARD checking this for 10111
I/libpersona( 6277): KNOX_SDCARD not a persona
I/SELinux ( 6277): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6277 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup( 1018): failed to open /acct/uid_10111/pid_5008/cgroup.procs: No such file or directory
,I/SELinux ( 6277): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6277): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6277): TimaSignature is unavailable
,D/ActivityThread( 6277): Added TimaKeyStore provider
,I/MusicStore( 6277): Database version: 120
,I/wpa_supplicant( 1907): nl80211: Received scan results (12 BSSes),
I/wpa_supplicant( 1907): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1907): Trying to associate with SSID '4E47373030',
I/wpa_supplicant( 1907): Trying to associate with  'G700',
I/wpa_supplicant( 1907): Re-associate with C0.AA.48
I/wpa_supplicant( 1907): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1907): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1018): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6277): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6277): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6277): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1907): Cmd 35605 not handled
,I/wpa_supplicant( 1907): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1907): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,I/wpa_supplicant( 1907): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1907): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1907): Associated with C0.AA.48
I/wpa_supplicant( 1907): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1907): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1907): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false,
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,I/wpa_supplicant( 1907): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
W/ResourcesManager( 6277): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
I/wpa_supplicant( 1907): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
W/ResourcesManager( 6277): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,I/wpa_supplicant( 1907): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1907): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1907): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1907): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1907): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1907): Blacklist: Clear (temp) 
I/wpa_supplicant( 1907): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
E/Tethering( 1018): No numeric data
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1018): clearTetheredNotification()
,D/WifiNative-wlan0( 1018): callSECApiVoid - ID [50]
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
,V/NetworkStats( 1018): performPollLocked() took 4ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/HotspotTile( 1177): updateTetherState():false, false
,E/WifiConfigStore( 1018): setLastSelectedConfiguration -1
,D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/JNIHelp ( 6277): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/CommandListener(  278): Setting iface cfg
,E/WifiStateMachine( 1018): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,E/WifiNative-wlan0( 1018): do suspend false
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,W/ActivityThread( 6277): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6277): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35c2a9a8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6277): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6277): GMSCore installation verified
,I/ConfigStore( 6277): Config Database version: 1
,E/SMD     (  291): DCD OFF
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/SQLiteLog( 1667): (10) POSIX Error : 11 SQLite Error : 3850
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1018): getStreamVolume 3 index 0
,I/MediaRouter( 6277): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6277): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6304): MountEmulatedStorage()
,E/Zygote  ( 6304): v2
I/libpersona( 6304): KNOX_SDCARD checking this for 10002
I/libpersona( 6304): KNOX_SDCARD not a persona
,I/SELinux ( 6304): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6304): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6304): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/dhcpcd  ( 6308): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6304 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 6308): version 5.5.6 starting
E/dhcpcd  ( 6308): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/GHttpClientFactory( 6277): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/TimaKeyStoreProvider( 6304): TimaSignature is unavailable
,D/ActivityThread( 6304): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GoogleURLConnFactory( 6277): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 6308): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6308): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6308): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6308): bssid match
,I/dhcpcd  ( 6308): wlan0: rebinding lease of 192.168.1.137
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1018): Killing 5318:com.google.android.gm/u0a101 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6330): MountEmulatedStorage(),
,E/Zygote  ( 6330): v2
,I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6330 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 6330): KNOX_SDCARD checking this for 1000
I/libpersona( 6330): KNOX_SDCARD not a persona
,I/SELinux ( 6330): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6330): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6330): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6330): TimaSignature is unavailable
,D/ActivityThread( 6330): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6330): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1018): failed to open /acct/uid_10101/pid_5318/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6330): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6330): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6330): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6330): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6330): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6330): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6345 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6345): MountEmulatedStorage()
E/Zygote  ( 6345): v2
I/libpersona( 6345): KNOX_SDCARD checking this for 10009
I/libpersona( 6345): KNOX_SDCARD not a persona
,I/SELinux ( 6345): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6345): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Killing 5075:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,E/SELinux ( 6345): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6345): TimaSignature is unavailable
,D/ActivityThread( 6345): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 4159:com.sec.spp.push/u0a35 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3669): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jan 13 16:35:36 GMT+01:00 2016
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3669): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onCreate()
,E/Zygote  ( 6361): MountEmulatedStorage(),
,E/Zygote  ( 6361): v2
I/libpersona( 6361): KNOX_SDCARD checking this for 10034
I/libpersona( 6361): KNOX_SDCARD not a persona
,I/SELinux ( 6361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/KLMS-2.5.183: ( 3669): KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6361 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/KLMS-2.5.183: ( 3669): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/SELinux ( 6361): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3669): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3669): StateImplV2(): networkChangeListener().END
,D/TimaKeyStoreProvider( 6361): TimaSignature is unavailable
,D/ActivityThread( 6361): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onDestroy()
,W/libprocessgroup( 1018): failed to open /acct/uid_10044/pid_5075/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_4159/cgroup.procs: No such file or directory
,I/SO_AGENT( 6361): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5802): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 6056): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6056): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6056): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
I/SA      ( 6056): [SLFUCHKMGR] constructor called
,I/SA      ( 6056): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6056): [OR] == isSIMCardReady false ==
,I/SA      ( 6056): [SCU] == networkStateCheck == false
,I/SA      ( 6056): [OR] onReceive END
,I/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5802): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/ActivityManager( 1018): Killing 5300:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,V/DownloadManager( 1229): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1620): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1289): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 1
,D/accuweather( 1620): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1620): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1620): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1620): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1620): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1620): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6378): MountEmulatedStorage(),
E/Zygote  ( 6378): v2
,I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6378 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/libpersona( 6378): KNOX_SDCARD checking this for 10125
I/libpersona( 6378): KNOX_SDCARD not a persona
I/SELinux ( 6378): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6378): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6378): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6378): TimaSignature is unavailable
,D/ActivityThread( 6378): Added TimaKeyStore provider
,W/ResourcesManager( 6378): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6378): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6378): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6378): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6378): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6378): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6393): MountEmulatedStorage()
,E/Zygote  ( 6393): v2
I/libpersona( 6393): KNOX_SDCARD checking this for 10145
I/libpersona( 6393): KNOX_SDCARD not a persona
,I/SELinux ( 6393): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6393 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
I/SELinux ( 6393): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6393): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 5724:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31,
,I/art     (  306): Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 20.013ms
,D/TimaKeyStoreProvider( 6393): TimaSignature is unavailable
,D/ActivityThread( 6393): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 17.429ms
,W/ResourcesManager( 6393): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6393): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6393): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6393): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6393): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 16.859ms
,W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_5300/cgroup.procs: No such file or directory
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/BadgeProvider( 5896): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/libprocessgroup( 1018): failed to open /acct/uid_10100/pid_5724/cgroup.procs: No such file or directory
,V/AlarmManager( 1018): waitForAlarm result :4
,D/BadgeProvider( 5896): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5896): sendNotify, [notify] : null
D/BadgeProvider( 5896): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5896): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5896): update, [UpdateCount] : 1
,D/Launcher.Model( 1485): reloadBadges entered.
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6416): MountEmulatedStorage(),
,E/Zygote  ( 6416): v2,
I/libpersona( 6416): KNOX_SDCARD checking this for 1000
I/libpersona( 6416): KNOX_SDCARD not a persona
,I/SELinux ( 6416): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6416): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6416 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 6416): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6416): TimaSignature is unavailable
,D/ActivityThread( 6416): Added TimaKeyStore provider
,D/SecurityLogAgent( 6416): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6416): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6416): StateMachine : Current State = 1
,D/SecurityLogAgent( 6416): StateMachine : Changed Current State = 1
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6432 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1018): Killing 5395:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,E/Zygote  ( 6432): MountEmulatedStorage(),
E/Zygote  ( 6432): v2
I/libpersona( 6432): KNOX_SDCARD checking this for 10159
I/libpersona( 6432): KNOX_SDCARD not a persona,
I/SELinux ( 6432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6432): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6432): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6432): TimaSignature is unavailable
,D/ActivityThread( 6432): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5755:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 61460(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 27MB/40MB, paused 2.856ms total 181.778ms
,I/ActivityManager( 1018): Killing 5786:com.samsung.helphub/1000 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 5409:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/iu.Environment( 1932): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,I/iu.UploadsManager( 1932): num queued entries: 0
,I/iu.UploadsManager( 1932): num updated entries: 0
,I/iu.SyncManager( 1932): NEXT; no task
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/ChimeraCfgMgr( 1932): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/dhcpcd  ( 6308): wlan0: acknowledged 192.168.1.137 from 192.168.1.1
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6451 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6451): MountEmulatedStorage()
E/Zygote  ( 6451): v2
I/libpersona( 6451): KNOX_SDCARD checking this for 10035
I/libpersona( 6451): KNOX_SDCARD not a persona
,I/SELinux ( 6451): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6451): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6451): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/dhcpcd  ( 6308): wlan0: leased 192.168.1.137 for 86400 seconds
,I/Babel   ( 6232): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager( 1018): Killing 5840:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10015/pid_5395/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5786/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_5409/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10091/pid_5755/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6451): TimaSignature is unavailable,
,D/ActivityThread( 6451): Added TimaKeyStore provider
,E/SPPClientService( 6451): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE,
E/SPPClientService( 6451): [SystemStateMoniter] Current Time : 89676
,E/SPPClientService( 6451): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6451): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6451): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
,D/SPPClientService( 6451): PushLog.txt file is not deleted.
,D/SPPClientService( 6451): PushLog.txt file is not deleted.
D/SPPClientService( 6451): ============PushLog. stop!
,E/Zygote  ( 6483): MountEmulatedStorage(),
I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6483 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6483): v2
I/libpersona( 6483): KNOX_SDCARD checking this for 10113
I/SELinux ( 6483): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/libpersona( 6483): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Killing 5859:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,I/SELinux ( 6483): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6483): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 6451): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 6483): TimaSignature is unavailable
,D/ActivityThread( 6483): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10152/pid_5840/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10156/pid_5859/cgroup.procs: No such file or directory
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6483): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6483):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6483):   adb logcat -s GAv4
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6483): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6483): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6483): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1018): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1018): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1018): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1018): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1018): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1018): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1018): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1018): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1018): LTETest block dns file not exists
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 1018): updateNetworkInfo()
,E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1018): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
E/WifiStateMachine( 1018): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
E/WifiStateMachine( 1018): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 1018):    accepting network in place of null
I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 1018): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1459): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/TelephonyNetworkFactory( 1459): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,I/WifiTrafficPoller( 1018): mBoosterFLAG : 0
I/WifiTrafficPoller( 1018): current booster mode : FullMode
D/WifiNative-wlan0( 1018): callSECApiVoid - ID [212]
,D/ConnectivityService( 1018): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): updateIfacesLocked()
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,V/NetworkStats( 1018): performPollLocked() took 2ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1018): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 15:35:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452699338130], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452699338113]}
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
,D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WebViewFactory( 6483): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6483): Time to load native libraries: 2 ms (timestamps 200-202)
I/LibraryLoader( 6483): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6483): Binding Chromium to main looper Looper (main, tid 1) {27ac0230}
,I/LibraryLoader( 6483): Expected native library version number "",actual native library version number ""
,I/chromium( 6483): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6483): Initializing chromium process, singleProcess=true
,W/art     ( 6483): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6483): ApplicationContext is null in ApplicationStatus
,W/chromium( 6483): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6483): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6483): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6483): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6483): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6483): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6483): Local Branch: 
I/Adreno-EGL( 6483): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6483): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6483):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6483): Requires BLUETOOTH permission
,I/NSApplication( 6483): Starting up...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6551 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6551): MountEmulatedStorage()
E/Zygote  ( 6551): v2
I/libpersona( 6551): KNOX_SDCARD checking this for 10081
I/libpersona( 6551): KNOX_SDCARD not a persona
,I/SELinux ( 6551): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6551): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6551): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 5477:com.android.vending/u0a28 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6551): TimaSignature is unavailable
,D/ActivityThread( 6551): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10028/pid_5477/cgroup.procs: No such file or directory
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,D/WaitQueueForNetworkActivate( 6150): notifyNetworkActivated
,W/ContextImpl( 6150): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 2995): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 6277): type=WIFI subType= reason=null isConnected=true
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,E/Zygote  ( 6575): MountEmulatedStorage()
,E/Zygote  ( 6575): v2
I/libpersona( 6575): KNOX_SDCARD checking this for 10075
I/libpersona( 6575): KNOX_SDCARD not a persona
,I/SELinux ( 6575): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6575): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,I/ActivityManager( 1018): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6575 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6575): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 6575): TimaSignature is unavailable
,D/ActivityThread( 6575): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6150): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6150): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6150): exit::IDLE
D/InitializeManagerStateMachine( 6150): entry::NETWORK_CHECK
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
D/InitializeManagerStateMachine( 6150): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6150): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6150): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6150): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6150): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6150): entry::SUCCESS
D/hcjo    ( 6150): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/hcjo    ( 6150): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6150): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/Hs20UtilService( 3603): Starting #10
,I/Hs20UtilService( 3603): Message received 5007
,D/InitializeManagerStateMachine( 6150): exit::SUCCESS
D/InitializeManagerStateMachine( 6150): entry::IDLE
,D/NearbySettings( 1327): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1327): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1327): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1327): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1327): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1327): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1018): Killing 5733:com.android.mms/u0a46 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3603): Starting #11
,I/Hs20UtilService( 3603): Message received 5007
,D/NearbySettings( 1327): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1327): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3603): Starting #12
,I/Hs20UtilService( 3603): Message received 5007
,D/NearbySettings( 1327): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1327): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1327): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1327): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1327): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1327): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3603): Starting #13
,I/Hs20UtilService( 3603): Message received 5007
,D/NearbySettings( 1327): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1327): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1018): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1018): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5772): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5772): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5772): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5772): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
I/splitIntent( 1018): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6277): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=4, Uoast
,D/CountryDetector( 1018): No listener is left
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,D/SRIB_DCS( 1177): log_dcs ThreadedRenderer::initialize entered! 
,I/DIAGMON_AGENT( 6330): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6330): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6330): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6330): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/libprocessgroup( 1018): failed to open /acct/uid_10046/pid_5733/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,W/GAV2    ( 6575): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/FOTA_Client( 6345): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6345): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/BooksApp( 6575): Created application version: 3.6.9 (30609)
,I/KLMS-2.5.183: ( 3669): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jan 13 16:35:38 GMT+01:00 2016
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3669): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3669): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3669): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 1018): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/KLMS-2.5.183: ( 3669): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3669): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3669): NetworkChangeOperations(): uploadRequestLog().START 
,I/DBG_POLICYDM( 5802): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.183: ( 3669): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3669): StateImplV2(): networkChangeListener().END
,I/SA      ( 6056): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5802): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,I/SA      ( 6056): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6056): [OR] == ACTION_CONNECTIVITY_CHANGE ==
E/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 6056): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6056): [OR] == isSIMCardReady false ==
,I/SA      ( 6056): [SCU] == networkStateCheck == true
I/SA      ( 6056): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 6056): isChinaCountryCode : false
I/SA      ( 6056): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6056): [OR] == networkStateCheck true ==
,I/SA      ( 6056): [OR] GetMyCountryZoneTask
,I/SA      ( 6056): [OR] onReceive END
I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,V/DownloadManager( 1229): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,I/SA      ( 6056): [SRS] prepareGetMyCountryZone
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 6056): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/DBG_POLICYDM( 5802): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/SA      ( 6056): [SSP] query invoked
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5802): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/SA      ( 6056): [TPMU] GetMccFromDB : null
I/SA      ( 6056): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6056): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
D/accuweather( 1620): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1289): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,E/DBG_POLICYDM( 5802): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/accuweather( 1620): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1620): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1620): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/accuweather( 1620): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/File    ( 6056): fail readDirectory() errno=2
,D/accuweather( 1620): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/DBG_POLICYDM( 5802): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/accuweather( 1620): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  291): DCD OFF
,D/QuickConnect( 6378): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6378): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/BooksSync( 6575): Starting books sync for 61035162, extras: ade
,I/QuickConnect( 6378): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecurityLogAgent( 6416): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6416): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6416): StateMachine : Current State = 1
,D/SecurityLogAgent( 6416): StateMachine : Changed Current State = 1
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10012
,I/iu.Environment( 1932): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 1932): num queued entries: 0
I/iu.UploadsManager( 1932): num updated entries: 0
,I/iu.SyncManager( 1932): NEXT; no task
,D/ChimeraCfgMgr( 1932): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ChimeraCfgMgr( 1932): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6451): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6451): [SystemStateMoniter] Current Time : 91333
,E/SPPClientService( 6451): [SystemStateMoniter] No Connect : false
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6232): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6232): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6232): (HTTPLog)-Static: isShipBuild true
I/System.out( 6232): (HTTPLog)-Thread-1082-198691829: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6232): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10104
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10104
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/hcjo    ( 6150): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6150): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6150): exit::IDLE
D/InitializeManagerStateMachine( 6150): entry::NETWORK_CHECK
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/InitializeManagerStateMachine( 6150): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6150): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6150): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6150): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6150): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6150): entry::SUCCESS
D/hcjo    ( 6150): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6150): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6150): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6150): exit::SUCCESS
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/InitializeManagerStateMachine( 6150): entry::IDLE
,I/System.out( 6232): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,E/SQLiteLog( 6575): (284) automatic index on view_volumes(volume_id)
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,W/Kids    ( 1932): [AccountUtils] Account not ready
W/Kids    ( 1932): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1932): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1932): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1932): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1932): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1932): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1932): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1932): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1932): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1932): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1932): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1932): 	at java.lang.Thread.run(Thread.java:818)
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/Babel   ( 6232): connection state changed from DISCONNECTED to CONNECTED
,I/BooksConfig( 6575): GmsCore Version = 7.8.99 (2134222-436)
,D/GCM     ( 1667): Connected
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1667): Message class com.google.f.a.a.p
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/art     ( 1667): Explicit concurrent mark sweep GC freed 13663(736KB) AllocSpace objects, 6(216KB) LOS objects, 40% free, 10MB/17MB, paused 1.181ms total 38.584ms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6575): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6575): Soft error
E/BooksSync( 6575): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6575): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6575): Sync error
E/BooksSync( 6575): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6575): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6575): Finished books sync
,I/SA      ( 6056): [RC New] Execute method=[GET] start
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 61984, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/SA      ( 6056): [RC New] Security=[true]
,I/System.out( 6056): Thread-1045(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6056): Thread-1045(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6056): Thread-1045(ApacheHTTPLog):isShipBuild true
I/System.out( 6056): Thread-1045(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6056): Thread-1045(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): uids 10041
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10041
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/ActivityManager( 1018): Killing 5914:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 43025(2MB) AllocSpace objects, 6(136KB) LOS objects, 33% free, 27MB/40MB, paused 2.721ms total 143.067ms
,W/libprocessgroup( 1018): failed to open /acct/uid_10047/pid_5914/cgroup.procs: No such file or directory
,E/SQLiteLog( 1667): (10) POSIX Error : 11 SQLite Error : 3850
,D/PackageManager( 1018): [MSG] MCS_UNBIND
,I/ActivityManager( 1018): Killing 5948:com.wsomacp/u0a25 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10025/pid_5948/cgroup.procs: No such file or directory
,I/SA      ( 6056): [RC New] [v2liruge] api execute + 621
,I/SA      ( 6056): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6056): AsyncTask #1 calls detatch()
,I/SA      ( 6056): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6056): [OCP] update openData : PL
,I/SA      ( 6056): [TPMU] getNetworkMcc : 
,I/SA      ( 6056): [SCU] saveMccToPreferece Start
,I/SA      ( 6056): [SCU] RegionMCC : 260
I/SA      ( 6056): [SSP] query invoked
,I/SA      ( 6056): [TPMU] GetMccFromDB : null
,I/SA      ( 6056): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6056): [SCU] saveMccToPreferece End
,I/SA      ( 6056): [RC New] executeRequest [v2liruge] end. 678
I/SA      ( 6056): [RC New] Execute end
,I/SA      ( 6056): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6056): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6308): wlan0: sending IPv6 Router Solicitation,
,I/PowerManagerService( 1018): [PWL] Off : 15s ago
,I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1932, ws=null) (elapsedTime=57361)
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/MusicLeanback( 6277): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6277): Stop autocaching.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,D/WearableService( 4484): callingUid 10012, callindPid: 4484
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/GmsUtils( 6277): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6277): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/SMD     (  291): DCD OFF
,I/SurfaceFlinger(  257): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1018): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 94317
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
D/PowerManagerService( 1018): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10054}) (elapsedTime=3464)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5772): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5772): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5772): [GetString-S]
,I/ReactiveServiceManager( 5772): Supported : 1
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 12
,D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 12
E/terrier ( 1018): handleString: Failed to handle string(-4)
E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5772): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5772): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5772): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5772): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5772): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5772): [ensureRegistration] - No Samsung account
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4190, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6575): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  ( 6308): wlan0: sending IPv6 Router Solicitation,
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{8a853d0 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService},
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 370
,I/jxcore-log( 6116): Test app app.js loaded
I/jxcore-log( 6116): 
,I/Choreographer( 6116): Skipped 656 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6116): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  291): DCD OFF
,I/dhcpcd  ( 6308): wlan0: sending IPv6 Router Solicitation,
I/dhcpcd  ( 6308): wlan0: no IPv6 Routers available
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6150): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6150): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6150): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6150): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6150): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6150): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6150): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6150): entry::IDLE
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6644): MountEmulatedStorage()
E/Zygote  ( 6644): v2
,I/libpersona( 6644): KNOX_SDCARD checking this for 10028
I/libpersona( 6644): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6644 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6644): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6644): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6644): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6644): TimaSignature is unavailable
,D/ActivityThread( 6644): Added TimaKeyStore provider
,D/Finsky  ( 6644): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6644): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/Settings( 6644): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6644): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6150): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6150): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6150): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6150): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 6150): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6150): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6150): entry::IDLE
,D/Finsky  ( 6644): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6644): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6644): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6644): [1140] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6644): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6644): [1140] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/Finsky  ( 6644): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6644): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6644): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6644): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager( 1018): Killing 5970:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10053/pid_5970/cgroup.procs: No such file or directory
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6644): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6644): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6644): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6644): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6644): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6644): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6644): [1] DailyHygiene.reschedule: Scheduling new run in 270 minutes (failures=4)
,D/DeviceConnectionService( 1725): client connected with version: 7571000
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 1667): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4220, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/SSRM:n  ( 1018): SIOP:: AP = 330
,I/PowerManagerService( 1018): [PWL] Off : 30s ago
,E/Watchdog( 1018): !@Sync 3
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/FactoryTest( 5560): Not factory mode
,D/FactoryTest( 5560): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5560): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5560): still no open session command from host, so toast
,W/ContextImpl( 5560): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5560): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5560): Timeline: Activity_launch_request id:com.android.settings time:116039
,E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4227, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 6116
,E/MTPRx   ( 5560): started activity for popup
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/ResourcesManager( 5560): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5560): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5560): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5560): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5560): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5560): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SettingsReceiverActivity( 5560): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
,D/InputDispatcher( 1018): Focus entered window: 6116
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1018): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@17978ee5 attribute=null, token = android.os.BinderProxy@97bd031
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SettingsReceiverActivity( 5560): dev.kiessupport is : TRUE
,D/PhoneWindow( 5560): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5560): *FMB* installDecor flags : 8388610
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,V/ActivityThread( 6116): updateVisibility : ActivityRecord{10c02aff token=android.os.BinderProxy@1fb07659 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6116): Timeline: Activity_idle id: android.os.BinderProxy@1fb07659 time:116219
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 310
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1
,W/ActivityManager( 1018): mDVFSHelper.release()
,V/AlarmManager( 1018): waitForAlarm result :4
,V/AlarmManager( 1018): ___SyncScheduler (v3) ACTIVATED___
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK,
V/AlarmManagerEXT( 1018): <AppSync3 Whitelist>
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,V/AlarmManagerEXT( 1018): (AppSync) ### 0 added ###
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  291): DCD OFF
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.sync.RemindersSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 29585(1571KB) AllocSpace objects, 15(240KB) LOS objects, 33% free, 27MB/40MB, paused 2.531ms total 143.852ms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ReminderSync( 1932): AuthError [T SyncAdapterThread-1:id=288:priority=5:group=main]
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 121177, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1018): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 152742, reason: Periodic
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1667): Explicit concurrent mark sweep GC freed 19529(1129KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 1.497ms total 64.458ms
,D/Finsky  ( 6644): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6644): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6644): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4228, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,I/PowerManagerService( 1018): [PWL] Off : 50s ago
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,I/MotionRecognitionService( 1018): Plugged
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,E/Watchdog( 1018): !@Sync 4
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6644): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6644): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6644): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SMD     (  291): DCD OFF
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0,
,I/BooksSync( 6575): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6575): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6575): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6575): Soft error
E/BooksSync( 6575): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6575): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6575): Sync error
E/BooksSync( 6575): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6575): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6575): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 122160, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/PowerManagerService( 1018): [PWL] Off : 75s ago,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4233, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6644): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6644): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6644): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4233, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/Watchdog( 1018): !@Sync 5
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4235, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SMD     (  291): DCD OFF
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
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
,I/PowerManagerService( 1018): [PWL] Off : 105s ago
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6644): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6644): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6644): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1667): Vacuum at: now=1452699451427 tag=VacuumService
,I/GoogleURLConnFactory( 1667): Using platform SSLCertificateSocketFactory
,W/Uploader( 1667): No account for auth token provided
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1667): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1667): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1667): (HTTPLog)-Static: isShipBuild true
I/System.out( 1667): (HTTPLog)-Thread-195-588093295: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1667): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1667): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1667): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1667, getuid(): 10012
,I/qtaguid ( 1667): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1667, getuid(): 10012
,W/Uploader( 1667): No account for auth token provided
,I/System.out( 1667): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 1667): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1667, getuid(): 10012
,W/Uploader( 1667): No account for auth token provided
,I/System.out( 1667): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1667): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1667, getuid(): 10012
,W/Uploader( 1667): No account for auth token provided
,I/System.out( 1667): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 1667): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1667, getuid(): 10012
,W/Uploader( 1667): No account for auth token provided
,I/System.out( 1667): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1667): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1667, getuid(): 10012
,W/Uploader( 1667):  no longer exists, so no auth token.
,I/System.out( 1667): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1667): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1667, getuid(): 10012
,W/Uploader( 1667): No account for auth token provided
,I/System.out( 1667): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1667): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1667, getuid(): 10012
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice,
D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
E/Uploader( 1667): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1667): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1667): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1667): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1667): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1667): 	at com.google.android.gms.auth.p.b(SourceFile:477),
E/Uploader( 1667): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1667): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1667): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1667): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1667): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1667): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1667): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1667): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 1667): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1667, getuid(): 10012
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1667): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4235, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6575): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6575): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 41219(2MB) AllocSpace objects, 41(716KB) LOS objects, 33% free, 27MB/41MB, paused 2.498ms total 145.028ms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6575): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6575): Soft error
E/BooksSync( 6575): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6575): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6575): Sync error
E/BooksSync( 6575): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6575): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6575): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 212190, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/PowerManagerService( 1018): [PWL] Off : 140s ago
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:99, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/PowerManagerService( 1018): [PSM] lowPowerModeEnabled: false (mLowPowerModeSetting: false, mAutoLowPowerModeConfigured: false, mBatteryLevel: 99, mLowBatteryTriggerLevel: 0)
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99,
D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/Watchdog( 1018): !@Sync 7
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
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
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:99, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): stay LED for charging
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:99, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1018): stay LED for charging
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,I/PowerManagerService( 1018): [PWL] Off : 180s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/Watchdog( 1018): !@Sync 8,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:99, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:99, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99,
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 280
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/Watchdog( 1018): !@Sync 9
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:99, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 225s ago
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  291): DCD OFF
,I/jxcore-log( 6116): --= Surplus to requirements =--
I/jxcore-log( 6116): 
I/jxcore-log( 6116): ****TEST TOOK:  ms ****
I/jxcore-log( 6116): 
I/jxcore-log( 6116): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6116): 
,D/AndroidRuntime( 6814): ,
D/AndroidRuntime( 6814): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6814): CheckJNI is OFF,
D/AndroidRuntime( 6814): readGMSProperty: start
D/AndroidRuntime( 6814): readGMSProperty: already setted!!
D/AndroidRuntime( 6814): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6814): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6814): readGMSProperty: end
D/AndroidRuntime( 6814): addProductProperty: start
,E/AffinityControl( 6814): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6814): Calling main entry com.android.commands.pm.Pm,
,D/PackageManager( 1018): START PACKAGE DELETE: observer{961660854}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
,D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1018): !@killApplicatoin: 10174, uninstall pkg
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10174 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 6116:com.test.thalitest/u0a174 (adj 0): stop com.test.thalitest cause uninstall pkg
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{3f4ec6bf u0 com.test.thalitest/.MainActivity t234}
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10174 user=0: pkg removed
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{3f4ec6bf u0 com.test.thalitest/.MainActivity t234 f}
W/ActivityManager( 1018): Duplicate finish request for ActivityRecord{3f4ec6bf u0 com.test.thalitest/.MainActivity t234 f}
,W/InputDispatcher( 1018): channel ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher( 1018): channel ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher( 1018): Attempted to unregister already unregistered input channel
I/WindowState( 1018): WIN DEATH: Window{3a0cc316 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  257): id=14 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=14 Removed NainActivit (-2/8)
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,I/SurfaceFlinger(  257): id=14 Removed NainActivit (-2/8)
,D/InputDispatcher( 1018): Focus left window: 6116
,D/InputDispatcher( 1018): Focused application released
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/art     ( 4095): Explicit concurrent mark sweep GC freed 2898(173KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 6MB/11MB, paused 781us total 31.850ms
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 6131): Explicit concurrent mark sweep GC freed 359(25KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 757us total 38.188ms
,E/SamsungIME( 1786): mOCRHelper is null
,W/GeofencerStateMachine( 1725): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 2995): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,D/RegisteredComponentCache( 1446): Collect Tech packages for Knox
,D/PersonaManager( 1446): isKioskContainerExistOnDevice
,I/DBG_DM  ( 2995): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 13
,I/DBG_DM  ( 2995): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 2995): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 2995): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 13
,I/DBG_DM  ( 2995): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/KLMS-2.5.183: ( 3669): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jan 13 16:39:20 GMT+01:00 2016
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/DBG_DM  ( 2995): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/KLMS-2.5.183: ( 3669): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
I/splitIntent( 1018): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1018): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,I/DBG_DM  ( 2995): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onCreate()
,E/Zygote  ( 6827): MountEmulatedStorage(),
I/KLMS-2.5.183: ( 3669): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/Zygote  ( 6827): v2
I/libpersona( 6827): KNOX_SDCARD checking this for 10094
I/libpersona( 6827): KNOX_SDCARD not a persona
I/SELinux ( 6827): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6827): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6827): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6827 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 26939(2MB) AllocSpace objects, 47(752KB) LOS objects, 33% free, 27MB/40MB, paused 2.987ms total 177.047ms
,I/art     ( 1018): WaitForGcToComplete blocked for 164.364ms for cause Explicit
,I/KLMS-2.5.183: ( 3669): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/DBG_DM  ( 2995): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/TimaKeyStoreProvider( 6827): TimaSignature is unavailable
,D/ActivityThread( 6827): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/PersonaManager( 1446): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1446): empty dynamic service
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): PACKAGE_REMOVED
,I/DBG_DM  ( 2995): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 13
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,I/DBG_DM  ( 2995): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 2995): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 2995): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 2995): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 2995): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,I/DBG_DM  ( 2995): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/SurfaceFlinger(  257): id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1018): Focus entered window: 2995
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2995): log_dcs ThreadedRenderer::initialize entered! 
,D/elm:15183( 6827): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
V/ActivityThread( 2995): updateVisibility : ActivityRecord{5e46712 token=android.os.BinderProxy@3eef37db {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/elm:15183( 6827): ELMEngine.ELMEngine( context ).
,D/elm:15183( 6827): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 6827): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15183( 6827): ElmAgentService : onCreate()
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/KLMS-2.5.183: ( 3669): KLMSIntentService(): onDestroy()
,W/InputMethodManagerService( 1018): Got RemoteException sending setActive(false) notification to pid 6116 uid 10174
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/elm:15183( 6827): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 6827): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6827): MDMBridge.getInstance()
D/elm:15183( 6827): MDMBridge.getAllLicenseInfoFromSDK()
,I/Timeline( 2995): Timeline: Activity_idle id: android.os.BinderProxy@3eef37db time:312903
,D/elm:15183( 6827): MDMBridge.getAllLicenseInfoFromSDK()
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{49ec543 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t233} time:312912
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
,D/SamsungIME( 1786): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1018): no available spell checker services found
,D/elm:15183( 6827): ElmAgentService : onDestroy().
,I/ActivityManager( 1018): Killing 5991:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1018): PackageReceiver onReceive()
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1018): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1018): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1018): DBIntegrity::getInstance - New instance created
,D/OTPFW   ( 1018): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10174 container id = 0
,I/OTPFW   ( 1018): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1018): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10174
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 10315(495KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 6.461ms total 246.794ms
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10174
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,D/TaskPersister( 1018): removeObsoleteFile: deleting file=234_task.xml
,D/TaskPersister( 1018): removeObsoleteFile: deleting file=233_task.xml
,I/PCWCLIENTTRACE_PushUtil( 5772): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5772): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5772): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5772): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/PanelView( 1177): There is/are notification(s) ,
I/libpersona( 6847): KNOX_SDCARD checking this for 10032
E/Zygote  ( 6847): MountEmulatedStorage()
I/libpersona( 6847): KNOX_SDCARD not a persona
E/Zygote  ( 6847): v2
I/SELinux ( 6847): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6847): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 6847): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6847 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/TimaKeyStoreProvider( 6847): TimaSignature is unavailable
,D/ActivityThread( 6847): Added TimaKeyStore provider
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1018): delete codoeFile: 
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.test.thalitest
I/AASA_removePackage( 1018): UID=10174 Target=com.test.thalitest
,D/PackageManager( 1018): result of delete: 1{961660854}
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/AndroidRuntime( 6814): Shutting down VM
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/FeatureConfig( 6847): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/SA      ( 6056): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 6056): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10174 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
I/ActivityManager( 1018): Killing 6011:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/Zygote  ( 6866): MountEmulatedStorage()
I/libpersona( 6866): KNOX_SDCARD checking this for 10044
E/Zygote  ( 6866): v2
I/libpersona( 6866): KNOX_SDCARD not a persona
I/SELinux ( 6866): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 6866): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6866 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux ( 6866): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5991/cgroup.procs: No such file or directory
,W/ResourcesManager( 6847): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6866): TimaSignature is unavailable
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6011/cgroup.procs: No such file or directory
D/ActivityThread( 6866): Added TimaKeyStore provider
,W/ResourcesManager( 6847): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6866): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6866): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6866): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6866): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6866): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6866): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6866): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6866): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ResourcesManager( 6847): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SMD     (  291): DCD OFF
,W/ResourcesManager( 6847): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6847): system/finder_cp/cpdata.xml file not found
,W/art     ( 6814): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,D/NearbySource( 6866): Nearby Source Create!
,D/NearbyContext( 6866): Nearby Context Create!
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6866): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 6866): Samsung link source created
,D/ContactProvider( 6866): getAllContactInfoList Start
,W/FileUtils( 6866): Failed to chmod(/data/data/com.sec.android.gallery3d/databases/local.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PackagesMonitor( 6866): PackagesMonitor onReceive :com.test.thalitest
,D/ContactProvider( 6866): getAllContactInfoList End
,I/syncContacts( 6866): thread: 1158, sync time = 39
E/SharedPreferencesImpl( 6866): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6888): MountEmulatedStorage(),
,E/Zygote  ( 6888): v2
I/libpersona( 6888): KNOX_SDCARD checking this for 10046
I/libpersona( 6888): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6888 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 6032:com.sec.knox.bridge/1000 (adj 15): empty #31
,I/SELinux ( 6888): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6888): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6888): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/art     (  306): Explicit concurrent mark sweep GC freed 8678(369KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 24.740ms
,D/TimaKeyStoreProvider( 6888): TimaSignature is unavailable,
D/ActivityThread( 6888): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 16.563ms
,W/ResourcesManager( 6888): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6888): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6888): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6888): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6888): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6888): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 603us total 16.952ms

```
