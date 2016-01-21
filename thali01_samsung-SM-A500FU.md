#### Test 568182548138a64_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/SELinux ( 5974): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5974): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
--------- beginning of system
I/ActivityManager( 1011): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5974 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/System.err( 1011): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1011): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1011): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1011): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1011): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1011): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1011): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1011): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1011): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1011): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1011): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1011): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1011): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1011): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1011): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1011): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1011): 	... 10 more
E/SmartFaceService( 1011): onReceive: android.intent.action.SCREEN_OFF
E/SmartFaceService( 1011): fail to set sysfs 0
D/PanelView( 1172): There is/are notification(s) 
D/SamsungIME( 1771): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
I/DBG_POLICYDM( 5929): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/BatteryStatsDumper( 1011): In refreshStats isReason Screen ON/OFF: true
W/libprocessgroup( 1011): failed to open /acct/uid_10035/pid_5307/cgroup.procs: No such file or directory
D/MotionRecognitionService( 1011):   mReceiver.onReceive : ACTION_SCREEN_OFF
D/NetworkStatsFactory( 1011): UpdateStatsForKnox updated
I/DBG_POLICYDM( 5929): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/TimaKeyStoreProvider( 5974): TimaSignature is unavailable
D/ActivityThread( 5974): Added TimaKeyStore provider
D/NotificationService( 1011): ACTION_SCREEN_OFF
D/LightsService( 1011): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1011) 
D/LightsService( 1011): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
D/LightsService( 1011): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1011): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
I/DBG_POLICYDM( 5929): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 5929): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
D/NetworkStatsFactory( 1011): UpdateStatsForKnox updated
I/DBG_POLICYDM( 5929): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
D/Mms/MmsConfig( 5835): Load Resize quality : 80
D/EasySignUpManager_1.0.1( 5835): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 5835): isAuth is false
D/Mms/MmsConfig( 5835): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
E/MotionRecognitionService( 1011):  handler : SCREEN_OFF end 
I/DBG_POLICYDM( 5929): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
E/WifiNative-wlan0( 1011): do suspend true
I/BatteryStatsDumper( 1011): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1011): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1011): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1011): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1011): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1011): Previous Battery Level: 0 Current Level: 100 Delta: -100
I/DBG_POLICYDM( 5929): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
D/TP/MmsSmsProvider( 1451): query,matched:2117, calling pid = 5835
D/TP/MmsSmsProvider( 1451): match 2117:Elapsed time : 1.711 ms
I/BackgroundCompactionService( 1011): Schedule Type1 BGCompaction
I/DBG_POLICYDM( 5929): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
I/DBG_POLICYDM( 5929): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 5929): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
D/EasySignUpManager_1.0.1( 5835): isAuth is false
I/DBG_POLICYDM( 5929): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
D/EasySignUpManager_1.0.1( 5835): getServiceStatus : serviceId (1) is OFF
E/CscParser( 5835): mps_code.dat does not exist
E/CscParser( 5835): customer_path =/system/csc/customer.xml
E/CscParser( 5835): fileName + /system/csc/customer.xml
I/DBG_POLICYDM( 5929): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/01/25/12:51:01
D/IpRemoteDisplayController( 1011): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1011): Bridge Server is not available
I/DBG_POLICYDM( 5929): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/01/21/23:39:34
I/DBG_POLICYDM( 5929): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 5929): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
I/DBG_POLICYDM( 5929): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 5929): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5929): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5929): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 5929): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 5929): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5929): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
E/CscParser( 5835): mps_code.dat does not exist
E/CscParser( 5835): customer_path =/system/csc/customer.xml
E/CscParser( 5835): fileName + /system/csc/customer.xml
I/DBG_POLICYDM( 5929): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 5929): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/CscParser( 5835): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 5835):  enable multiwindow = true
D/ChimeraCfgMgr( 3571): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3571): Module APK com.google.android.play.games already loaded
E/PhotosPlugin( 5944): Loading PhotosPlugin
E/Mms/MessageUtils( 5835): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5835): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 5835): [end]    init() consume time = 267.478073
D/Mms/Contact( 5835): [start]    init() consume time = 2.525208
I/DBG_POLICYDM( 5929): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
E/SPPClientService( 5974): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5974): [PushClientApplication] Push log off : This is Ship build version
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
D/Mms/Contact( 5835): [end]    init consume time = 23.133177
E/Zygote  ( 6010): MountEmulatedStorage()
E/Zygote  ( 6010): v2
I/libpersona( 6010): KNOX_SDCARD checking this for 10038
I/libpersona( 6010): KNOX_SDCARD not a persona
I/SELinux ( 6010): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ChimeraCfgMgr( 3571): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/ActivityManager( 1011): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=6010 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
D/GpsLocationProvider( 1011): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/SELinux ( 6010): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6010): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5929): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/Mms/DraftCache( 5835): [start]    rebuildCache consume time = 22.153125
D/TP/MmsSmsProvider( 1451): query,matched:13, calling pid = 5835
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SPPClientService( 5974): PushLog.txt file is not deleted.
D/SPPClientService( 5974): PushLog.txt file is not deleted.
D/SPPClientService( 5974): ============PushLog. stop!
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/TP/MmsSmsProvider( 1451): query,matched:12, calling pid = 5835
D/TP/MmsSmsProvider( 1451): match 13:Elapsed time : 4.351 ms
D/TP/MmsSmsProvider( 1451): match 12:Elapsed time : 1.072 ms
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/PersonaManagerService( 1011): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1011): MSG_ACTION_SCREEN_OFF called
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
D/TimaKeyStoreProvider( 6010): TimaSignature is unavailable
D/ActivityThread( 6010): Added TimaKeyStore provider
D/AsyncTaskServiceImpl( 3571): Submit a task: k
D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/ServiceManager(  329): Waiting for service AtCmdFwd...
V/EmergencyMode( 1412): [EmergencyStateReceiver] binteractive [false] why[3]
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MethodReflector( 5835): getSubId is called
D/Mms/TelephonyUtils( 5835): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5835): getTelephonyProperty is called
D/Mms/DownloadManager( 5835): roaming -> false (slotId = 0)
D/Mms/DraftCache( 5835): [end]    rebuildCache consume time = 46.341198
D/Mms/DownloadManager( 5835): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5835): auto download without roaming -> true
D/Mms/DownloadManager( 5835): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5835): getSubId is called
I/ActivityManager( 1011): Killing 5327:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
D/ChimeraCfgMgr( 3571): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/Mms/ArtClassLoader( 5835): init [DONE] art
D/Mms/MethodReflector( 5835): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5835): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5835): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5835): getTelephonyProperty is called
D/Mms/DownloadManager( 5835): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5835): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5835): auto download without roaming -> true
D/Mms/DownloadManager( 5835): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5835): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5835): mAutoDownload ------> true
D/ChimeraCfgMgr( 3571): Loading module com.google.android.gms.vision from APK com.google.android.gms
W/ResourcesManager( 6010): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6010): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/k       ( 3571): Processing package: com.test.thalitest
D/accuweather( 1716): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1716): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/NfcService( 1436): call the applyRouting
D/GassUtils( 3571): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 3571): Found info for package com.test.thalitest in db.
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
I/DBG_POLICYDM( 5929): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
D/ComposerPerformance( 5835): 1453415975066 ms / [DONE] Composer constructor
E/CII     ( 5835): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5835): ReservationManager()
I/Mms/ReservationManager( 5835): resetAfterConnected()
D/Mms/Conversation( 5835): [start]    init() consume time = 92.607969
D/TP/MmsSmsProvider( 1451): query,matched:7, calling pid = 5835
D/TP/MmsSmsProvider( 1451): match 7:Elapsed time : 1.368 ms
D/accuweather( 1716): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
D/TP/MmsSmsProvider( 1451): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1451): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1451): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1451): sUpgradeVersion = 0, db.getVersion() = 81
D/TP/MmsSmsProvider( 1451): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1451): need read changed broadcast:false
I/Mms/ReservationManager( 5835): getReservedSendMessageCount(): retMessageCount=0
D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MmsApp( 5835): [end]    onCreate() consume time = 23.747135
D/ActivityManager( 1011): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/Conversation( 5835): [end]    init consume time = 9.8875
D/Mms/MessagingNotification( 5835): [start]    init() consume time = 2.862552
D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 3571): Using Auth Proxy for data requests.
W/BaseAppContext( 3571): Using Auth Proxy for data requests.
D/Mms/MessagingNotification( 5835): [end]    init consume time = 15.191094
D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/DownloadManager( 5835): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5835): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5835): getSubId is called
D/Mms/TelephonyUtils( 5835): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5835): getTelephonyProperty is called
D/Mms/DownloadManager( 5835): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5835): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5835): auto download without roaming -> true
D/Mms/DownloadManager( 5835): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5835): mAutoDownload ------> true
D/Mms/SpamFilter( 5835): [start]    SpamFilter fill() begin consume time = 8.887448
D/Mms/Synchronizer( 5835): [start]    doSync consume time = 4.874062
D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/FreeMessageStatusReceiver( 5835): onReceive, action : android.intent.action.PACKAGE_ADDED
D/TP/MmsSmsProvider( 1451): query,matched:0, calling pid = 5835
V/TP/MmsSmsProvider( 1451): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1451): match 0:Elapsed time : 1.581 ms
D/TP/MmsSmsProvider( 1451): update, matched:300, calling pid = 5835
V/TP/MmsSmsProvider( 1451): syncDBData start
V/TP/MmsSmsProvider( 1451): syncDBData sms end
V/TP/MmsSmsProvider( 1451): syncDBData mms end
V/TP/MmsSmsProvider( 1451): syncDBData end
D/SSRM:n  ( 1011): SIOP:: AP = 330
D/Mms/Synchronizer( 5835): [end]    doSync consume time = 20.040157
D/TP/MmsSmsProvider( 1451): query,matched:400, calling pid = 5835
D/ActivityManager( 1011): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
I/DBG_POLICYDM( 5929): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/LibSecureUISvc( 1909): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
E/Zygote  ( 6036): MountEmulatedStorage()
I/libpersona( 6036): KNOX_SDCARD checking this for 10072
E/Zygote  ( 6036): v2
I/libpersona( 6036): KNOX_SDCARD not a persona
I/SELinux ( 6036): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1011): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6036 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1011): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/Mms/SpamFilter( 5835): [end]    SpamFilter fill() finished consume time = 23.052135
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/SELinux ( 6036): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6036): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5929): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6036): TimaSignature is unavailable
D/ActivityThread( 6036): Added TimaKeyStore provider
W/libprocessgroup( 1011): failed to open /acct/uid_10035/pid_5327/cgroup.procs: No such file or directory
E/Zygote  ( 6051): MountEmulatedStorage()
I/libpersona( 6051): KNOX_SDCARD checking this for 10047
E/Zygote  ( 6051): v2
I/libpersona( 6051): KNOX_SDCARD not a persona
I/SELinux ( 6051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1011): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6051 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 6051): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6051): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/PowerManagerService( 1011): [PWL] sb release: PowerManagerService.Broadcasts
D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/FreeMessageReceiverService( 5835): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5835): onHandleIntent: ACTION_PACKAGE_ADDED
D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1011): Killing 5399:com.sec.android.diagmonagent/1000 (adj 15): empty #31
W/BaseAppContext( 3571): Using Auth Proxy for data requests.
D/BadgeProvider( 6036): onCreate
D/BadgeProvider( 6036): DatabaseHelper
I/ActivityManager( 1011): Killing 5415:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
D/TimaKeyStoreProvider( 6051): TimaSignature is unavailable
D/ActivityThread( 6051): Added TimaKeyStore provider
W/BaseAppContext( 3571): Using Auth Proxy for data requests.
W/BaseAppContext( 3571): Using Auth Proxy for data requests.
W/BaseAppContext( 3571): Using Auth Proxy for data requests.
W/ResourcesManager( 6051): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6051): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6051): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/Mms/MessagingNotification( 5835): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1451): query,matched:26, calling pid = 5835
D/TP/SmsProvider( 1451): match 26:Elapsed time : 1.035 ms
D/TP/MmsSmsProvider( 1451): query,matched:6, calling pid = 5835
D/TP/MmsSmsProvider( 1451): match 6:Elapsed time : 1.217 ms
W/BaseAppContext( 3571): Using Auth Proxy for data requests.
D/ActivityManager( 1011): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
D/SSRM:a  ( 1011): DeviceInfo:: 000000000000
D/SSRM:a  ( 1011): SettingsAirViewInfo:: 000000000
E/Zygote  ( 6067): MountEmulatedStorage()
E/Zygote  ( 6067): v2
I/libpersona( 6067): KNOX_SDCARD checking this for 10025
I/SELinux ( 6067): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6067): KNOX_SDCARD not a persona
I/SELinux ( 6067): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1011): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6067 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/SELinux ( 6067): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1011): failed to open /acct/uid_1000/pid_5399/cgroup.procs: No such file or directory
W/libprocessgroup( 1011): failed to open /acct/uid_10142/pid_5415/cgroup.procs: No such file or directory
I/art     (  306): Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 705us total 25.654ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 856us total 18.597ms
D/TimaKeyStoreProvider( 6067): TimaSignature is unavailable
,D/ActivityThread( 6067): Added TimaKeyStore provider
I/ActivityManager( 1011): Killing 5430:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 17.196ms
W/ResourcesManager( 6067): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/OMACP   ( 6067): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
W/libprocessgroup( 1011): failed to open /acct/uid_10042/pid_5430/cgroup.procs: No such file or directory
D/Mms/Omacp( 5835): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/OMACP   ( 6067): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 6067): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 6067): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 6067): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 6067): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 6067): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 6067): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 6067): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/PeopleDatabaseHelper( 3571): cleanUpNonGplusAccounts done.
I/OMACP   ( 6067): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 6067): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 6067): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 6067): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 6067): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/ActivityManager( 1011): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DBG_POLICYDM( 5929): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/MyFiles ( 6051): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5929): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
D/ActivityManager( 1011): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/System.out( 5620): Thread-973(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5620): Thread-973(ApacheHTTPLog):isShipBuild true
I/System.out( 5620): Thread-973(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5620): Thread-973(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
E/installd(  286): system dir 0 : /system/app/
E/installd(  286): system dir 1 : /system/priv-app/
E/installd(  286): system dir 2 : /vendor/app/
E/installd(  286): system dir 3 : /oem/app/
I/TactileAssist( 1011): enable value -1
I/TactileAssist( 1011): internal enable value -1
I/TactileAssist( 1011): intensity value -1
I/TactileAssist( 1011): saveAppList value true
I/TactileAssist( 1011): List of disabled apps :
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1011): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 6092): MountEmulatedStorage()
E/Zygote  ( 6092): v2
I/libpersona( 6092): KNOX_SDCARD checking this for 10053
I/libpersona( 6092): KNOX_SDCARD not a persona
I/SELinux ( 6092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1011): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6092 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 6092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6092): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6092): TimaSignature is unavailable
D/ActivityThread( 6092): Added TimaKeyStore provider
W/ResourcesManager( 6092): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 6092): onReceive() it will make start service
D/ActivityManager( 1011): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/ActivityManager( 1011): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 6092): onHandleIntent()
D/Compatibility( 6092): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
I/UpdateIcingCorporaServi( 5488): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 6092): found: 2
D/Compatibility( 6092): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6092): skipping ResolveInfo{8dbb03e com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6092): considering ResolveInfo{3311e9f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6092): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6092): enabling receiver ResolveInfo{2138abec com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/SL_DEBUG( 6010): isLoggable:: isProductShip = 1
D/Compatibility( 6092): enabling receiver ResolveInfo{e0b4bb5 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6092): enabling receiver ResolveInfo{2ede924a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/SL_DEBUG( 6010): isLoggable:: SL_DEBUG_EXIST = false
D/Compatibility( 6092): enabling receiver ResolveInfo{349305bb com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6092): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/AndroidRuntime( 6082): 
D/AndroidRuntime( 6082): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6082): CheckJNI is OFF
D/AndroidRuntime( 6082): readGMSProperty: start
D/AndroidRuntime( 6082): readGMSProperty: already setted!!
D/AndroidRuntime( 6082): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6082): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6082): readGMSProperty: end
D/AndroidRuntime( 6082): addProductProperty: start
I/ServiceManager(  329): Waiting for service AtCmdFwd...
D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6010): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1011): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
I/UpdateIcingCorporaServi( 5488): UpdateCorporaTask done [took 322 ms] updated apps [took 322 ms] 
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6010): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/Icing   ( 3571): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
I/qtaguid ( 5620): Untagging socket 44
I/qtaguid ( 5620): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5620): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5620): untagSocket(44) failed with errno -22
I/System.out( 5620): Thread-973 calls detatch()
D/ActivityManager( 1011): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
I/BatteryStatsDumper( 1011): Writing to database completed
I/art     ( 1011): Explicit concurrent mark sweep GC freed 259405(17MB) AllocSpace objects, 14(5MB) LOS objects, 33% free, 28MB/42MB, paused 7.871ms total 261.407ms
I/ActivityManager( 1011): Killing 5551:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/AffinityControl( 6082): AffinityControl: registerfunction enter
E/Zygote  ( 6130): MountEmulatedStorage()
I/libpersona( 6130): KNOX_SDCARD checking this for 10041
E/Zygote  ( 6130): v2
I/libpersona( 6130): KNOX_SDCARD not a persona
I/SELinux ( 6130): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1011): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6130 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6130): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6130): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 6082): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 6130): TimaSignature is unavailable
D/ActivityThread( 6130): Added TimaKeyStore provider
W/libprocessgroup( 1011): failed to open /acct/uid_10069/pid_5551/cgroup.procs: No such file or directory
I/Icing   ( 3571): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
E/PersonaManagerService( 1011): inState():  stateMachine is null !!
I/PersonaManagerService( 1011): PersonaId don't exist
I/ActivityManager( 1011): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1011): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/GAV2    ( 5944): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SA      ( 6130): [SSP] onCreated
W/ActivityManager( 1011): mDVFSHelper.acquire()
D/PhoneWindow( 1011): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1011): *FMB* installDecor flags : 25362712
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1011): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6153 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1011): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1011): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1011): Focused application set to: xxxx
D/InputDispatcher( 1011): Focus left window: 3106
E/Zygote  ( 6153): MountEmulatedStorage()
E/Zygote  ( 6153): v2
I/libpersona( 6153): KNOX_SDCARD checking this for 10155
I/libpersona( 6153): KNOX_SDCARD not a persona
I/SELinux ( 6153): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/PhoneWindow( 1011): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1011): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, uhalitest
D/AndroidRuntime( 6082): Shutting down VM
I/SELinux ( 6153): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6153): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1011): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1011): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6153): TimaSignature is unavailable
D/ActivityThread( 6153): Added TimaKeyStore provider
V/ActivityManager( 1011): Display changed displayId=0
D/StatusBarManagerService( 1011): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1011): isKioskContainerExistOnDevice
I/SA      ( 6130): [TPM] There is no property file
I/SA      ( 6130): [SCU] isHaveSA() - false
I/SA      ( 6130): [TPM] getModelProperty : null
I/SA      ( 6130): [TPM] getCSCProperty : null
I/ActivityManager( 1011): Killing 5582:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/SurfaceFlinger(  257): id=10 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  257): id=10 Removed YUIInstallC (-2/9)
I/SA      ( 6130): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6130): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6130): [DM] TFT FEATURE: false
I/SA      ( 6130): [PMR] Received action : android.intent.action.PACKAGE_ADDED
V/ActivityThread( 3106): updateVisibility : ActivityRecord{3ee228cf token=android.os.BinderProxy@1a324512 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/SA      ( 6130): [DM] init START
I/SA      ( 6130): [DM] This device is not a Vodafone
D/ChimeraCfgMgr( 3571): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3571): Module APK com.google.android.play.games already loaded
W/ResourceType( 6130): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6130): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6130): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6130): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6130): [SCU] isHaveSA() - false
I/SA      ( 6130): support phone number id : false
I/SA      ( 6130): [DM] Supports Ref Jpn : true
I/SA      ( 6130): [DM] init END
I/SA      ( 6130): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 6130): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
I/ActivityManager( 1011): Killing 5598:com.google.android.apps.plus/u0a120 (adj 15): empty #31
W/libprocessgroup( 1011): failed to open /acct/uid_1000/pid_5582/cgroup.procs: No such file or directory
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
W/art     ( 6082): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/Zygote  ( 6181): MountEmulatedStorage()
E/Zygote  ( 6181): v2
I/libpersona( 6181): KNOX_SDCARD checking this for 10100
I/libpersona( 6181): KNOX_SDCARD not a persona
I/SELinux ( 6181): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1011): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6181 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1011): Killing 5216:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/ActivityManager( 1011): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000,
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,I/SELinux ( 6181): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6181): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GAV2    ( 5944): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/WebViewFactory( 6153): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/TimaKeyStoreProvider( 6181): TimaSignature is unavailable
,D/ActivityThread( 6181): Added TimaKeyStore provider
,D/ActivityManager( 1011): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/LibraryLoader( 6153): Time to load native libraries: 2 ms (timestamps 2393-2395)
I/LibraryLoader( 6153): Expected native library version number "",actual native library version number ""
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/libprocessgroup( 1011): failed to open /acct/uid_10120/pid_5598/cgroup.procs: No such file or directory
W/libprocessgroup( 1011): failed to open /acct/uid_10150/pid_5216/cgroup.procs: No such file or directory
D/PackageIntentReceiver( 6181): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6181): Not GearManger package! 
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6204): MountEmulatedStorage(),
E/Zygote  ( 6204): v2
I/libpersona( 6204): KNOX_SDCARD checking this for 1000
I/libpersona( 6204): KNOX_SDCARD not a persona
,I/SELinux ( 6204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6204): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1011): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6204 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/AccountFeatureHelper( 5944): Write apps_features disabled false
,V/WebViewChromiumFactoryProvider( 6153): Binding Chromium to main looper Looper (main, tid 1) {2138abec}
,I/LibraryLoader( 6153): Expected native library version number "",actual native library version number ""
I/chromium( 6153): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/TimaKeyStoreProvider( 6204): TimaSignature is unavailable
,D/ActivityThread( 6204): Added TimaKeyStore provider
,I/BrowserStartupController( 6153): Initializing chromium process, singleProcess=true
,W/art     ( 6153): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6153): ApplicationContext is null in ApplicationStatus
,W/chromium( 6153): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6153): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 6153): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 6153): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6153): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6153): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6153): Local Branch: 
I/Adreno-EGL( 6153): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6153): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6153):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/ActivityManager( 1011): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5620): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5620): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  ( 6224): MountEmulatedStorage()
,E/Zygote  ( 6224): v2
,I/libpersona( 6224): KNOX_SDCARD checking this for 1000
I/libpersona( 6224): KNOX_SDCARD not a persona
,I/SELinux ( 6224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1011): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6224 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1011): Killing 5062:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,E/SELinux ( 6224): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6224): TimaSignature is unavailable
,D/ActivityThread( 6224): Added TimaKeyStore provider
,W/GAV2    ( 5944): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,W/ResourcesManager( 5620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/SMD     (  290): DCD OFF,
,D/ActivityManager( 1011): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 6224): Received: android.intent.action.PACKAGE_ADDED
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl( 6224): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/Zygote  ( 6253): MountEmulatedStorage()
E/Zygote  ( 6253): v2
,I/libpersona( 6253): KNOX_SDCARD checking this for 10120
I/libpersona( 6253): KNOX_SDCARD not a persona
I/SELinux ( 6253): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6253): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
W/libprocessgroup( 1011): failed to open /acct/uid_10040/pid_5062/cgroup.procs: No such file or directory
,I/ActivityManager( 1011): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6253 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1011): Killing 4563:com.google.android.music:main/u0a111 (adj 15): empty #31
,E/SELinux ( 6253): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1011): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/TimaKeyStoreProvider( 6253): TimaSignature is unavailable
,D/ActivityThread( 6253): Added TimaKeyStore provider
,D/AcmsService( 6224): Enter Oncreate
,D/AcmsServiceMonitor( 6224): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6224): creating AcmsCore
,D/AcmsCore( 6224): AcmsCore.getAcmsCore() - Enter
,D/AcmsCore( 6224): AcmsCore
W/ActivityManager( 1011): Activity pause timeout for ActivityRecord{2d75950e u0 com.test.thalitest/.MainActivity t8}
,W/ResourcesManager( 6253): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsCore( 6224): init
,D/AcmsCore( 6224): Looper handler is not null
,D/AcmsCore( 6224): Post to AcmsCoreHandler
,D/AcmsServiceMonitor( 6224): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/ActivityManager( 1011): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/AcmsServiceMonitor( 6224): Incrementing - Counter value: 1
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
D/AcmsCore( 6224): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6224): onStartCommand
D/AcmsService( 6224): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6224): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6224): Incrementing - Counter value: 2
D/AcmsService( 6224): Incremented Counter Value : onStartCommand
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1011): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 6224): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsCertificateMngr( 6224): AcmsCertificateMngr
D/Finsky  ( 5620): [1] DailyHygiene.access$600: Logging device features
,W/chromium( 6153): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1011): waitForAlarm result :4
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/AcmsRevocationMngr( 6224): AcmsRevocationMngr
,D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/DeviceConnectionService( 1829): client connected with version: 8296000
D/AcmsService( 6224): Inside handle Intent
D/AcmsService( 6224): App added - package name: com.test.thalitest
D/AcmsCore( 6224): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6224): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6224): Incrementing - Counter value: 3
D/AcmsCore( 6224): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6224): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6224): Decrementing - Counter value: 2
,D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Mms/MmsApp( 5835):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5835): [start]    fillCache consume time = 1919.611354
D/Mms/ComposeMessageFragment( 5835): fillCache, easy = false
,W/libprocessgroup( 1011): failed to open /acct/uid_10111/pid_4563/cgroup.procs: No such file or directory
,D/Finsky  ( 5620): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5620): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/Icing   ( 3571): Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
,W/art     ( 6153): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager( 1011): Killing 4897:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,W/AwContents( 6153): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6153): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6153): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6153): CordovaWebView is running on device made by: samsung
,W/art     ( 6153): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6153): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6153): Render dirty regions requested: true
,D/ActivityManager( 1011): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1011): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1011): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1011): handleActiveUserChange for user 0
D/PersonaManagerService( 1011): getPersonasForUser(): returning null!
,W/libprocessgroup( 1011): failed to open /acct/uid_10134/pid_4897/cgroup.procs: No such file or directory
,I/ActivityManager( 1011): Killing 5377:com.android.calendar/u0a135 (adj 15): empty #31
,V/ActivityThread( 6153): updateVisibility : ActivityRecord{10366a08 token=android.os.BinderProxy@116821fa {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6153): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6153): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=404, NainActivit
D/AbsListView( 5835): Get MotionRecognitionManager
,D/MotionRecognitionService( 1011):  ssp status : false
,D/Mms/ComposeMessageFragment( 5835): [end]    fillCache consume time = 176.917187
,D/InputDispatcher( 1011): Focus entered window: 6153
,D/SRIB_DCS( 6153): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 6153): Initialized EGL, version 1.4
,W/libprocessgroup( 1011): failed to open /acct/uid_10135/pid_5377/cgroup.procs: No such file or directory
,D/PointerIcon( 1011): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1011): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 6153): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6153): Enabling debug mode 0
,I/wpa_supplicant( 2063): nl80211: Received scan results (2 BSSes),
,D/WifiP2pService( 1011): InactiveState{ what=147461 }
,D/WifiP2pService( 1011): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1011): DefaultState{ what=147461 }
,D/ActivityManager( 1011): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,I/Icing   ( 3571): Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/InputMethodManagerService( 1011): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1172): There is/are notification(s) 
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1771): getCurrentCandidateView
,I/ActivityManager( 1011): Displayed Component not be shown by security: +870ms (total +979ms)
,I/Timeline( 1011): Timeline: Activity_windows_visible id: ActivityRecord{2d75950e u0 com.test.thalitest/.MainActivity t8} time:83062
W/ActivityManager( 1011): mDVFSHelper.release()
,I/SurfaceFlinger(  257): id=13 Removed uhalitest (7/9)
,W/IInputConnectionWrapper( 6153): showStatusIcon on inactive InputConnection
,I/Timeline( 6153): Timeline: Activity_idle id: android.os.BinderProxy@116821fa time:83072
,I/SurfaceFlinger(  257): id=13 Removed uhalitest (-2/9)
,D/ActivityManager( 1011): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/BubbleViewCache( 5835): fillCache bubble = 1
,W/BindingManager( 6153): Cannot call determinedVisibility() - never saw a connection for the pid: 6153
,D/SamsungIME( 1771): Dismiss ExpandCandiate
,I/splitIntent( 1011): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1011): Killing 5239:com.google.android.gm/u0a101 (adj 15): empty #31
,I/ActivityManager( 1011): Killing 5352:com.google.android.talk/u0a104 (adj 15): empty #31
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1309): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1309): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1309): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1309): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1309): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1453437480000
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1453415977559
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1309): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/JsMessageQueue( 6153): Set native->JS mode to OnlineEventsBridgeMode
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1716): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 1
,D/accuweather( 1716): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1716): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1716): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/libprocessgroup( 1011): failed to open /acct/uid_10104/pid_5352/cgroup.procs: No such file or directory
W/libprocessgroup( 1011): failed to open /acct/uid_10101/pid_5239/cgroup.procs: No such file or directory
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,I/SamsungIME( 1771): getDebugLevel  : 0x4f4c
,D/accuweather( 1716): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1716): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1716): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1011): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1011): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5620): [995] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/jxcore_app_log( 6153): JniHelper::setJavaVM(0xb7cba450), pthread_self() = -1205820768
,D/ActivityManager( 1011): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SamsungIME( 1771): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1771): KeybaordView init() : load resources
,I/chromium( 6153): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/System.out( 5620): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5620): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5620): (HTTPLog)-Static: isShipBuild true
,I/System.out( 5620): (HTTPLog)-Thread-983-964739267: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 5620): (HTTPLog)-Static: isSBSettingEnabled false
,I/SamsungIME( 1771): getCurrentKeyboard
,I/SamsungIME( 1771): getTextKeyboard
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
,D/SamsungIME( 1771): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/System.out( 5620): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,I/DBG_POLICYDM( 5929): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5929): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5929): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5929): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5929): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5929): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5929): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/SamsungIME( 1771): [SwiftkeyWrapper] currentLangauge : 1701729619
,V/AlarmManager( 1011): waitForAlarm result :4
,D/KeyguardViewMediator( 1172): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1172): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1172): *** Keyguard wallpaper service already unbounded
,D/AcmsKeyStoreHelper( 6224):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6224): Key Store exist
,I/AcmsKeyStoreHelper( 6224): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6224):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 6224): getKeyStoreForApplication success 
D/AcmsCore( 6224): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6224): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6224): Decrementing - Counter value: 1
D/AcmsCore( 6224): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6224): This is NOT a valid MirrorLink app
D/AcmsCore( 6224): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6224): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6224): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6224): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6224): getSvcCounter - Counter value: 0
D/AcmsService( 6224): Enter onDestroy
I/AcmsService( 6224): cleanUp(): inside service clean up
D/AcmsCore( 6224): AcmsCore: inside DeInit
D/AcmsCore( 6224): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6224): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6224): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6224): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6224): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6224): getSvcCounter - Counter value: 0
,D/AcmsService( 6224): killing acms process
,I/Process ( 6224): Sending signal. PID: 6224 SIG: 9
,I/ActivityManager( 1011): Process ACMS.Process (pid 6224)(adj 0) has died(44,1166)
,W/jxcore-log( 6153): Initializing JXcore engine
W/jxcore-log( 6153): JXcore engine is ready
,E/audit   ( 1898): type=1400 msg=audit(1453415979.091:205): avc:  denied  { ioctl } for  pid=6296 comm="Thread-1085" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1898):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1898): type=1300 msg=audit(1453415979.091:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9ea008f8 items=0 ppid=306 ppcomm=main pid=6296 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1085" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1898): type=1320 msg=audit(1453415979.091:205): 
,W/jxcore-log( 6153): Starting JXcore engine
,W/jxcore-log( 6153): Platform android
W/jxcore-log( 6153): 
W/jxcore-log( 6153): Process ARCH arm
W/jxcore-log( 6153): 
,D/CAR.SERVICE( 5787): mConnectedToCar = false, abort
,E/ActivityThread( 5787): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@d22657b that was originally bound here
E/ActivityThread( 5787): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@d22657b that was originally bound here
E/ActivityThread( 5787): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5787): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5787): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5787): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5787): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5787): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5787): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5787): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5787): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5787): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5787): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5787): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5787): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5787): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 5787): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 5787): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 5787): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5787): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5787): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5787): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5787): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 5787): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@22b73f62 that was originally bound here
E/ActivityThread( 5787): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@22b73f62 that was originally bound here
E/ActivityThread( 5787): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5787): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5787): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5787): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5787): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5787): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5787): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5787): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5787): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5787): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5787): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5787): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5787): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 5787): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 5787): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 5787): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5787): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5787): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5787): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5787): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1011): Unbind failed: could not find connection for android.os.BinderProxy@279a54d0
,I/PowerManagerService( 1011): [PWL] Off : 6s ago
,I/jxcore-log( 6153): JXcore Cordova bridge is ready!
I/jxcore-log( 6153): 
,W/jxcore-log( 6153): JXcore engine is started
,E/jxcore  ( 6153): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6153): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6153): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,V/ApplicationPolicy( 1011): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1011): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/InputDispatcher( 1011): Focused application set to: xxxx
,I/ActivityManager( 1011): Killing 5468:com.samsung.aasaservice/1000 (adj 15): empty #31
,I/SurfaceFlinger(  257): id=14 Removed NainActivit (6/8)
,I/SurfaceFlinger(  257): id=14 Removed NainActivit (-2/8)
,D/InputDispatcher( 1011): Focus left window: 6153
,D/PointerIcon( 1011): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1011): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1011): mDVFSHelper.acquire()
,E/ViewRootImpl( 6153): sendUserActionEvent() mView == null
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 19
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 19
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3106): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1011): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1011): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1011): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 19
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,W/libprocessgroup( 1011): failed to open /acct/uid_1000/pid_5468/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3106): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3106): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1011): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1011): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1011): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1011): handleActiveUserChange for user 0
D/PersonaManagerService( 1011): getPersonasForUser(): returning null!
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/SurfaceFlinger(  257): id=15 createSurf (720x1280),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1011): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1011): Focus entered window: 3106
D/PointerIcon( 1011): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1011): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 3106): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBarManagerService( 1011): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/SMD     (  290): DCD OFF
V/ActivityThread( 3106): updateVisibility : ActivityRecord{3ee228cf token=android.os.BinderProxy@1a324512 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/InputMethodManagerService( 1011): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6153): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1771): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/PanelView( 1172): There is/are notification(s) 
,I/Timeline( 3106): Timeline: Activity_idle id: android.os.BinderProxy@1a324512 time:85660
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/ActivityManager( 1011): mDVFSHelper.release()
,I/Timeline( 1011): Timeline: Activity_windows_visible id: ActivityRecord{26f68853 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t7} time:85685
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:2, health:2, present:true, voltage: 4343, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1011): stay LED for charging
,D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ActivityManager( 1011): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,E/SMD     (  290): DCD OFF
,D/TaskPersister( 1011): removeObsoleteFile: deleting file=7_task.xml
,V/AlarmManager( 1011): waitForAlarm result :8
,D/SSRM:n  ( 1011): SIOP:: AP = 330
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PackageManager( 1011): [MSG] MCS_UNBIND
,I/ActivityManager( 1011): Killing 5080:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,D/PersonaManager( 1011): isKioskContainerExistOnDevice
,W/libprocessgroup( 1011): failed to open /acct/uid_10044/pid_5080/cgroup.procs: No such file or directory
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1011): waitForAlarm result :4
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1011): bindService callerProcessName:android, calleePkgName: android, action: null
D/ActivityManager( 1011): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1011): onStart. jobID=801
,I/BackgroundCompactionService( 1011): onStart done. jobID=801
,I/BackgroundCompactionService( 1011): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1011): compact_memory command done
,I/PowerManagerService( 1011): [PWL] Off : 16s ago
,I/ActivityManager( 1011): Waited long enough for: ServiceRecord{12d9f111 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/Finsky  ( 5620): [985] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5620): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/LightsService( 1011): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1011) 
,D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,D/LightsService( 1011): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,D/LightsService( 1011): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/BatteryService( 1011): turn on LED for fully charged
,E/lights  ( 1011): write_int failed to open -1
I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/LightsService( 1011): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/SecContentProvider2( 1011): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1011): mCursor = null
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/ApplicationPolicy( 1011): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,V/ApplicationPolicy( 1011): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,I/ValidateNoPeople( 1011): skipping global notification
D/WindowManager( 1011): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 1011): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1172
,I/PowerManagerService( 1011): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
,I/PowerManagerService( 1011): Waking up from sleep (uid 10054)...
,D/PowerManagerService( 1011): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/KeyguardServiceDelegate( 1011): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@1afddd9b)
,D/PowerManagerService( 1011): [s] UserActivityState : 0 -> 1
,D/KeyguardViewMediator( 1172): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1172): notifyScreenOnLocked
,D/PowerManagerService( 1011): [PWL] sb acquire: PowerManagerService.Display
,I/DisplayPowerController( 1011): Blocking screen on until initial contents have been drawn.
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/WindowOrientationListener( 1011): sensor enabled
,I/Sensors ( 1011): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardViewMediator( 1172): handleNotifyScreenOn
D/StatusBarKeyguardViewManager( 1172): onScreenTurnedOn()
,D/DisplayPowerController( 1011): getFinalBrightness : Summary is 5 -> 5
D/SensorService( 1011): [SO] changed settle time [1]
D/SensorService( 1011): [SO] setDelay [66000000]
D/SensorService( 1011): [SO] activate (ident=0xb8511408, enabled=1)
D/SensorService( 1011): [SO] AR_init
I/Sensors ( 1011): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/DisplayPowerController( 1011): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 1011): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1011): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/libsuspend( 1011): !@autosuspend_wakeup_count_disable
,I/libsuspend( 1011): !@autosuspend_wakeup_count_disable done
D/DisplayManagerService( 1011): !@display_state: OFF -> ON
,D/SurfaceFlinger(  257): Set power mode=2, type=0 flinger=0xb7d7c690
,D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 2 on display: 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SensorManager( 1011): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,I/DisplayManagerService( 1011): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1011): Display changed displayId=0
,D/KnoxNotification( 1172): ----- inflateViews : modified publicViewLocal -----
,D/PersonaManager( 1011): isKioskContainerExistOnDevice
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,D/KnoxNotification( 1172): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1172): PersonaID is invalid or persona doesn't exists. : -1
,D/SensorService( 1011): [SO] currT = 96220307826, prevT = 79040121114, diff = 17180186712, [0.077 0.096 10.075]
D/SensorService( 1011): [SO] Reset Rotation Old [100], Init [1]
,D/CoverManagerWhiteLists( 1011): isAllowedToUse : SIGNATURE_MATCH
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
,I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
D/SamsungIME( 1771): showDlgMsgBox : false true true
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 19
D/SecKeyguardClockSingleView( 1172): onScreenTurnedOn
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/StatusBarKeyguardViewManager( 1172): callback.onShown()
,D/NfcService( 1436): call the applyRouting
,V/KeyguardServiceDelegate( 1011): **** SHOWN CALLED ****
D/DisplayPowerController( 1011): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
I/DisplayPowerController( 1011): Unblocked screen on after 112 ms
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/DisplayPowerState( 1011): !@ ColorFade exit
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/PalmMotion( 1011): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1011): [PALM] SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService( 1011):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1011): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
,D/LightsService( 1011): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1011) 
,D/PalmMotion( 1011): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1011): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1011): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK,
,D/LightsService( 1011): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SSRM:a  ( 1011): DeviceInfo:: 000000000000
D/SSRM:a  ( 1011): SettingsAirViewInfo:: 000000000
I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/SurfaceFlinger(  257): id=12 Removed DolorFade (8/8)
,D/LightsService( 1011): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1011) 
I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 19
,D/LightsService( 1011): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
I/SurfaceFlinger(  257): id=12 Removed DolorFade (-2/8)
D/BatteryService( 1011): turn off LED
D/LightsService( 1011): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1011): write_led_info failed to open -1
,E/lights  ( 1011): write_led_info failed to open -1
E/lights  ( 1011): write_led_info failed to open -1
E/lights  ( 1011): write_led_info failed to open -1
E/lights  ( 1011): write_led_info failed to open -1
E/lights  ( 1011): write_led_info failed to open -1
D/LightsService( 1011): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/lights  ( 1011): write_led_info failed to open -1
E/lights  ( 1011): write_led_info failed to open -1
E/lights  ( 1011): write_led_info failed to open -1
E/libEGL  ( 1011): call to OpenGL ES API with no current context (logged once per thread)
D/PowerManagerService( 1011): Excessive delay in ColorFade : dismiss: 18ms
D/DisplayPowerController( 1011): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1011): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1011): lcd : 5 +
D/lights  ( 1011): lcd : 5 -
D/DisplayPowerController( 1011): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1011): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1011): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1011): SecHardwareInterface.setBatteryADC : true
,E/SmartFaceService( 1011): onReceive: android.intent.action.SCREEN_ON
W/System.err( 1011): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1011): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1011): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1011): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1011): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1011): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1011): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1011): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1011): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1011): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1011): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1011): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SmartFaceService( 1011): fail to set sysfs 1
W/System.err( 1011): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1011): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1011): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1011): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1011): 	... 10 more
,D/BatteryMeterView( 1172): onDraw batteryColor : -1
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3106): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,D/SensorService( 1011): [SO] currT = 96290112982, prevT = 79040121114, diff = 17249991868, [0.096 0.077 10.036]
,D/SensorService( 1011): [SO] 0.096 0.077 10.036
D/SensorService( 1011): [SO] [100 -> 255]
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 2 on display 0
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 1
D/SurfaceControl( 1011): Excessive delay in setPowerMode(): 148ms
E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
D/PowerManagerService( 1011): Excessive delay in !@display_state: ON: 149ms
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
D/MISC PowerHAL( 1011): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,D/MISC PowerHAL( 1011): sysfs_write +: /sys/class/input/event1/device/enabled: 1
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,V/UserPresentBroadcastReceiver( 1829): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/InputMethodManagerService( 1011): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms,
D/MotionRecognitionService( 1011):   mReceiver.onReceive : ACTION_SCREEN_ON
I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
,D/NotificationService( 1011): ACTION_SCREEN_ON
D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/LightsService( 1011): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1011) 
,D/LightsService( 1011): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 1011): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1011): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1011): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1011): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,E/MotionRecognitionService( 1011):  handler : SCREEN_ON end
,W/NotificationService( 1011): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/WifiNative-wlan0( 1011): do suspend false
I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 19
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=on
V/voice   (  285): voice_set_parameters: enter: screen_state=on
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3106): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3106): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/MISC PowerHAL( 1011): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1011): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1011): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1011): postActiveUserChange, showWhenLocked: false
,D/IpRemoteDisplayController( 1011): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1011): Bridge Server is not available
D/KnoxTimeoutHandler( 1011): handleActiveUserChange for user 0
D/PersonaManagerService( 1011): getPersonasForUser(): returning null!
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/GpsLocationProvider( 1011): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/PhoneStatusBar( 1172): Icon Only
D/PersonaManagerService( 1011): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 1011): MSG_ACTION_SCREEN_ON called
,I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,I/wpa_supplicant( 2063): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2063): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2063): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2063): Scan requested (ret=0) - scan timeout 30 seconds
,D/CoverManagerWhiteLists( 1011): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1436): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1436): call the applyRouting
,I/Timeline( 3106): Timeline: Activity_idle id: android.os.BinderProxy@1a324512 time:96399
,D/accuweather( 1716): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1716): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
D/accuweather( 1716): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1716): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1716): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1716): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1716): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 23 39
,D/ActivityManager( 1011): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1011): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1771): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/MISC PowerHAL( 1011): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/MISC PowerHAL( 1011): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 1011): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1011): Excessive delay in MISC setInteractive(true) while turning screen on: 155ms
,I/QCOM PowerHAL( 1011): Got set_interactive hint
,D/PowerManagerService( 1011): Excessive delay in nativeSetInteractive(true): 158ms
,D/lights  ( 1011): button : 1 +
,D/PowerManagerService( 1011): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 310ms
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1011): [PWL] sb release: PowerManagerService.Broadcasts
,D/lights  ( 1011): button : 1 -
,D/SSRM:n  ( 1011): SIOP:: AP = 320
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1309): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1309): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1309): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1309): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1453437480000
D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1453415990840
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1309): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1309): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/BatteryStatsDumper( 1011): In refreshStats isReason Screen ON/OFF: true
,D/NetworkStatsFactory( 1011): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1011): UpdateStatsForKnox updated
,I/BatteryStatsDumper( 1011): Screen bin #0: time=30305 power=0.17677916666666665
,I/BatteryStatsDumper( 1011): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1011): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1011): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1011): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1011): Previous Battery Level: 100 Current Level: 100 Delta: 0
,I/BatteryStatsDumper( 1011): Writing to database completed
,D/SSRM:a  ( 1011): DeviceInfo:: 000000000000
D/SSRM:a  ( 1011): SettingsAirViewInfo:: 000000000
,E/SMD     (  290): DCD OFF
,D/lights  ( 1011): button : 0 +
,D/lights  ( 1011): button : 0 -
,I/wpa_supplicant( 2063): nl80211: Received scan results (3 BSSes)
,D/WifiP2pService( 1011): InactiveState{ what=147461 }
,D/WifiP2pService( 1011): P2pEnabledState{ what=147461 }
,D/WifiP2pService( 1011): DefaultState{ what=147461 }
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1011): [SO] 0.077 0.077 10.036
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  290): DCD OFF
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  290): DCD OFF
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1011): waitForAlarm result :8
,V/AlarmManager( 1011): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1011): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1011): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/accuweather( 1716): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1716): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1716): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1716): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 23 40
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged,
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SSRM:n  ( 1011): SIOP:: AP = 310
,E/SMD     (  290): DCD OFF,
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Watchdog( 1011): !@Sync 3
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  290): DCD OFF
,D/SensorService( 1011): [SO] 0.077 0.096 10.036
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  290): DCD OFF
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1011): waitForAlarm result :4
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/art     ( 1011): Explicit concurrent mark sweep GC freed 68878(3MB) AllocSpace objects, 20(842KB) LOS objects, 33% free, 28MB/42MB, paused 2.553ms total 160.676ms
,D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1011): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1829): Vacuum at: now=1453416008278 tag=VacuumService
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1829): Scheduling Phenotype for one-off execution 7478 seconds from now (1453416008690)
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1829): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000,
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1829): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1829): Using platform SSLCertificateSocketFactory
,D/FactoryTest( 5448): Not factory mode
D/FactoryTest( 5448): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5448): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5448): still no open session command from host, so toast
,W/ContextImpl( 5448): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5448): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
I/Timeline( 5448): Timeline: Activity_launch_request id:com.android.settings time:114529
,E/PersonaManagerService( 1011): inState():  stateMachine is null !!
,I/PersonaManagerService( 1011): PersonaId don't exist
I/ActivityManager( 1011): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1011): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,D/CustomFrequencyManagerService( 1011): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1011  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1011): mDVFSHelper.acquire()
,V/ApplicationPolicy( 1011): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1011): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1011): Focused application set to: xxxx
,D/InputDispatcher( 1011): Focus left window: 3106
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIInstallConfirmActivity(366/onUserLeaveHint)] 
,E/MTPRx   ( 5448): started activity for popup
,D/PointerIcon( 1011): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1011): setMouseCustomIcon IconType is same.101
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 19
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIInstallConfirmActivity(371/onUserLeaveHint)] Home Key!!
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 3
,D/LightsService( 1011): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1011) 
,D/LightsService( 1011): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
I/DBG_DM  ( 3106): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService( 1011): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1011): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
D/ApplicationPolicy( 1011): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1011): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1011): showStatusBarByNotification() mOpenByNotification=false,
,I/DBG_DM  ( 3106): [com.wssyncmldm.db.file.XDB(3671/llIIIIlllllIIllllllI)] FUMO_Status : 220,
,W/NotificationService( 1011): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIFotaPostponeActivity(381/llIIIIlllllIIllIIllI)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,V/ActivityManager( 1011): Display changed displayId=0
,D/Launcher( 1473): onRestart, Launcher: 6439575
,D/KnoxNotification( 1172): ----- inflateViews : modified publicViewLocal -----
,D/Launcher( 1473): onStart, Launcher: 6439575
D/Launcher.HomeView( 1473): onStart
V/ActivityThread( 1473): updateVisibility : ActivityRecord{317af803 token=android.os.BinderProxy@1c8282eb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,I/SurfaceFlinger(  257): id=16 createSurf (720x1280),1 flag=4, Mauncher
,V/WindowOrientationListener( 1011): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1011): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,V/WindowOrientationListener( 1011): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,D/StatusBarManagerService( 1011): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/SRIB_DCS( 1473): log_dcs ThreadedRenderer::initialize entered! 
,D/KnoxNotification( 1172): ----- inflateViews : modified KnoxViewLocal -----
,D/LocationManagerService( 1011): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/PersonaManager( 1172): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
,I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/ResourcesManager( 5448): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5448): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5448): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5448): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5448): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5448): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5448): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame( 1011): Set to : 0
,V/ApplicationPolicy( 1011): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1011): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1011): Focused application set to: xxxx
,D/InputDispatcher( 1011): Focus entered window: 1473
,D/PointerIcon( 1011): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1011): setMouseCustomIcon IconType is same.101
,E/ActivityManager( 1011): Invalid thumbnail dimensions: 650x650
,W/OpenGLRenderer( 1473): SFEffectCache::get: create texture(0x9fae0724): name, size, mSize = 39, 147408, 326760
,D/InputMethodManagerService( 1011): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1011): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1771): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
D/SettingsReceiverActivity( 5448): dev.kiessupport is : TRUE
,I/System.out( 1829): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1829): Tagging socket 88 with tag 3000120100000000{805310977,0} for uid -1, pid: 1829, getuid(): 10012
,D/PhoneWindow( 5448): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5448): *FMB* installDecor flags : 8388610
,D/Launcher( 1473): onResume, Launcher: 6439575
,D/SettingsProvider( 1011): name = kids_home_mode
,D/SettingsProvider( 1011): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1011): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1011): selectionArgs: false
,D/SettingsProvider( 1011): selectionArgs: 10007
D/SecContentProvider( 1011): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1011): ret = -1
,D/Launcher.HomeView( 1473): onResume
,D/Launcher( 1473): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/PersonaManager( 1011): isKioskContainerExistOnDevice
,I/ActivityManager( 1011): Displayed Component not be shown by security: +23ms
,I/qtaguid ( 1829): Tagging socket 91 with tag 3000120100000000{805310977,0} for uid -1, pid: 1829, getuid(): 10012
,D/MenuAppsGridFragment( 1473): onResume
,D/WallpaperManager( 1473): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/WallpaperManager( 1473): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1473): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/splitIntent( 1011): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
I/splitIntent( 1011): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6352): MountEmulatedStorage()
,E/Zygote  ( 6352): v2
I/libpersona( 6352): KNOX_SDCARD checking this for 10044
I/libpersona( 6352): KNOX_SDCARD not a persona
,I/SELinux ( 6352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1011): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6352 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux ( 6352): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1011): handle home activity for 0
I/WallpaperManagerService( 1011): switchPersonaWallpaper is called for personaId-0
,D/KnoxTimeoutHandler( 1011): post home show event for user 0
D/ActivityManager( 1011): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1011): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1011): postActiveUserChange, showWhenLocked: false
,D/WallpaperManagerService( 1011):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1011): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1011): handleActiveUserChange for user 0
D/PersonaManagerService( 1011): getPersonasForUser(): returning null!
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,D/ActivityManager( 1011): startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6352): TimaSignature is unavailable
,D/ActivityThread( 6352): Added TimaKeyStore provider
E/Zygote  ( 6367): MountEmulatedStorage()
E/Zygote  ( 6367): v2
I/libpersona( 6367): KNOX_SDCARD checking this for 10088
I/libpersona( 6367): KNOX_SDCARD not a persona
,I/SELinux ( 6367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1011): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6367 uid=10088 gids={50088, 9997} abi=armeabi-v7a
I/Timeline( 1473): Timeline: Activity_idle id: android.os.BinderProxy@1c8282eb time:114939
,I/SELinux ( 6367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
E/SELinux ( 6367): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6367): TimaSignature is unavailable
,D/ActivityThread( 6367): Added TimaKeyStore provider
,E/Zygote  ( 6380): MountEmulatedStorage()
,E/Zygote  ( 6380): v2
I/libpersona( 6380): KNOX_SDCARD checking this for 10142
I/libpersona( 6380): KNOX_SDCARD not a persona
I/SELinux ( 6380): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6380): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1011): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6380 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6380): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/BroadcastQueue( 1011): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1473, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/TimaKeyStoreProvider( 6380): TimaSignature is unavailable
,D/ActivityThread( 6380): Added TimaKeyStore provider
,W/ResourcesManager( 6367): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ResourcesManager( 6352): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,W/ResourcesManager( 6352): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6352): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6352): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6352): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6352): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6352): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Recents_RecreateReceiver( 2488): onReceive by home
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,D/ActivityManager( 1011): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1011): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6397 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,V/TaskCloserActivity( 6380): TaskCloserActivity enter()
,E/Zygote  ( 6397): MountEmulatedStorage()
E/Zygote  ( 6397): v2
I/libpersona( 6397): KNOX_SDCARD checking this for 10139
I/libpersona( 6397): KNOX_SDCARD not a persona
,I/ActivityManager( 1011): Killing 5817:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
I/SELinux ( 6397): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,V/TaskCloserActivity( 6380): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,I/SELinux ( 6397): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6397): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,I/ActivityManager( 1011): Killing 4830:com.samsung.android.sm/1000 (adj 15): empty #31
,I/art     (  306): Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 654us total 31.499ms
,D/TimaKeyStoreProvider( 6397): TimaSignature is unavailable
,D/ActivityThread( 6397): Added TimaKeyStore provider
,D/LocationManagerService( 1011): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 20.367ms
,W/ResourcesManager( 6397): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6397): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6397): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6397): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 6397): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1829): Tagging socket 88 with tag 3000120100000000{805310977,0} for uid -1, pid: 1829, getuid(): 10012
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 18.513ms
,I/ActivityManager( 1011): Killing 5508:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/NearbySource( 6352): Nearby Source Create!
,D/NearbyContext( 6352): Nearby Context Create!
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6352): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6352): Samsung link source created
,D/ContactProvider( 6352): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1011): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WindowOrientationListener( 1011):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/WifiDisplayAdapter( 1011): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/SensorService( 1011): [SO] activate (ident=0xb8511408, enabled=0)
I/Sensors ( 1011): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/GalleryCacheReady( 6352): Receive : home resume
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
W/libprocessgroup( 1011): failed to open /acct/uid_1000/pid_4830/cgroup.procs: No such file or directory
W/libprocessgroup( 1011): failed to open /acct/uid_10152/pid_5817/cgroup.procs: No such file or directory
W/libprocessgroup( 1011): failed to open /acct/uid_10015/pid_5508/cgroup.procs: No such file or directory
,D/SensorManager( 1011): unregisterListener ::   
,I/Sensors ( 1011): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1011): [SO] changed settle time [0]
D/SensorService( 1011): [SO] setDelay [200000000]
D/SensorService( 1011): [SO] activate (ident=0xb8511408, enabled=1)
D/SensorService( 1011): [SO] AR_init
I/Sensors ( 1011): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/Mms/UIEventReceiver( 5835): ui event
D/CustomFrequencyManagerService( 1011): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1011  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1011): mDVFSHelper.release()
I/Timeline( 1011): Timeline: Activity_windows_visible id: ActivityRecord{1b6b47fb u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t6} time:115306
I/splitIntent( 1011): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,I/ActivityManager( 1011): Killing 5855:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,D/SensorManager( 1011): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,I/SurfaceFlinger(  257): id=15 Removed YUIInstallC (7/8)
I/SurfaceFlinger(  257): id=15 Removed YUIInstallC (-2/8)
,I/ActivityManager( 1011): Killing 5200:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31,
,D/CustomFrequencyManagerService( 1011): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1011  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/DBG_DM  ( 3106): [com.wssyncmldm.ui.XUIInstallConfirmActivity(508/onDestroy)] 
,D/ContactProvider( 6352): getAllContactInfoList End
,I/syncContacts( 6352): thread: 1093, sync time = 82
,W/libprocessgroup( 1011): failed to open /acct/uid_1000/pid_5200/cgroup.procs: No such file or directory
,W/libprocessgroup( 1011): failed to open /acct/uid_10156/pid_5855/cgroup.procs: No such file or directory
,D/LocationManagerService( 1011): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1829): Tagging socket 88 with tag 3000120100000000{805310977,0} for uid -1, pid: 1829, getuid(): 10012
,D/LocationManagerService( 1011): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1829): Tagging socket 88 with tag 3000120100000000{805310977,0} for uid -1, pid: 1829, getuid(): 10012
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/SensorService( 1011): [SO] Reset Rotation Old [100], Init [1]
,D/LocationManagerService( 1011): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1829): Tagging socket 88 with tag 3000120100000000{805310977,0} for uid -1, pid: 1829, getuid(): 10012
,D/CustomFrequencyManagerService( 1011): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1011  tag : ACTIVITY_RESUME_BOOSTER@11
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1011): [SO] currT = 115700081933, prevT = 115280104017, diff = 419977916, [0.077 0.096 10.075]
,D/SensorService( 1011): [SO] 0.077 0.096 10.075
D/SensorService( 1011): [SO] [100 -> 255]
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PowerManagerService( 1011): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1172 (0x0)
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1011): SIOP:: AP = 310,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/TaskPersister( 1011): removeObsoleteFile: deleting file=7_task_thumbnail.png
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF,
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1011): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1011): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1011): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1011): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1011): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1011): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1011): lcd : 1 +
,D/lights  ( 1011): lcd : 1 -
,D/DisplayPowerController( 1011): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1011): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  290): DCD OFF
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/PowerManagerService( 1011): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1011): Nap time (uid 1000)...
,D/PowerManagerService( 1011): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
,I/PowerManagerService( 1011): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
,I/PowerManagerService( 1011): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService( 1011): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/WindowOrientationListener( 1011): WindowOrientationListener disabled
D/SensorService( 1011): [SO] activate (ident=0xb8511408, enabled=0)
,I/Sensors ( 1011): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/PowerManagerService( 1011): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService( 1011): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
,D/PowerManagerService( 1011): handleSandman : startDream(true)
,E/PowerManagerService( 1011): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1011): Sleeping (uid 1000)...
D/PowerManagerService( 1011): [s] UserActivityState : 4 -> 0
,I/SurfaceFlinger(  257): id=17 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1011): unregisterListener ::   
,D/KeyguardViewMediator( 1172): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1172): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1172): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1172): notifyScreenOffLocked
,D/PowerManagerService( 1011): Excessive delay in ColorFade : createSurface: 11ms
,D/Launcher.HomeView( 1473): onPause
,D/KeyguardViewMediator( 1172): timeout : 5000
D/Launcher( 1473): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/PowerManagerService( 1011): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 35ms
,D/KeyguardViewMediator( 1172): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1172): handleNotifyScreenOff
D/VolumePanel( 1172): onScreenTurnedOff()
,D/VolumePanel( 1172): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF end
,D/LightsService( 1011): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1011) 
,D/SecKeyguardClockSingleView( 1172): onScreenTurnedOff
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/DisplayPowerController( 1011): ColorFade: onAnimationStart
D/DisplayPowerController( 1011): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1011): performScreenOffTransition : no brightness animation
D/LightsService( 1011): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1011): turn on LED for fully charged
E/lights  ( 1011): write_int failed to open -1
D/LightsService( 1011): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1011): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/TaskCloserActivity( 6380): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,V/ActivityThread( 1473): updateVisibility : ActivityRecord{317af803 token=android.os.BinderProxy@1c8282eb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1473): onStop
,E/SmartFaceService( 1011): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1011): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1011): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1011): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1011): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1011): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1011): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1011): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1011): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1011): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1011): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1011): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1011): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1011): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1011): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1011): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1011): 	at libcore.io.IoBridge.open(IoBridge.java:442)
,W/System.err( 1011): 	... 10 more
E/SmartFaceService( 1011): fail to set sysfs 0
,I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
,D/MotionRecognitionService( 1011):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1011):  handler : SCREEN_OFF end 
D/SamsungIME( 1771): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/NotificationService( 1011): ACTION_SCREEN_OFF
D/LightsService( 1011): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1011) 
D/LightsService( 1011): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1011): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1011): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/WifiNative-wlan0( 1011): do suspend true
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/BackgroundCompactionService( 1011): Schedule Type1 BGCompaction
,D/IpRemoteDisplayController( 1011): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1011): Bridge Server is not available
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
,D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/GpsLocationProvider( 1011): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PersonaManagerService( 1011): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1011): MSG_ACTION_SCREEN_OFF called
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1412): [EmergencyStateReceiver] binteractive [false] why[3]
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NfcService( 1436): call the applyRouting,
,D/accuweather( 1716): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1011): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1716): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 1716): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1716): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1716): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1716): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1909): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SSRM:n  ( 1011): SIOP:: AP = 300
,D/PowerManagerService( 1011): [PWL] sb release: PowerManagerService.Broadcasts
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1716): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1716): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1716): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1716): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1716): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/DisplayPowerState( 1011): !@ ColorFade entry
,D/DisplayPowerController( 1011): ColorFade: onAnimationEnd
,D/DisplayPowerController( 1011): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1011): performScreenOffTransition : no brightness animation
,D/lights  ( 1011): lcd : 0 +
,D/lights  ( 1011): lcd : 0 -
,D/DisplayPowerController( 1011): getFinalBrightness : Summary is 0 -> 0
,D/DisplayPowerController( 1011): performScreenOffTransition : no brightness animation
,D/MISC PowerHAL( 1011): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1011): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1011): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/PowerManagerService( 1011): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService( 1011): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1011): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1011): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,D/MISC PowerHAL( 1011): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1011): Got set_interactive hint
,D/DisplayManagerService( 1011): !@display_state: ON -> OFF
,I/DisplayManagerService( 1011): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1011): Display changed displayId=0
,D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb7d7c690
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/BatteryStatsDumper( 1011): In refreshStats isReason Screen ON/OFF: true
,D/NetworkStatsFactory( 1011): UpdateStatsForKnox updated
,I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8bf37c8
I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1195427704)
,D/NetworkStatsFactory( 1011): UpdateStatsForKnox updated
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1195427704) wakelock released: 1, error no: 0
I/rmt_storage(  271): 
,I/BatteryStatsDumper( 1011): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1011): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1011): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1011): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1011): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1011): Previous Battery Level: 100 Current Level: 100 Delta: 0
I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8bf37c8
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
,D/SurfaceControl( 1011): Excessive delay in setPowerMode(): 263ms
,I/libsuspend( 1011): !@autosuspend_wakeup_count_enable
D/PowerManagerService( 1011): Excessive delay in !@display_state: OFF: 265ms
I/libsuspend( 1011): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1011): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 272ms
,I/PowerManagerService( 1011): [PWL] Off : 0s ago
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
I/PowerManagerService( 1011): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1011): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1011): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1011, ws=null) (elapsedTime=222),
,I/BatteryStatsDumper( 1011): Writing to database completed
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1011): waitForAlarm result :4
,D/KeyguardViewMediator( 1172): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1172): doKeyguard: not showing because lockscreen is off,
V/KeyguardEffectViewController( 1172): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1011): [PWL] Off : 5s ago,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1011): waitForAlarm result :8
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1011): SIOP:: AP = 290,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 4,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/AlarmManager( 1011): waitForAlarm result :8
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1011): [PWL] Off : 15s ago,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
,D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SSRM:n  ( 1011): SIOP:: AP = 270
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2588): Disconnected process message: 10
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1011): waitForAlarm result :4
,D/ActivityManager( 1011): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1011): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0,
,I/BackgroundCompactionService( 1011): onStart. jobID=801
,I/BackgroundCompactionService( 1011): onStart done. jobID=801
,I/BackgroundCompactionService( 1011): Execute BGCompaction (type1). (1 times)
,I/BackgroundCompactionService( 1011): compact_memory command done,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1011): [PWL] Off : 30s ago
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1011): waitForAlarm result :8,
,D/SSRM:n  ( 1011): SIOP:: AP = 280
D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 5
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1011): [PWL] Off : 50s ago
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1011): !@Sync 6
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1011): [PWL] Off : 75s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ClearcutLoggerApiImpl( 1829): disconnect managed GoogleApiClient
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1011): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/Watchdog( 1011): !@Sync 7
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1011): [PWL] Off : 105s ago,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1011): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1011): userId = 0, bbcId = -10000
,W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 3571): Aggregate from 1453414277695 (log), 1453414277695 (data)
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1011): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast,
,E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6483): MountEmulatedStorage()
I/libpersona( 6483): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6483): v2
I/libpersona( 6483): KNOX_SDCARD not a persona
I/SELinux ( 6483): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1011): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6483 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6483): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6483): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6483): TimaSignature is unavailable
,D/ActivityThread( 6483): Added TimaKeyStore provider
,W/ResourcesManager( 6483): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1011): Killing 5875:com.sec.pcw.device/1000 (adj 15): empty #31
,W/libprocessgroup( 1011): failed to open /acct/uid_1000/pid_5875/cgroup.procs: No such file or directory
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1011): !@Sync 8,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1011): [PWL] Off : 140s ago
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
,D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1011): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1011): !@Sync 9
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1011): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_initialize( 1011): initializing...
D/TimaService( 1011): TIMA: TimaService scheduler is intialized. 
,I/TLC_TIMA_PKM_initialize( 1011): root = /firmware/image, root_strlen = 15
D/TimaService( 1011): TIMA: checkEvent, operation: 50000 subject: 10000
I/TLC_TIMA_PKM_initialize( 1011): process = tima_pkm, process_strlen = 8
D/TimaService( 1011): TimaServiceHandler.handleMessage what =1
I/TZ: qc_tlc_communication( 1011): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1011): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1011): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1011): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1011): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1011): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1011): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1011): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1011): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1011): Trustlet response is completed
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1011): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1011): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1011): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1011): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1011): !@Sync 10
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/Watchdog( 1011): !@Sync 11
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1011): [PWL] Off : 225s ago
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/Watchdog( 1011): !@Sync 12
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1011): [PWL] Off : 275s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/Watchdog( 1011): !@Sync 13
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/Watchdog( 1011): !@Sync 14
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1011): [PWL] Off : 330s ago,
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1011): waitForAlarm result :8
,V/AlarmManager( 1011): No more alarm at this time.nowELAPSED=465674 batch.start=797764
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/Watchdog( 1011): !@Sync 15
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/bootchecker(  325): bootchecker wake up!!
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/Watchdog( 1011): !@Sync 16
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
,D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1011): [PWL] Off : 390s ago
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1011): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/Watchdog( 1011): !@Sync 17
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/Watchdog( 1011): !@Sync 18,
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1011): [PWL] Off : 455s ago
,I/Atfwd_Daemon(  329): Stop the daemon....
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 19,
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,I/MotionRecognitionService( 1011): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
,I/MotionRecognitionService( 1011): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
,D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1011): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/TimaService( 1011): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1011): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1011): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1011): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1011): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1011): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1011): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 20
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1011): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 21
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1011): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1011): [PWL] Off : 525s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
,D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,I/MotionRecognitionService( 1011): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 22
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1011): !@Sync 23
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1011): [PWL] Off : 600s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 24
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
,D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 25
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1011): waitForAlarm result :8,
,E/Watchdog( 1011): !@Sync 26,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1011): [PWL] Off : 680s ago
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 27
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 28,
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1011): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 29,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1011): [PWL] Off : 765s ago,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1011): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
,D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1011): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/TimaService( 1011): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1011): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1011): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1011): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1011): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1011): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1011): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 30,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
,D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1011): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1011): waitForAlarm result :8,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 31
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
,D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1011): !@Sync 32
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1011): [PWL] Off : 855s ago
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
,D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 33,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1011): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1011): Plugged
I/MotionRecognitionService( 1011): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 34
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
,D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 35
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1011): [PWL] Off : 950s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 36
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 37,
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 38
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1011): [PWL] Off : 1050s ago
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 39
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1011): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 1011): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1011): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1011): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1011): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1011): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1011): Updating Usage Statistics in DB @ 1453417110019
,I/ApplicationPolicy( 1011): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1011): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1011): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1011): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1011): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1011): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1011): ::isTableExists: Table exists 
,I/ApplicationUsage( 1011): Done Updating Usage Statistics in DB @ 1453417110423
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 40
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged
,I/MotionRecognitionService( 1011): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1011): Plugged,
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1011): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 41
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1011): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1011): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1011): stay LED for fully charged
D/BatteryService( 1011): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1011): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1011): mGripSensorEnabled= false
V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2588): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2588): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1011): !@Sync 42
,D/SSRM:n  ( 1011): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1011): [PWL] Off : 1155s ago
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1011): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1011): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6925): 
D/AndroidRuntime( 6925): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6925): CheckJNI is OFF
D/AndroidRuntime( 6925): readGMSProperty: start
D/AndroidRuntime( 6925): readGMSProperty: already setted!!
D/AndroidRuntime( 6925): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6925): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6925): readGMSProperty: end
D/AndroidRuntime( 6925): addProductProperty: start
E/AffinityControl( 6925): AffinityControl: registerfunction enter
D/AndroidRuntime( 6925): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1011): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1011): START PACKAGE DELETE: observer{816633840}
D/PackageManager( 1011): pkg{<packageName>}
D/PackageManager( 1011): user{0}
D/PackageManager( 1011): caller{2000}
D/PackageManager( 1011): flags{3}
D/PersonaManagerService( 1011): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1011): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1011): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1011): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1011): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1011): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1011): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1011): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1011): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1011): !@killApplicatoin: 10155, uninstall pkg
I/ActivityManager( 1011): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
I/ActivityManager( 1011): Killing 6153:com.test.thalitest/u0a155 (adj 15): stop com.test.thalitest cause uninstall pkg
W/ActivityManager( 1011): Spurious death for ProcessRecord{17034169 6153:com.test.thalitest/u0a155}, curProc for 6153: null
I/ActivityManager( 1011): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
W/ActivityManager( 1011): CustomStartingWindow se packge removed so remove capture also
I/art     ( 5705): Explicit concurrent mark sweep GC freed 20556(1121KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 6MB/11MB, paused 1.515ms total 57.726ms
I/art     ( 5488): Explicit concurrent mark sweep GC freed 400(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 1.522ms total 61.012ms
I/InputReader( 1011): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1771): mOCRHelper is null
W/GeofencerStateMachine( 1829): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.183: ( 3598): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 21 23:59:47 GMT+01:00 2016
D/RegisteredComponentCache( 1436): Collect Tech packages for Knox
D/PersonaManager( 1436): isKioskContainerExistOnDevice
D/ActivityManager( 1011): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.183: ( 3598): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1011): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1011): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6938): MountEmulatedStorage()
E/Zygote  ( 6938): v2
I/libpersona( 6938): KNOX_SDCARD checking this for 10094
I/libpersona( 6938): KNOX_SDCARD not a persona
I/ActivityManager( 1011): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6938 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6938): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6938): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6938): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
I/art     ( 3571): Explicit concurrent mark sweep GC freed 4895(329KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 13MB/18MB, paused 1.128ms total 189.950ms
E/Zygote  ( 6947): MountEmulatedStorage()
I/libpersona( 6947): KNOX_SDCARD checking this for 10149
E/Zygote  ( 6947): v2
I/libpersona( 6947): KNOX_SDCARD not a persona
I/SELinux ( 6947): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1011): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6947 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/PackagesMonitor( 6352): PackagesMonitor onReceive :com.test.thalitest
I/SELinux ( 6947): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6947): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6938): TimaSignature is unavailable
D/ActivityThread( 6938): Added TimaKeyStore provider
D/PersonaManager( 1436): isKioskContainerExistOnDevice
D/SecContentProvider2( 1011): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1011): mCursor = null
D/RegisteredServicesCache( 1436): empty dynamic service
I/KLMS-2.5.183: ( 3598): KLMSIntentService(): onCreate()
I/KLMS-2.5.183: ( 3598): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/TimaKeyStoreProvider( 6947): TimaSignature is unavailable
D/ActivityThread( 6947): Added TimaKeyStore provider
D/Mms/FreeMessageStatusReceiver( 5835): onReceive, action : android.intent.action.PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3598): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
W/SQLiteConnectionPool( 3571): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/art     ( 1011): Explicit concurrent mark sweep GC freed 68817(7MB) AllocSpace objects, 277(4MB) LOS objects, 33% free, 29MB/44MB, paused 3.286ms total 272.615ms
I/art     ( 1011): WaitForGcToComplete blocked for 175.126ms for cause Explicit
I/KLMS-2.5.183: ( 3598): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/ActivityManager( 1011): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/art     ( 6483): Explicit concurrent mark sweep GC freed 379(32KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 2.438ms total 39.226ms
I/TactileAssist( 1011): enable value -1
I/TactileAssist( 1011): internal enable value -1
I/TactileAssist( 1011): intensity value -1
D/Mms/FreeMessageReceiverService( 5835): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5835): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1011): saveAppList value true
D/elm:15183( 6938): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/KLMS-2.5.183: ( 3598): KLMSIntentService(): PACKAGE_REMOVED
D/elm:15183( 6938): ELMEngine.ELMEngine( context ).
E/SQLiteLog( 6483): (284) automatic index on crash_info_summary(package_name_touched)
D/elm:15183( 6938): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1011): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
I/TactileAssist( 1011): List of disabled apps :
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
I/KLMS-2.5.183: ( 3598): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3598): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/elm:15183( 6938): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/BadgeProvider( 6036): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6036): sendNotify, [notify] : null
D/BadgeProvider( 6036): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6036): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6036): update, [UpdateCount] : 1
D/elm:15183( 6938): ElmAgentService : onCreate()
D/elm:15183( 6938): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6938): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6938): MDMBridge.getInstance()
D/elm:15183( 6938): MDMBridge.getAllLicenseInfoFromSDK()
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
D/elm:15183( 6938): MDMBridge.getAllLicenseInfoFromSDK()
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6974): MountEmulatedStorage()
E/Zygote  ( 6974): v2
I/libpersona( 6974): KNOX_SDCARD checking this for 1000
I/libpersona( 6974): KNOX_SDCARD not a persona
I/SELinux ( 6974): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6974): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6974): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1011): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6974 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3598): KLMSIntentService(): listeningToPackageRemoved().END
D/elm:15183( 6938): ElmAgentService : onDestroy().
I/KLMS-2.5.183: ( 3598): KLMSIntentService(): onDestroy()
D/ThemeInfoUtil( 6947): getCurrentFestivalName is [null]
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
D/ThemeInfoUtil( 6947): isCurrentFestival = false
D/TimaKeyStoreProvider( 6974): TimaSignature is unavailable
D/ActivityThread( 6974): Added TimaKeyStore provider
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 1011): PackageReceiver onReceive()
I/HarmonyEASService( 1011): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1011): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1011): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1011): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1011): DBIntegrity::getInstance - New instance created
E/Zygote  ( 6990): MountEmulatedStorage()
E/Zygote  ( 6990): v2
I/libpersona( 6990): KNOX_SDCARD checking this for 1000
I/SELinux ( 6990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6990): KNOX_SDCARD not a persona
I/SELinux ( 6990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/OTPFW   ( 1011): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
I/ActivityManager( 1011): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6990 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/OTPFW   ( 1011): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1011): ProvisionData::getAllEntries Table is empty
E/SELinux ( 6990): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BackupManagerService( 1011): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1011): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1011): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1011): uID is 10155
V/EnterpriseBillingPolicy( 1011): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1011): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1011): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1011): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1011): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1011): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1011): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1011): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1011): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1011): uID is 10155
V/EnterpriseBillingPolicy( 1011): Removed Packageuid is0
D/SSRM:aZ ( 1011): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1011): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1011): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1011): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1011): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1011): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1011): getBillingProfileForVpnEngine - end - null
V/AlarmManagerEXT( 1011): com.test.thalitest(10155) is removed.
D/TaskPersister( 1011): removeObsoleteFile: deleting file=8_task.xml
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6990): TimaSignature is unavailable
D/ActivityThread( 6990): Added TimaKeyStore provider
E/Zygote  ( 7005): MountEmulatedStorage()
I/libpersona( 7005): KNOX_SDCARD checking this for 10152
E/Zygote  ( 7005): v2
I/libpersona( 7005): KNOX_SDCARD not a persona
I/ActivityManager( 1011): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7005 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/ActivityManager( 1011): Killing 5893:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
I/SELinux ( 7005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1011): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/Compatibility( 6092): onReceive() it will make start service
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
I/SELinux ( 7005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7005): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 6092): onHandleIntent()
D/Compatibility( 6092): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/ActivityManager( 1011): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
D/Compatibility( 6092): found: 2
D/Compatibility( 6092): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6092): skipping ResolveInfo{177b8916 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6092): considering ResolveInfo{624297 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6092): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6092): enabling receiver ResolveInfo{31ea8c84 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 6092): enabling receiver ResolveInfo{29c63c6d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6092): enabling receiver ResolveInfo{191f20a2 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/UpdateIcingCorporaServi( 5488): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/TimaKeyStoreProvider( 7005): TimaSignature is unavailable
D/Compatibility( 6092): enabling receiver ResolveInfo{d7e7133 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ActivityThread( 7005): Added TimaKeyStore provider
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
D/AASAservice-UpdateReceiver( 6974): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
I/art     ( 1011): Explicit concurrent mark sweep GC freed 16777(991KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 29MB/44MB, paused 3.706ms total 309.090ms
W/System.err( 6974): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6974): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6974): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6974): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6974): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6974): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6974): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6974): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6974): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6974): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6974): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6974): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6974): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/Zygote  ( 7023): MountEmulatedStorage()
E/Zygote  ( 7023): v2
I/libpersona( 7023): KNOX_SDCARD checking this for 10003
I/libpersona( 7023): KNOX_SDCARD not a persona
I/SELinux ( 7023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/Compatibility( 6092): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/ActivityManager( 1011): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7023 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
I/SELinux ( 7023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
D/PackageManager( 1011): delete codoeFile: 
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
D/AASAuninstall( 1011): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
I/AASA_removePackage( 1011): UID=10155 Target=com.test.thalitest
D/PackageManager( 1011): result of delete: 1{816633840}
W/ContextImpl( 6990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/AndroidRuntime( 6925): Shutting down VM
E/Zygote  ( 7038): MountEmulatedStorage()
E/Zygote  ( 7038): v2
I/libpersona( 7038): KNOX_SDCARD checking this for 1000
I/libpersona( 7038): KNOX_SDCARD not a persona
I/SELinux ( 7038): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/TimaKeyStoreProvider( 7023): TimaSignature is unavailable
D/ActivityThread( 7023): Added TimaKeyStore provider
I/SELinux ( 7038): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1011): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7038 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 7038): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1011): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/SQLiteLog( 7005): (284) automatic index on shooting_modes(title_id)
D/TimaKeyStoreProvider( 7038): TimaSignature is unavailable
D/ActivityThread( 7038): Added TimaKeyStore provider
D/ActivityManager( 1011): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
D/RCPManager( 5566):  in createShortcut() for packageName: com.test.thalitest userId0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 1011):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1011): queryAllProviders():  providerCallBack is not register for 0
D/UserAnalysis.PlaceProvider( 7023): PlaceProvider onCreate()
E/Zygote  ( 7056): MountEmulatedStorage()
E/Zygote  ( 7056): v2
I/libpersona( 7056): KNOX_SDCARD checking this for 10156
I/libpersona( 7056): KNOX_SDCARD not a persona
I/SELinux ( 7056): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1011): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7056 uid=10156 gids={50156, 9997} abi=armeabi-v7a
I/SELinux ( 7056): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7056): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/PCWCLIENTTRACE_LOG( 7038): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7038): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7038): new DMDBOpenHelper instance
D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1011): userId = 0, bbcId = -10000
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/UserAnalysis.SecureDbManager( 7023): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 7023): SecurePlaceDbHelper() 
D/UserAnalysis( 7023): Create SecureDbHelper
I/PCWCLIENTTRACE_PushUtil( 7038): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7038): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7038): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7038): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/TimaKeyStoreProvider( 7056): TimaSignature is unavailable
D/ActivityThread( 7056): Added TimaKeyStore provider
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
D/IntelligenceServiceApplication( 7023): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 7023): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
D/Launcher.Model( 1473): reloadBadges entered.
E/Zygote  ( 7071): MountEmulatedStorage()
E/Zygote  ( 7071): v2
I/libpersona( 7071): KNOX_SDCARD checking this for 1000
I/libpersona( 7071): KNOX_SDCARD not a persona
I/SELinux ( 7071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1011): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7071 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/IntelligenceServiceApplication( 7023): no applications having user consent for prediction
I/ActivityManager( 1011): Killing 5908:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
D/ActivityManager( 1011): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
I/SELinux ( 7071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7071): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/TapandpayWidget:TapandpayAppWidgetProvider( 7056): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 7056): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 7056): Clear T&P info.
D/ActivityManager( 1011): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetection::stopService] Service stopped.
D/TimaKeyStoreProvider( 7071): TimaSignature is unavailable
D/ActivityThread( 7071): Added TimaKeyStore provider
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/TapandpayWidget:TapandpayAppWidgetProvider( 7056): Widget is not attached.
E/SQLiteLog( 6483): (284) automatic index on crash_info_summary(package_name_touched)
W/art     ( 6925): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
I/libpersona( 7089): KNOX_SDCARD checking this for 10035
E/Zygote  ( 7089): MountEmulatedStorage()
I/libpersona( 7089): KNOX_SDCARD not a persona
E/Zygote  ( 7089): v2
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
I/ActivityManager( 1011): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7089 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
I/SELinux ( 7089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 7023): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
I/ActivityManager( 1011): Killing 5929:com.policydm/1000 (adj 15): empty #31
I/SELinux ( 7089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7089): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1011): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/BluetoothAdapter( 7023): cancelDiscovery
W/ActivityManager( 1011): userId = 0, bbcId = -10000
W/ActivityManager( 1011): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1011): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     (  306): Explicit concurrent mark sweep GC freed 8735(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 706us total 21.523ms
D/BadgeProvider( 6036): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6036): sendNotify, [notify] : null
D/BadgeProvider( 6036): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6036): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6036): update, [UpdateCount] : 1
D/TimaKeyStoreProvider( 7089): TimaSignature is unavailable
D/ActivityThread( 7089): Added TimaKeyStore provider
D/ActivityManager( 1011): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 17.361ms
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1011): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 7071): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 

```
