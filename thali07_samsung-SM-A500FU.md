#### Test 55431344148e3f8_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Mms/Contact( 5813): [end]    init consume time = 19.327031
D/TP/MmsSmsProvider( 1473): query,matched:13, calling pid = 5813
D/TP/MmsSmsProvider( 1473): match 13:Elapsed time : 3.560 ms
D/Mms/ArtClassLoader( 5813): init [DONE] art
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/DraftCache( 5813): [start]    rebuildCache consume time = 10.924896
--------- beginning of system
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1473): query,matched:12, calling pid = 5813
D/Mms/MethodReflector( 5813): getSubId is called
D/Mms/TelephonyUtils( 5813): getLongSubId from simSlot 0, return Value = -1
D/TP/MmsSmsProvider( 1473): match 12:Elapsed time : 2.010 ms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/Mms/MethodReflector( 5813): getTelephonyProperty is called
D/Mms/DownloadManager( 5813): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5813): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5813): auto download without roaming -> true
D/Mms/DownloadManager( 5813): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5813): getSubId is called
D/Mms/MethodReflector( 5813): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5813): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5813): getLongSubId from simSlot 1, return Value = -1000
D/Mms/DraftCache( 5813): [end]    rebuildCache consume time = 13.662448
D/Mms/MethodReflector( 5813): getTelephonyProperty is called
D/Mms/DownloadManager( 5813): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5813): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5813): auto download without roaming -> true
D/Mms/DownloadManager( 5813): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5813): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5813): mAutoDownload ------> true
D/ComposerPerformance( 5813): 1452246472663 ms / [DONE] Composer constructor
E/CII     ( 5813): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5813): ReservationManager()
D/Mms/Conversation( 5813): [start]    init() consume time = 8.77125
I/Mms/ReservationManager( 5813): resetAfterConnected()
D/TP/MmsSmsProvider( 1473): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1473): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1473): updateThread(), thread_id = 9223372036854775807
D/TP/MmsSmsProvider( 1473): query,matched:7, calling pid = 5813
V/TP/MmsSmsDatabaseHelper( 1473): sUpgradeVersion = 0, db.getVersion() = 81
D/TP/MmsSmsProvider( 1473): match 7:Elapsed time : 1.380 ms
D/TP/MmsSmsProvider( 1473): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1473): need read changed broadcast:false
D/Mms/Conversation( 5813): [end]    init consume time = 11.676875
I/DBG_POLICYDM( 5877): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
D/Mms/MessagingNotification( 5813): [start]    init() consume time = 4.982865
D/Mms/MessagingNotification( 5813): [end]    init consume time = 2.358854
I/Mms/ReservationManager( 5813): getReservedSendMessageCount(): retMessageCount=0
D/Mms/MmsApp( 5813): [end]    onCreate() consume time = 6.020573
D/TP/MmsSmsProvider( 1473): query,matched:0, calling pid = 5813
V/TP/MmsSmsProvider( 1473): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1473): match 0:Elapsed time : 1.780 ms
I/DBG_POLICYDM( 5877): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
D/Mms/Synchronizer( 5813): [start]    doSync consume time = 7.873906
D/TP/MmsSmsProvider( 1473): update, matched:300, calling pid = 5813
V/TP/MmsSmsProvider( 1473): syncDBData start
V/TP/MmsSmsProvider( 1473): syncDBData sms end
D/Mms/SpamFilter( 5813): [start]    SpamFilter fill() begin consume time = 1.880885
V/TP/MmsSmsProvider( 1473): syncDBData mms end
V/TP/MmsSmsProvider( 1473): syncDBData end
D/Mms/Synchronizer( 5813): [end]    doSync consume time = 1.618386
D/TP/MmsSmsProvider( 1473): query,matched:400, calling pid = 5813
I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 5877): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/Mms/DownloadManager( 5813): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5813): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5813): getSubId is called
D/Mms/TelephonyUtils( 5813): getLongSubId from simSlot 0, return Value = -1
E/Zygote  ( 5972): MountEmulatedStorage()
E/Zygote  ( 5972): v2
I/libpersona( 5972): KNOX_SDCARD checking this for 10072
I/libpersona( 5972): KNOX_SDCARD not a persona
I/SELinux ( 5972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/Mms/MethodReflector( 5813): getTelephonyProperty is called
I/ActivityManager( 1013): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5972 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/Mms/DownloadManager( 5813): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5813): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5813): auto download without roaming -> true
D/Mms/DownloadManager( 5813): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5813): mAutoDownload ------> true,
I/SELinux ( 5972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5972): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/Mms/SpamFilter( 5813): [end]    SpamFilter fill() finished consume time = 20.435833
I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
D/TimaKeyStoreProvider( 5972): TimaSignature is unavailable
D/ActivityThread( 5972): Added TimaKeyStore provider
I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
D/Mms/FreeMessageStatusReceiver( 5813): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
E/Zygote  ( 5989): MountEmulatedStorage()
E/Zygote  ( 5989): v2
I/libpersona( 5989): KNOX_SDCARD checking this for 10047
I/libpersona( 5989): KNOX_SDCARD not a persona
I/SELinux ( 5989): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5989 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
I/SELinux ( 5989): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/DBG_POLICYDM( 5877): [com.policydm.XSPPReceiver(53/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/SELinux ( 5989): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
E/Zygote  ( 5999): MountEmulatedStorage()
I/libpersona( 5999): KNOX_SDCARD checking this for 10038
E/Zygote  ( 5999): v2
I/libpersona( 5999): KNOX_SDCARD not a persona
I/SELinux ( 5999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5999 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 5999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Killing 5350:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
D/BadgeProvider( 5972): onCreate
D/BadgeProvider( 5972): DatabaseHelper
E/SELinux ( 5999): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5989): TimaSignature is unavailable
D/ActivityThread( 5989): Added TimaKeyStore provider
D/Mms/MessagingNotification( 5813): checkBadgeCount unreadCount=0 badgeCount=0
D/Mms/FreeMessageReceiverService( 5813): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5813): onHandleIntent: ACTION_PACKAGE_ADDED
I/ActivityManager( 1013): Killing 5228:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 5999): TimaSignature is unavailable
W/ResourcesManager( 5989): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5989): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5989): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 1013): Killing 3712:com.android.providers.calendar/u0a42 (adj 15): empty #31
D/ActivityThread( 5999): Added TimaKeyStore provider
D/TP/SmsProvider( 1473): query,matched:26, calling pid = 5813
D/TP/SmsProvider( 1473): match 26:Elapsed time : 3.935 ms
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ConfigFetchService( 1981): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1981): launchTask
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1473): query,matched:6, calling pid = 5813
D/TP/MmsSmsProvider( 1473): match 6:Elapsed time : 0.876 ms
D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1981): Module APK com.google.android.play.games already loaded
W/ResourcesManager( 5999): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5999): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5877): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/DBG_POLICYDM( 5877): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 5877): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
V/ConfigFetchTask( 1981): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1X3wtX3bDakR4ZE8tkvokKBccA1GCRpqINdSzLvqu5tHuIH0nyZuZRql44yQIw6gE5U9rV1tix03mze5Vlhqg1oUQOQYVMBrpeJ7OfYmTZrcTZQFmFyqRGvfQFm-bIZeQZUE3pAIarp6Vym_DyUgrZcKdsEO97Pp-8nuxZbIkFo1tvNJXwYS58HSdKt4rsY5uj-CFMQ
I/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
E/Zygote  ( 6029): MountEmulatedStorage()
E/Zygote  ( 6029): v2
I/libpersona( 6029): KNOX_SDCARD checking this for 10025
I/libpersona( 6029): KNOX_SDCARD not a persona
I/SELinux ( 6029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6029 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/SELinux ( 6029): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
I/PeopleContactsSync( 1981): CP2 sync disabled
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/AndroidRuntime( 5995): 
D/AndroidRuntime( 5995): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5995): CheckJNI is OFF
D/AndroidRuntime( 5995): readGMSProperty: start
D/Vision  ( 1981): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/AndroidRuntime( 5995): readGMSProperty: already setted!!
D/AndroidRuntime( 5995): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5995): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5995): readGMSProperty: end
D/AndroidRuntime( 5995): addProductProperty: start
D/Vision  ( 1981): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1981): No vision deps
I/GoogleURLConnFactory( 1981): Using platform SSLCertificateSocketFactory
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 6029): TimaSignature is unavailable
D/ActivityThread( 6029): Added TimaKeyStore provider
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
I/DBG_POLICYDM( 5877): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/ActivityManager( 1013): Killing 4003:com.google.android.talk/u0a104 (adj 15): empty #31
I/DBG_POLICYDM( 5877): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
W/ResourcesManager( 6029): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5877): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5877): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 5877): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 5877): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5877): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 5877): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
I/DBG_POLICYDM( 5877): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 5877): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
W/libprocessgroup( 1013): failed to open /acct/uid_10035/pid_5350/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10042/pid_3712/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 5877): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/01/11/16:11:56
I/DBG_POLICYDM( 5877): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/01/08/10:47:53
I/DBG_POLICYDM( 5877): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
D/MyFiles ( 5989): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager( 1013): Killing 5507:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
I/OMACP   ( 6029): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/Mms/Omacp( 5813): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/OMACP   ( 6029): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 6029): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 6029): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 6029): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 6029): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 6029): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 6029): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 6029): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 6029): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 6029): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 6029): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 6029): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 6029): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5228/cgroup.procs: No such file or directory
I/System.out( 1981): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1981): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1981): (HTTPLog)-Static: isShipBuild true
I/System.out( 1981): (HTTPLog)-Thread-277-795147645: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1981): (HTTPLog)-Static: isSBSettingEnabled false
W/libprocessgroup( 1013): failed to open /acct/uid_10069/pid_5507/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10104/pid_4003/cgroup.procs: No such file or directory
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
I/DBG_POLICYDM( 5877): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
I/GAv4    ( 5840): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5840):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5840):   adb logcat -s GAv4
I/TactileAssist( 1013): enable value -1
I/TactileAssist( 1013): internal enable value -1
I/TactileAssist( 1013): intensity value -1
I/TactileAssist( 1013): saveAppList value true
I/TactileAssist( 1013): List of disabled apps :
I/System.out( 1981): KnoxVpnUidStorageknoxVpnSupported API value returned is false
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
W/GAv4    ( 5840): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5877): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
E/AffinityControl( 5995): AffinityControl: registerfunction enter
I/qtaguid ( 1981): Tagging socket 96 with tag 40b00000000{1035,0} for uid -1, pid: 1981, getuid(): 10012
D/AndroidRuntime( 5995): Calling main entry com.android.commands.am.Am
E/Zygote  ( 6058): MountEmulatedStorage()
I/libpersona( 6058): KNOX_SDCARD checking this for 10053
E/Zygote  ( 6058): v2
I/libpersona( 6058): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6058 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 6058): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/PackageManager( 1013): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/PersonaManagerService( 1013): inState():  stateMachine is null !!
I/PersonaManagerService( 1013): PersonaId don't exist
I/ActivityManager( 1013): do not start freezing screen for locked container getKeyguardshowstate = false
I/SELinux ( 6058): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
E/SELinux ( 6058): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/GAv4    ( 5840): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5840): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/TimaKeyStoreProvider( 6058): TimaSignature is unavailable
D/ActivityThread( 6058): Added TimaKeyStore provider
W/ActivityManager( 1013): mDVFSHelper.acquire()
W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5
I/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1013): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1013): *FMB* installDecor flags : 25362712
I/qtaguid ( 1981): Tagging socket 102 with tag 40b00000000{1035,0} for uid -1, pid: 1981, getuid(): 10012
E/Zygote  ( 6080): MountEmulatedStorage()
I/libpersona( 6080): KNOX_SDCARD checking this for 10175
E/Zygote  ( 6080): v2
I/libpersona( 6080): KNOX_SDCARD not a persona
I/SELinux ( 6080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/PhoneWindow( 1013): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1013): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 6080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/SurfaceFlinger(  256): id=13 createSurf (1x1),1 flag=404, uhalitest
E/SELinux ( 6080): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/ActivityManager( 1013): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6080 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TimaKeyStoreProvider( 6080): TimaSignature is unavailable
D/ActivityThread( 6080): Added TimaKeyStore provider
W/AnalyticsTrackerProxyImpl( 5840): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
D/InputDispatcher( 1013): Focused application set to: xxxx
V/AlarmManager( 1013): waitForAlarm result :4
D/InputDispatcher( 1013): Focus left window: 2974
D/AndroidRuntime( 5995): Shutting down VM
V/ActivityManager( 1013): Display changed displayId=0
D/StatusBarManagerService( 1013): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/DBG_POLICYDM( 5877): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
W/ResourcesManager( 6058): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
D/PersonaManager( 1013): isKioskContainerExistOnDevice
D/Compatibility( 6058): onReceive() it will make start service
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
I/SurfaceFlinger(  256): id=11 Removed YUIInstallC (5/9)
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
W/BaseAppContext( 1981): Using Auth Proxy for data requests.
W/BaseAppContext( 1981): Using Auth Proxy for data requests.
V/ActivityThread( 2974): updateVisibility : ActivityRecord{94e52fc token=android.os.BinderProxy@6f4ab2 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/Compatibility( 6058): onHandleIntent()
D/Compatibility( 6058): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
E/Zygote  ( 6099): MountEmulatedStorage()
E/Zygote  ( 6099): v2
I/libpersona( 6099): KNOX_SDCARD checking this for 1000
I/libpersona( 6099): KNOX_SDCARD not a persona
I/SELinux ( 6099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/Compatibility( 6058): found: 2
I/ActivityManager( 1013): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6099 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6099): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
D/TimaKeyStoreProvider( 6099): TimaSignature is unavailable
D/ActivityThread( 6099): Added TimaKeyStore provider
D/Compatibility( 6058): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6058): skipping ResolveInfo{25bae319 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6058): considering ResolveInfo{1a7fde com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6058): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6058): enabling receiver ResolveInfo{21f245bf com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/DBG_POLICYDM( 5877): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
D/Compatibility( 6058): enabling receiver ResolveInfo{3622148c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6058): enabling receiver ResolveInfo{1f0d97d5 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/SL_DEBUG( 5999): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5999): isLoggable:: SL_DEBUG_EXIST = false
W/BaseAppContext( 1981): Using Auth Proxy for data requests.
D/Compatibility( 6058): enabling receiver ResolveInfo{20cabbea com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6058): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
W/BaseAppContext( 1981): Using Auth Proxy for data requests.
W/art     ( 5995): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/BaseAppContext( 1981): Using Auth Proxy for data requests.
I/WebViewFactory( 6080): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
W/ContextImpl( 6099): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/LibraryLoader( 6080): Time to load native libraries: 2 ms (timestamps 3663-3665)
I/LibraryLoader( 6080): Expected native library version number "",actual native library version number ""
E/Zygote  ( 6121): MountEmulatedStorage()
E/Zygote  ( 6121): v2
I/libpersona( 6121): KNOX_SDCARD checking this for 1000
I/libpersona( 6121): KNOX_SDCARD not a persona
I/SELinux ( 6121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6121 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6121): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 5522:com.sec.knox.bridge/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 6121): TimaSignature is unavailable
W/BaseAppContext( 1981): Using Auth Proxy for data requests.
D/ActivityThread( 6121): Added TimaKeyStore provider
I/art     (  302): Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 662us total 25.680ms
V/WebViewChromiumFactoryProvider( 6080): Binding Chromium to main looper Looper (main, tid 1) {1f0d97d5}
I/LibraryLoader( 6080): Expected native library version number "",actual native library version number ""
I/chromium( 6080): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 19.233ms
W/ResourcesManager( 6121): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 18.548ms
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/ContextImpl( 5999): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
I/BrowserStartupController( 6080): Initializing chromium process, singleProcess=true
W/art     ( 6080): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6080): ApplicationContext is null in ApplicationStatus
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5522/cgroup.procs: No such file or directory
W/chromium( 6080): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6080): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6080): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6080): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6080): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6080): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6080): Local Branch: 
I/Adreno-EGL( 6080): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6080): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6080):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/qtaguid ( 1981): Untagging socket 96
I/ActivityManager( 1013): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6145 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 5539:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
E/Zygote  ( 6145): MountEmulatedStorage()
E/Zygote  ( 6145): v2
I/libpersona( 6145): KNOX_SDCARD checking this for 1000
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
I/libpersona( 6145): KNOX_SDCARD not a persona
I/SELinux ( 6145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6145): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5999): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/ConfigFetchService( 1981): fetch service done; releasing wakelock
I/ConfigFetchService( 1981): stopping self
D/TimaKeyStoreProvider( 6145): TimaSignature is unavailable
D/ActivityThread( 6145): Added TimaKeyStore provider
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
W/ResourcesManager( 6145): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5840): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5840): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
I/ActivityManager( 1013): Killing 5446:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
W/ContextImpl( 5840): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/art     ( 1013): Explicit concurrent mark sweep GC freed 221616(14MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/41MB, paused 3.142ms total 193.754ms
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5539/cgroup.procs: No such file or directory
E/Zygote  ( 6177): MountEmulatedStorage()
E/Zygote  ( 6177): v2
I/libpersona( 6177): KNOX_SDCARD checking this for 10041
I/libpersona( 6177): KNOX_SDCARD not a persona
I/SELinux ( 6177): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6177 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1013): Activity pause timeout for ActivityRecord{313f3205 u0 com.test.thalitest/.MainActivity t231}
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
I/SELinux ( 6177): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6177): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
W/libprocessgroup( 1013): failed to open /acct/uid_10057/pid_5446/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 6177): TimaSignature is unavailable
D/ActivityThread( 6177): Added TimaKeyStore provider
V/JNIHelp ( 5840): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/SA      ( 6177): [SSP] onCreated
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6196): MountEmulatedStorage()
E/Zygote  ( 6196): v2
I/libpersona( 6196): KNOX_SDCARD checking this for 10057
I/libpersona( 6196): KNOX_SDCARD not a persona
I/SELinux ( 6196): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6196): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6196 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/SELinux ( 6196): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 5006:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
W/System  ( 5840): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@89646b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 5840): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 5840): Installed default security provider GmsCore_OpenSSL
I/SA      ( 6177): [TPM] There is no property file
I/SA      ( 6177): [SCU] isHaveSA() - false
I/SA      ( 6177): [TPM] getModelProperty : null
I/SA      ( 6177): [TPM] getCSCProperty : null
I/SA      ( 6177): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6177): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6177): [DM] TFT FEATURE: false
I/SA      ( 6177): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6177): [DM] init START
D/TimaKeyStoreProvider( 6196): TimaSignature is unavailable
D/ActivityThread( 6196): Added TimaKeyStore provider
I/SA      ( 6177): [DM] This device is not a Vodafone
I/ActivityManager( 1013): Killing 5656:com.sec.android.diagmonagent/1000 (adj 15): empty #31
W/ResourceType( 6177): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6177): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6177): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6177): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6177): [SCU] isHaveSA() - false
I/SA      ( 6177): support phone number id : false
I/SA      ( 6177): [DM] Supports Ref Jpn : true
I/SA      ( 6177): [DM] init END
I/SA      ( 6177): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 6177): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
I/ActivityManager( 1013): Killing 5067:com.google.android.gms:car/u0a12 (adj 15): empty #31
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/PowerManagerService( 1013): [PWL] Off : 5s ago
I/PowerManagerService( 1013): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1013): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1013): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1981, ws=null) (elapsedTime=47608)
I/PowerManagerService( 1013): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1013, ws=WorkSource{10054}) (elapsedTime=781)
V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/art     ( 6080): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6080): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6080): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6080): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6080): CordovaWebView is running on device made by: samsung
W/art     ( 6080): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6080): Attempt to remove local handle scope entry from IRT, ignoring
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
W/ActivityManager( 1013): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5006/cgroup.procs: No such file or directory
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6224): MountEmulatedStorage()
I/libpersona( 6224): KNOX_SDCARD checking this for 10010
E/Zygote  ( 6224): v2
I/libpersona( 6224): KNOX_SDCARD not a persona
I/SELinux ( 6224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6224 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 6224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6224): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6224): TimaSignature is unavailable
D/ActivityThread( 6224): Added TimaKeyStore provider
D/OpenGLRenderer( 6080): Render dirty regions requested: true
D/ActivityManager( 1013): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1013): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1013): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1013): handleActiveUserChange for user 0
D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
W/chromium( 6080): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6080): updateVisibility : ActivityRecord{17fbaf66 token=android.os.BinderProxy@4a7a4a8 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6080): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6080): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=14 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1013): Focus entered window: 6080
D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/SRIB_DCS( 6080): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6080): Initialized EGL, version 1.4
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
D/OpenGLRenderer( 6080): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6080): Enabling debug mode 0
I/splitIntent( 1013): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 1013): Killing 5245:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/KeyguardViewMediator( 1172): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
D/KeyguardViewMediator( 1172): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1172): *** Keyguard wallpaper service already unbounded
D/InputMethodManagerService( 1013): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/PanelView( 1172): There is/are notification(s) 
I/ActivityManager( 1013): Displayed Component not be shown by security: +1s45ms (total +1s160ms)
W/ActivityManager( 1013): mDVFSHelper.release()
I/Timeline( 1013): Timeline: Activity_windows_visible id: ActivityRecord{313f3205 u0 com.test.thalitest/.MainActivity t231} time:84499
W/art     ( 1981): Suspending all threads took: 5.468ms
I/SurfaceFlinger(  256): id=13 Removed uhalitest (7/9)
I/SurfaceFlinger(  256): id=13 Removed uhalitest (-2/9)
I/art     ( 1981): Background sticky concurrent mark sweep GC freed 18810(1222KB) AllocSpace objects, 11(583KB) LOS objects, 13% free, 13MB/15MB, paused 7.993ms total 92.182ms
W/IInputConnectionWrapper( 6080): showStatusIcon on inactive InputConnection
I/Timeline( 6080): Timeline: Activity_idle id: android.os.BinderProxy@4a7a4a8 time:84523
I/SamsungIME( 1731): getCurrentCandidateView
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5656/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10012/pid_5067/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10150/pid_5245/cgroup.procs: No such file or directory
D/LocationManagerService( 1013): getProviders()=[passive]
I/Mms/MmsApp( 5813):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5813): [start]    fillCache consume time = 1971.508229
D/Mms/ComposeMessageFragment( 5813): fillCache, easy = false
D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1981): Module APK com.google.android.play.games already loaded
W/BindingManager( 6080): Cannot call determinedVisibility() - never saw a connection for the pid: 6080
D/SamsungIME( 1731): Dismiss ExpandCandiate
I/SamsungIME( 1731): getDebugLevel  : 0x4f4c
D/AbsListView( 5813): Get MotionRecognitionManager
D/MotionRecognitionService( 1013):  ssp status : false
D/Mms/ComposeMessageFragment( 5813): [end]    fillCache consume time = 113.320052
I/SamsungIME( 1731): getDebugLevel  : 0x4f4c
I/UpdateIcingCorporaServi( 6196): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/SamsungIME( 1731): KeybaordView init() : load resources
I/SamsungIME( 1731): getCurrentKeyboard
I/SamsungIME( 1731): getTextKeyboard
D/JsMessageQueue( 6080): Set native->JS mode to OnlineEventsBridgeMode
D/SamsungIME( 1731): [SwiftkeyWrapper] currentLangauge : 1701729619
D/Mms/BubbleViewCache( 5813): fillCache bubble = 1
I/UpdateIcingCorporaServi( 6196): UpdateCorporaTask done [took 127 ms] updated apps [took 127 ms] 
I/ActivityManager( 1013): Killing 5677:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
D/jxcore_app_log( 6080): JniHelper::setJavaVM(0xb84fd450), pthread_self() = -1197111416
D/JX-Cordova( 6080): jxcore cordova android initializing
W/libprocessgroup( 1013): failed to open /acct/uid_10142/pid_5677/cgroup.procs: No such file or directory
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=6258 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/Zygote  ( 6258): MountEmulatedStorage(),
I/libpersona( 6258): KNOX_SDCARD checking this for 10012
E/Zygote  ( 6258): v2
I/libpersona( 6258): KNOX_SDCARD not a persona
I/SELinux ( 6258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6258): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,E/SMD     (  287): DCD OFF
,D/TimaKeyStoreProvider( 6258): TimaSignature is unavailable
,D/ActivityThread( 6258): Added TimaKeyStore provider
,W/ResourcesManager( 6258): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6258): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6258): VM with version 2.1.0 has multidex support
I/MultiDex( 6258): install
I/MultiDex( 6258): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6258): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6258): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6258): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11c52d4c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6258): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1714): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/splitIntent( 1013): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1013): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1013): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1013): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1714): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1981): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1013): Killing 5146:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4477): callingUid 10012, callindPid: 4477
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1689): [185] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1981): Restart initialization of location
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1013): failed to open /acct/uid_10040/pid_5146/cgroup.procs: No such file or directory
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4180, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log( 6080): Initializing JXcore engine
W/jxcore-log( 6080): JXcore engine is ready
,W/jxcore-log( 6080): Starting JXcore engine
,E/audit   ( 1845): type=1400 msg=audit(1452246476.281:205): avc:  denied  { ioctl } for  pid=6080 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1845):  SEPF_SM-A500FU_5.0.2_0027
,E/audit   ( 1845): type=1300 msg=audit(1452246476.281:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=bebcad58 items=0 ppid=302 ppcomm=main pid=6080 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1845): type=1320 msg=audit(1452246476.281:205): 
,W/jxcore-log( 6080): Platform android
W/jxcore-log( 6080): 
W/jxcore-log( 6080): Process ARCH arm
W/jxcore-log( 6080): 
,I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5877): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/jxcore-log( 6080): JXcore Cordova bridge is ready!
I/jxcore-log( 6080): 
,W/jxcore-log( 6080): JXcore engine is started
,I/chromium( 6080): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigService( 1714): onDestroy
,I/jxcore-log( 6080): Toggling radios to true
I/jxcore-log( 6080): 
,D/BluetoothAdapter( 6080): enable()
,D/BluetoothAdapter( 6080): enable(): BT is already enabled..!
,D/SecContentProvider( 1013): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1013): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1013): mCursor = null
,D/WifiService( 1013): setWifiEnabled: true pid=6080, uid=10175
,W/ActivityManager( 1013): Permission Denial: getCurrentUser() from pid=6080, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1013): Failed getting userId using ActivityManagerNative
W/WifiService( 1013): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6080, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1013): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1013): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1013): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1013): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1013): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1013): name = wifi_on
,I/WifiService( 1013): disconnect: pid=6080, uid=10175
,I/jxcore-log( 6080): Radios toggled
I/jxcore-log( 6080): 
,I/wpa_supplicant( 2143): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6080): Received device characteristics:
I/jxcore-log( 6080): Bluetooth address: 7C:F9:0E:51:18:22
I/jxcore-log( 6080): Bluetooth name: Thali Test (Galaxy A5)
I/jxcore-log( 6080): Device name: samsung-SM-A500FU
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): Perf Test app loaded loaded
I/jxcore-log( 6080): 
,D/SSRM:n  ( 1013): SIOP:: AP = 360
,I/jxcore-log( 6080): check test folder
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): found test : ./testFindPeers.js
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): found test : ./testSendData.js
I/jxcore-log( 6080): 
,I/wpa_supplicant( 2143): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 2143): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2143): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 2143): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2143): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/wpa_supplicant( 2143): Cmd 35605 not handled
E/WifiStateMachine( 1013): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 2143): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2143): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2143): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 2143): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 2143): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 2143): First Scan Start
I/wpa_supplicant( 2143): Scan requested (ret=0) - scan timeout 30 seconds
I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceStatusChanged wlan0, false
,D/Tethering( 1013): InitialState.processMessage what=4
,E/WifiConfigStore( 1013): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Tethering( 1013): No numeric data
D/Tethering( 1013): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1013): clearTetheredNotification()
,I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, false
,V/NetworkStats( 1013): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1013): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1013): UpdateStatsForKnox main else ---
,D/Tethering( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceStatusChanged wlan0, false
,E/WifiNative-wlan0( 1013): do suspend true
,D/HotspotTile( 1172): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1172): updateTetherState():false, false
V/NetworkStats( 1013): performPollLocked() took 7ms
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
,I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, false
,D/WifiP2pService( 1013): InactiveState{ what=143375 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=143375 }
D/Tethering( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1714): Read error: ssl=0xb8a90740: I/O error during system call, Connection timed out,
V/NativeCrypto( 1714): SSL shutdown failed: ssl=0xb8a90740: I/O error during system call, Broken pipe
D/ConnectivityService( 1013): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine( 1013): Start Disconnecting Watchdog 1
D/ConnectivityService( 1013): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/ConnectivityService( 1013): updateNetworkInfo()
E/ConnectivityService( 1013): updateNetworkInfo()
I/wpa_supplicant( 2143): wlan0: Setting scan request: 0 sec 0 usec
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1013): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiTrafficPoller( 1013): evaluateTrafficStatsPolling
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1013): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1013): Tagging socket 362 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1013, getuid(): 1000
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14949 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6950 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null,
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
I/qtaguid ( 1013): Untagging socket 362,
,I/System.out( 1013): (HTTPLog)-Static: isSBSettingEnabled false
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3549): Starting #8
,E/WifiNative-wlan0( 1013): do suspend true
,D/WifiP2pService( 1013): InactiveState{ what=143375 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 3549): Message received 5007
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1321): MountReceiver.mPrefHandler - 7002
D/CommandListener(  277): Clearing all IP addresses on wlan0
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524292
D/ConnectivityService( 1013): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1013): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1013): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1473): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1473): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_P2P( 1013): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): ValidatedState{ when=-6ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/EntConnectivity( 1013): Not allowed due to - mEnabled false - primarySimSlot false
,D/CSLegacyTypeTracker( 1013): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1013): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1013): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 1013): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): doQuit - quitNow()
,D/EntConnectivity( 1013): Not allowed due to - mEnabled false - primarySimSlot false
,D/WifiNetworkAgent( 1013): NetworkAgent: NetworkAgent channel lost
,I/WifiTrafficPoller( 1013): evaluateTrafficStatsPolling,
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1013): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/WIFI    ( 1013): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1013): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1013): mCursor = null
,D/Tethering( 1013): MasterInitialState.processMessage what=3
,V/NetworkStats( 1013): updateIfacesLocked()
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
V/NetworkStats( 1013): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1013): UpdateStatsForKnox updated,
D/NetworkStatsFactory( 1013): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1172): EthernetConnected: false
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1172): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
V/NetworkStats( 1013): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
V/NetworkStats( 1013): performPollLocked() took 16ms
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/SecContentProvider2( 1013): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1013): mCursor = null
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
,I/chromium( 6080): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/Zygote  ( 6289): MountEmulatedStorage()
E/Zygote  ( 6289): v2
I/libpersona( 6289): KNOX_SDCARD checking this for 10104
I/libpersona( 6289): KNOX_SDCARD not a persona
,I/SELinux ( 6289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6289): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6289 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 6289): TimaSignature is unavailable
,D/ActivityThread( 6289): Added TimaKeyStore provider
,W/ResourcesManager( 6289): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3,
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,I/Babel_SMS( 6289): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6289): MmsConfig.loadMmsSettings
I/Babel_SMS( 6289): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel_SMS( 6289): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6289): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6289): MmsConfig.loadFromResources
,E/Babel_SMS( 6289): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6289): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/art     ( 6289): Suspending all threads took: 8.370ms,
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  282): getCameraInfo: X
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  282): getCameraInfo: X
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6289): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6289): startup - clean
,I/Babel   ( 6289): deleted: false for 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3549): Starting #9
,I/Hs20UtilService( 3549): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1321): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1321): MountReceiver.mPrefHandler - 7002
,W/VideoCapabilities( 6289): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6289): Unsupported mime audio/evrc
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6289): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6289): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6289): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6289): Unsupported mime audio/x-ms-wma
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/AudioCapabilities( 6289): Unsupported mime audio/x-ima
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6289): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6289): Unsupported mime audio/evrc
,D/ConnectivityService( 1013): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1013): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 2974): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,W/VideoCapabilities( 6289): Unsupported mime video/wvc1
,I/DBG_DM  ( 2974): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,W/VideoCapabilities( 6289): Unsupported mime video/x-ms-wmv
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ApplicationPolicy( 1013): updateDataUsageMap
,W/VideoCapabilities( 6289): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6289): Unsupported mime video/wvc1
,W/VideoCapabilities( 6289): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6289): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6289): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6289): Unsupported mime video/mp43
,W/VideoCapabilities( 6289): Unsupported mime video/sorenson
,W/VideoCapabilities( 6289): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6289): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6289): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6289): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6289): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6289): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1013): Killing 5044:com.google.android.music:main/u0a111 (adj 15): empty #31
,I/vclib   ( 6289): onServiceConnected
,W/Babel   ( 6289): Attempted to change video mute state without an active call.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1013): failed to open /acct/uid_10111/pid_5044/cgroup.procs: No such file or directory
,D/AcmsKeyStoreHelper( 5899):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5899): Key Store exist
,I/AcmsKeyStoreHelper( 5899): Hence loading the keystore file
,I/wpa_supplicant( 2143): nl80211: Received scan results (11 BSSes)
,I/wpa_supplicant( 2143): wlan0: Setting scan request: 8 sec 0 usec,
I/wpa_supplicant( 2143): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 2143): Trying to associate with  'G700'
I/wpa_supplicant( 2143): Re-associate with C0.AA.48
,I/wpa_supplicant( 2143): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 2143): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1013): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1013): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1013): mCursor = null
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/AcmsKeyStoreHelper( 5899):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5899): getKeyStoreForApplication success 
D/AcmsCore( 5899): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5899): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5899): Decrementing - Counter value: 1
D/AcmsCore( 5899): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5899): This is NOT a valid MirrorLink app
D/AcmsCore( 5899): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5899): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5899): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5899): Counter value is 0: Stopping ACMS service
,I/PCWCLIENTTRACE_PushUtil( 5828): SPPPushClient is installed : true
D/AcmsServiceMonitor( 5899): getSvcCounter - Counter value: 0
I/PCWCLIENTTRACE_PushUtil( 5828): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5828): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5828): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/AcmsService( 5899): Enter onDestroy
I/AcmsService( 5899): cleanUp(): inside service clean up
D/AcmsCore( 5899): AcmsCore: inside DeInit
D/AcmsCore( 5899): AcmsCore: mLooperHandler is not null and making it null
,I/splitIntent( 1013): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
I/splitIntent( 1013): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1013): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1013): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,D/AcmsCertificateMngr( 5899): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5899): AcmsRevocationMngr: inside cleanup
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5828): noConnectivity : true
D/AcmsKeyStoreHelper( 5899): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5899): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5899): getSvcCounter - Counter value: 0
D/AcmsService( 5899): killing acms process
I/Process ( 5899): Sending signal. PID: 5899 SIG: 9
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6332): MountEmulatedStorage()
E/Zygote  ( 6332): v2
,I/libpersona( 6332): KNOX_SDCARD checking this for 10111
I/libpersona( 6332): KNOX_SDCARD not a persona
,I/SELinux ( 6332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6332): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6332 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1013): waitForAlarm result :8
,V/AlarmManager( 1013): waitForAlarm result :4
,V/AlarmManager( 1013): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1013): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1013): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/TimaKeyStoreProvider( 6332): TimaSignature is unavailable
,D/ActivityThread( 6332): Added TimaKeyStore provider
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
E/wpa_supplicant( 2143): Cmd 35605 not handled
,I/wpa_supplicant( 2143): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2143): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2143): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 2143): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 2143): Associated with C0.AA.48
I/wpa_supplicant( 2143): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 2143): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2143): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030,
,D/Tethering( 1013): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceStatusChanged wlan0, false
D/Tethering( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceStatusChanged wlan0, false
D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, true
D/Tethering( 1013): interfaceLinkStateChanged wlan0, true
D/Tethering( 1013): interfaceStatusChanged wlan0, true
,D/SecContentProvider2( 1013): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1013): mCursor = null
,E/Tethering( 1013): No numeric data
,D/Tethering( 1013): sendTetherStateChangedBroadcast 1, 0, 0
I/wpa_supplicant( 2143): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/Tethering( 1013): clearTetheredNotification()
,I/wpa_supplicant( 2143): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2143): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/SecContentProvider2( 1013): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1013): mCursor = null
I/wpa_supplicant( 2143): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 2143): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2143): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 2143): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 2143): Blacklist: Clear (temp) 
I/wpa_supplicant( 2143): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, true
D/Tethering( 1013): interfaceLinkStateChanged wlan0, true
D/Tethering( 1013): interfaceStatusChanged wlan0, true
V/NetworkStats( 1013): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1013): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1013): UpdateStatsForKnox main else ---
,V/NetworkStats( 1013): performPollLocked() took 3ms
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/HotspotTile( 1172): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1172): updateTetherState():false, false
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
D/WifiNative-wlan0( 1013): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1013): setLastSelectedConfiguration -1
,D/ConnectivityService( 1013): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1013): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1013): updateNetworkInfo()
D/ConnectivityService( 1013): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiConfigStore( 1013): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiConfigStore( 1013): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
I/ActivityManager( 1013): Process ACMS.Process (pid 5899)(adj 0) has died(44,1059)
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CommandListener(  277): Setting iface cfg
,E/WifiStateMachine( 1013): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1013): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1013): mCursor = null
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/WifiNative-wlan0( 1013): do suspend false
,D/SecContentProvider2( 1013): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1013): mCursor = null
D/WifiP2pService( 1013): InactiveState{ what=143375 }
D/WifiP2pService( 1013): P2pEnabledState{ what=143375 }
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/MusicStore( 6332): Database version: 120
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6332): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6332): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6332): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6332): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6332): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6332): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/SQLiteLog( 1714): (10) POSIX Error : 11 SQLite Error : 3850
,E/dhcpcd  ( 6357): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6357): version 5.5.6 starting
,W/ActivityThread( 6332): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6332): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f04a9f3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6332): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6332): GMSCore installation verified
E/dhcpcd  ( 6357): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/ConfigStore( 6332): Config Database version: 1,
,I/dhcpcd  ( 6357): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6357): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6357): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6357): bssid match,
I/dhcpcd  ( 6357): wlan0: rebinding lease of 192.168.1.137
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/dhcpcd  ( 6357): wlan0: acknowledged 192.168.1.137 from 192.168.1.1
,I/AudioService( 1013): getStreamVolume 3 index 0
,I/MediaRouter( 6332): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6332): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 6357): wlan0: leased 192.168.1.137 for 86400 seconds
,E/Zygote  ( 6369): MountEmulatedStorage()
I/libpersona( 6369): KNOX_SDCARD checking this for 10002,
,E/Zygote  ( 6369): v2
I/libpersona( 6369): KNOX_SDCARD not a persona
I/SELinux ( 6369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6369): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6369 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GHttpClientFactory( 6332): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6369): TimaSignature is unavailable,
D/ActivityThread( 6369): Added TimaKeyStore provider
,I/GoogleURLConnFactory( 6332): Using platform SSLCertificateSocketFactory
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1013): Killing 5165:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/ActivityManager( 1013): Killing 5388:com.google.android.gm/u0a101 (adj 15): empty #32
,I/ActivityManager( 1013): Killing 4216:com.sec.spp.push/u0a35 (adj 15): empty #31
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6406): MountEmulatedStorage()
,E/Zygote  ( 6406): v2
I/libpersona( 6406): KNOX_SDCARD checking this for 1000
I/libpersona( 6406): KNOX_SDCARD not a persona
,I/SELinux ( 6406): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6406): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6406): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6406 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6406): TimaSignature is unavailable
,D/ActivityThread( 6406): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6406): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1013): failed to open /acct/uid_10044/pid_5165/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10101/pid_5388/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10035/pid_4216/cgroup.procs: No such file or directory
,E/WifiNative-wlan0( 1013): do suspend true
,I/DIAGMON_AGENT( 6406): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6406): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6406): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6406): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6406): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6406): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/WifiP2pService( 1013): InactiveState{ what=143375 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=143375 },
,E/Zygote  ( 6423): MountEmulatedStorage()
E/Zygote  ( 6423): v2
I/libpersona( 6423): KNOX_SDCARD checking this for 10009
I/libpersona( 6423): KNOX_SDCARD not a persona
I/SELinux ( 6423): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6423): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1013): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6423 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6423): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 5797:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
E/WifiStateMachine( 1013): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1013): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1013): callSECApiInt - ID [210]
,E/ConnectivityService( 1013): updateNetworkInfo()
D/ConnectivityService( 1013): Adding iface wlan0 to network 503
D/ConnectivityService( 1013): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 6423): TimaSignature is unavailable
,D/WifiWatchdogStateMachine( 1013): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1013): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1013): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1013): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1013): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityThread( 6423): Added TimaKeyStore provider
,E/WifiStateMachine( 1013): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1013): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1013): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1013): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1013): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1013): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1013): LTETest block dns file not exists
,D/ConnectivityService( 1013): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 1013): updateNetworkInfo()
,E/ConnectivityService( 1013): updateNetworkInfo()
D/ConnectivityService( 1013): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1013): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): Connected
D/ConnectivityService( 1013): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,E/WifiStateMachine( 1013): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/System.out( 1013): (HTTPLog)-Static: isSBSettingEnabled false
E/WifiStateMachine( 1013): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/EnterpriseController(  277): uids 1000
,D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 1000
I/WifiTrafficPoller( 1013): evaluateTrafficStatsPolling
D/ConnectivityService( 1013):    accepting network in place of null
D/WIFI    ( 1013): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/WIFI_P2P( 1013): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1473): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1473): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker( 1013): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1013): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
,D/ConnectivityService( 1013): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1013): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1013): mBoosterFLAG : 0
I/WifiTrafficPoller( 1013): current booster mode : FullMode
,D/WifiNative-wlan0( 1013): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/ConnectivityService( 1013): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1013): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1013): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/Tethering( 1013): MasterInitialState.processMessage what=3
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
V/NetworkStats( 1013): updateIfacesLocked()
V/NetworkStats( 1013): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1013): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1013): UpdateStatsForKnox main else ---
W/libprocessgroup( 1013): failed to open /acct/uid_10100/pid_5797/cgroup.procs: No such file or directory
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
V/NetworkStats( 1013): performPollLocked() took 4ms
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit,
V/NetworkStats( 1013): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1172): EthernetConnected: false
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1172): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ActivityManager( 1013): Killing 5472:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3567): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 10:48:01 GMT+01:00 2016
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3567): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3567): KLMSIntentService(): onCreate()
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3567): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3567): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3567): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
I/KLMS-2.5.183: ( 3567): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
I/libpersona( 6445): KNOX_SDCARD checking this for 10034
E/Zygote  ( 6445): MountEmulatedStorage()
I/libpersona( 6445): KNOX_SDCARD not a persona
E/Zygote  ( 6445): v2
I/SELinux ( 6445): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6445): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/KLMS-2.5.183: ( 3567): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,E/SELinux ( 6445): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/KLMS-2.5.183: ( 3567): StateImplV2(): networkChangeListener().START
,I/ActivityManager( 1013): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6445 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3567): NetworkChangeOperations(): uploadRequestLog().START 
,I/System.out( 1013): KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,I/KLMS-2.5.183: ( 3567): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3567): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3567): KLMSIntentService(): onDestroy()
,I/art     (  302): Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 25.108ms
,D/TimaKeyStoreProvider( 6445): TimaSignature is unavailable
,D/ActivityThread( 6445): Added TimaKeyStore provider
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 16.941ms
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 09:48:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452246481139], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452246481119]},
D/ConnectivityService( 1013): Validated NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): Don't send network conditions - lacking user consent.
D/ConnectivityService( 1013): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): Validated
D/ConnectivityService( 1013): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1013): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1013): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
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
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 17.168ms
,I/SO_AGENT( 6445): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5877): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1013): failed to open /acct/uid_10015/pid_5472/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5877): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 6177): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
I/SA      ( 6177): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6177): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6177): [SLFUCHKMGR] constructor called
,E/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 6177): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6177): [OR] == isSIMCardReady false ==
,I/SA      ( 6177): [SCU] == networkStateCheck == true
,I/SA      ( 6177): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6177): isChinaCountryCode : false
I/SA      ( 6177): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6177): [OR] == networkStateCheck true ==
I/SA      ( 6177): [OR] GetMyCountryZoneTask
,I/SA      ( 6177): [OR] onReceive END
,I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/ActivityManager( 1013): Killing 5370:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,V/DownloadManager( 1221): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE,
,I/SA      ( 6177): [SRS] prepareGetMyCountryZone
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/accuweather( 1576): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 6177): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6177): [SSP] query invoked
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,I/DBG_POLICYDM( 5877): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/accuweather( 1576): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
I/DBG_POLICYDM( 5877): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/accuweather( 1576): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/accuweather( 1576): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1576): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,E/DBG_POLICYDM( 5877): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,I/DBG_POLICYDM( 5877): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,W/libprocessgroup( 1013): failed to open /acct/uid_10035/pid_5370/cgroup.procs: No such file or directory
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 68294(3MB) AllocSpace objects, 7(160KB) LOS objects, 33% free, 27MB/41MB, paused 2.552ms total 158.609ms
,I/SA      ( 6177): [TPMU] GetMccFromDB : null
I/SA      ( 6177): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6177): [TPM] isNoProxy(default) : true
,D/accuweather( 1576): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SecContentProvider2( 1013): uri = 15 selection = getAppBlockDownloadState
D/accuweather( 1576): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SecContentProvider2( 1013): mCursor = null
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/SMD     (  287): DCD OFF
,E/File    ( 6177): fail readDirectory() errno=2
,E/Zygote  ( 6465): MountEmulatedStorage()
I/libpersona( 6465): KNOX_SDCARD checking this for 10125
E/Zygote  ( 6465): v2
,I/libpersona( 6465): KNOX_SDCARD not a persona
I/SELinux ( 6465): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6465 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6465): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6465): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6465): TimaSignature is unavailable
,D/ActivityThread( 6465): Added TimaKeyStore provider
,W/ResourcesManager( 6465): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6465): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6465): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6465): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6465): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6465): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6480): MountEmulatedStorage(),
,E/Zygote  ( 6480): v2
I/libpersona( 6480): KNOX_SDCARD checking this for 10145
I/libpersona( 6480): KNOX_SDCARD not a persona
,I/SELinux ( 6480): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1013): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6480 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 5840:com.google.android.apps.docs/u0a91 (adj 15): empty #31
I/SELinux ( 6480): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6480): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6480): TimaSignature is unavailable
,D/ActivityThread( 6480): Added TimaKeyStore provider
,W/ResourcesManager( 6480): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6480): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6480): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6480): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6480): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ConnectivityService( 1013): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 2974): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,E/JavaBinder( 1013): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 1013): Failure sending broadcast Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
W/BroadcastQueue( 1013): android.os.TransactionTooLargeException
W/BroadcastQueue( 1013): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1013): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1013): 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1220)
W/BroadcastQueue( 1013): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:529)
W/BroadcastQueue( 1013): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:665)
W/BroadcastQueue( 1013): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:717)
W/BroadcastQueue( 1013): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:194)
W/BroadcastQueue( 1013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue( 1013): 	at android.os.Looper.loop(Looper.java:145)
W/BroadcastQueue( 1013): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue( 1013): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,I/NetworkMonitor( 6332): type=WIFI subType= reason=null isConnected=true
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1013): mCursor = null
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,E/Zygote  ( 6499): MountEmulatedStorage()
E/Zygote  ( 6499): v2
I/libpersona( 6499): KNOX_SDCARD checking this for 10075
I/libpersona( 6499): KNOX_SDCARD not a persona
,I/SELinux ( 6499): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1013): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6499 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6499): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/RCPManagerService( 1013): exchangeData() failure , invalid userId
E/SELinux ( 6499): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/GpsLocationProvider( 1013): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1013): failed to open /acct/uid_10091/pid_5840/cgroup.procs: No such file or directory,
,D/TimaKeyStoreProvider( 6499): TimaSignature is unavailable
,D/ActivityThread( 6499): Added TimaKeyStore provider
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/BadgeProvider( 5972): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 1498): reloadBadges entered.
,D/BadgeProvider( 5972): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5972): sendNotify, [notify] : null
D/BadgeProvider( 5972): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5972): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5972): update, [UpdateCount] : 1
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6519): MountEmulatedStorage(),
E/Zygote  ( 6519): v2
I/libpersona( 6519): KNOX_SDCARD checking this for 1000
I/libpersona( 6519): KNOX_SDCARD not a persona
,I/SELinux ( 6519): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1013): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6519 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 6519): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Killing 5860:com.samsung.helphub/1000 (adj 15): empty #31
,E/SELinux ( 6519): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6519): TimaSignature is unavailable
,D/ActivityThread( 6519): Added TimaKeyStore provider
,D/SecurityLogAgent( 6519): KnoxConfiguration : Current State = 1
,I/SA      ( 6177): [RC New] Execute method=[GET] start
,D/SecurityLogAgent( 6519): KnoxConfiguration : Current State Mapping Found 
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/SecurityLogAgent( 6519): StateMachine : Current State = 1
,D/SecurityLogAgent( 6519): StateMachine : Changed Current State = 1
,I/SA      ( 6177): [RC New] Security=[true]
,I/System.out( 6177): Thread-1065(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 6177): Thread-1065(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6177): Thread-1065(ApacheHTTPLog):isShipBuild true
I/System.out( 6177): Thread-1065(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6177): Thread-1065(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/EnterpriseController(  277): uids 10041
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10041
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5860/cgroup.procs: No such file or directory
,E/Zygote  ( 6538): MountEmulatedStorage()
,E/Zygote  ( 6538): v2
I/libpersona( 6538): KNOX_SDCARD checking this for 10159
I/libpersona( 6538): KNOX_SDCARD not a persona
,I/SELinux ( 6538): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6538 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 5487:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,I/SELinux ( 6538): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6538): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6538): TimaSignature is unavailable
,D/ActivityThread( 6538): Added TimaKeyStore provider
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1013): failed to open /acct/uid_10032/pid_5487/cgroup.procs: No such file or directory
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ConnectivityService( 1013): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/GAV2    ( 6499): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6561): MountEmulatedStorage(),
I/libpersona( 6561): KNOX_SDCARD checking this for 10035
E/Zygote  ( 6561): v2
I/libpersona( 6561): KNOX_SDCARD not a persona
I/SELinux ( 6561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6561): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6561 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BooksApp( 6499): Created application version: 3.6.9 (30609)
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6289): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6289): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6289): (HTTPLog)-Static: isShipBuild true
I/System.out( 6289): (HTTPLog)-Thread-1091-168220870: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6289): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10104
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10104
,D/ConnectivityService( 1013): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1013): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1013): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/TimaKeyStoreProvider( 6561): TimaSignature is unavailable,
V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityThread( 6561): Added TimaKeyStore provider
,I/System.out( 6289): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1714): Explicit concurrent mark sweep GC freed 16928(943KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/17MB, paused 1.066ms total 46.320ms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 6289): connection state changed from UNKNOWN to CONNECTED
,E/SPPClientService( 6561): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6561): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6561): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6561): [SystemStateMoniter] Current Time : 92136
,E/SPPClientService( 6561): [SystemStateMoniter] No Connect : true
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/SPPClientService( 6561): PushLog.txt file is not deleted.
D/SPPClientService( 6561): PushLog.txt file is not deleted.
D/SPPClientService( 6561): ============PushLog. stop!
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/SPPClientService( 6561): [[SystemStateMonitorService]] No Active Internet
,E/Zygote  ( 6584): MountEmulatedStorage()
,E/Zygote  ( 6584): v2
I/libpersona( 6584): KNOX_SDCARD checking this for 10113
I/libpersona( 6584): KNOX_SDCARD not a persona
,I/SELinux ( 6584): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6584): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1013): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6584 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6584): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ApplicationPolicy( 1013): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1013): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/ActivityManager( 1013): Killing 5916:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,W/Kids    ( 1981): [AccountUtils] Account not ready
W/Kids    ( 1981): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1981): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1981): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1981): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1981): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1981): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1981): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1981): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1981): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1981): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1981): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1981): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/TimaKeyStoreProvider( 6584): TimaSignature is unavailable
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityThread( 6584): Added TimaKeyStore provider
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 6499): Starting books sync for 61035162, extras: ade
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1013): failed to open /acct/uid_10152/pid_5916/cgroup.procs: No such file or directory
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6584): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6584): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6584):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6584):   adb logcat -s GAv4
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6584): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6584): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/SQLiteLog( 6499): (284) automatic index on view_volumes(volume_id)
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6584): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6584): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6584): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6584): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/BooksConfig( 6499): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/SA      ( 6177): [RC New] [v2liruge] api execute + 666
I/SA      ( 6177): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6177): AsyncTask #1 calls detatch()
,I/SA      ( 6177): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6177): [OCP] update openData : PL
,I/SA      ( 6177): [TPMU] getNetworkMcc : 
,D/ApplicationPolicy( 1013): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1013): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/SA      ( 6177): [SCU] saveMccToPreferece Start
I/SA      ( 6177): [SCU] RegionMCC : 260
I/SA      ( 6177): [SSP] query invoked
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
I/SA      ( 6177): [TPMU] GetMccFromDB : null
I/SA      ( 6177): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6177): [SCU] saveMccToPreferece End
,I/SA      ( 6177): [RC New] executeRequest [v2liruge] end. 734,
I/SA      ( 6177): [RC New] Execute end,
D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/SA      ( 6177): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6177): [OR] GetMyCountryZoneTask Success
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms,
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6584): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,E/BooksAccountManager( 6499): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksSync( 6499): Soft error
E/BooksSync( 6499): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6499): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6499): Sync error
E/BooksSync( 6499): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6499): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6499): Finished books sync
,D/SyncManager( 1013): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 63957, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1013): Killing 5934:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,I/LibraryLoader( 6584): Time to load native libraries: 24 ms (timestamps 2615-2639)
,I/LibraryLoader( 6584): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6584): Binding Chromium to main looper Looper (main, tid 1) {3f2fc211}
,I/LibraryLoader( 6584): Expected native library version number "",actual native library version number ""
,I/chromium( 6584): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1013): mCursor = null
,I/BrowserStartupController( 6584): Initializing chromium process, singleProcess=true
,W/art     ( 6584): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6584): ApplicationContext is null in ApplicationStatus
,W/chromium( 6584): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6584): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6584): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6584): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6584): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6584): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6584): Local Branch: 
I/Adreno-EGL( 6584): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6584): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6584):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/libprocessgroup( 1013): failed to open /acct/uid_10156/pid_5934/cgroup.procs: No such file or directory
,W/AudioManagerAndroid( 6584): Requires BLUETOOTH permission
,I/NSApplication( 6584): Starting up...
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6644): MountEmulatedStorage(),
I/libpersona( 6644): KNOX_SDCARD checking this for 10081
,E/Zygote  ( 6644): v2
I/libpersona( 6644): KNOX_SDCARD not a persona
I/SELinux ( 6644): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6644 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6644): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1013): Killing 5813:com.android.mms/u0a46 (adj 15): empty #31
I/ActivityManager( 1013): Killing 5555:com.android.vending/u0a28 (adj 15): empty #32
,E/SELinux ( 6644): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6644): TimaSignature is unavailable
,D/ActivityThread( 6644): Added TimaKeyStore provider
,D/CountryDetector( 1013): No listener is left
,D/WaitQueueForNetworkActivate( 6224): notifyNetworkActivated
,W/libprocessgroup( 1013): failed to open /acct/uid_10046/pid_5813/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10028/pid_5555/cgroup.procs: No such file or directory
,W/ContextImpl( 6224): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6224): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6224): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6224): exit::IDLE
D/InitializeManagerStateMachine( 6224): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6224): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6224): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6224): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6224): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6224): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6224): entry::SUCCESS
D/hcjo    ( 6224): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3549): Starting #10
D/hcjo    ( 6224): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6224): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6224): exit::SUCCESS
D/InitializeManagerStateMachine( 6224): entry::IDLE
,I/Hs20UtilService( 3549): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1013): Killing 5989:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3549): Starting #11
,I/Hs20UtilService( 3549): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 3549): Starting #12
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3549): Message received 5007
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3549): Starting #13
,I/Hs20UtilService( 3549): Message received 5007
,D/WifiStateMachine( 1013): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1013): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1013): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5828): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5828): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5828): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5828): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1013): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
,I/splitIntent( 1013): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1013): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
,I/splitIntent( 1013): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6332): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  256): id=15 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6406): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6406): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6406): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6406): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PackageManager( 1013): [MSG] MCS_UNBIND
,D/PowerManagerService( 1013): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1013
,D/SRIB_DCS( 1172): log_dcs ThreadedRenderer::initialize entered! 
,I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5877): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5877): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,W/libprocessgroup( 1013): failed to open /acct/uid_10047/pid_5989/cgroup.procs: No such file or directory
,I/FOTA_Client( 6423): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6423): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/ActivityManager( 1013): Killing 6029:com.wsomacp/u0a25 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3567): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 10:48:03 GMT+01:00 2016
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3567): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3567): KLMSIntentService(): onCreate()
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3567): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3567): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3567): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3567): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3567): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3567): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3567): NetworkChangeOperations(): uploadRequestLog().START 
,I/DBG_POLICYDM( 5877): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.183: ( 3567): NetworkChangeOperations(): uploadRequestLog().END 
,I/DBG_POLICYDM( 5877): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,E/DBG_POLICYDM( 5877): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/KLMS-2.5.183: ( 3567): StateImplV2(): networkChangeListener().END
I/SA      ( 6177): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6177): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6177): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/KLMS-2.5.183: ( 3567): KLMSIntentService(): onDestroy()
,I/SA      ( 6177): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6177): [OR] == isSIMCardReady false ==
,I/SA      ( 6177): [SCU] == networkStateCheck == true
I/SA      ( 6177): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6177): isChinaCountryCode : false
I/SA      ( 6177): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6177): [OR] == networkStateCheck true ==
I/SA      ( 6177): [OR] GetMyCountryZoneTask
,I/SA      ( 6177): [OR] onReceive END
,I/SA      ( 6177): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1221): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 6177): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6177): [SSP] query invoked
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/libprocessgroup( 1013): failed to open /acct/uid_10025/pid_6029/cgroup.procs: No such file or directory
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 30923(1689KB) AllocSpace objects, 4(104KB) LOS objects, 33% free, 27MB/41MB, paused 2.622ms total 158.167ms
,I/SA      ( 6177): [TPMU] GetMccFromDB : null
I/SA      ( 6177): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6177): [TPM] isNoProxy(default) : true
I/SA      ( 6177): [RC New] Execute method=[GET] start
,D/accuweather( 1576): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SecContentProvider2( 1013): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1013): mCursor = null
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 1576): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1576): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1576): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1576): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1576): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1576): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6465): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6465): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6465): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6519): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6519): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6519): StateMachine : Current State = 1
,D/SecurityLogAgent( 6519): StateMachine : Changed Current State = 1
,I/SA      ( 6177): [RC New] Security=[true]
,I/System.out( 6177): Thread-1067(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6177): Thread-1067(ApacheHTTPLog):isShipBuild true
I/System.out( 6177): Thread-1067(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6177): Thread-1067(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6561): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6561): [SystemStateMoniter] Current Time : 93789
,E/SPPClientService( 6561): [SystemStateMoniter] No Connect : false
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6289): (HTTPLog)-Static: isSBSettingEnabled false
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6224): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6224): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6224): exit::IDLE
,D/InitializeManagerStateMachine( 6224): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6224): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6224): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6224): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6224): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6224): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6224): entry::SUCCESS
D/hcjo    ( 6224): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6224): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6224): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6224): exit::SUCCESS
D/InitializeManagerStateMachine( 6224): entry::IDLE
,D/ApplicationPolicy( 1013): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1013): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,W/Kids    ( 1981): [AccountUtils] Account not ready
W/Kids    ( 1981): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1981): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1981): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1981): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1981): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1981): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1981): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1981): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1981): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1981): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1981): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1981): 	at java.lang.Thread.run(Thread.java:818)
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6080): BLE is supported
I/jxcore-log( 6080): 
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,I/PowerManagerService( 1013): [PWL] Off : 15s ago,
I/PowerManagerService( 1013): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1013): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1013): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1981, ws=null) (elapsedTime=57609)
,I/SA      ( 6177): [RC New] [v2liruge] api execute + 579
,I/SA      ( 6177): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6177): AsyncTask #2 calls detatch()
,I/SA      ( 6177): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6177): [OCP] update openData : PL
,I/SA      ( 6177): [TPMU] getNetworkMcc : 
,I/SA      ( 6177): [SCU] saveMccToPreferece Start
,I/SA      ( 6177): [SCU] RegionMCC : 260
I/SA      ( 6177): [SSP] query invoked
,I/SA      ( 6177): [TPMU] GetMccFromDB : null
I/SA      ( 6177): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6177): [SCU] saveMccToPreferece End
I/SA      ( 6177): [RC New] executeRequest [v2liruge] end. 654
I/SA      ( 6177): [RC New] Execute end
I/SA      ( 6177): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6177): [OR] GetMyCountryZoneTask Success
,E/SMD     (  287): DCD OFF
,I/dhcpcd  ( 6357): wlan0: sending IPv6 Router Solicitation
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WearableService( 4477): callingUid 10012, callindPid: 4477
I/MusicLeanback( 6332): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6332): Stop autocaching.
,E/GmsUtils( 6332): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6332): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4256, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging,
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/SurfaceFlinger(  256): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  256): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1013): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1013) eventTime = 96784
D/PowerManagerService( 1013): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1013 (0x0)
,D/PowerManagerService( 1013): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1013, ws=WorkSource{10054}) (elapsedTime=3482)
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6499): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1013): waitForAlarm result :4
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,E/SMD     (  287): DCD OFF
,I/ActivityManager( 1013): Waited long enough for: ServiceRecord{32dff68f u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/GCM     ( 1714): Connected
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1714): Message class com.google.f.a.a.p
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5828): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5828): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5828): [GetString-S]
,I/ReactiveServiceManager( 5828): Supported : 1
,D/QSEECOMAPI: ( 1013): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1013): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1013): Loaded image: APP id = 12
,D/QSEECOMAPI: ( 1013): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1013): QSEECom_shutdown_app, app_id = 12
,E/terrier ( 1013): handleString: Failed to handle string(-4)
,E/terrier ( 1013): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5828): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5828): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5828): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5828): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5828): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5828): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 6357): wlan0: sending IPv6 Router Solicitation
,D/SSRM:n  ( 1013): SIOP:: AP = 340
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6704): MountEmulatedStorage()
,E/Zygote  ( 6704): v2
I/libpersona( 6704): KNOX_SDCARD checking this for 10028
,I/libpersona( 6704): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6704 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6704): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6704): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6704): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6704): TimaSignature is unavailable
,D/ActivityThread( 6704): Added TimaKeyStore provider
,D/Finsky  ( 6704): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6704): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/Settings( 6704): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6704): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/AlarmManager( 1013): waitForAlarm result :4
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6704): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6704): [1] 2.run: Finished loading 1 libraries.
,I/dhcpcd  ( 6357): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6357): wlan0: no IPv6 Routers available
,D/Finsky  ( 6704): [1144] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6704): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6704): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6704): [1144] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/Finsky  ( 6704): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6704): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6704): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6704): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager( 1013): Killing 6058:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,W/libprocessgroup( 1013): failed to open /acct/uid_10053/pid_6058/cgroup.procs: No such file or directory
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6224): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6224): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6224): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6224): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6224): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6224): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6224): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6224): entry::IDLE
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1013): waitForAlarm result :4
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6704): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6704): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6704): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6224): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6224): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6224): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 6224): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6224): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6224): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6224): entry::IDLE
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 23976(1205KB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 27MB/41MB, paused 2.527ms total 150.194ms
,W/Finsky  ( 6704): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6704): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6704): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6704): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1689): client connected with version: 7571000
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4266, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1013): !@Sync 3
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1013): waitForAlarm result :4
,D/SSRM:n  ( 1013): SIOP:: AP = 320
,I/PowerManagerService( 1013): [PWL] Off : 30s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/FactoryTest( 5628): Not factory mode
,D/FactoryTest( 5628): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5628): DRIVER_TIME_OUT 60s lapsed,
D/MTPRx   ( 5628): still no open session command from host, so toast
W/ContextImpl( 5628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
I/Timeline( 5628): Timeline: Activity_launch_request id:com.android.settings time:117040
W/ContextImpl( 5628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
E/PersonaManagerService( 1013): inState():  stateMachine is null !!,
I/PersonaManagerService( 1013): PersonaId don't exist
I/ActivityManager( 1013): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings,
W/ActivityManager( 1013): mDVFSHelper.acquire()
,D/PersonaManager( 1013): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1013): Focused application set to: xxxx
,D/InputDispatcher( 1013): Focus left window: 6080
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,E/MTPRx   ( 5628): started activity for popup
,W/ResourcesManager( 5628): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5628): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5628): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5628): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5628): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5628): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5628): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1013): Focused application set to: xxxx
,D/InputDispatcher( 1013): Focus entered window: 6080
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/InputMethodManagerService( 1013): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1013): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1a3f2118 attribute=null, token = android.os.BinderProxy@1de882a4
,D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,D/SettingsReceiverActivity( 5628): dev.kiessupport is : TRUE
,D/PhoneWindow( 5628): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5628): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1013): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1013): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1013): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1013): handleActiveUserChange for user 0
D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
,V/ActivityThread( 6080): updateVisibility : ActivityRecord{17fbaf66 token=android.os.BinderProxy@4a7a4a8 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6080): Timeline: Activity_idle id: android.os.BinderProxy@4a7a4a8 time:117220
,D/PersonaManager( 1013): isKioskContainerExistOnDevice
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 300
,W/ActivityManager( 1013): mDVFSHelper.release()
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,V/AlarmManager( 1013): waitForAlarm result :4
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6704): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6704): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6704): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,E/SQLiteLog( 1714): (10) POSIX Error : 11 SQLite Error : 3850
,V/AlarmManager( 1013): waitForAlarm result :4
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/BooksSync( 6499): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6499): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1013): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1013): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/art     ( 1714): Explicit concurrent mark sweep GC freed 29490(1714KB) AllocSpace objects, 10(360KB) LOS objects, 39% free, 10MB/17MB, paused 2.619ms total 61.409ms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6499): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6499): Soft error
E/BooksSync( 6499): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6499): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6499): Sync error
E/BooksSync( 6499): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6499): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6499): Finished books sync
,D/SyncManager( 1013): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 125311, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1013): mCursor = null
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4272, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1013): stay LED for charging
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1013): Plugged,
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1013): SIOP:: AP = 300
,I/PowerManagerService( 1013): [PWL] Off : 50s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4275, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1013): !@Sync 4
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1013): SIOP:: AP = 290
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager( 1013): waitForAlarm result :4
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6704): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6704): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6704): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 290
,V/AlarmManager( 1013): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,I/PowerManagerService( 1013): [PWL] Off : 75s ago
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1013): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1013): SIOP:: AP = 290
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1013): waitForAlarm result :4
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6704): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6704): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6704): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1013): !@Sync 5
,D/SSRM:n  ( 1013): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4278, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1013): [PWL] Off : 105s ago
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1013): waitForAlarm result :4
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6704): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6704): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6704): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1013): waitForAlarm result :4
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6499): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6499): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1013): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1013): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6499): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6499): Soft error
E/BooksSync( 6499): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6499): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
E/BooksSync( 6499): Sync error
E/BooksSync( 6499): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6499): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6499): Finished books sync
,D/SyncManager( 1013): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 190977, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1013): mCursor = null
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1013): !@Sync 6
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1013): waitForAlarm result :4
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1714): Vacuum at: now=1452246594500 tag=VacuumService
,I/GoogleURLConnFactory( 1714): Using platform SSLCertificateSocketFactory
,W/Uploader( 1714): No account for auth token provided
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1714): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1714): (HTTPLog)-Static: isShipBuild true
I/System.out( 1714): (HTTPLog)-Thread-203-295560840: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1714): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10012
,I/qtaguid ( 1714): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10012
,W/Uploader( 1714): No account for auth token provided
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10012
,W/Uploader( 1714): No account for auth token provided
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10012
,W/Uploader( 1714): No account for auth token provided
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10012
,W/Uploader( 1714):  no longer exists, so no auth token.
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10012
,W/Uploader( 1714): No account for auth token provided
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10012
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 44710(2MB) AllocSpace objects, 45(760KB) LOS objects, 33% free, 27MB/41MB, paused 2.597ms total 165.782ms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1013): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1013): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,E/Uploader( 1714): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1714): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10012
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  287): DCD OFF
,E/SQLiteLog( 1714): (10) POSIX Error : 11 SQLite Error : 3850
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4278, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,V/AlarmManager( 1013): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1013): [PWL] Off : 140s ago
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1013): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1,
D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/Watchdog( 1013): !@Sync 7
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4281, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1013): !@Sync 8
,I/PowerManagerService( 1013): [PWL] Off : 180s ago
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,V/AlarmManager( 1013): waitForAlarm result :8
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1013): !@Sync 9
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1013): stay LED for charging
I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/jxcore-log( 6080): Connected to the server!
I/jxcore-log( 6080): 
,I/chromium( 6080): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/PowerManagerService( 1013): [PWL] Off : 225s ago
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,D/TimaService( 1013): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1013): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1013): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1013): initializing...,
I/TLC_TIMA_PKM_initialize( 1013): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1013): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1013): root = /firmware/image, root_len = 15,
I/TZ: qc_tlc_communication( 1013): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1013): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1013): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1013): max_message_size = 524416 = 0x80080,
D/QSEECOMAPI: ( 1013): QSEECom_get_handle sb_length = 0x80080,
D/QSEECOMAPI: ( 1013): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1013): Loaded image: APP id = 13
,I/TZ: qc_tlc_communication( 1013): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1013): Trustlet response is completed
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4277, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/TLC_TIMA_PKM_measure_kernel( 1013): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1013): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1013): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1013): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1013): !@Sync 10
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1013): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6499): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6499): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1013): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1013): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6499): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6499): Soft error
E/BooksSync( 6499): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6499): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6499): Sync error
E/BooksSync( 6499): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6499): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6499): Finished books sync
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/SyncManager( 1013): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 321984, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1013): mCursor = null
,E/SMD     (  287): DCD OFF
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,V/AlarmManager( 1013): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1013): !@Sync 11
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,V/AlarmManager( 1013): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,I/PowerManagerService( 1013): [PWL] Off : 275s ago,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4281, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4278, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1013): !@Sync 12
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4281, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,V/AlarmManager( 1013): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1013): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1013): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,W/GLSActivity( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1714): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1714): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1714): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 6704): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6704): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6704): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6704): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6704): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6704): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6704): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 6704): Ignoring header User-Agent because its value was null.
,I/System.out( 6704): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6704): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6704): (HTTPLog)-Static: isShipBuild true
I/System.out( 6704): (HTTPLog)-Thread-1168-335520329: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6704): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10028
,I/System.out( 6704): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1013): !@Sync 13
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1013): [PWL] Off : 330s ago
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4278, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6080): --- start :testFindPeers.js---
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): testFindPeers created [object Object]
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): serverPort is 8876
I/jxcore-log( 6080): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): start: Peer ID: 7C:F9:0E:51:18:22, peer name: Thali Test (Galaxy A5)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6080): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6080): initialize: My bluetooth address is 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6080): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): startListeningForIncomingConnections: Starting...
,D/BluetoothSocket( 6080): bindListen(): myUserId = 0
,W/BluetoothAdapter( 6080): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6080): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,D/BluetoothSocket( 6080): bindListen(), new LocalSocket 
D/BluetoothSocket( 6080): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6080): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9d1b6d7
D/BluetoothSocket( 6080): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): start: OK
,I/io.jxcore.node.ConnectionHelper( 6080): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): start: Peer ID: 7C:F9:0E:51:18:22, peer name: Thali Test (Galaxy A5)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6080): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6080): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): start: {"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6080): start: Identity string: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1013): InactiveState{ what=139292 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 1013): P2pEnabledState add service
,D/WifiP2pService( 1013): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): start: Starting P2P device discovery...
,D/WifiP2pService( 1013): InactiveState{ what=139265 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139265 }
D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6080): start: OK
,I/jxcore-log( 6080): StartBroadcasting started ok
I/jxcore-log( 6080): 
,I/chromium( 6080): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 6080): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6080): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6080): onDiscoveryManagerStateChanged: RUNNING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: STARTED
,D/WifiP2pService( 1013): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 },
D/WifiP2pService( 1013): InactiveState{ what=147477 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 },
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 3 device(s) discovered
D/WifiDisplayController( 1013): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 1013): InactiveState{ what=139301 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1013): P2pEnabledState add service request
,D/WifiP2pManager( 6080): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service request added successfully
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
,D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
,D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 6 device(s) discovered
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 6 device(s) discovered
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1013): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42,
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 1013): InactiveState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState discover services
,D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 2143): p2p0: P2P: Reject scan trigger since one is already pending,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service discovery started successfully
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2143): p2p0: P2P: Reject scan trigger since one is already pending,
I/wpa_supplicant( 2143): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
,D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 Nexus 5]
,I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 6080): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 Nexus 5] is available
,I/jxcore-log( 6080): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"Nexus 5","peerAvailable":true}]
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 6080): 
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC One M8s]
,I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 6080): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC One M8s] is available
,I/jxcore-log( 6080): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC One M8s","peerAvailable":true}]
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): Found peer : 90:E7:C4:F6:69:77, peerAvailable: true
I/jxcore-log( 6080): 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4273, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
D/BatteryService( 1013): stay LED for charging
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10,
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1013): !@Sync 14
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4277, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: RESTARTING
,D/WifiP2pService( 1013): InactiveState{ what=139268 },
I/wpa_supplicant( 2143): P2P-FIND-STOPPED 
,D/WifiP2pService( 1013): InactiveState{ what=147493 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1013): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): Start timer timeout, starting now...
,D/WifiP2pService( 1013): InactiveState{ what=139265 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139265 }
,D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): P2P device discovery started successfully
D/WifiP2pService( 1013): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 6 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1013): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1013): P2pEnabledState{ what=139307 },
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/WifiP2pService( 1013): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): restart: Restarting...
,D/WifiP2pService( 1013): InactiveState{ what=139301 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1013): P2pEnabledState add service request
,D/WifiP2pManager( 6080): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service request added successfully
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/WifiP2pService( 1013): InactiveState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState discover services
,D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service discovery started successfully
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 7 device(s) discovered
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
,D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1013): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,D/io.jxcore.node.ConnectionHelper( 6080): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
I/jxcore-log( 6080): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":true}]
I/jxcore-log( 6080): 
I/jxcore-log( 6080): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 6080): 
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [44:80:EB:7B:5A:05 XT1072]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 XT1072]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07,
D/io.jxcore.node.ConnectionHelper( 6080): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 XT1072] is available
,I/jxcore-log( 6080): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"XT1072","peerAvailable":true}]
I/jxcore-log( 6080): 
I/jxcore-log( 6080): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 6080): 
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6080): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
I/jxcore-log( 6080): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 6080): 
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 },
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
,D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 8 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 6080): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
I/jxcore-log( 6080): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"G3-1","peerAvailable":true}]
,I/jxcore-log( 6080): 
I/jxcore-log( 6080): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 6080): ,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1013): !@Sync 15
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/WifiP2pService( 1013): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6080): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
I/jxcore-log( 6080): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 6080): 
I/jxcore-log( 6080): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 6080): 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4273, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1013): stay LED for charging
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/MotionRecognitionService( 1013): Plugged,
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PowerManagerService( 1013): [PWL] Off : 390s ago
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
,D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): restart: Restarting...
D/WifiP2pService( 1013): InactiveState{ what=139307 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1013): P2pEnabledState clear service request
,D/WifiP2pService( 1013): InactiveState{ what=139301 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1013): P2pEnabledState add service request
,D/WifiP2pManager( 6080): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service request added successfully
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,D/WifiP2pService( 1013): InactiveState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState discover services
,D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service discovery started successfully
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiP2pService( 1013): InactiveState{ what=147494 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6080): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
I/jxcore-log( 6080): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log( 6080): 
I/jxcore-log( 6080): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 6080): ,
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
,D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 1013): InactiveState{ what=147494 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147494 },
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6080): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
I/jxcore-log( 6080): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":true}]
I/jxcore-log( 6080): 
I/jxcore-log( 6080): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 6080): ,
,D/SSRM:n  ( 1013): SIOP:: AP = 270,
,E/SMD     (  287): DCD OFF,
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1013): InactiveState{ what=147477 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437,
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1013): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1013): DefaultState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1013): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
,D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): restart: Restarting...
,D/WifiP2pService( 1013): InactiveState{ what=139307 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1013): P2pEnabledState clear service request
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1013): InactiveState{ what=139301 },
,D/WifiP2pService( 1013): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1013): P2pEnabledState add service request
,D/WifiP2pManager( 6080): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service request added successfully
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/WifiP2pService( 1013): InactiveState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState discover services
,D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service discovery started successfully
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/bootchecker(  309): bootchecker wake up!!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6080): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,I/jxcore-log( 6080): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log( 6080): 
I/jxcore-log( 6080): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 6080): 
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4271, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1013): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC One M8s]
D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
D/WifiP2pService( 1013): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC One M8s]
,I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC One M8s] already in the list, will not add again
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
,D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
,D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 10 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1013): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c,
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42,
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interface,Address: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1013): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1013): P2pEnabledState{ what=139307 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/WifiP2pService( 1013): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1013): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1013): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80,
D/WifiP2pService( 1013): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiP2pManager( 6080): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service request added successfully
,D/WifiP2pService( 1013): InactiveState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1013): P2pEnabledState discover services
,D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service discovery started successfully
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,E/Watchdog( 1013): !@Sync 16
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4277, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1013): stay LED for charging,
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1013): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6080): timeout now
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): weAreDoneNow
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): done, now sending data to server
I/jxcore-log( 6080): 
,E/SMD     (  287): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: RESTARTING
,D/WifiP2pService( 1013): InactiveState{ what=139268 }
,I/wpa_supplicant( 2143): P2P-FIND-STOPPED 
,D/WifiP2pService( 1013): InactiveState{ what=147493 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1013): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1013): !@Sync 17
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4278, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): Start timer timeout, starting now...
,D/WifiP2pService( 1013): InactiveState{ what=139265 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139265 }
D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): P2P device discovery started successfully
D/WifiP2pService( 1013): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1013): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1013): P2pEnabledState{ what=139307 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1013): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/WifiP2pService( 1013): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 1013): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): restart: Restarting...
D/WifiP2pService( 1013): P2pEnabledState add service request
D/WifiP2pManager( 6080): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service request added successfully
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=147477 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1013): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80,
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1013): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1013): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1013): DefaultState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1013): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiP2pService( 1013): InactiveState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1013): P2pEnabledState discover services
,D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 2143): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service discovery started successfully
,I/wpa_supplicant( 2143): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 2143): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
,I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1013): InactiveState{ what=147494 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): InactiveState{ what=139283 },
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,I/PowerManagerService( 1013): [PWL] Off : 455s ago,
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=147477 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1013): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
,D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)],
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4271, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1013): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdevic,eName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6080): teardown
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): testFindPeers stopped
I/jxcore-log( 6080): 
,I/io.jxcore.node.ConnectionHelper( 6080): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): shutdown
D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@3210e973, channel: 6, state: LISTENING
D/BluetoothSocket( 6080): close() this: android.bluetooth.BluetoothSocket@3210e973, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9d1b6d7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3a46a030mSocket: android.net.LocalSocket@2a0104a9 impl:android.net.LocalSocketImpl@3590aa2e fd:FileDescriptor[111]
D/BluetoothSocket( 6080): Closing mSocket: android.net.LocalSocket@2a0104a9 impl:android.net.LocalSocketImpl@3590aa2e fd:FileDescriptor[111]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6080): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): stop: Stopping services
,D/WifiP2pService( 1013): InactiveState{ what=139298 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 1013): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6080): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6080): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6080): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): setState: NOT_STARTED
,I/jxcore-log( 6080): StopBroadcasting went ok
I/jxcore-log( 6080): 
,D/WifiP2pService( 1013): InactiveState{ what=139268 }
I/wpa_supplicant( 2143): P2P-FIND-STOPPED 
,I/jxcore-log( 6080): --- start :testSendData.js---
I/jxcore-log( 6080): 
,D/WifiP2pService( 1013): InactiveState{ what=139307 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1013): P2pEnabledState clear service request
,D/WifiP2pService( 1013): remove channel information from framework
I/jxcore-log( 6080): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":15}bt-address length : 14
I/jxcore-log( 6080): 
D/WifiP2pService( 1013): InactiveState{ what=147493 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1013): discovery change broadcast false
,I/jxcore-log( 6080): daya100000
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): check server
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): serverPort is 53514
I/jxcore-log( 6080): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): start: Peer ID: 7C:F9:0E:51:18:22, peer name: Thali Test (Galaxy A5)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6080): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6080): initialize: My bluetooth address is 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6080): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): startListeningForIncomingConnections: Starting...
,D/BluetoothSocket( 6080): bindListen(): myUserId = 0,
W/BluetoothAdapter( 6080): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket( 6080): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
D/BluetoothSocket( 6080): bindListen(), new LocalSocket 
D/BluetoothSocket( 6080): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6080): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1fad8f5c,
,D/BluetoothSocket( 6080): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): start: OK
I/io.jxcore.node.ConnectionHelper( 6080): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): start: Peer ID: 7C:F9:0E:51:18:22, peer name: Thali Test (Galaxy A5)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6080): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6080): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): start: {"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6080): start: Identity string: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1013): InactiveState{ what=139292 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139292 }
D/WifiP2pService( 1013): P2pEnabledState add service
D/WifiP2pService( 1013): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6080): start: OK
,I/jxcore-log( 6080): StartBroadcasting started ok
I/jxcore-log( 6080): 
D/WifiP2pService( 1013): InactiveState{ what=139265 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139265 }
,D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1013): discovery change broadcast true
,I/jxcore-log( 6080): [ { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log( 6080):   { address: '34:FC:EF:11:AE:67', tryCount: 0 },
I/jxcore-log( 6080):   { address: '08:EC:A9:50:75:41', tryCount: 0 },
I/jxcore-log( 6080):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 6080):   { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log( 6080):   { address: 'E0:DB:10:14:E2:C0', tryCount: 0 },
I/jxcore-log( 6080):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log( 6080):   { address: 'F4:F1:E1:5C:3B:E2', tryCount: 0 },
I/jxcore-log( 6080):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 6080):   { address: '90:E7:C4:F6:69:77', tryCount: 0 },
I/jxcore-log( 6080):   { address: '58:3F:54:73:64:C0', tryCount: 0 },
I/jxcore-log( 6080):   { address: 'F8:95:C7:87:85:54', tryCount: 0 },
I/jxcore-log( 6080):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 6080):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 } ]
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): startWithNextDevice
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): do fake peer & start
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:55:35.930Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:55:35.931Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:55:35.932Z SendDataConnector.js: do connect now
I/jxcore-log( 6080): 
,I/io.jxcore.node.ConnectionHelper( 6080): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 6080): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): connect: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 6080): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 1065)
,I/jxcore-log( 6080): 2016-01-08T09:55:35.949Z SendDataTCPServer.js: TCP/IP server is bound to port: 53514
I/jxcore-log( 6080): 
I/chromium( 6080): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6080): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6080): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6080): Local services cleared successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service requests cleared successfully
I/chromium( 6080): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6080): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onWifiStateChanged: State changed to 2
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6080): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6080): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: STARTED,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WifiP2pService( 1013): InactiveState{ what=139268 }
I/wpa_supplicant( 2143): P2P-FIND-STOPPED 
,D/WifiP2pService( 1013): InactiveState{ what=147493 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): P2P device discovery stopped successfully
,D/WifiP2pService( 1013): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1013): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: RESTARTING
,D/WifiP2pService( 1013): InactiveState{ what=139268 }
,D/BluetoothUtils( 6080): isSocketAllowedBySecurityPolicy start : device null
,D/BluetoothSocket( 6080): connect(): myUserId = 0
W/BluetoothAdapter( 6080): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2626): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 6080): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[114]}
,D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2626): db_query_execute: result 1
,D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2626): db_query_execute: result 1
,W/bt-btif ( 2626): info:x10
,D/        ( 2626): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2626): aclStateChangeCallback: Device is NULL
,E/SMD     (  287): DCD OFF
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = [],
,W/bt-sdp  ( 2626): process_service_search_attr_rsp
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
,I/BluetoothBondStateMachine( 2626): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.NAME_CHANGED
,D/SecContentProvider( 1013): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2626): check_cod: remote_cod = 0x5a020c
V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.CLASS_CHANGED
,I/BluetoothBondStateMachine( 2626): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 2626): isSecureModeOn:false
,I/BluetoothBondStateMachine( 2626): Entering PendingCommandState State
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1172):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1172):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1321): onReceive
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6972): MountEmulatedStorage()
,I/libpersona( 6972): KNOX_SDCARD checking this for 10100
E/Zygote  ( 6972): v2
I/libpersona( 6972): KNOX_SDCARD not a persona
I/SELinux ( 6972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/.GMHFPReceiver: pid=6972 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 6972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6972): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6972): TimaSignature is unavailable
,D/ActivityThread( 6972): Added TimaKeyStore provider
,E/BluetoothHeadset( 6972): BTStateChangeCB is registed
,D/BluetoothHeadset( 6972): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6972): BluetoothHeadset service is binded
D/GMFPReceiver( 6972): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 6972): jangil::setProperties()
,D/GMFPReceiver( 6972): jangil::printBTStatus()
,D/SettingsProvider( 1013): name = Wearable0001
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10100
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10100
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GMFPReceiver( 6972): ::::::::Wearable0001::false
,D/SettingsProvider( 1013): name = Wearable0002
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10100
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10100
,D/GMFPReceiver( 6972): ::::::::Wearable0002::false
,D/GMFPReceiver( 6972): onServiceConnected() : 1
D/GMFPReceiver( 6972): mBluetoothHeadset = true
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1013): Killing 6099:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_6099/cgroup.procs: No such file or directory
,D/btif_config_util( 2626): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2626): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2626): Failed to remove device: B0:C5:59:3F:75:69
,D/SecContentProvider( 1013): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2626): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2626): isSecureModeOn:false
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1172):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1172):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1321): onReceive
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 6972): BTStateChangeCB is registed
,D/BluetoothHeadset( 6972): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,D/HidService( 2626): getHidService(): returning com.android.bluetooth.hid.HidService@3989a195
E/BluetoothHeadset( 6972): BluetoothHeadset service is binded
,D/GMFPReceiver( 6972): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 6972): jangil::setProperties()
,D/SettingsProvider( 1013): name = bluetooth_input_device_priority_B0:C5:59:3F:75:69
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
,D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1013): ret = -1
,D/HidService( 2626): Saved priority B0:C5:59:3F:75:69 = -1
D/GMFPReceiver( 6972): jangil::printBTStatus()
,D/SettingsProvider( 1013): name = bluetooth_a2dp_sink_priority_B0:C5:59:3F:75:69
D/SettingsProvider( 1013): name = Wearable0001
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10100
,D/SettingsProvider( 1013): name = bluetooth_headset_priority_B0:C5:59:3F:75:69
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
I/BluetoothBondStateMachine( 2626): StableState(): Entering Off State
,D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
D/GMFPReceiver( 6972): ::::::::Wearable0001::false
,D/SettingsProvider( 1013): name = Wearable0002
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10100
,D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
D/GMFPReceiver( 6972): ::::::::Wearable0002::false
,D/GMFPReceiver( 6972): onServiceConnected() : 1
D/GMFPReceiver( 6972): mBluetoothHeadset = true
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,W/bt-btif ( 2626): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2626): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2626): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2626): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): onSocketConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1065)
,D/BluetoothSocket( 6080): getInputStream(): myUserId = 0,
D/BluetoothSocket( 6080): getOutputStream(): myUserId = 0,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): onBytesWritten: 81 bytes successfully written (thread ID: 1066),
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Outgoing connection initialized (*handshake* thread ID: 1066)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Exiting thread (thread ID: 1065)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6080): Entering thread (ID: 1066)
,E/SMD     (  287): DCD OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): onBytesRead: Read 81 bytes successfully (thread ID: 1066)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Handshake succeeded with [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): onHandshakeSucceeded: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6080): Exiting thread (ID: 1066)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): onConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/io.jxcore.node.ConnectionHelper( 6080): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/io.jxcore.node.ConnectionHelper( 6080): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
,W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,D/BluetoothSocket( 6080): getInputStream(): myUserId = 0
,D/BluetoothSocket( 6080): getOutputStream(): myUserId = 0
,I/io.jxcore.node.ConnectionHelper( 6080): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 6080): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 6080): Entering thread (ID: 1067)
,D/io.jxcore.node.OutgoingSocketThread( 6080): Server socket local port: 39733
,I/io.jxcore.node.OutgoingSocketThread( 6080): Now accepting connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): Start timer timeout, starting now...
,D/WifiP2pService( 1013): InactiveState{ what=139265 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139265 }
D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1013): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6080): onListeningForIncomingConnections: Outgoing connection is using port 39733 (peer ID: B0:C5:59:3F:75:69)
I/jxcore-log( 6080): 2016-01-08T09:55:40.975Z SendDataConnector.js: CLIENT connected to 39733, error: null
I/jxcore-log( 6080): 
I/jxcore-log( 6080): 2016-01-08T09:55:40.975Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6080): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 6080): 2016-01-08T09:55:40.982Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6080): 
,I/io.jxcore.node.OutgoingSocketThread( 6080): Incoming data from address: /127.0.0.1, port: 39733
D/io.jxcore.node.OutgoingSocketThread( 6080): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6080): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6080): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6080): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6080): Exiting thread (ID: 1067)
,D/io.jxcore.node.StreamCopyingThread( 6080): Entering thread (ID: 1069, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6080): Entering thread (ID: 1068, name: Sender)
,D/        ( 2626): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:9396
,I/jxcore-log( 6080): 2016-01-08T09:55:42.236Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6080): 
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 },
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiP2pService( 1013): InactiveState{ what=139283 },
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1013): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null,, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pManager( 6080): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service request added successfully
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1013): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1013): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pService( 1013): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1013): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/        ( 2626): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:29788
,I/jxcore-log( 6080): 2016-01-08T09:55:42.680Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6080): 
,D/WifiP2pService( 1013): InactiveState{ what=139310 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1013): P2pEnabledState discover services
,D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service discovery started successfully
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6080): 2016-01-08T09:55:43.731Z SendDataConnector.js: CLIENT is data received : 30000,
I/jxcore-log( 6080): 
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,D/        ( 2626): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:7524
,I/jxcore-log( 6080): 2016-01-08T09:55:45.479Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6080): 
,D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2626): db_query_execute: result 1
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6080): 2016-01-08T09:55:46.148Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6080): 
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6080): 2016-01-08T09:55:46.692Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6080): 
,D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2626): db_query_execute: result 1
,W/bt-btif ( 2626): info:x10
,D/        ( 2626): remote version info [7c:f9:0e:37:96:ab]: 0, 0, 0
,E/BluetoothRemoteDevices( 2626): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2626): tBTM_SEC_DEV:0xa461c0d8 rs_disc_pending=1
,W/bt-btif ( 2626): bta_dm_check_av:0
,W/bt-btif ( 2626): btif_dm_cback : unhandled event (14)
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
,E/bt-btm  ( 2626): tBTM_SEC_DEV:0xa461c0d8 rs_disc_pending=1
,W/bt-btif ( 2626): bta_dm_check_av:0
W/bt-btif ( 2626): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6080): 2016-01-08T09:55:48.029Z SendDataConnector.js: CLIENT is data received : 70000,
I/jxcore-log( 6080): 
,E/Watchdog( 1013): !@Sync 18
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 6080): 2016-01-08T09:55:48.643Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6080): 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4267, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/jxcore-log( 6080): 2016-01-08T09:55:49.016Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6080): 
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6080): 2016-01-08T09:55:49.850Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:55:49.851Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): oneRoundDownNow
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:55:49.854Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:55:49.855Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6080): 
,D/io.jxcore.node.ConnectionHelper( 6080): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
,I/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
,I/io.jxcore.node.OutgoingSocketThread( 6080): close
D/io.jxcore.node.OutgoingSocketThread( 6080): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6080): doStop: Thread ID: 1069
,D/io.jxcore.node.OutgoingSocketThread( 6080): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6080): doStop: Thread ID: 1068
D/io.jxcore.node.OutgoingSocketThread( 6080): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6080): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6080): Either failed to read from the output stream or write to the input stream (thread ID: 1068, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6080): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6080): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6080): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6080): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6080): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@1ee13eb, channel: 6, state: CONNECTED
,D/BluetoothSocket( 6080): close() this: android.bluetooth.BluetoothSocket@1ee13eb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f324548, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7339fe1mSocket: android.net.LocalSocket@14b7d106 impl:android.net.LocalSocketImpl@49803c7 fd:FileDescriptor[114]
D/BluetoothSocket( 6080): Closing mSocket: android.net.LocalSocket@14b7d106 impl:android.net.LocalSocketImpl@49803c7 fd:FileDescriptor[114]
,W/io.jxcore.node.StreamCopyingThread( 6080): Either failed to read from the output stream or write to the input stream (thread ID: 1069, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6080): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6080): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@1ee13eb, channel: 6, state: CLOSED
,D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@1ee13eb, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6080): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
E/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6080): Exiting thread (ID: 1068, name: Sender)
E/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6080): Exiting thread (ID: 1069, name: Receiver)
I/jxcore-log( 6080): 2016-01-08T09:55:49.874Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): ---- round done--------
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): startWithNextDevice
I/jxcore-log( 6080): 
I/jxcore-log( 6080): do fake peer & start
I/jxcore-log( 6080): 
I/jxcore-log( 6080): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
I/jxcore-log( 6080): 2016-01-08T09:55:49.877Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
I/jxcore-log( 6080): 2016-01-08T09:55:49.877Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
I/jxcore-log( 6080): 2016-01-08T09:55:49.877Z SendDataConnector.js: do connect now
I/jxcore-log( 6080): 
,I/io.jxcore.node.ConnectionHelper( 6080): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6080): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): connect: [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): onConnecting: null 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6080): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 1070)
,D/BluetoothUtils( 6080): isSocketAllowedBySecurityPolicy start : device null
,D/BluetoothSocket( 6080): connect(): myUserId = 0
W/BluetoothAdapter( 6080): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2626): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 2626): db_query_execute: result 1
D/BluetoothSocket( 6080): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.CLASS_CHANGED
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
I/BluetoothBondStateMachine( 2626): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,D/SecContentProvider( 1013): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2626): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2626): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11,
,D/BtConfig.SecureMode( 2626): isSecureModeOn:false
I/BluetoothBondStateMachine( 2626): Entering PendingCommandState State
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver onReceive,
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED,
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.BOND_STATE_CHANGED
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,W/bt-btif ( 2626): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
D/BluetoothTile( 1172):  onBluetoothPairedDevicesChanged:
,D/BluetoothNotiBroadcastReceiver( 1321): onReceive
,D/BluetoothTile( 1172):  handleUpdatestate:false name:null
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 6972): BTStateChangeCB is registed
,D/BluetoothHeadset( 6972): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6972): BluetoothHeadset service is binded
D/GMFPReceiver( 6972): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 6972): jangil::setProperties()
,D/GMFPReceiver( 6972): jangil::printBTStatus()
,D/SettingsProvider( 1013): name = Wearable0001
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10100
,D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
D/GMFPReceiver( 6972): ::::::::Wearable0001::false
,D/SettingsProvider( 1013): name = Wearable0002
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10100
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,D/GMFPReceiver( 6972): ::::::::Wearable0002::false
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/GMFPReceiver( 6972): onServiceConnected() : 1
D/GMFPReceiver( 6972): mBluetoothHeadset = true
,D/btif_config_util( 2626): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2626): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2626): Failed to remove device: 7C:F9:0E:37:96:AB
,D/SecContentProvider( 1013): uri = 4 selection = bluetoothLogForRemote
,D/BluetoothTile( 1172):  onBluetoothPairedDevicesChanged:
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,I/BluetoothBondStateMachine( 2626): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2626): isSecureModeOn:false
,D/HidService( 2626): getHidService(): returning com.android.bluetooth.hid.HidService@3989a195
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/SettingsProvider( 1013): name = bluetooth_input_device_priority_7C:F9:0E:37:96:AB
D/BluetoothTile( 1172):  handleUpdatestate:false name:null
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/HidService( 2626): Saved priority 7C:F9:0E:37:96:AB = -1
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/SettingsProvider( 1013): name = bluetooth_a2dp_sink_priority_7C:F9:0E:37:96:AB
,D/BluetoothNotiBroadcastReceiver( 1321): onReceive
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1013): ret = -1
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
D/SettingsProvider( 1013): name = bluetooth_headset_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
I/BluetoothBondStateMachine( 2626): StableState(): Entering Off State
,E/BluetoothHeadset( 6972): BTStateChangeCB is registed
,D/BluetoothHeadset( 6972): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6972): BluetoothHeadset service is binded
,D/GMFPReceiver( 6972): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 6972): jangil::setProperties()
,D/GMFPReceiver( 6972): jangil::printBTStatus()
,D/SettingsProvider( 1013): name = Wearable0001
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1013): selectionArgs: false
,D/SettingsProvider( 1013): selectionArgs: 10100
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1013): ret = -1
,D/GMFPReceiver( 6972): ::::::::Wearable0001::false
,D/SettingsProvider( 1013): name = Wearable0002
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10100
,D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,D/GMFPReceiver( 6972): ::::::::Wearable0002::false
D/GMFPReceiver( 6972): onServiceConnected() : 1
D/GMFPReceiver( 6972): mBluetoothHeadset = true
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,E/bt-btm  ( 2626): tBTM_SEC_DEV:0xa461c29c rs_disc_pending=1
,W/bt-btif ( 2626): bta_dm_check_av:0
,W/bt-btif ( 2626): btif_dm_cback : unhandled event (14)
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1013): InactiveState{ what=147477 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
,D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): restart: Restarting...
,D/WifiP2pService( 1013): InactiveState{ what=139307 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1013): P2pEnabledState clear service request
,D/WifiP2pService( 1013): InactiveState{ what=139301 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1013): P2pEnabledState add service request
,D/WifiP2pManager( 6080): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service request added successfully
,D/WifiP2pService( 1013): InactiveState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState discover services
D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service discovery started successfully
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1],
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1013): InactiveState{ what=147494 },
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 },
,D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local.",
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1],
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState receive service response,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC One M8s]
,I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
,W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC One M8s] already in the list, will not add again
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,D/io.jxcore.node.ConnectionHelper( 6080): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1013): InactiveState{ what=147477 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 },
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
,D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 },
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1013): InactiveState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): restart: Restarting...
D/WifiP2pService( 1013): InactiveState{ what=139307 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139307 },
D/WifiP2pService( 1013): P2pEnabledState clear service request
,D/WifiP2pService( 1013): InactiveState{ what=139301 }
D/WifiP2pManager( 6080): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1013): P2pEnabledState{ what=139301 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service request added successfully
D/WifiP2pService( 1013): P2pEnabledState add service request
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/bt-btm  ( 2626): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2626): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1172): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver onReceive,
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1321): ACTION_ACL_DISCONNECTED
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
,D/KeyguardViewMediator( 1172): isGear1: device is not B1!
,D/BluetoothAdapterService( 2626): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c8f7edb
,D/BtConfig.SecureMode( 2626): isSecureModeOn:false
,D/SecContentProvider( 1013): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothPbapService( 2626): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6196): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6196): Bluetooth Device Name: A5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): onConnectionTimeout: [34:FC:EF:11:AE:67 Nexus 5]
,I/jxcore-log( 6080): 2016-01-08T09:56:04.887Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [34:FC:EF:11:AE:67 Nexus 5] timed out
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:56:04.888Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [34:FC:EF:11:AE:67 Nexus 5] timed out
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:56:04.889Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6080): 
,D/WifiP2pService( 1013): InactiveState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState discover services
,D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service discovery started successfully,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1],
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 6080): 2016-01-08T09:56:09.890Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67,
I/jxcore-log( 6080): 
I/jxcore-log( 6080): 2016-01-08T09:56:09.891Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,W/bt-btm  ( 2626): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 2626): tBTM_SEC_DEV:0xa461c0d8 rs_disc_pending=2
W/bt-btif ( 2626): bta_dm_check_av:0
W/bt-btif ( 2626): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2626): Reset sec_bd_name and name flag. (BR/EDR link)
E/bt-btm  ( 2626): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 0:0
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2626): db_query_execute: result 1
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
,D/KeyguardViewMediator( 1172): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver onReceive
V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_ACL_DISCONNECTED
E/BluetoothEventManager( 1321): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2626): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c8f7edb
,D/BtConfig.SecureMode( 2626): isSecureModeOn:false
,D/SecContentProvider( 1013): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/KeyguardViewMediator( 1172): isGear1: device is not B1!
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2626): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6196): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6196): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/Atfwd_Daemon(  313): Stop the daemon....,
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1013): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6499): Starting books sync for 61035162, extras: ade
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6499): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1013): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1013): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksAccountManager( 6499): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6499): Soft error
E/BooksSync( 6499): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6499): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6499): Sync error
E/BooksSync( 6499): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6499): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6499): Finished books sync
,D/SyncManager( 1013): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 583789, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1013): mCursor = null
,D/io.jxcore.node.ConnectionHelper( 6080): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
,E/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6080): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:AE:67), either no such connection or failed to close the connection
,I/jxcore-log( 6080): 2016-01-08T09:56:14.894Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:56:14.895Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 6080): 
I/jxcore-log( 6080): 2016-01-08T09:56:14.896Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:56:14.896Z SendDataConnector.js: do connect now
I/jxcore-log( 6080): 
,I/io.jxcore.node.ConnectionHelper( 6080): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6080): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): connect: [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): onConnecting: null 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6080): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 1072)
,D/BluetoothUtils( 6080): isSocketAllowedBySecurityPolicy start : device null
,D/BluetoothSocket( 6080): connect(): myUserId = 0
W/BluetoothAdapter( 6080): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2626): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 6080): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1013): !@Sync 19
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): onConnectionTimeout: [34:FC:EF:11:AE:67 Nexus 5]
,I/jxcore-log( 6080): 2016-01-08T09:56:29.903Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [34:FC:EF:11:AE:67 Nexus 5] timed out
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:56:29.904Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [34:FC:EF:11:AE:67 Nexus 5] timed out
I/jxcore-log( 6080): 
I/jxcore-log( 6080): 2016-01-08T09:56:29.904Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6080): 
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: RESTARTING
,D/WifiP2pService( 1013): InactiveState{ what=139268 }
I/wpa_supplicant( 2143): P2P-FIND-STOPPED 
,D/WifiP2pService( 1013): InactiveState{ what=147493 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1013): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,I/PowerManagerService( 1013): [PWL] Off : 525s ago
,I/PowerManagerService( 1013): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1013): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1013): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=2626, ws=null) (elapsedTime=58328)
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6080): 2016-01-08T09:56:34.905Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:56:34.906Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
,E/SMD     (  287): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): Start timer timeout, starting now...
,D/WifiP2pService( 1013): InactiveState{ what=139265 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139265 }
D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1013): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4271, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/io.jxcore.node.ConnectionHelper( 6080): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
,E/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6080): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:AE:67), either no such connection or failed to close the connection
,I/jxcore-log( 6080): 2016-01-08T09:56:39.910Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
I/jxcore-log( 6080): 2016-01-08T09:56:39.911Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:56:39.911Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
I/jxcore-log( 6080): 2016-01-08T09:56:39.912Z SendDataConnector.js: do connect now
I/jxcore-log( 6080): 
,I/io.jxcore.node.ConnectionHelper( 6080): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6080): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): connect: [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): onConnecting: null 34:FC:EF:11:AE:67
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6080): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 1074)
,D/BluetoothUtils( 6080): isSocketAllowedBySecurityPolicy start : device null
,D/BluetoothSocket( 6080): connect(): myUserId = 0
W/BluetoothAdapter( 6080): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2626): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 6080): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): restart: Restarting...
,D/WifiP2pService( 1013): InactiveState{ what=139307 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1013): P2pEnabledState clear service request
,D/WifiP2pService( 1013): InactiveState{ what=139301 },
,D/WifiP2pService( 1013): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1013): P2pEnabledState add service request
,D/WifiP2pManager( 6080): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service request added successfully
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,V/AlarmManager( 1013): waitForAlarm result :4
,D/WifiP2pService( 1013): InactiveState{ what=139310 },
D/WifiP2pService( 1013): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1013): P2pEnabledState discover services
,D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service discovery started successfully
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 0:0
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2626): db_query_execute: result 1
,D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2626): db_query_execute: result 1
,W/bt-btif ( 2626): info:x10
,D/        ( 2626): remote version info [7c:f9:0e:37:96:ab]: 7, f, 610c
,D/KeyguardViewMediator( 1172): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_ACL_CONNECTED
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1321): onReceive
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.NAME_CHANGED
,D/KeyguardViewMediator( 1172): isGear1: device is not B1!
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6196): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6196): Bluetooth Device Name: A5-1
,W/bt-btif ( 2626): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2626): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2626): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket( 6080): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@38ca6df4
,E/BluetoothRemoteDevices( 2626): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): Incoming connection accepted
,D/BluetoothSocket( 6080): getInputStream(): myUserId = 0
,D/BluetoothSocket( 6080): getOutputStream(): myUserId = 0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): Incoming connection initialized (thread ID: 1075)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6080): Entering thread (ID: 1075)
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1013): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F,204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1013): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,W/bt-btif ( 2626): invalid rfc slot id: 5,
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6080): Disconnected: bt socket closed, read return: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): removeThreadFromList: Removing thread with ID 1075
D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@1a69591d, channel: 6, state: CONNECTED
D/BluetoothSocket( 6080): close() this: android.bluetooth.BluetoothSocket@1a69591d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@216ff792, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@27071563mSocket: android.net.LocalSocket@341a7560 impl:android.net.LocalSocketImpl@27476a19 fd:FileDescriptor[114]
D/BluetoothSocket( 6080): Closing mSocket: android.net.LocalSocket@341a7560 impl:android.net.LocalSocketImpl@27476a19 fd:FileDescriptor[114]
,D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@1a69591d, channel: 6, state: CLOSED
D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@1a69591d, channel: 6, state: CLOSED
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): Handshake failed (thread ID: 1075)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6080): Exiting thread (ID: 1075)
,W/bt-rfcomm( 2626): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0,
W/bt-rfcomm( 2626): RFCOMM_DisconnectInd LCID:0x46
,D/TimaService( 1013): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1013): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1013): TimaServiceHandler.handleMessage what =1
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1013): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1013): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1013): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1013): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/Watchdog( 1013): !@Sync 20
,E/bt-btm  ( 2626): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2626): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1172): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1321): ACTION_ACL_DISCONNECTED
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2626): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c8f7edb
,D/BtConfig.SecureMode( 2626): isSecureModeOn:false
,D/SecContentProvider( 1013): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2626): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
D/KeyguardViewMediator( 1172): isGear1: device is not B1!
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6196): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6196): Bluetooth Device Name: A5-1
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/bt-btif ( 2626): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0,
D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:24841,
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value 1
D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@2411fade, channel: -1, state: INIT
D/BluetoothSocket( 6080): close() this: android.bluetooth.BluetoothSocket@2411fade, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3bcba4bf, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2ca1878cmSocket: android.net.LocalSocket@1a5b8ed5 impl:android.net.LocalSocketImpl@2c3ee6ea fd:FileDescriptor[115]
D/BluetoothSocket( 6080): Closing mSocket: android.net.LocalSocket@1a5b8ed5 impl:android.net.LocalSocketImpl@2c3ee6ea fd:FileDescriptor[115]
,D/IOP_DB_BT( 2626): db_query_execute: result 1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1070)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1070)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Exiting thread (thread ID: 1070)
,W/bt-btif ( 2626): invalid rfc slot id: 7
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): shutdown (thread ID: 1070)
D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@2411fade, channel: -1, state: CLOSED
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:AE:67 Nexus 5]
,I/jxcore-log( 6080): 2016-01-08T09:56:49.653Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [34:FC:EF:11:AE:67 Nexus 5] failed
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:56:49.654Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [34:FC:EF:11:AE:67 Nexus 5] failed
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:56:49.654Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6080): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/SSRM:n  ( 1013): SIOP:: AP = 290
,D/btif_config_util( 2626): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1013): InactiveState{ what=139307 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1013): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1013): P2pEnabledState clear service request,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): restart: Restarting...
,D/WifiP2pService( 1013): InactiveState{ what=139301 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1013): P2pEnabledState add service request
D/WifiP2pManager( 6080): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service request added successfully
,D/WifiP2pService( 1013): InactiveState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState discover services
,D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true,
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service discovery started successfully
,I/jxcore-log( 6080): 2016-01-08T09:56:54.654Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:56:54.655Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
,E/SMD     (  287): DCD OFF
,W/bt-sdp  ( 2626): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2626): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 2626): db_query_execute: result 1
W/bt-btif ( 2626): invalid rfc slot id: 8
D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@41fcddb, channel: -1, state: INIT
D/BluetoothSocket( 6080): close() this: android.bluetooth.BluetoothSocket@41fcddb, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4a59078, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@21534351mSocket: android.net.LocalSocket@309c87b6 impl:android.net.LocalSocketImpl@10c36cb7 fd:FileDescriptor[116]
D/BluetoothSocket( 6080): Closing mSocket: android.net.LocalSocket@309c87b6 impl:android.net.LocalSocketImpl@10c36cb7 fd:FileDescriptor[116]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1072)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1072)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Exiting thread (thread ID: 1072)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): shutdown (thread ID: 1072),
D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@41fcddb, channel: -1, state: CLOSED
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/io.jxcore.node.ConnectionHelper( 6080): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
,E/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6080): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:AE:67), either no such connection or failed to close the connection
,I/jxcore-log( 6080): 2016-01-08T09:56:59.659Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:56:59.660Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 6080): 
I/jxcore-log( 6080): 2016-01-08T09:56:59.660Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:56:59.661Z SendDataConnector.js: do connect now
I/jxcore-log( 6080): 
,I/io.jxcore.node.ConnectionHelper( 6080): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6080): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): connect: [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): onConnecting: null 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6080): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 1077)
,D/BluetoothUtils( 6080): isSocketAllowedBySecurityPolicy start : device null
,D/BluetoothSocket( 6080): connect(): myUserId = 0
,W/BluetoothAdapter( 6080): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2626): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 6080): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,V/AlarmManager( 1013): waitForAlarm result :8
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=139283 },
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 },
,D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiP2pService( 1013): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80,
D/WifiP2pService( 1013): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService( 1013): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1013): InactiveState{ what=139301 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1013): P2pEnabledState{ what=139301 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1013): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): restart: Restarting...
D/WifiP2pManager( 6080): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service request added successfully
,W/bt-sdp  ( 2626): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2626): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
W/bt-btif ( 2626): invalid rfc slot id: 9
D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@3adf3c24, channel: -1, state: INIT
D/BluetoothSocket( 6080): close() this: android.bluetooth.BluetoothSocket@3adf3c24, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d37c38d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1a616942mSocket: android.net.LocalSocket@14981d53 impl:android.net.LocalSocketImpl@1ee5f690 fd:FileDescriptor[117]
D/BluetoothSocket( 6080): Closing mSocket: android.net.LocalSocket@14981d53 impl:android.net.LocalSocketImpl@1ee5f690 fd:FileDescriptor[117]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1074)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1074)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Exiting thread (thread ID: 1074)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): shutdown (thread ID: 1074)
D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@3adf3c24, channel: -1, state: CLOSED
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:AE:67 Nexus 5]
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 2626): db_query_execute: result 1
D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value *
I/jxcore-log( 6080): 2016-01-08T09:57:06.543Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [34:FC:EF:11:AE:67 Nexus 5] failed
I/jxcore-log( 6080): 
D/IOP_DB_BT( 2626): db_query_execute: result 1
I/jxcore-log( 6080): 2016-01-08T09:57:06.543Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [34:FC:EF:11:AE:67 Nexus 5] failed
I/jxcore-log( 6080): 
I/jxcore-log( 6080): 2016-01-08T09:57:06.544Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6080): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2626): db_query_execute: result 1
,W/bt-btif ( 2626): info:x10
D/        ( 2626): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2626): aclStateChangeCallback: Device is NULL
,D/WifiP2pService( 1013): InactiveState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1013): P2pEnabledState discover services
,D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service discovery started successfully
,E/SMD     (  287): DCD OFF
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,D/SSRM:n  ( 1013): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
,I/jxcore-log( 6080): 2016-01-08T09:57:11.545Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:57:11.546Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
,D/btif_config_util( 2626): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6080): timeout now
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): weAreDoneNow, resultArray.length: 1
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): sendReportNow
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): done, now sending data to server
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:57:15.958Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6080): 
,D/io.jxcore.node.ConnectionHelper( 6080): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
,E/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6080): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:AE:67), either no such connection or failed to close the connection
,I/jxcore-log( 6080): 2016-01-08T09:57:15.962Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
,D/io.jxcore.node.ConnectionHelper( 6080): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
,E/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6080): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:AE:67), either no such connection or failed to close the connection
,I/jxcore-log( 6080): 2016-01-08T09:57:16.550Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:57:16.550Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 6080): 
I/jxcore-log( 6080): 2016-01-08T09:57:16.551Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:57:16.551Z SendDataConnector.js: do connect now
I/jxcore-log( 6080): 
,I/io.jxcore.node.ConnectionHelper( 6080): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6080): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): connect: [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): onConnecting: null 34:FC:EF:11:AE:67
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6080): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 1079)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6080): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,D/BluetoothSocket( 6080): connect(): myUserId = 0
,W/BluetoothAdapter( 6080): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2626): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/BluetoothSocket( 6080): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1013): !@Sync 21,
,W/bt-sdp  ( 2626): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
,E/bt-btif ( 2626): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2626): invalid rfc slot id: 11
,D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2626): db_query_execute: result 1
,D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@3c6a0b89, channel: -1, state: INIT
D/BluetoothSocket( 6080): close() this: android.bluetooth.BluetoothSocket@3c6a0b89, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3da0d78e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4fd3bafmSocket: android.net.LocalSocket@205bebbc impl:android.net.LocalSocketImpl@185ed745 fd:FileDescriptor[115]
,D/BluetoothSocket( 6080): Closing mSocket: android.net.LocalSocket@205bebbc impl:android.net.LocalSocketImpl@185ed745 fd:FileDescriptor[115]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1077)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): shutdown (thread ID: 1077)
,D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@3c6a0b89, channel: -1, state: CLOSED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1077)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6080): Exiting thread (thread ID: 1077)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:AE:67 Nexus 5]
,I/jxcore-log( 6080): 2016-01-08T09:57:18.586Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [34:FC:EF:11:AE:67 Nexus 5] failed
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:57:18.586Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [34:FC:EF:11:AE:67 Nexus 5] failed
I/jxcore-log( 6080): 
I/jxcore-log( 6080): oneRoundDownNow
I/jxcore-log( 6080): 
I/jxcore-log( 6080): 2016-01-08T09:57:18.587Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6080): 
D/io.jxcore.node.ConnectionHelper( 6080): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
,E/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6080): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6080): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:AE:67), either no such connection or failed to close the connection
I/jxcore-log( 6080): 2016-01-08T09:57:18.589Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6080): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
,D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib,.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService( 1013): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1013): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1013): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 2626): db_query_execute: result 1
,D/WifiP2pService( 1013): InactiveState{ what=139301 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1013): P2pEnabledState add service request
,D/WifiP2pManager( 6080): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service request added successfully
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1013): InactiveState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1013): P2pEnabledState discover services
,D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service discovery started successfully
,D/SSRM:n  ( 1013): SIOP:: AP = 280
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.CLASS_CHANGED
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
,I/BluetoothBondStateMachine( 2626): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,D/SecContentProvider( 1013): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2626): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 2626): isSecureModeOn:false
I/BluetoothBondStateMachine( 2626): Entering PendingCommandState State
,D/BluetoothTile( 1172):  onBluetoothPairedDevicesChanged:
,E/bt-btif ( 2626): check_cod: remote_cod = 0x5a020c
,D/BluetoothTile( 1172):  handleUpdatestate:false name:null
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1321): onReceive
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 6972): BTStateChangeCB is registed
,D/BluetoothHeadset( 6972): doBind(): CallingUid(myUserHandle) = 0,
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6972): BluetoothHeadset service is binded
D/GMFPReceiver( 6972): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 6972): jangil::setProperties()
,D/GMFPReceiver( 6972): jangil::printBTStatus()
,D/SettingsProvider( 1013): name = Wearable0001
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10100
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
D/GMFPReceiver( 6972): ::::::::Wearable0001::false
,D/SettingsProvider( 1013): name = Wearable0002
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
,D/SettingsProvider( 1013): selectionArgs: 10100
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,D/GMFPReceiver( 6972): ::::::::Wearable0002::false
D/GMFPReceiver( 6972): onServiceConnected() : 1
D/GMFPReceiver( 6972): mBluetoothHeadset = true
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
,I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1],
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 6080): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
,E/SMD     (  287): DCD OFF
,D/WifiP2pService( 1013): InactiveState{ what=147494 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1013): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6080): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6080): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/btif_config_util( 2626): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2626): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2626): Failed to remove device: 08:EC:A9:50:75:41
,D/SecContentProvider( 1013): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2626): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10,
,D/BtConfig.SecureMode( 2626): isSecureModeOn:false
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/BluetoothTile( 1172):  onBluetoothPairedDevicesChanged:
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
D/HidService( 2626): getHidService(): returning com.android.bluetooth.hid.HidService@3989a195
V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/SettingsProvider( 1013): name = bluetooth_input_device_priority_08:EC:A9:50:75:41
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
D/HidService( 2626): Saved priority 08:EC:A9:50:75:41 = -1
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/SettingsProvider( 1013): name = bluetooth_a2dp_sink_priority_08:EC:A9:50:75:41
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1172):  handleUpdatestate:false name:null
,D/SettingsProvider( 1013): name = bluetooth_headset_priority_08:EC:A9:50:75:41
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
,D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1013): ret = -1
I/BluetoothBondStateMachine( 2626): StableState(): Entering Off State
,D/BluetoothNotiBroadcastReceiver( 1321): onReceive
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 6972): BTStateChangeCB is registed
,D/BluetoothHeadset( 6972): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6972): BluetoothHeadset service is binded
,D/GMFPReceiver( 6972): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 6972): jangil::setProperties()
,D/GMFPReceiver( 6972): jangil::printBTStatus()
,D/SettingsProvider( 1013): name = Wearable0001
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
,D/SettingsProvider( 1013): selectionArgs: 10100
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,D/GMFPReceiver( 6972): ::::::::Wearable0001::false
,D/SettingsProvider( 1013): name = Wearable0002
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10100
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,D/GMFPReceiver( 6972): ::::::::Wearable0002::false
D/GMFPReceiver( 6972): onServiceConnected() : 1
D/GMFPReceiver( 6972): mBluetoothHeadset = true
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,E/bt-btm  ( 2626): tBTM_SEC_DEV:0xa461c624 rs_disc_pending=1,
W/bt-btif ( 2626): bta_dm_check_av:0
W/bt-btif ( 2626): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2626): new conn_srvc id:26, app_id:255
,D/BluetoothSocket( 6080): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@a56de9a
W/bt-btif ( 2626): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2626): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2626): setRfcommConnected true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): Incoming connection accepted
,D/BluetoothSocket( 6080): getInputStream(): myUserId = 0
,D/BluetoothSocket( 6080): getOutputStream(): myUserId = 0,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): Incoming connection initialized (thread ID: 1081)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6080): Entering thread (ID: 1081)
,E/SMD     (  287): DCD OFF
,W/bt-btif ( 2626): invalid rfc slot id: 10
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6080): Disconnected: bt socket closed, read return: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): removeThreadFromList: Removing thread with ID 1081
D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@23ebe3cb, channel: 6, state: CONNECTED
,D/BluetoothSocket( 6080): close() this: android.bluetooth.BluetoothSocket@23ebe3cb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24da07a8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@331aa2c1mSocket: android.net.LocalSocket@2344a66 impl:android.net.LocalSocketImpl@fd2f1a7 fd:FileDescriptor[114]
D/BluetoothSocket( 6080): Closing mSocket: android.net.LocalSocket@2344a66 impl:android.net.LocalSocketImpl@fd2f1a7 fd:FileDescriptor[114]
,D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@23ebe3cb, channel: 6, state: CLOSED
,D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@23ebe3cb, channel: 6, state: CLOSED
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): Handshake failed (thread ID: 1081)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6080): Exiting thread (ID: 1081)
,W/bt-rfcomm( 2626): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 2626): RFCOMM_DisconnectInd LCID:0x4d
,E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2143): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1013): InactiveState{ what=147477 },
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1013): InactiveState{ what=147477 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): restart: Restarting...
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5,, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1013): InactiveState{ what=139307 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1013): P2pEnabledState clear service request
,D/WifiP2pService( 1013): InactiveState{ what=139283 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1013): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1013): P2pEnabledState{ what=139301 },
D/WifiP2pService( 1013): P2pEnabledState add service request
,D/WifiP2pManager( 6080): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service request added successfully
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/bt-btm  ( 2626): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2626): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
,D/KeyguardViewMediator( 1172): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1321): ACTION_ACL_DISCONNECTED
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/KeyguardViewMediator( 1172): isGear1: device is not B1!
,D/BluetoothAdapterService( 2626): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c8f7edb
D/BtConfig.SecureMode( 2626): isSecureModeOn:false
,D/SecContentProvider( 1013): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2626): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6196): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 6196): Bluetooth Device Name: A3-1
,D/SSRM:n  ( 1013): SIOP:: AP = 280
,D/WifiP2pService( 1013): InactiveState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1013): P2pEnabledState discover services
,D/WifiService( 1013): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1013): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1013): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2143): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service discovery started successfully
,E/SMD     (  287): DCD OFF,
,W/bt-sdp  ( 2626): SDP - Rcvd conn cnf with error: 0xd  CID 0x4b,
E/bt-btif ( 2626): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@109bf654, channel: 1, state: INIT
D/BluetoothSocket( 6080): close() this: android.bluetooth.BluetoothSocket@109bf654, channel: 1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@306da9fd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3f2aa6f2mSocket: android.net.LocalSocket@35330143 impl:android.net.LocalSocketImpl@2dec23c0 fd:FileDescriptor[116]
D/BluetoothSocket( 6080): Closing mSocket: android.net.LocalSocket@35330143 impl:android.net.LocalSocketImpl@2dec23c0 fd:FileDescriptor[116]
D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@109bf654, channel: 1, state: CLOSED
,D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2626): db_query_execute: result 1
W/bt-btif ( 2626): invalid rfc slot id: 12
,D/BluetoothUtils( 6080): isSocketAllowedBySecurityPolicy start : device null
,D/BluetoothSocket( 6080): connect(): myUserId = 0
W/BluetoothAdapter( 6080): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2626): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/BluetoothSocket( 6080): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2626): db_query_execute: result 1
,D/IOP_DB_BT( 2626): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2626): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2626): db_query_execute: result 1
W/bt-btif ( 2626): info:x10
,D/        ( 2626): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 2626): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
,I/wpa_supplicant( 2143): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1013): InactiveState{ what=147477 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1013): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
D/WifiDisplayController( 1013): Received list of peers.
D/WifiDisplayController( 1013):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1013):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1013): InactiveState{ what=139283 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1013): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/jxcore-log( 6080): teardown
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): testSendData stopped
I/jxcore-log( 6080): 
,I/io.jxcore.node.ConnectionHelper( 6080): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): shutdown
D/BluetoothSocket( 6080): close() in, this: android.bluetooth.BluetoothSocket@26efe8f9, channel: 6, state: LISTENING
,D/BluetoothSocket( 6080): close() this: android.bluetooth.BluetoothSocket@26efe8f9, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1fad8f5c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16b8403emSocket: android.net.LocalSocket@3dfa6e9f impl:android.net.LocalSocketImpl@1f4fbbec fd:FileDescriptor[113],
D/BluetoothSocket( 6080): Closing mSocket: android.net.LocalSocket@3dfa6e9f impl:android.net.LocalSocketImpl@1f4fbbec fd:FileDescriptor[113]
D/WifiP2pService( 1013): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6080): Exiting thread
,D/WifiP2pService( 1013): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6080): onServerStopped
D/WifiP2pService( 1013): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6080): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6080): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6080): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6080): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6080): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6080): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6080): setState: NOT_STARTED
I/jxcore-log( 6080): StopBroadcasting went ok
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): 2016-01-08T09:57:32.251Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 6080): 
D/WifiP2pService( 1013): InactiveState{ what=139268 }
,I/wpa_supplicant( 2143): P2P-FIND-STOPPED 
I/chromium( 6080): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6080): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6080): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6080): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6080): P2P device discovery stopped successfully
D/WifiP2pService( 1013): InactiveState{ what=139307 }
D/WifiP2pService( 1013): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1013): P2pEnabledState clear service request
D/WifiP2pService( 1013): remove channel information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6080): Service requests cleared successfully
,D/WifiP2pService( 1013): InactiveState{ what=147493 }
D/WifiP2pService( 1013): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1013): discovery change broadcast false
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6080): ****TEST TOOK:  ms ****
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6080): 
,E/SMD     (  287): DCD OFF
,D/btif_config_util( 2626): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/AndroidRuntime( 7065): 
D/AndroidRuntime( 7065): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7065): CheckJNI is OFF
D/AndroidRuntime( 7065): readGMSProperty: start
D/AndroidRuntime( 7065): readGMSProperty: already setted!!
D/AndroidRuntime( 7065): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7065): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7065): readGMSProperty: end
D/AndroidRuntime( 7065): addProductProperty: start
,E/AffinityControl( 7065): AffinityControl: registerfunction enter
,D/AndroidRuntime( 7065): Calling main entry com.android.commands.pm.Pm,
,D/PackageManager( 1013): START PACKAGE DELETE: observer{258245524}
D/PackageManager( 1013): pkg{<packageName>}
D/PackageManager( 1013): user{0}
D/PackageManager( 1013): caller{2000}
D/PackageManager( 1013): flags{3}
,D/PersonaManagerService( 1013): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1013): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1013): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1013): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1013): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1013): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1013): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1013): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1013): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1013): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1013): !@killApplicatoin: 10175, uninstall pkg
,I/ActivityManager( 1013): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
,I/ActivityManager( 1013): Killing 6080:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1013): Skipping PackageSetting{31e8d3da com.example.hello/10176} due to missing metadata
,I/ActivityManager( 1013):   Force finishing activity ActivityRecord{313f3205 u0 com.test.thalitest/.MainActivity t231}
,W/ActivityManager( 1013): mDVFSHelper.acquire()
,I/ActivityManager( 1013): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
,I/ActivityManager( 1013):   Force finishing activity ActivityRecord{313f3205 u0 com.test.thalitest/.MainActivity t231 f}
,W/ActivityManager( 1013): Duplicate finish request for ActivityRecord{313f3205 u0 com.test.thalitest/.MainActivity t231 f}
,W/ActivityManager( 1013): CustomStartingWindow se packge removed so remove capture also
,E/JavaBinder( 1013): !!! FAILED BINDER TRANSACTION !!!
,I/art     ( 5129): Explicit concurrent mark sweep GC freed 2369(132KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 764us total 26.595ms
,I/art     ( 6196): Explicit concurrent mark sweep GC freed 15355(882KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 9MB/12MB, paused 811us total 49.543ms
,W/InputDispatcher( 1013): channel ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 1013): channel ~ Channel is unrecoverably broken and will be disposed!
,E/bt-btif ( 2626): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:14, channel:-1
,D/InputDispatcher( 1013): Focus left window: 6080
,D/InputDispatcher( 1013): Focused application released
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/WindowState( 1013): WIN DEATH: Window{2a5c80d u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
W/InputDispatcher( 1013): Attempted to unregister already unregistered input channel
I/SurfaceFlinger(  256): id=14 Removed NainActivit (6/8)
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (-2/8),
I/SurfaceFlinger(  256): id=14 Removed NainActivit (-2/8)
,I/DBG_DM  ( 2974): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] ,
,I/DBG_DM  ( 2974): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 11
,I/InputReader( 1013): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1731): mOCRHelper is null
,I/DBG_DM  ( 2974): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,W/GeofencerStateMachine( 1689): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 2974): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0,
I/DBG_DM  ( 2974): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 11
,I/DBG_DM  ( 2974): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 2974): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,D/RegisteredComponentCache( 1457): Collect Tech packages for Knox
,D/PersonaManager( 1457): isKioskContainerExistOnDevice
,I/KLMS-2.5.183: ( 3567): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 10:57:38 GMT+01:00 2016
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/DBG_DM  ( 2974): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 2974): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/KLMS-2.5.183: ( 3567): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1013): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
,I/splitIntent( 1013): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
,I/splitIntent( 1013): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1013): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/ApplicationPolicy( 1013): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 2974): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 11
I/libpersona( 7078): KNOX_SDCARD checking this for 10094
I/KLMS-2.5.183: ( 3567): KLMSIntentService(): onCreate()
I/libpersona( 7078): KNOX_SDCARD not a persona
E/Zygote  ( 7078): MountEmulatedStorage()
E/Zygote  ( 7078): v2
,I/SELinux ( 7078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/DBG_DM  ( 2974): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
I/KLMS-2.5.183: ( 3567): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/SELinux ( 7078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 7078): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/DBG_DM  ( 2974): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/ActivityManager( 1013): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7078 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/DBG_DM  ( 2974): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 2974): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
I/DBG_DM  ( 2974): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1013): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1013): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1013): postActiveUserChange, showWhenLocked: false
,I/DBG_DM  ( 2974): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/SurfaceFlinger(  256): id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1013): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1013): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1013): Focus entered window: 2974
,I/art     (  302): Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 788us total 23.370ms
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2974): log_dcs ThreadedRenderer::initialize entered! 
,D/TimaKeyStoreProvider( 7078): TimaSignature is unavailable
,I/KLMS-2.5.183: ( 3567): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ActivityThread( 7078): Added TimaKeyStore provider
V/ActivityThread( 2974): updateVisibility : ActivityRecord{94e52fc token=android.os.BinderProxy@6f4ab2 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 48144(5MB) AllocSpace objects, 38(628KB) LOS objects, 33% free, 28MB/42MB, paused 3.653ms total 230.591ms
,I/art     ( 1013): WaitForGcToComplete blocked for 221.643ms for cause Explicit
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 18.309ms
,I/KLMS-2.5.183: ( 3567): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 17.881ms
,I/KLMS-2.5.183: ( 3567): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.183: ( 3567): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.183: ( 3567): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/PersonaManager( 1457): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1457): empty dynamic service
,D/elm:15183( 7078): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1013): mCursor = null
,D/elm:15183( 7078): ELMEngine.ELMEngine( context ).
,D/elm:15183( 7078): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/InputMethodManagerService( 1013): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/bt-btm  ( 2626): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2626): btm_sec_disconnected - Clearing Pending flag
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 1013): Got RemoteException sending setActive(false) notification to pid 6080 uid 10175
,D/elm:15183( 7078): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/KeyguardViewMediator( 1172): Received android.bluetooth.device.action.ACL_DISCONNECTED
,I/Timeline( 2974): Timeline: Activity_idle id: android.os.BinderProxy@6f4ab2 time:668389
,D/BluetoothUtils( 2626): getBtEnabledContainers(): btContainers = []
,D/elm:15183( 7078): ElmAgentService : onCreate()
,D/SamsungIME( 1731): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/elm:15183( 7078): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 7078): MainReceiver.listeningToPackageRemoved()
,D/elm:15183( 7078): MDMBridge.getInstance()
D/elm:15183( 7078): MDMBridge.getAllLicenseInfoFromSDK()
,V/BluetoothEventManager( 1321): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1321): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1172): isGear1: device is not B1!
,D/EnterpriseDeviceManagerService( 1013): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1013): Admin package name: com.google.android.gms
,D/elm:15183( 7078): MDMBridge.getAllLicenseInfoFromSDK()
,W/ActivityManager( 1013): mDVFSHelper.release()
I/Timeline( 1013): Timeline: Activity_windows_visible id: ActivityRecord{1d7e7e2f u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t230} time:668416
,W/TextServicesManagerService( 1013): no available spell checker services found
,D/elm:15183( 7078): ElmAgentService : onDestroy().
,I/ActivityManager( 1013): Killing 6121:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.183: ( 3567): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.183: ( 3567): KLMSIntentService(): onDestroy()
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1013): PackageReceiver onReceive()
,I/HarmonyEASService( 1013): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1013): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,I/OTPFW   ( 1013): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1013): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1013): DBIntegrity::getInstance - New instance created
,D/OTPFW   ( 1013): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
,D/PersonaManager( 1013): isKioskContainerExistOnDevice
,I/OTPFW   ( 1013): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1013): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1013): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1013): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1013): uID is 10175
V/EnterpriseBillingPolicy( 1013): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/SSRM:aZ ( 1013): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicy( 1013): uID is 10175
V/EnterpriseBillingPolicy( 1013): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - enter
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 13149(699KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 11.548ms total 221.601ms
,V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - end - null
,W/NotificationService( 1013): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/KnoxTimeoutHandler( 1013): handleActiveUserChange for user 0
D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1013): BroadcastReceiver ACTION_ACL_DISCONNECTED
,D/TaskPersister( 1013): removeObsoleteFile: deleting file=231_task.xml
,D/TaskPersister( 1013): removeObsoleteFile: deleting file=230_task.xml
,I/PCWCLIENTTRACE_PushUtil( 5828): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5828): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5828): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5828): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7098): MountEmulatedStorage()
,I/libpersona( 7098): KNOX_SDCARD checking this for 10032
E/Zygote  ( 7098): v2
I/libpersona( 7098): KNOX_SDCARD not a persona
D/PanelView( 1172): There is/are notification(s) 
I/SELinux ( 7098): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 7098): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7098 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
E/SELinux ( 7098): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/TimaKeyStoreProvider( 7098): TimaSignature is unavailable
,D/ActivityThread( 7098): Added TimaKeyStore provider
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,W/ResourceType( 1013): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,I/FeatureConfig( 7098): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SA      ( 6177): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6177): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10175 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,D/PackageManager( 1013): delete codoeFile: 
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AASAuninstall( 1013): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
I/AASA_removePackage( 1013): UID=10175 Target=com.test.thalitest
I/ActivityManager( 1013): Killing 6145:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/PackageManager( 1013): result of delete: 1{258245524}
,W/ResourcesManager( 1013): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1013): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1013): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 7065): Shutting down VM
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7116): MountEmulatedStorage()
E/Zygote  ( 7116): v2
I/libpersona( 7116): KNOX_SDCARD checking this for 10044
I/libpersona( 7116): KNOX_SDCARD not a persona
,I/SELinux ( 7116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1013): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7116 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 7116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 7116): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1013): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1013): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_6121/cgroup.procs: No such file or directory
,W/ResourcesManager( 7098): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 7116): TimaSignature is unavailable
,D/ActivityThread( 7116): Added TimaKeyStore provider
,W/ResourcesManager( 7098): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 7116): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7116): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7116): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7116): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7116): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7116): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7116): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7116): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_6145/cgroup.procs: No such file or directory
,W/ResourcesManager( 7098): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
W/ResourcesManager( 7098): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7098): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 7098): system/finder_cp/cpdata.xml file not found
,W/art     ( 7065): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/NearbySource( 7116): Nearby Source Create!
D/NearbyContext( 7116): Nearby Context Create!
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7116): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 7116): Samsung link source created
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider( 7116): getAllContactInfoList Start
,I/PackagesMonitor( 7116): PackagesMonitor onReceive :com.test.thalitest
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7137): MountEmulatedStorage()
E/Zygote  ( 7137): v2
I/libpersona( 7137): KNOX_SDCARD checking this for 10046
I/libpersona( 7137): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7137 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux ( 7137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Killing 5972:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,I/SELinux ( 7137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 7137): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7137): TimaSignature is unavailable
,D/ActivityThread( 7137): Added TimaKeyStore provider
D/ContactProvider( 7116): getAllContactInfoList End
,I/syncContacts( 7116): thread: 1173, sync time = 88
,W/ResourcesManager( 7137): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7137): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7137): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7137): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7137): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7137): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/Mms/MmsApp( 7137): [start]    onCreate() consume time = 0.0

```
