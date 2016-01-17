#### Test 56151093914d164_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/TP/MmsSmsProvider( 1459): query,matched:0, calling pid = 5770
V/TP/MmsSmsProvider( 1459): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1459): match 0:Elapsed time : 1.159 ms
D/Mms/SpamFilter( 5770): [start]    SpamFilter fill() begin consume time = 1.996146
D/TP/MmsSmsProvider( 1459): update, matched:300, calling pid = 5770
V/TP/MmsSmsProvider( 1459): syncDBData start
V/TP/MmsSmsProvider( 1459): syncDBData sms end
D/TP/MmsSmsProvider( 1459): query,matched:400, calling pid = 5770
V/TP/MmsSmsProvider( 1459): syncDBData mms end
V/TP/MmsSmsProvider( 1459): syncDBData end
D/Mms/Synchronizer( 5770): [end]    doSync consume time = 5.39474
--------- beginning of system
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5932): MountEmulatedStorage()
E/Zygote  ( 5932): v2
I/SELinux ( 5932): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5932): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5932): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/libpersona( 5932): KNOX_SDCARD checking this for 10072
I/libpersona( 5932): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5932 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/Mms/DownloadManager( 5770): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5770): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5770): getSubId is called
D/Mms/TelephonyUtils( 5770): getLongSubId from simSlot 0, return Value = -1
D/Mms/SpamFilter( 5770): [end]    SpamFilter fill() finished consume time = 36.366198
D/Mms/MethodReflector( 5770): getTelephonyProperty is called
D/Mms/DownloadManager( 5770): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5770): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5770): auto download without roaming -> true
D/Mms/DownloadManager( 5770): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5770): mAutoDownload ------> true
D/TimaKeyStoreProvider( 5932): TimaSignature is unavailable
D/ActivityThread( 5932): Added TimaKeyStore provider
D/Mms/FreeMessageStatusReceiver( 5770): onReceive, action : android.intent.action.PACKAGE_ADDED
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 5839): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 5839): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
E/Zygote  ( 5949): MountEmulatedStorage()
E/Zygote  ( 5949): v2
I/libpersona( 5949): KNOX_SDCARD checking this for 10047
I/libpersona( 5949): KNOX_SDCARD not a persona
D/BadgeProvider( 5932): onCreate
I/SELinux ( 5949): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/BadgeProvider( 5932): DatabaseHelper
I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/ActivityManager( 1014): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5949 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 5949): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5949): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
D/TimaKeyStoreProvider( 5949): TimaSignature is unavailable
I/DBG_POLICYDM( 5839): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
D/ActivityThread( 5949): Added TimaKeyStore provider
D/Mms/MessagingNotification( 5770): checkBadgeCount unreadCount=0 badgeCount=0
I/ActivityManager( 1014): Killing 5310:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
I/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
D/TP/SmsProvider( 1459): query,matched:26, calling pid = 5770
D/Mms/FreeMessageReceiverService( 5770): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5770): onHandleIntent: ACTION_PACKAGE_ADDED
D/TP/SmsProvider( 1459): match 26:Elapsed time : 3.022 ms
I/ActivityManager( 1014): Killing 5192:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
I/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
W/ResourcesManager( 5949): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5949): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5949): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5839): [com.policydm.XSPPReceiver(53/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5967): MountEmulatedStorage()
E/Zygote  ( 5967): v2
I/libpersona( 5967): KNOX_SDCARD checking this for 10038
I/libpersona( 5967): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5967 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 5967): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1014): Killing 3749:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/SELinux ( 5967): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5967): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ConfigFetchService( 1950): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1950): launchTask
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/TP/MmsSmsProvider( 1459): query,matched:6, calling pid = 5770
D/TP/MmsSmsProvider( 1459): match 6:Elapsed time : 1.208 ms
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1950): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1950): Module APK com.google.android.play.games already loaded
I/PeopleContactsSync( 1950): CP2 sync disabled
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1950): Loading module com.google.android.gms.vision from APK com.google.android.gms
V/AlarmManager( 1014): waitForAlarm result :4
D/TimaKeyStoreProvider( 5967): TimaSignature is unavailable
D/ActivityThread( 5967): Added TimaKeyStore provider
D/Vision  ( 1950): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1950): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1950): No vision deps
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 5967): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5967): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
V/ConfigFetchTask( 1950): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UdwvY7mrM7CDi6Hew6ZixS4gqzNKzKtph69DiGzay9sduT2zkanuki2b3SOeP-WXCHrJBwh868r7bPUYcEZTb_Td8vLBcDiSZyzj4lDnu_SfWJmKGb0Wc2lXU0avNMO6ar0_4aPQn_jid5q8H8hyutjO0y9_cp_WEFTPVszSKGSp6oviAJFskzqaqXZ-Z6dYaaiA_6TpReabUPhQHb9SjMS0cV2pOqkUuf4Uy1MCGV8fMUkho
I/GoogleURLConnFactory( 1950): Using platform SSLCertificateSocketFactory
I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5986 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/Zygote  ( 5986): MountEmulatedStorage()
I/libpersona( 5986): KNOX_SDCARD checking this for 10025
E/Zygote  ( 5986): v2
I/libpersona( 5986): KNOX_SDCARD not a persona
I/SELinux ( 5986): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5986): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5986): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5839): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
D/TimaKeyStoreProvider( 5986): TimaSignature is unavailable
D/ActivityThread( 5986): Added TimaKeyStore provider
W/libprocessgroup( 1014): failed to open /acct/uid_10035/pid_5310/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5192/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10042/pid_3749/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 5839): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/ActivityManager( 1014): Killing 3878:com.google.android.talk/u0a104 (adj 15): empty #31
I/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 5839): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
D/AndroidRuntime( 5965): 
D/AndroidRuntime( 5965): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
D/AndroidRuntime( 5965): CheckJNI is OFF
D/AndroidRuntime( 5965): readGMSProperty: start
D/AndroidRuntime( 5965): readGMSProperty: already setted!!
D/AndroidRuntime( 5965): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5965): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5965): readGMSProperty: end
D/AndroidRuntime( 5965): addProductProperty: start
W/ResourcesManager( 5986): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5839): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
I/DBG_POLICYDM( 5839): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 5839): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 5839): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
I/DBG_POLICYDM( 5839): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 5839): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/01/18/17:26:23
I/DBG_POLICYDM( 5839): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/OMACP   ( 5986): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
I/DBG_POLICYDM( 5839): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5839): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 5839): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
W/art     ( 1950): Verification of void com.google.android.gms.games.broker.DataBroker.<init>(android.content.Context) took 176.546ms
I/DBG_POLICYDM( 5839): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/01/17/16:02:25
I/DBG_POLICYDM( 5839): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5839): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 5839): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
I/DBG_POLICYDM( 5839): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
D/Mms/Omacp( 5770): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
I/System.out( 1950): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1950): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1950): (HTTPLog)-Static: isShipBuild true
I/System.out( 1950): (HTTPLog)-Thread-276-694327968: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1950): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
W/libprocessgroup( 1014): failed to open /acct/uid_10104/pid_3878/cgroup.procs: No such file or directory
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/MyFiles ( 5949): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager( 1014): Killing 5465:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 5839): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
I/System.out( 1950): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1950): Tagging socket 96 with tag 40b00000000{1035,0} for uid -1, pid: 1950, getuid(): 10012
W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
E/AffinityControl( 5965): AffinityControl: registerfunction enter
D/AndroidRuntime( 5965): Calling main entry com.android.commands.am.Am
I/TactileAssist( 1014): enable value -1
I/TactileAssist( 1014): internal enable value -1
I/TactileAssist( 1014): intensity value -1
I/TactileAssist( 1014): saveAppList value true
I/DBG_POLICYDM( 5839): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
I/TactileAssist( 1014): List of disabled apps :
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
W/libprocessgroup( 1014): failed to open /acct/uid_10069/pid_5465/cgroup.procs: No such file or directory
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/PackageManager( 1014): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
W/ActivityManager( 1014): mDVFSHelper.acquire()
I/qtaguid ( 1950): Tagging socket 104 with tag 40b00000000{1035,0} for uid -1, pid: 1950, getuid(): 10012
I/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
D/PhoneWindow( 1014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1014): *FMB* installDecor flags : 25362712
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6023): MountEmulatedStorage()
I/libpersona( 6023): KNOX_SDCARD checking this for 10174
E/Zygote  ( 6023): v2
I/libpersona( 6023): KNOX_SDCARD not a persona
I/SELinux ( 6023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1014): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6023 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled return false
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/SurfaceFlinger(  256): id=13 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6023): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 3035
D/AndroidRuntime( 5965): Shutting down VM
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6039): MountEmulatedStorage()
E/Zygote  ( 6039): v2
I/libpersona( 6039): KNOX_SDCARD checking this for 10053
I/libpersona( 6039): KNOX_SDCARD not a persona
I/SELinux ( 6039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1014): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6039 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 6039): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6023): TimaSignature is unavailable
D/ActivityThread( 6023): Added TimaKeyStore provider
I/DBG_POLICYDM( 5839): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
V/ActivityManager( 1014): Display changed displayId=0
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/TimaKeyStoreProvider( 6039): TimaSignature is unavailable
D/ActivityThread( 6039): Added TimaKeyStore provider
D/PersonaManager( 1014): isKioskContainerExistOnDevice
I/GAv4    ( 5807): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5807):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5807):   adb logcat -s GAv4
V/ActivityThread( 3035): updateVisibility : ActivityRecord{46caec7 token=android.os.BinderProxy@399ea06a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/PowerManagerService( 1014): [PWL] Off : 5s ago
I/PowerManagerService( 1014): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1014): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1014): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1950, ws=null) (elapsedTime=47854)
I/PowerManagerService( 1014): [PWL]       PARTIAL_WAKE_LOCK              'Config Service fetch' (uid=10012, pid=1950, ws=WorkSource{10174 com.test.thalitest}) (elapsedTime=647)
I/PowerManagerService( 1014): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1014, ws=WorkSource{10054}) (elapsedTime=583)
W/BaseAppContext( 1950): Using Auth Proxy for data requests.
W/BaseAppContext( 1950): Using Auth Proxy for data requests.
W/GAv4    ( 5807): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ResourcesManager( 6039): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/SurfaceFlinger(  256): id=11 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  256): id=11 Removed YUIInstallC (-2/9)
D/Compatibility( 6039): onReceive() it will make start service
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/Compatibility( 6039): onHandleIntent()
I/DBG_POLICYDM( 5839): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
D/Compatibility( 6039): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10174, android.intent.extra.user_handle=0}]
W/GAv4    ( 5807): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
D/Compatibility( 6039): found: 2
I/SL_DEBUG( 5967): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5967): isLoggable:: SL_DEBUG_EXIST = false
D/Compatibility( 6039): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6039): skipping ResolveInfo{35ff5a31 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6039): considering ResolveInfo{3e1a8516 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6039): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6039): enabling receiver ResolveInfo{adb8e97 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6039): enabling receiver ResolveInfo{24b7e884 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6039): enabling receiver ResolveInfo{53e686d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6039): enabling receiver ResolveInfo{30b1dca2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/AnalyticsTrackerProxyImpl( 5807): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
W/art     ( 5965): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/Zygote  ( 6062): MountEmulatedStorage()
I/ActivityManager( 1014): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6062 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 6062): v2
I/libpersona( 6062): KNOX_SDCARD checking this for 1000
I/libpersona( 6062): KNOX_SDCARD not a persona
I/SELinux ( 6062): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6062): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6062): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 6039): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 6062): TimaSignature is unavailable
D/ActivityThread( 6062): Added TimaKeyStore provider
W/BaseAppContext( 1950): Using Auth Proxy for data requests.
I/DBG_POLICYDM( 5839): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
W/GAv4    ( 5807): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/qtaguid ( 1950): Untagging socket 96
I/ConfigFetchService( 1950): fetch service done; releasing wakelock
I/ConfigFetchService( 1950): stopping self
W/BaseAppContext( 1950): Using Auth Proxy for data requests.
W/BaseAppContext( 1950): Using Auth Proxy for data requests.
W/art     ( 5807): Suspending all threads took: 8.908ms
I/WebViewFactory( 6023): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/DBG_POLICYDM( 5839): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
I/LibraryLoader( 6023): Time to load native libraries: 2 ms (timestamps 3820-3822)
W/ContextImpl( 6062): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
I/LibraryLoader( 6023): Expected native library version number "",actual native library version number ""
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6081): MountEmulatedStorage()
E/Zygote  ( 6081): v2
I/libpersona( 6081): KNOX_SDCARD checking this for 1000
I/libpersona( 6081): KNOX_SDCARD not a persona
I/SELinux ( 6081): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1014): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6081 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6081): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6081): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 1674): Explicit concurrent mark sweep GC freed 17867(1038KB) AllocSpace objects, 3(108KB) LOS objects, 39% free, 10MB/17MB, paused 1.125ms total 50.676ms
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5967): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/TimaKeyStoreProvider( 6081): TimaSignature is unavailable
I/ActivityManager( 1014): Killing 5480:com.sec.knox.bridge/1000 (adj 15): empty #31
D/ActivityThread( 6081): Added TimaKeyStore provider
W/BaseAppContext( 1950): Using Auth Proxy for data requests.
W/ResourcesManager( 6081): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
V/WebViewChromiumFactoryProvider( 6023): Binding Chromium to main looper Looper (main, tid 1) {53e686d}
I/LibraryLoader( 6023): Expected native library version number "",actual native library version number ""
I/chromium( 6023): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
I/BrowserStartupController( 6023): Initializing chromium process, singleProcess=true
W/art     ( 6023): Attempt to remove local handle scope entry from IRT, ignoring
W/ContextImpl( 5967): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
E/SysUtils( 6023): ApplicationContext is null in ApplicationStatus
I/ActivityManager( 1014): Killing 5496:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
W/BroadcastQueue( 1014): Exception when sending broadcast to ComponentInfo{com.sec.knox.bridge/com.sec.knox.bridge.PersonaShortcutReceiver}
W/BroadcastQueue( 1014): android.os.DeadObjectException
W/BroadcastQueue( 1014): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1014): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1014): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1014): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1014): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1014): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1014): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1014): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1014): 	at android.os.Binder.execTransact(Binder.java:461)
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/chromium( 6023): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/Zygote  ( 6105): MountEmulatedStorage()
E/Zygote  ( 6105): v2
I/libpersona( 6105): KNOX_SDCARD checking this for 1000
I/libpersona( 6105): KNOX_SDCARD not a persona
E/libEGL  ( 6023): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6023): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6023): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6023): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6023): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6023): Local Branch: 
I/Adreno-EGL( 6023): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6023): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6023):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/SELinux ( 6105): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6105): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6105): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6105 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ActivityManager( 1014): Spurious death for ProcessRecord{2aa7b72f 6105:com.sec.knox.bridge/1000}, curProc for 5480: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/TimaKeyStoreProvider( 6105): TimaSignature is unavailable
D/ActivityThread( 6105): Added TimaKeyStore provider
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 6105): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/Zygote  ( 6125): MountEmulatedStorage()
E/Zygote  ( 6125): v2
I/libpersona( 6125): KNOX_SDCARD checking this for 10041
I/libpersona( 6125): KNOX_SDCARD not a persona
I/SELinux ( 6125): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6125): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6125): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6125 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1014): Activity pause timeout for ActivityRecord{26c9d45e u0 com.test.thalitest/.MainActivity t234}
I/ActivityManager( 1014): Killing 5555:com.google.android.apps.plus/u0a120 (adj 15): empty #31
I/art     (  307): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 663us total 32.991ms
D/TimaKeyStoreProvider( 6125): TimaSignature is unavailable
D/ActivityThread( 6125): Added TimaKeyStore provider
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5480/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5496/cgroup.procs: No such file or directory
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 18.846ms
I/ActivityManager( 1014): Killing 5395:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
W/BroadcastQueue( 1014): Exception when sending broadcast to ComponentInfo{com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor}
W/BroadcastQueue( 1014): android.os.DeadObjectException
W/BroadcastQueue( 1014): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1014): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1014): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1014): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1014): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1014): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1014): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1014): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1014): 	at android.os.Binder.execTransact(Binder.java:461)
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 19.233ms
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 5807): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
E/Zygote  ( 6151): MountEmulatedStorage()
E/Zygote  ( 6151): v2
I/libpersona( 6151): KNOX_SDCARD checking this for 10120
I/libpersona( 6151): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6151 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 5807): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5807): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ActivityManager( 1014): Spurious death for ProcessRecord{1fcea872 6151:com.google.android.apps.plus/u0a120}, curProc for 5555: null
I/SELinux ( 6151): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6151): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1014): Killing 4969:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
E/SELinux ( 6151): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/art     ( 1014): Explicit concurrent mark sweep GC freed 238271(16MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/40MB, paused 10.617ms total 241.599ms
I/SA      ( 6125): [SSP] onCreated
D/TimaKeyStoreProvider( 6151): TimaSignature is unavailable
D/ActivityThread( 6151): Added TimaKeyStore provider
I/SA      ( 6125): [TPM] There is no property file
I/SA      ( 6125): [SCU] isHaveSA() - false
I/SA      ( 6125): [TPM] getModelProperty : null
I/SA      ( 6125): [TPM] getCSCProperty : null
I/SA      ( 6125): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6125): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6125): [DM] TFT FEATURE: false
I/SA      ( 6125): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6125): [DM] init START
W/ResourcesManager( 6151): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/libprocessgroup( 1014): failed to open /acct/uid_10120/pid_5555/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10057/pid_5395/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4969/cgroup.procs: No such file or directory
I/SA      ( 6125): [DM] This device is not a Vodafone
W/ResourceType( 6125): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
V/JNIHelp ( 5807): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ResourceType( 6125): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6125): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6125): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6125): [SCU] isHaveSA() - false
I/SA      ( 6125): support phone number id : false
I/SA      ( 6125): [DM] Supports Ref Jpn : true
I/SA      ( 6125): [DM] init END
I/SA      ( 6125): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 6125): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10174 extra.user_handle.:0 ]
I/ActivityManager( 1014): Killing 4990:com.google.android.gms:car/u0a12 (adj 15): empty #31
W/ActivityThread( 5807): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5807): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@363fccc3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5807): Installed default security provider GmsCore_OpenSSL
W/art     ( 6023): Attempt to remove local handle scope entry from IRT, ignoring
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1014): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
W/AwContents( 6023): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6023): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6023): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6023): CordovaWebView is running on device made by: samsung
W/art     ( 6023): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6023): Attempt to remove local handle scope entry from IRT, ignoring
W/libprocessgroup( 1014): failed to open /acct/uid_10012/pid_4990/cgroup.procs: No such file or directory
D/OpenGLRenderer( 6023): Render dirty regions requested: true
D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
V/ActivityThread( 6023): updateVisibility : ActivityRecord{1161a19e token=android.os.BinderProxy@11ac8e20 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
W/chromium( 6023): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/PhoneWindow( 6023): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6023): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=14 createSurf (1x1),1 flag=404, NainActivit
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
D/InputDispatcher( 1014): Focus entered window: 6023
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6023): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6023): Initialized EGL, version 1.4
D/OpenGLRenderer( 6023): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6023): Enabling debug mode 0
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/PanelView( 1179): There is/are notification(s) 
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SamsungIME( 1761): getCurrentCandidateView
I/Mms/MmsApp( 5770):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5770): [start]    fillCache consume time = 1944.861145
D/Mms/ComposeMessageFragment( 5770): fillCache, easy = false
I/ActivityManager( 1014): Displayed Component not be shown by security: +1s135ms (total +1s256ms)
W/IInputConnectionWrapper( 6023): showStatusIcon on inactive InputConnection
I/Timeline( 6023): Timeline: Activity_idle id: android.os.BinderProxy@11ac8e20 time:84696
W/ActivityManager( 1014): mDVFSHelper.release()
I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{26c9d45e u0 com.test.thalitest/.MainActivity t234} time:84698
I/SurfaceFlinger(  256): id=13 Removed uhalitest (7/9)
I/SurfaceFlinger(  256): id=13 Removed uhalitest (-2/9)
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6196): MountEmulatedStorage()
E/Zygote  ( 6196): v2
I/libpersona( 6196): KNOX_SDCARD checking this for 10057
I/libpersona( 6196): KNOX_SDCARD not a persona
I/SELinux ( 6196): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6196): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1014): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6196 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/SELinux ( 6196): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 5616:com.sec.android.diagmonagent/1000 (adj 15): empty #31
D/AbsListView( 5770): Get MotionRecognitionManager
D/MotionRecognitionService( 1014):  ssp status : false
D/SamsungIME( 1761): Dismiss ExpandCandiate
D/Mms/ComposeMessageFragment( 5770): [end]    fillCache consume time = 127.544791
D/TimaKeyStoreProvider( 6196): TimaSignature is unavailable
D/ActivityThread( 6196): Added TimaKeyStore provider
D/ChimeraCfgMgr( 1950): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1950): Module APK com.google.android.play.games already loaded
I/SamsungIME( 1761): getDebugLevel  : 0x4f4c
,D/Mms/BubbleViewCache( 5770): fillCache bubble = 1
,W/BindingManager( 6023): Cannot call determinedVisibility() - never saw a connection for the pid: 6023
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5616/cgroup.procs: No such file or directory
,I/SamsungIME( 1761): getDebugLevel  : 0x4f4c
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/SamsungIME( 1761): KeybaordView init() : load resources
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SamsungIME( 1761): getCurrentKeyboard,
I/SamsungIME( 1761): getTextKeyboard
,E/Zygote  ( 6218): MountEmulatedStorage()
,E/Zygote  ( 6218): v2
I/libpersona( 6218): KNOX_SDCARD checking this for 10010
I/libpersona( 6218): KNOX_SDCARD not a persona
,I/SELinux ( 6218): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1014): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6218 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
I/SELinux ( 6218): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6218): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/SamsungIME( 1761): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/TimaKeyStoreProvider( 6218): TimaSignature is unavailable
,D/ActivityThread( 6218): Added TimaKeyStore provider
,D/JsMessageQueue( 6023): Set native->JS mode to OnlineEventsBridgeMode
,I/splitIntent( 1014): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1014): Killing 5639:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/KeyguardViewMediator( 1179): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1179): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1179): *** Keyguard wallpaper service already unbounded
,D/jxcore_app_log( 6023): JniHelper::setJavaVM(0xb8226450), pthread_self() = -1200097960
,D/JX-Cordova( 6023): jxcore cordova android initializing
,D/LocationManagerService( 1014): getProviders()=[passive]
,W/libprocessgroup( 1014): failed to open /acct/uid_10142/pid_5639/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 6196): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,E/SMD     (  287): DCD OFF
,I/UpdateIcingCorporaServi( 6196): UpdateCorporaTask done [took 123 ms] updated apps [took 123 ms] 
,I/ActivityManager( 1014): Killing 5207:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6240): MountEmulatedStorage(),
,E/Zygote  ( 6240): v2,
I/libpersona( 6240): KNOX_SDCARD checking this for 10012
I/libpersona( 6240): KNOX_SDCARD not a persona
,I/SELinux ( 6240): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/SELinux ( 6240): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1014): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=6240 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/SELinux ( 6240): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6240): TimaSignature is unavailable
,D/ActivityThread( 6240): Added TimaKeyStore provider
,W/ResourcesManager( 6240): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6240): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6240): VM with version 2.1.0 has multidex support
I/MultiDex( 6240): install
I/MultiDex( 6240): VM has multidex support, MultiDex support library is disabled.
W/libprocessgroup( 1014): failed to open /acct/uid_10150/pid_5207/cgroup.procs: No such file or directory
,V/JNIHelp ( 6240): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6240): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6240): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@44bb944: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6240): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1014): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1014): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1014): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
D/GCM     ( 1674): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1674): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1950): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1014): Killing 5119:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4476): callingUid 10012, callindPid: 4476
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1743): [192] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1950): Restart initialization of location
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10040/pid_5119/cgroup.procs: No such file or directory
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4173, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1014): stay LED for charging
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/jxcore-log( 6023): Initializing JXcore engine
W/jxcore-log( 6023): JXcore engine is ready
,W/jxcore-log( 6023): Starting JXcore engine
,I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5839): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/AcmsKeyStoreHelper( 5857):  getKeyStoreForApplication Enter
,E/audit   ( 1856): type=1400 msg=audit(1453042948.952:205): avc:  denied  { ioctl } for  pid=6023 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1856):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1856): type=1300 msg=audit(1453042948.952:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=beac0d58 items=0 ppid=307 ppcomm=main pid=6023 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1856): type=1320 msg=audit(1453042948.952:205): 
,I/AcmsKeyStoreHelper( 5857): Key Store exist
I/AcmsKeyStoreHelper( 5857): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 5857):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5857): getKeyStoreForApplication success 
D/AcmsCore( 5857): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5857): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5857): Decrementing - Counter value: 1
D/AcmsCore( 5857): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5857): This is NOT a valid MirrorLink app
D/AcmsCore( 5857): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5857): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5857): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5857): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5857): getSvcCounter - Counter value: 0
,D/AcmsService( 5857): Enter onDestroy
I/AcmsService( 5857): cleanUp(): inside service clean up
D/AcmsCore( 5857): AcmsCore: inside DeInit
D/AcmsCore( 5857): AcmsCore: mLooperHandler is not null and making it null
,D/AcmsCertificateMngr( 5857): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5857): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5857): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5857): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5857): getSvcCounter - Counter value: 0
D/AcmsService( 5857): killing acms process
I/Process ( 5857): Sending signal. PID: 5857 SIG: 9
,W/jxcore-log( 6023): Platform android
W/jxcore-log( 6023): 
W/jxcore-log( 6023): Process ARCH arm
W/jxcore-log( 6023): 
,I/ActivityManager( 1014): Process ACMS.Process (pid 5857)(adj 0) has died(36,1088)
,I/jxcore-log( 6023): JXcore Cordova bridge is ready!
I/jxcore-log( 6023): 
,W/jxcore-log( 6023): JXcore engine is started
,I/chromium( 6023): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6023): Toggling radios to true
I/jxcore-log( 6023): 
,D/BluetoothAdapter( 6023): enable()
,D/BluetoothAdapter( 6023): enable(): BT is already enabled..!
,D/SecContentProvider( 1014): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1014): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1014): mCursor = null
,D/WifiService( 1014): setWifiEnabled: true pid=6023, uid=10174
,W/ActivityManager( 1014): Permission Denial: getCurrentUser() from pid=6023, uid=10174 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1014): Failed getting userId using ActivityManagerNative
W/WifiService( 1014): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6023, uid=10174 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1014): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1014): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1014): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1014): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1014): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1014): name = wifi_on
,I/WifiService( 1014): disconnect: pid=6023, uid=10174
,I/wpa_supplicant( 2087): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6023): Radios toggled
I/jxcore-log( 6023): 
,I/jxcore-log( 6023): My device name is: samsung-SM-A500FU
I/jxcore-log( 6023): 
,I/wpa_supplicant( 2087): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 2087): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2087): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 2087): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2087): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/wpa_supplicant( 2087): Cmd 35605 not handled
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
D/Tethering( 1014): InitialState.processMessage what=4
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,E/WifiStateMachine( 1014): WifiStateMachine: Leaving Connected state
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false,
,D/Tethering( 1014): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2087): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2087): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2087): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2087): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 2087): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 2087): First Scan Start
E/Tethering( 1014): No numeric data
I/wpa_supplicant( 2087): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 1014): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1014): clearTetheredNotification()
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
D/HotspotTile( 1179): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1179): updateTetherState():false, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/NetworkStats( 1014): performPollLocked() took 4ms,
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,E/WifiNative-wlan0( 1014): do suspend true
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1674): Read error: ssl=0xb87b1b18: I/O error during system call, Connection timed out,
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1014): updateNetworkInfo()
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2,
E/ConnectivityService( 1014): updateNetworkInfo()
E/WifiStateMachine( 1014): Start Disconnecting Watchdog 1
I/wpa_supplicant( 2087): wlan0: Setting scan request: 0 sec 0 usec
V/NativeCrypto( 1674): SSL shutdown failed: ssl=0xb87b1b18: I/O error during system call, Broken pipe
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,D/ConnectivityService( 1014): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Forcing reevaluation
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14949 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6950 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1014): Tagging socket 361 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
,I/qtaguid ( 1014): Untagging socket 361
,I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,E/WifiNative-wlan0( 1014): do suspend true,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/WifiP2pService( 1014): InactiveState{ what=143375 }
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3530): Starting #8
,I/Hs20UtilService( 3530): Message received 5007
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1322): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1322): MountReceiver.mPrefHandler - 7002
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  277): Clearing all IP addresses on wlan0
D/ConnectivityService( 1014): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ConnectivityService( 1014): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Validated
D/EntConnectivity( 1014): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityService( 1014): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524292
D/WIFI_P2P( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/TelephonyNetworkFactory( 1459): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/TelephonyNetworkFactory( 1459): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/CSLegacyTypeTracker( 1014): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1014): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/Zygote  ( 6268): MountEmulatedStorage()
E/Zygote  ( 6268): v2
I/libpersona( 6268): KNOX_SDCARD checking this for 10104
I/libpersona( 6268): KNOX_SDCARD not a persona
,I/SELinux ( 6268): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6268): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6268): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6268 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ConnectivityService( 1014): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): doQuit - quitNow()
D/EntConnectivity( 1014): Not allowed due to - mEnabled false - primarySimSlot false
D/Tethering( 1014): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1014): MasterInitialState.processMessage what=3
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): updateIfacesLocked()
V/NetworkStats( 1014): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
D/StatusBar.NetworkController( 1179): EthernetConnected: false
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1179): updateDataNetType()
D/StatusBar.NetworkController( 1179): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1179): updateLTEICONDataNetType:0
V/NetworkStats( 1014): performPollLocked() took 4ms
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/WifiNetworkAgent( 1014): NetworkAgent: NetworkAgent channel lost
I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1179): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/WIFI    ( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 6268): TimaSignature is unavailable
,D/ActivityThread( 6268): Added TimaKeyStore provider
,W/ResourcesManager( 6268): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
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
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3,
D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3,
D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3,
D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel_SMS( 6268): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6268): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6268): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 6268): MmsConfig.loadFromDatabase
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Babel_SMS( 6268): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6268): MmsConfig.loadFromResources
,E/Babel_SMS( 6268): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6268): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml,
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  282): getCameraInfo: X
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  282): getCameraInfo: X
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Settings( 6268): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/SMD     (  287): DCD OFF
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1014): SIOP:: AP = 380
,I/Babel_Crash( 6268): startup - clean
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 6268): deleted: false for 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1014): updateDataUsageMap
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3035): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3035): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6268): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6268): Unsupported mime audio/evrc
,W/AudioCapabilities( 6268): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6268): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6268): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6268): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6268): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6268): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6268): Unsupported mime audio/evrc
,W/VideoCapabilities( 6268): Unsupported mime video/wvc1
,W/VideoCapabilities( 6268): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6268): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6268): Unsupported mime video/wvc1
,W/VideoCapabilities( 6268): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6268): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6268): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6268): Unsupported mime video/mp43
,W/VideoCapabilities( 6268): Unsupported mime video/sorenson
,W/VideoCapabilities( 6268): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6268): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6268): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6268): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6268): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6268): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1014): Killing 5024:com.google.android.music:main/u0a111 (adj 15): empty #31
,I/vclib   ( 6268): onServiceConnected
,W/Babel   ( 6268): Attempted to change video mute state without an active call.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/Hs20UtilService( 3530): Starting #9
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1322): MountReceiver.onReceive - Set preference state off
I/Hs20UtilService( 3530): Message received 5007
V/NearbySettings( 1322): MountReceiver.mPrefHandler - 7002
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
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/libprocessgroup( 1014): failed to open /acct/uid_10111/pid_5024/cgroup.procs: No such file or directory
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/PCWCLIENTTRACE_PushUtil( 5794): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5794): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5794): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5794): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1014): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
,I/splitIntent( 1014): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1014): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5794): noConnectivity : true
,E/Zygote  ( 6312): MountEmulatedStorage()
,E/Zygote  ( 6312): v2
I/libpersona( 6312): KNOX_SDCARD checking this for 10111
I/libpersona( 6312): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6312 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 6312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6312): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6312): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6312): TimaSignature is unavailable
,D/ActivityThread( 6312): Added TimaKeyStore provider
,I/ConfigService( 1674): onDestroy
,I/MusicStore( 6312): Database version: 120
,I/wpa_supplicant( 2087): nl80211: Received scan results (9 BSSes),
I/wpa_supplicant( 2087): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 2087): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 2087): Trying to associate with  'G700'
I/wpa_supplicant( 2087): Re-associate with C0.AA.48
I/wpa_supplicant( 2087): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 2087): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1014): didn't find BSSID Trying to associate with SSID 'NG700',
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6312): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6312): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/wpa_supplicant( 2087): Cmd 35605 not handled
,I/wpa_supplicant( 2087): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2087): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2087): wlan0: State: ASSOCIATING -> ASSOCIATED
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2087): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 2087): Associated with C0.AA.48
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
I/wpa_supplicant( 2087): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2087): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2087): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,W/ContextImpl( 6312): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceStatusChanged wlan0, false
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,I/wpa_supplicant( 2087): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2087): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 2087): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 2087): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 2087): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2087): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2087): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 2087): Blacklist: Clear (temp) 
I/wpa_supplicant( 2087): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, true
D/Tethering( 1014): interfaceStatusChanged wlan0, true
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, true
D/Tethering( 1014): interfaceStatusChanged wlan0, true
,E/Tethering( 1014): No numeric data
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1014): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1014): clearTetheredNotification()
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
D/HotspotTile( 1179): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1179): updateTetherState():false, false
,D/WifiNative-wlan0( 1014): callSECApiVoid - ID [50]
,V/NetworkStats( 1014): performPollLocked() took 3ms
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,E/WifiConfigStore( 1014): setLastSelectedConfiguration -1
,D/ConnectivityService( 1014): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1014): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1014): updateNetworkInfo()
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/AlarmManager( 1014): waitForAlarm result :4
E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/ResourcesManager( 6312): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6312): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/CommandListener(  277): Setting iface cfg
,E/WifiStateMachine( 1014): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1014): mCursor = null
,E/WifiNative-wlan0( 1014): do suspend false
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1014): mCursor = null
,V/JNIHelp ( 6312): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6312): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6312): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ca8bf4b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6312): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6312): GMSCore installation verified
,I/ConfigStore( 6312): Config Database version: 1
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1014): getStreamVolume 3 index 0
,I/MediaRouter( 6312): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6312): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/dhcpcd  ( 6340): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6340): version 5.5.6 starting
,E/dhcpcd  ( 6340): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6344): MountEmulatedStorage()
I/ActivityManager( 1014): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6344 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6344): v2
I/libpersona( 6344): KNOX_SDCARD checking this for 10002
I/libpersona( 6344): KNOX_SDCARD not a persona
I/SELinux ( 6344): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6344): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6344): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 6340): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6340): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6340): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6340): bssid match
I/dhcpcd  ( 6340): wlan0: rebinding lease of 192.168.1.137
,D/TimaKeyStoreProvider( 6344): TimaSignature is unavailable
,D/ActivityThread( 6344): Added TimaKeyStore provider
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GHttpClientFactory( 6312): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6312): Using platform SSLCertificateSocketFactory
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1014): Killing 5349:com.google.android.gm/u0a101 (adj 15): empty #31
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6366 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 6366): MountEmulatedStorage()
E/Zygote  ( 6366): v2
I/libpersona( 6366): KNOX_SDCARD checking this for 1000
I/libpersona( 6366): KNOX_SDCARD not a persona
,I/SELinux ( 6366): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6366): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6366): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6366): TimaSignature is unavailable
,D/ActivityThread( 6366): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6366): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1014): failed to open /acct/uid_10101/pid_5349/cgroup.procs: No such file or directory
,V/AlarmManager( 1014): waitForAlarm result :4
,I/DIAGMON_AGENT( 6366): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,I/DIAGMON_AGENT( 6366): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,I/DIAGMON_AGENT( 6366): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6366): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6366): ./extraInfo: <unknown ssid>
W/DIAGMON_AGENT( 6366): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6381): MountEmulatedStorage()
,E/Zygote  ( 6381): v2
I/libpersona( 6381): KNOX_SDCARD checking this for 10009
I/libpersona( 6381): KNOX_SDCARD not a persona
I/SELinux ( 6381): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1014): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6381 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 5138:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
I/SELinux ( 6381): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6381): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6381): TimaSignature is unavailable
,D/ActivityThread( 6381): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_10044/pid_5138/cgroup.procs: No such file or directory
,I/ActivityManager( 1014): Killing 4178:com.sec.spp.push/u0a35 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3578): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Jan 17 16:02:32 GMT+01:00 2016
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3578): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3578): KLMSIntentService(): onCreate()
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3578): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3578): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 6397): MountEmulatedStorage(),
I/ActivityManager( 1014): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6397 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 6397): v2
I/libpersona( 6397): KNOX_SDCARD checking this for 10034
I/libpersona( 6397): KNOX_SDCARD not a persona
I/KLMS-2.5.183: ( 3578): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/SELinux ( 6397): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/KLMS-2.5.183: ( 3578): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3578): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3578): StateImplV2(): networkChangeListener().END
,I/SELinux ( 6397): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6397): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3578): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6397): TimaSignature is unavailable
,D/ActivityThread( 6397): Added TimaKeyStore provider
,I/SO_AGENT( 6397): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5839): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 6125): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,I/SA      ( 6125): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6125): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 6125): [SLFUCHKMGR] constructor called
,W/libprocessgroup( 1014): failed to open /acct/uid_10035/pid_4178/cgroup.procs: No such file or directory
,E/DBG_POLICYDM( 5839): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 6125): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6125): [OR] == isSIMCardReady false ==
,I/SA      ( 6125): [SCU] == networkStateCheck == false
I/SA      ( 6125): [OR] onReceive END
,I/ActivityManager( 1014): Killing 5431:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,V/DownloadManager( 1223): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1601): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1601): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1601): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1601): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1601): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1601): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1601): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6414): MountEmulatedStorage(),
E/Zygote  ( 6414): v2
I/ActivityManager( 1014): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6414 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/libpersona( 6414): KNOX_SDCARD checking this for 10125
I/libpersona( 6414): KNOX_SDCARD not a persona
,I/SELinux ( 6414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6414): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  307): Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 688us total 23.552ms
,D/TimaKeyStoreProvider( 6414): TimaSignature is unavailable
,D/ActivityThread( 6414): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 16.716ms
,W/ResourcesManager( 6414): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 17.769ms
W/ResourcesManager( 6414): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6414): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup( 1014): failed to open /acct/uid_10015/pid_5431/cgroup.procs: No such file or directory
,D/QuickConnect( 6414): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6414): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6414): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6429): MountEmulatedStorage()
,E/Zygote  ( 6429): v2
I/libpersona( 6429): KNOX_SDCARD checking this for 10145
I/SELinux ( 6429): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 6429): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6429 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 5331:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
I/SELinux ( 6429): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6429): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6429): TimaSignature is unavailable
,D/ActivityThread( 6429): Added TimaKeyStore provider
,W/ResourcesManager( 6429): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6429): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6429): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6429): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6429): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1014): failed to open /acct/uid_10035/pid_5331/cgroup.procs: No such file or directory
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/dhcpcd  ( 6340): wlan0: acknowledged 192.168.1.137 from 192.168.1.1
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/BadgeProvider( 5932): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/BadgeProvider( 5932): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5932): sendNotify, [notify] : null
D/BadgeProvider( 5932): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5932): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5932): update, [UpdateCount] : 1
D/Launcher.Model( 1488): reloadBadges entered.
,I/dhcpcd  ( 6340): wlan0: leased 192.168.1.137 for 86400 seconds,
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6456 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 6456): MountEmulatedStorage(),
E/Zygote  ( 6456): v2
I/libpersona( 6456): KNOX_SDCARD checking this for 1000,
I/libpersona( 6456): KNOX_SDCARD not a persona
,I/SELinux ( 6456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6456): TimaSignature is unavailable,
,D/ActivityThread( 6456): Added TimaKeyStore provider
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 62340(3MB) AllocSpace objects, 6(144KB) LOS objects, 33% free, 27MB/40MB, paused 2.998ms total 182.012ms,
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1014): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1014): Killing 5761:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31,
,D/SecurityLogAgent( 6456): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6456): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6456): StateMachine : Current State = 1
,D/SecurityLogAgent( 6456): StateMachine : Changed Current State = 1
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6490): MountEmulatedStorage()
I/ActivityManager( 1014): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6490 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6490): v2
I/libpersona( 6490): KNOX_SDCARD checking this for 10159
I/libpersona( 6490): KNOX_SDCARD not a persona
I/SELinux ( 6490): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1014): Killing 5807:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,I/SELinux ( 6490): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6490): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,E/WifiNative-wlan0( 1014): do suspend true
,D/TimaKeyStoreProvider( 6490): TimaSignature is unavailable
,D/ActivityThread( 6490): Added TimaKeyStore provider
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1014): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1014): VerifyingLinkState enter
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1014): callSECApiInt - ID [210]
,E/ConnectivityService( 1014): updateNetworkInfo()
,D/ConnectivityService( 1014): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1014): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1014): updateDnsLinkProperty: enter
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiWatchdogStateMachine.DnsPinger( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
,D/ConnectivityService( 1014): Adding Route [fe80::/64 -> :: wlan0] to network 503
,I/ActivityManager( 1014): Killing 5824:com.samsung.helphub/1000 (adj 15): empty #31
,E/WifiStateMachine( 1014): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1014): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1014): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1014): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1014): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 1014): LTETest block dns file not exists
,W/libprocessgroup( 1014): failed to open /acct/uid_10100/pid_5761/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10091/pid_5807/cgroup.procs: No such file or directory
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/WifiStateMachine( 1014): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1014): mBoosterFLAG : 0
I/WifiTrafficPoller( 1014): current booster mode : FullMode
,E/WifiStateMachine( 1014): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiNative-wlan0( 1014): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 1014): updateNetworkInfo()
E/ConnectivityService( 1014): updateNetworkInfo()
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1014): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1014): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 1000
,E/JavaBinder( 1014): !!! FAILED BINDER TRANSACTION !!!
,D/ConnectivityService( 1014):    accepting network in place of null
,D/WIFI    ( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/WIFI_P2P( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1459): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1459): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1014): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 1014): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/ActivityManager( 1014): Failed to clear dns cache for: com.samsung.helphub
,D/Tethering( 1014): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1014): MasterInitialState.processMessage what=3
D/ConnectivityService( 1014): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
V/NetworkStats( 1014): updateIfacesLocked()
,V/NetworkStats( 1014): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/ConnectivityService( 1014): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,V/NetworkStats( 1014): performPollLocked() took 4ms
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524290
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1179): EthernetConnected: false
,D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1179): updateDataNetType()
D/StatusBar.NetworkController( 1179): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1179): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1179): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1950): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1950): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6513): MountEmulatedStorage()
,E/Zygote  ( 6513): v2
I/libpersona( 6513): KNOX_SDCARD checking this for 10035
I/libpersona( 6513): KNOX_SDCARD not a persona
,I/SELinux ( 6513): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/SELinux ( 6513): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1014): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6513 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6513): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
I/System.out( 1014): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5824/cgroup.procs: No such file or directory
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6268): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6268): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6268): (HTTPLog)-Static: isShipBuild true
I/System.out( 6268): (HTTPLog)-Thread-1086-459425534: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6268): (HTTPLog)-Static: isSBSettingEnabled false
,D/TimaKeyStoreProvider( 6513): TimaSignature is unavailable
,D/EnterpriseController(  277): uids 10104
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10104
D/ActivityThread( 6513): Added TimaKeyStore provider
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 15:02:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453042953063], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453042953042]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Validated
,D/ConnectivityService( 1014): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1014): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1014): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1014): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524290
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1179): EthernetConnected: false
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1179): updateDataNetType()
D/StatusBar.NetworkController( 1179): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1179): updateLTEICONDataNetType:0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1179): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 6268): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
W/Kids    ( 1950): [AccountUtils] Account not ready
W/Kids    ( 1950): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1950): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1950): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1950): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1950): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1950): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1950): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1950): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1950): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1950): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1950): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1950): 	at java.lang.Thread.run(Thread.java:818)
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
,D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,E/SPPClientService( 6513): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6513): [PushClientApplication] Push log off : This is Ship build version
E/SPPClientService( 6513): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6513): [SystemStateMoniter] Current Time : 90731
,E/SPPClientService( 6513): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6513): PushLog.txt file is not deleted.
,D/SPPClientService( 6513): PushLog.txt file is not deleted.
D/SPPClientService( 6513): ============PushLog. stop!
,I/Babel   ( 6268): connection state changed from UNKNOWN to CONNECTED
,E/Zygote  ( 6532): MountEmulatedStorage(),
E/Zygote  ( 6532): v2
I/libpersona( 6532): KNOX_SDCARD checking this for 10113
I/libpersona( 6532): KNOX_SDCARD not a persona
,I/SELinux ( 6532): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6532): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1014): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6532 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6532): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 5446:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 6513): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 6532): TimaSignature is unavailable
,D/ActivityThread( 6532): Added TimaKeyStore provider
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ActivityManager( 1014): Killing 5877:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10032/pid_5446/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10152/pid_5877/cgroup.procs: No such file or directory
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6532): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6532): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6532): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6532):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6532):   adb logcat -s GAv4
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6532): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6532): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6532): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6532): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6532): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3035): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 6312): type=WIFI subType= reason=null isConnected=true
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6570): MountEmulatedStorage()
E/Zygote  ( 6570): v2
I/libpersona( 6570): KNOX_SDCARD checking this for 10075
I/libpersona( 6570): KNOX_SDCARD not a persona
I/SELinux ( 6570): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6570): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6570): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6570 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 6570): TimaSignature is unavailable
,D/ActivityThread( 6570): Added TimaKeyStore provider
,I/WebViewFactory( 6532): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/LibraryLoader( 6532): Time to load native libraries: 1 ms (timestamps 1173-1174)
I/LibraryLoader( 6532): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6532): Binding Chromium to main looper Looper (main, tid 1) {f94dc29}
,I/LibraryLoader( 6532): Expected native library version number "",actual native library version number ""
I/chromium( 6532): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6532): Initializing chromium process, singleProcess=true
,W/art     ( 6532): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6532): ApplicationContext is null in ApplicationStatus
,W/chromium( 6532): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6532): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6532): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6532): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6532): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6532): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6532): Local Branch: 
I/Adreno-EGL( 6532): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6532): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6532):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6532): Requires BLUETOOTH permission
,I/NSApplication( 6532): Starting up...
,E/SMD     (  287): DCD OFF
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6603): MountEmulatedStorage(),
E/Zygote  ( 6603): v2
I/libpersona( 6603): KNOX_SDCARD checking this for 10081
I/libpersona( 6603): KNOX_SDCARD not a persona
,I/SELinux ( 6603): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6603): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6603): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6603 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 5512:com.android.vending/u0a28 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 5898:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #32
,D/TimaKeyStoreProvider( 6603): TimaSignature is unavailable
,D/ActivityThread( 6603): Added TimaKeyStore provider
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/GAV2    ( 6570): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BooksApp( 6570): Created application version: 3.6.9 (30609)
,W/libprocessgroup( 1014): failed to open /acct/uid_10156/pid_5898/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10028/pid_5512/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 6218): notifyNetworkActivated
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1014): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/ContextImpl( 6218): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 6570): Starting books sync for 61035162, extras: ade
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6218): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6218): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6218): exit::IDLE
D/InitializeManagerStateMachine( 6218): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6218): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6218): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6218): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6218): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6218): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6218): entry::SUCCESS
D/hcjo    ( 6218): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3530): Starting #10
,D/hcjo    ( 6218): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6218): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/Hs20UtilService( 3530): Message received 5007
,D/InitializeManagerStateMachine( 6218): exit::SUCCESS
D/InitializeManagerStateMachine( 6218): entry::IDLE
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1322): MountReceiver.onReceive - Keep current state
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3530): Starting #11
,I/Hs20UtilService( 3530): Message received 5007
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1322): MountReceiver.onReceive - Keep current state
,E/SQLiteLog( 6570): (284) automatic index on view_volumes(volume_id)
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3530): Starting #12
D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 3530): Message received 5007
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1322): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3530): Starting #13
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1322): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3530): Message received 5007
,D/WifiStateMachine( 1014): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1014): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5794): SPPPushClient is installed : true
,I/BooksConfig( 6570): GmsCore Version = 7.8.99 (2134222-436)
,I/PCWCLIENTTRACE_PushUtil( 5794): sales region : global,
I/PCWCLIENTTRACE_PushUtil( 5794): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5794): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1014): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
I/splitIntent( 1014): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1014): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6312): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  256): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1014): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,D/SRIB_DCS( 1179): log_dcs ThreadedRenderer::initialize entered! 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 6366): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6366): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6366): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6366): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/GCM     ( 1674): Connected
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,D/GCM     ( 1674): Message class com.google.f.a.a.p
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/FOTA_Client( 6381): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,E/BooksAccountManager( 6570): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,W/FOTA_Client( 6381): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksSync( 6570): Soft error
E/BooksSync( 6570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6570): Sync error
E/BooksSync( 6570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6570): Finished books sync
,I/KLMS-2.5.183: ( 3578): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Jan 17 16:02:34 GMT+01:00 2016
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3578): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3578): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3578): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3578): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/SyncManager( 1014): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 63635, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/KLMS-2.5.183: ( 3578): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/ActivityManager( 1014): Killing 5770:com.android.mms/u0a46 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3578): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3578): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3578): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3578): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.183: ( 3578): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3578): StateImplV2(): networkChangeListener().END
,I/DBG_POLICYDM( 5839): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.183: ( 3578): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5839): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 6125): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6125): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6125): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
,E/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 6125): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6125): [OR] == isSIMCardReady false ==
,I/SA      ( 6125): [SCU] == networkStateCheck == true
I/SA      ( 6125): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6125): isChinaCountryCode : false
I/SA      ( 6125): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6125): [OR] == networkStateCheck true ==
,I/SA      ( 6125): [OR] GetMyCountryZoneTask
I/SA      ( 6125): [OR] onReceive END
,I/SA      ( 6125): [SRS] prepareGetMyCountryZone
,I/ActivityManager( 1014): Killing 5949:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,V/DownloadManager( 1223): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/CountryDetector( 1014): No listener is left
,W/libprocessgroup( 1014): failed to kill pid 5770: No such process
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/accuweather( 1601): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 6125): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6125): [SSP] query invoked
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1601): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
I/DBG_POLICYDM( 5839): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,D/accuweather( 1601): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1601): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1601): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/SecContentProvider2( 1014): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1014): mCursor = null
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,D/accuweather( 1601): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
D/accuweather( 1601): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SA      ( 6125): [TPMU] GetMccFromDB : null
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,D/QuickConnect( 6414): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6414): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6414): PeriphStartReceiver.onReceive - no need to start
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5839): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/SA      ( 6125): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6125): [TPM] isNoProxy(default) : true
,E/DBG_POLICYDM( 5839): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/SecurityLogAgent( 6456): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6456): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6456): StateMachine : Current State = 1
,D/SecurityLogAgent( 6456): StateMachine : Changed Current State = 1
,I/DBG_POLICYDM( 5839): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
E/File    ( 6125): fail readDirectory() errno=2
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1014): reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1014): Tagging socket 361 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
,W/libprocessgroup( 1014): failed to open /acct/uid_10046/pid_5770/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10047/pid_5949/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,I/qtaguid ( 1014): Untagging socket 361
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 15:02:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453042954663], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453042954642]}
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Don't send network conditions - lacking user consent.
,D/ConnectivityService( 1014): Validated NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Validated
D/ConnectivityService( 1014): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1014): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,D/ConnectivityService( 1014): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524290
,D/ChimeraCfgMgr( 1950): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1950): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6513): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6513): [SystemStateMoniter] Current Time : 92300
,E/SPPClientService( 6513): [SystemStateMoniter] No Connect : false
,I/System.out( 6268): (HTTPLog)-Static: isSBSettingEnabled false
,I/jxcore-log( 6023): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6023): 
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 39558(2MB) AllocSpace objects, 5(120KB) LOS objects, 33% free, 27MB/40MB, paused 2.663ms total 147.907ms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6218): AutoUpdateManager:IDLE:execute
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/InitializeManagerStateMachine( 6218): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6218): exit::IDLE
D/InitializeManagerStateMachine( 6218): entry::NETWORK_CHECK
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/InitializeManagerStateMachine( 6218): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6218): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6218): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6218): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6218): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6218): entry::SUCCESS
D/hcjo    ( 6218): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6218): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6218): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6218): exit::SUCCESS
D/InitializeManagerStateMachine( 6218): entry::IDLE
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 1950): [AccountUtils] Account not ready
W/Kids    ( 1950): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1950): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1950): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1950): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1950): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1950): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1950): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1950): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1950): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1950): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1950): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1950): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
,D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
,D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/SA      ( 6125): [RC New] Execute method=[GET] start
,I/SA      ( 6125): [RC New] Security=[true]
,I/System.out( 6125): Thread-1055(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6125): Thread-1055(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6125): Thread-1055(ApacheHTTPLog):isShipBuild true
I/System.out( 6125): Thread-1055(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6125): Thread-1055(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10041
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10041
,I/jxcore-log( 6023): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6023): 
,I/jxcore-log( 6023): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6023): 
,I/jxcore-log( 6023): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6023): 
,I/jxcore-log( 6023): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6023): 
,I/jxcore-log( 6023): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6023): 
,I/jxcore-log( 6023): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6023): 
,I/SA      ( 6125): [RC New] [v2liruge] api execute + 636
,I/SA      ( 6125): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6125): AsyncTask #1 calls detatch()
,I/SA      ( 6125): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6125): [OCP] update openData : PL
,I/SA      ( 6125): [TPMU] getNetworkMcc : 
,I/SA      ( 6125): [SCU] saveMccToPreferece Start
,I/SA      ( 6125): [SCU] RegionMCC : 260
I/SA      ( 6125): [SSP] query invoked
,I/SA      ( 6125): [TPMU] GetMccFromDB : null
,I/SA      ( 6125): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6125): [SCU] saveMccToPreferece End
,I/SA      ( 6125): [RC New] executeRequest [v2liruge] end. 688
I/SA      ( 6125): [RC New] Execute end
,I/SA      ( 6125): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6125): [OR] GetMyCountryZoneTask Success
,D/PackageManager( 1014): [MSG] MCS_UNBIND
,I/ActivityManager( 1014): Killing 5986:com.wsomacp/u0a25 (adj 15): empty #31
,I/dhcpcd  ( 6340): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6340): wlan0: sendmsg: Cannot assign requested address
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/PowerManagerService( 1014): [PWL] Off : 15s ago
,I/PowerManagerService( 1014): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1014): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1014): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1950, ws=null) (elapsedTime=57856)
,W/libprocessgroup( 1014): failed to open /acct/uid_10025/pid_5986/cgroup.procs: No such file or directory
,D/ConnectivityService( 1014): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524295
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524295
,I/jxcore-log( 6023): Test app app.js loaded
I/jxcore-log( 6023): 
,I/chromium( 6023): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4476): callingUid 10012, callindPid: 4476
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,I/MusicLeanback( 6312): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6312): Stop autocaching.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/GmsUtils( 6312): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6312): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  256): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  256): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1014): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1014) eventTime = 95324
,D/PowerManagerService( 1014): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014 (0x0)
,D/PowerManagerService( 1014): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1014, ws=WorkSource{10054}) (elapsedTime=3473)
,D/GCM     ( 1674): Connected
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1674): Message class com.google.f.a.a.p
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4255, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6570): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5794): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5794): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5794): [GetString-S]
,I/ReactiveServiceManager( 5794): Supported : 1
,D/QSEECOMAPI: ( 1014): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1014): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1014): Loaded image: APP id = 12
,D/QSEECOMAPI: ( 1014): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1014): QSEECom_shutdown_app, app_id = 12
,E/terrier ( 1014): handleString: Failed to handle string(-4)
E/terrier ( 1014): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5794): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5794): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5794): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5794): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5794): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5794): [ensureRegistration] - No Samsung account
,E/SMD     (  287): DCD OFF
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{25508620 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/dhcpcd  ( 6340): wlan0: sending IPv6 Router Solicitation
,D/SSRM:n  ( 1014): SIOP:: AP = 370
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
,I/dhcpcd  ( 6340): wlan0: sending IPv6 Router Solicitation,
I/dhcpcd  ( 6340): wlan0: no IPv6 Routers available
,E/Zygote  ( 6683): MountEmulatedStorage(),
,E/Zygote  ( 6683): v2
I/libpersona( 6683): KNOX_SDCARD checking this for 10028
,I/libpersona( 6683): KNOX_SDCARD not a persona
,I/SELinux ( 6683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1014): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6683 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 6683): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6683): TimaSignature is unavailable
,D/ActivityThread( 6683): Added TimaKeyStore provider
,D/Finsky  ( 6683): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6218): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6218): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6218): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6218): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6218): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6218): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6218): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6218): entry::IDLE
,D/Finsky  ( 6683): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/Settings( 6683): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6683): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 6683): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6683): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6683): [1142] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
D/Finsky  ( 6683): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6683): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6683): [1142] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/ActivityManager( 1014): Killing 6039:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,I/art     ( 1674): Explicit concurrent mark sweep GC freed 19315(1053KB) AllocSpace objects, 8(288KB) LOS objects, 39% free, 10MB/17MB, paused 1.312ms total 53.317ms
,V/Finsky  ( 6683): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/libprocessgroup( 1014): failed to open /acct/uid_10053/pid_6039/cgroup.procs: No such file or directory,
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6218): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6218): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6218): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6218): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 6218): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6218): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6218): entry::IDLE
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0,
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6683): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6683): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6683): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6683): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6683): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6683): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6683): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6683): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6683): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6683): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1743): client connected with version: 7571000
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4272, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 3
,V/AlarmManager( 1014): waitForAlarm result :4
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1014): SIOP:: AP = 330
,I/PowerManagerService( 1014): [PWL] Off : 30s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/FactoryTest( 5597): Not factory mode
,D/FactoryTest( 5597): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5597): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 5597): still no open session command from host, so toast
,W/ContextImpl( 5597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,I/Timeline( 5597): Timeline: Activity_launch_request id:com.android.settings time:117189
W/ContextImpl( 5597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1014): mDVFSHelper.acquire(),
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 6023
,E/MTPRx   ( 5597): started activity for popup
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5597): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5597): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5597): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5597): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5597): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5597): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5597): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1014): Focused application set to: xxxx
,D/InputDispatcher( 1014): Focus entered window: 6023
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1014): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@277475bc attribute=null, token = android.os.BinderProxy@2df2a788
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SettingsReceiverActivity( 5597): dev.kiessupport is : TRUE
,D/PhoneWindow( 5597): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5597): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,V/ActivityThread( 6023): updateVisibility : ActivityRecord{1161a19e token=android.os.BinderProxy@11ac8e20 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6023): Timeline: Activity_idle id: android.os.BinderProxy@11ac8e20 time:117379
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,V/AlarmManager( 1014): waitForAlarm result :8
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 320
,W/ActivityManager( 1014): mDVFSHelper.release()
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,V/AlarmManager( 1014): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1014): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1014): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 33000(1710KB) AllocSpace objects, 15(260KB) LOS objects, 33% free, 27MB/40MB, paused 2.520ms total 161.577ms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6683): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6683): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6683): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4278, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1014): SIOP:: AP = 310
,I/PowerManagerService( 1014): [PWL] Off : 50s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 4
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 300
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager( 1014): waitForAlarm result :4
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6683): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6683): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6683): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4281, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 300
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6570): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6570): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6570): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6570): Soft error
E/BooksSync( 6570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6570): Sync error
E/BooksSync( 6570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6570): Finished books sync
,D/SyncManager( 1014): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 123727, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1014): mCursor = null
,I/PowerManagerService( 1014): [PWL] Off : 75s ago
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 300
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/Finsky  ( 6683): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6683): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6683): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 5
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1,
D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1014): [PWL] Off : 105s ago
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6683): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6683): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6683): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1014): !@Sync 6
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1674): Vacuum at: now=1453043066974 tag=VacuumService
,I/GoogleURLConnFactory( 1674): Using platform SSLCertificateSocketFactory
,W/Uploader( 1674): No account for auth token provided
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1674): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1674): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1674): (HTTPLog)-Static: isShipBuild true
I/System.out( 1674): (HTTPLog)-Thread-198-779198564: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1674): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1674): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1674): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1674, getuid(): 10012
,I/qtaguid ( 1674): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1674, getuid(): 10012
,W/Uploader( 1674): No account for auth token provided
,I/System.out( 1674): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1674): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1674, getuid(): 10012
,W/Uploader( 1674): No account for auth token provided
,I/System.out( 1674): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1674): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1674, getuid(): 10012
,W/Uploader( 1674):  no longer exists, so no auth token.
,I/System.out( 1674): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1674): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1674, getuid(): 10012
,W/Uploader( 1674): No account for auth token provided
,I/System.out( 1674): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1674): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1674, getuid(): 10012
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
,E/Uploader( 1674): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1674): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1674): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1674): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
,D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1674): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1674): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1674, getuid(): 10012
D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6570): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6570): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6570): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6570): Soft error
E/BooksSync( 6570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6570): Sync error
E/BooksSync( 6570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6570): Finished books sync
,D/SyncManager( 1014): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 215506, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1014): mCursor = null
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,I/PowerManagerService( 1014): [PWL] Off : 140s ago
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4285, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/Watchdog( 1014): !@Sync 7
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,V/AlarmManager( 1014): waitForAlarm result :8
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1014): !@Sync 8
,I/PowerManagerService( 1014): [PWL] Off : 180s ago
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4285, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1014): stay LED for charging
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 290,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 9,
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1014): waitForAlarm result :8
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 225s ago
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4285, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
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
,D/QSEECOMAPI: ( 1014): Loaded image: APP id = 13
,I/TZ: qc_tlc_communication( 1014): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1014): Trustlet response is completed
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1014): !@Sync 10
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/jxcore-log( 6023): --= Surplus to requirements =--
I/jxcore-log( 6023): 
,I/jxcore-log( 6023): ****TEST TOOK:  ms ****
I/jxcore-log( 6023): 
I/jxcore-log( 6023): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6023): 
,D/AndroidRuntime( 6853): 
D/AndroidRuntime( 6853): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6853): CheckJNI is OFF
D/AndroidRuntime( 6853): readGMSProperty: start
D/AndroidRuntime( 6853): readGMSProperty: already setted!!
D/AndroidRuntime( 6853): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6853): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6853): readGMSProperty: end
D/AndroidRuntime( 6853): addProductProperty: start
,E/AffinityControl( 6853): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6853): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 1014): START PACKAGE DELETE: observer{298592064}
D/PackageManager( 1014): pkg{<packageName>}
D/PackageManager( 1014): user{0}
D/PackageManager( 1014): caller{2000}
D/PackageManager( 1014): flags{3}
,D/PersonaManagerService( 1014): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager( 1014): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1014): !@killApplicatoin: 10174, uninstall pkg
,I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10174 user=-1: uninstall pkg
,I/ActivityManager( 1014): Killing 6023:com.test.thalitest/u0a174 (adj 0): stop com.test.thalitest cause uninstall pkg
,I/WindowState( 1014): WIN DEATH: Window{1a8cf521 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (6/8)
,I/ActivityManager( 1014):   Force finishing activity ActivityRecord{26c9d45e u0 com.test.thalitest/.MainActivity t234}
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (-2/8)
D/InputDispatcher( 1014): Focus left window: 6023
I/SurfaceFlinger(  256): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
W/ActivityManager( 1014): mDVFSHelper.acquire()
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1014): Spurious death for ProcessRecord{23626679 6023:com.test.thalitest/u0a174}, curProc for 6023: null
,I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10174 user=0: pkg removed
,I/ActivityManager( 1014):   Force finishing activity ActivityRecord{26c9d45e u0 com.test.thalitest/.MainActivity t234 f}
W/ActivityManager( 1014): Duplicate finish request for ActivityRecord{26c9d45e u0 com.test.thalitest/.MainActivity t234 f}
,W/ActivityManager( 1014): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 5101): Explicit concurrent mark sweep GC freed 2371(132KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 772us total 26.741ms
,I/art     ( 6196): Explicit concurrent mark sweep GC freed 359(25KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 882us total 32.728ms
,I/DBG_DM  ( 3035): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
D/InputDispatcher( 1014): Focused application released
,I/DBG_DM  ( 3035): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 13
,I/DBG_DM  ( 3035): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 3035): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3035): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 13
,E/SamsungIME( 1761): mOCRHelper is null
,I/DBG_DM  ( 3035): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,W/GeofencerStateMachine( 1743): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.183: ( 3578): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Jan 17 16:06:30 GMT+01:00 2016
,I/DBG_DM  ( 3035): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/RegisteredComponentCache( 1441): Collect Tech packages for Knox
,D/PersonaManager( 1441): isKioskContainerExistOnDevice
,I/DBG_DM  ( 3035): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3035): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/KLMS-2.5.183: ( 3578): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1014): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
,I/splitIntent( 1014): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
,I/splitIntent( 1014): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,I/KLMS-2.5.183: ( 3578): KLMSIntentService(): onCreate()
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3578): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/SMD     (  287): DCD OFF
I/DBG_DM  ( 3035): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 13
E/Zygote  ( 6866): MountEmulatedStorage()
,E/Zygote  ( 6866): v2
I/libpersona( 6866): KNOX_SDCARD checking this for 10094
I/libpersona( 6866): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3035): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0,
,I/SELinux ( 6866): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/KLMS-2.5.183: ( 3578): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/ActivityManager( 1014): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6866 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.183: ( 3578): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/DBG_DM  ( 3035): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
I/DBG_DM  ( 3035): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
I/SELinux ( 6866): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/DBG_DM  ( 3035): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
E/SELinux ( 6866): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3035): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
I/KLMS-2.5.183: ( 3578): KLMSIntentService(): PACKAGE_REMOVED
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,I/DBG_DM  ( 3035): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/KLMS-2.5.183: ( 3578): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.183: ( 3578): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/SurfaceFlinger(  256): id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1014): mCursor = null
,D/InputDispatcher( 1014): Focus entered window: 3035
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 58167(4MB) AllocSpace objects, 89(1485KB) LOS objects, 33% free, 27MB/41MB, paused 3.122ms total 189.131ms
,I/art     ( 1014): WaitForGcToComplete blocked for 105.385ms for cause Explicit
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3035): log_dcs ThreadedRenderer::initialize entered! 
,V/ActivityThread( 3035): updateVisibility : ActivityRecord{46caec7 token=android.os.BinderProxy@399ea06a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/TimaKeyStoreProvider( 6866): TimaSignature is unavailable
,D/ActivityThread( 6866): Added TimaKeyStore provider
,D/PersonaManager( 1441): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1441): empty dynamic service
,W/ActivityManager( 1014): mDVFSHelper.release()
I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{1c22192b u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t233} time:328533
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1014): Got RemoteException sending setActive(false) notification to pid 6023 uid 10174
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 3035): Timeline: Activity_idle id: android.os.BinderProxy@399ea06a time:328555
,D/SamsungIME( 1761): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/EnterpriseDeviceManagerService( 1014): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1014): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1014): no available spell checker services found
,D/elm:15183( 6866): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 6866): ELMEngine.ELMEngine( context ).
,D/elm:15183( 6866): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 6866): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.183: ( 3578): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15183( 6866): ElmAgentService : onCreate()
,D/elm:15183( 6866): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 6866): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6866): MDMBridge.getInstance()
D/elm:15183( 6866): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15183( 6866): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.183: ( 3578): KLMSIntentService(): onDestroy()
,D/elm:15183( 6866): ElmAgentService : onDestroy().
,I/ActivityManager( 1014): Killing 6062:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 11185(603KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 3.001ms total 174.275ms
,I/art     ( 1014): WaitForGcToComplete blocked for 348.398ms for cause Explicit
,W/ResourceType( 1014): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1014): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1014): PackageReceiver onReceive()
,I/HarmonyEASService( 1014): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1014): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/OTPFW   ( 1014): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1014): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1014): DBIntegrity::getInstance - New instance created
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/OTPFW   ( 1014): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10174 container id = 0
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/OTPFW   ( 1014): ProvisionData::getAllEntries Enter
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1014): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1014): onPackageRemoved : com.test.thalitest
E/OTPFW   ( 1014): ProvisionData::getAllEntries Table is empty
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_6062/cgroup.procs: No such file or directory
,D/BackupManagerService( 1014): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1014): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10174
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10174
,V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
,D/TaskPersister( 1014): removeObsoleteFile: deleting file=234_task.xml
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
D/TaskPersister( 1014): removeObsoleteFile: deleting file=233_task.xml
,D/PanelView( 1179): There is/are notification(s) 
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,D/SSRM:aZ ( 1014): MSG_TYPE_APP_REMOVED::
,W/art     ( 1014): Suspending all threads took: 5.621ms,
,I/PCWCLIENTTRACE_PushUtil( 5794): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5794): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5794): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5794): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 9669(485KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 20.583ms total 203.080ms
,E/Zygote  ( 6887): MountEmulatedStorage()
E/Zygote  ( 6887): v2
I/libpersona( 6887): KNOX_SDCARD checking this for 10032
I/libpersona( 6887): KNOX_SDCARD not a persona
I/SELinux ( 6887): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/ActivityManager( 1014): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6887 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,I/SELinux ( 6887): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,E/SELinux ( 6887): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6887): TimaSignature is unavailable
,D/ActivityThread( 6887): Added TimaKeyStore provider
,D/PackageManager( 1014): delete codoeFile: 
,D/AASAuninstall( 1014): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.test.thalitest
I/AASA_removePackage( 1014): UID=10174 Target=com.test.thalitest
,D/PackageManager( 1014): result of delete: 1{298592064}
,D/AndroidRuntime( 6853): Shutting down VM
,I/FeatureConfig( 6887): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/SA      ( 6125): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6125): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10174 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1014): Killing 6081:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ResourcesManager( 6887): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6887): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6887): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6887): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 6905): MountEmulatedStorage()
E/Zygote  ( 6905): v2
I/libpersona( 6905): KNOX_SDCARD checking this for 10044
I/libpersona( 6905): KNOX_SDCARD not a persona
,I/SELinux ( 6905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1014): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6905 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6887): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/SELinux ( 6905): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6887): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6887): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  307): Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 23.530ms
W/ResourcesManager( 6887): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6905): TimaSignature is unavailable
,D/ActivityThread( 6905): Added TimaKeyStore provider
,W/ResourcesManager( 6887): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 16.958ms
,W/ResourcesManager( 6887): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6905): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6905): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6905): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6905): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 16.893ms
W/ResourcesManager( 6905): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6905): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6905): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6905): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6887): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_6081/cgroup.procs: No such file or directory
,W/ResourcesManager( 6887): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6887): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 6887): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6887): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6887): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/GalaxyFinderApplication( 6887): system/finder_cp/cpdata.xml file not found
,W/art     ( 6853): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/NearbySource( 6905): Nearby Source Create!
,D/NearbyContext( 6905): Nearby Context Create!
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/,
W/ContextImpl( 6905): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
D/SLinkSource( 6905): Samsung link source created
,D/ContactProvider( 6905): getAllContactInfoList Start
,W/FileUtils( 6905): Failed to chmod(/data/data/com.sec.android.gallery3d/databases/local.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PackagesMonitor( 6905): PackagesMonitor onReceive :com.test.thalitest
,E/SharedPreferencesImpl( 6905): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6926): MountEmulatedStorage()
E/Zygote  ( 6926): v2
I/libpersona( 6926): KNOX_SDCARD checking this for 10046
I/libpersona( 6926): KNOX_SDCARD not a persona
,I/SELinux ( 6926): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6926): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6926): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6926 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 6105:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6926): TimaSignature is unavailable
,D/ActivityThread( 6926): Added TimaKeyStore provider
,D/ContactProvider( 6905): getAllContactInfoList End
,I/syncContacts( 6905): thread: 1163, sync time = 89
,W/ResourcesManager( 6926): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6926): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6926): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6926): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6926): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6926): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.

```
