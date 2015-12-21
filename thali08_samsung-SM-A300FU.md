#### Test 50650278d1b06e8_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
I/DBG_POLICYDM( 5556): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
I/DBG_POLICYDM( 5556): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
I/DBG_POLICYDM( 5556): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 5556): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 5556): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/DBG_POLICYDM( 5556): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 5556): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 5556): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 5556): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
I/DBG_POLICYDM( 5556): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 5556): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 5556): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 5556): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 5556): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
I/DBG_POLICYDM( 5556): [com.policydm.XSPPReceiver(53/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
E/SMD     (  298): DCD OFF
I/ServiceManager(  335): Waiting for service AtCmdFwd...
I/DBG_POLICYDM( 5556): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
--------- beginning of system
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/art     ( 5467): Suspending all threads took: 35.384ms
E/Zygote  ( 5590): MountEmulatedStorage()
E/Zygote  ( 5590): v2
I/libpersona( 5590): KNOX_SDCARD checking this for 10036
I/libpersona( 5590): KNOX_SDCARD not a persona
I/SELinux ( 5590): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5590 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 4777:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
I/SELinux ( 5590): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5590): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5590): TimaSignature is unavailable
D/ActivityThread( 5590): Added TimaKeyStore provider
D/NativeLibraryUtils( 5467): Install completed successfully. count=14 extracted=0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/CAR.SERVICE( 5467): Connecting to CarCallService...
W/libprocessgroup( 1019): failed to open /acct/uid_10055/pid_4777/cgroup.procs: No such file or directory
I/System.out( 5264): Thread-882(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5264): Thread-882(ApacheHTTPLog):isShipBuild true
I/System.out( 5264): Thread-882(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5264): Thread-882(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
I/art     ( 5467): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5467): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/CAR.SERVICE( 5467): com.google.android.projection.gearhead isn't installed.
I/DBG_POLICYDM( 5556): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/DBG_POLICYDM( 5556): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/CAR.TEL.Service( 5467): Creating a new CarCallService.
D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1967): Module APK com.google.android.play.games already loaded
D/CAR.TEL.PhoneAdapter( 5467): Creating a new PhoneAdapter instance
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5467): setListener: com.google.android.gms.car.dn@3a3324cc
W/ActivityManager( 1019): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5467): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5467): Starting CarCallService with initial phone null
D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/DBG_POLICYDM( 5556): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 5556): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
I/DBG_POLICYDM( 5556): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
I/DBG_POLICYDM( 5556): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
I/qtaguid ( 5264): Untagging socket 44
I/qtaguid ( 5264): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5264): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5264): untagSocket(44) failed with errno -22
I/System.out( 5264): Thread-882 calls detatch()
D/CAR.SERVICE( 5467): Package validated; name: com.android.vending
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
I/SA      ( 5590): [SSP] onCreated
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
D/AsyncTaskServiceImpl( 1967): Submit a task: k
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/SA      ( 5590): [TPM] There is no property file
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SA      ( 5590): [SCU] isHaveSA() - false
I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
I/SA      ( 5590): [TPM] getModelProperty : null
I/SA      ( 5590): [TPM] getCSCProperty : null
I/DBG_POLICYDM( 5556): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 5556): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/SA      ( 5590): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5590): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5590): [DM] TFT FEATURE: false
I/DBG_POLICYDM( 5556): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
I/SA      ( 5590): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5590): [DM] init START
I/SA      ( 5590): [DM] This device is not a Vodafone
I/DBG_POLICYDM( 5556): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2015/12/24/09:31:06
I/DBG_POLICYDM( 5556): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2015/12/21/00:51:47
I/DBG_POLICYDM( 5556): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 5556): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
D/AndroidRuntime( 5596): 
D/AndroidRuntime( 5596): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5596): CheckJNI is OFF
D/AndroidRuntime( 5596): readGMSProperty: start
D/AndroidRuntime( 5596): readGMSProperty: already setted!!
D/AndroidRuntime( 5596): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5596): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5596): readGMSProperty: end
D/AndroidRuntime( 5596): addProductProperty: start
I/DBG_POLICYDM( 5556): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.vision from APK com.google.android.gms
V/Finsky  ( 5264): [1] GearheadStateMonitor.access$100: mIsProjecting:false
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
I/DBG_POLICYDM( 5556): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
W/ResourceType( 5590): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
D/k       ( 1967): Processing package: com.test.thalitest
W/ResourceType( 5590): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
I/DBG_POLICYDM( 5556): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5556): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5556): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 5556): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
I/DBG_POLICYDM( 5556): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5556): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 5556): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
I/ActivityManager( 1019): Killing 4892:com.sec.smartcard.manager/u0a149 (adj 15): empty #31
W/ResourceType( 5590): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 5590): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5590): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
I/SA      ( 5590): [SCU] isHaveSA() - false
I/SA      ( 5590): support phone number id : false
I/SA      ( 5590): [DM] Supports Ref Jpn : true
I/SA      ( 5590): [DM] init END
I/SA      ( 5590): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5590): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10326 extra.user_handle.:0 ]
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/GassUtils( 1967): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 1967): Found info for package com.test.thalitest in db.
E/Zygote  ( 5634): MountEmulatedStorage()
I/ActivityManager( 1019): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5634 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 5634): v2
I/libpersona( 5634): KNOX_SDCARD checking this for 10009
I/SELinux ( 5634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 5634): KNOX_SDCARD not a persona
I/SELinux ( 5634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Killing 4996:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
E/SELinux ( 5634): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/UpdateIcingCorporaServi( 3254): UpdateCorporaTask done [took 936 ms] updated apps [took 935 ms] 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     (  314): Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 624us total 33.846ms
I/DBG_POLICYDM( 5556): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
E/AffinityControl( 5596): AffinityControl: registerfunction enter
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 19.728ms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5634): TimaSignature is unavailable
D/ActivityThread( 5634): Added TimaKeyStore provider
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 5596): Calling main entry com.android.commands.am.Am
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 627us total 21.908ms
I/DBG_POLICYDM( 5556): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5556): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1019): mDVFSHelper.acquire()
I/SurfaceFlinger(  258): id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  258): id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1019): Set to : 0
I/DBG_POLICYDM( 5556): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
E/Zygote  ( 5654): MountEmulatedStorage()
E/Zygote  ( 5654): v2
I/libpersona( 5654): KNOX_SDCARD checking this for 10326
I/libpersona( 5654): KNOX_SDCARD not a persona
I/SELinux ( 5654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5654 uid=10326 gids={50326, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
E/SELinux ( 5654): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  258): id=12 createSurf (540x960),1 flag=404, uhalitest
I/DBG_POLICYDM( 5556): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1480
D/AndroidRuntime( 5596): Shutting down VM
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
W/libprocessgroup( 1019): failed to open /acct/uid_10149/pid_4892/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4996/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5654): TimaSignature is unavailable
I/DBG_POLICYDM( 5556): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
D/ActivityThread( 5654): Added TimaKeyStore provider
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1019): Display changed displayId=0
I/PeopleDatabaseHelper( 1967): cleanUpNonGplusAccounts done.
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/ServiceManager(  335): Waiting for service AtCmdFwd...
D/PersonaManager( 1019): isKioskContainerExistOnDevice
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=7 Removed Mauncher (5/9)
W/ActivityManager( 1019): userId = 0, bbcId = -10000
I/SurfaceFlinger(  258): id=7 Removed Mauncher (-2/9)
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/ActivityThread( 1480): updateVisibility : ActivityRecord{3d72041f token=android.os.BinderProxy@283acb38 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1480): onTrimMemory. Level: 20
I/ActivityManager( 1019): Killing 5051:com.sec.android.app.sns3/u0a30 (adj 15): empty #31
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/Finsky  ( 5264): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/art     ( 5596): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/WebViewFactory( 5654): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
W/libprocessgroup( 1019): failed to open /acct/uid_10030/pid_5051/cgroup.procs: No such file or directory
I/LibraryLoader( 5654): Loading: webviewchromium
I/LibraryLoader( 5654): Time to load native libraries: 5 ms (timestamps 433-438)
I/LibraryLoader( 5654): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5654): Binding Chromium to main looper Looper (main, tid 1) {3a361261}
I/LibraryLoader( 5654): Expected native library version number "",actual native library version number ""
I/chromium( 5654): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5654): Initializing chromium process, renderers=0
W/art     ( 5654): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5654): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5654): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 5654): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/Adreno-EGL( 5654): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5654): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5654): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5654): Local Branch: 
I/Adreno-EGL( 5654): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5654): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5654):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/chromium( 5654): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 5654): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/art     ( 5654): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5654): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5654): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5654): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 5654): CordovaWebView is running on device made by: samsung
W/art     ( 5654): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5654): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{361f6d48 u0 com.test.thalitest/.MainActivity t2}
D/OpenGLRenderer( 5654): Render dirty regions requested: true
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
V/ActivityThread( 5654): updateVisibility : ActivityRecord{14500337 token=android.os.BinderProxy@351755d1 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 5654): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5654): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1019): Focus entered window: 5654
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5654): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5654): Initialized EGL, version 1.4
D/OpenGLRenderer( 5654): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5654): Enabling debug mode 0
W/art     ( 1967): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 312.400ms
D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
I/ActivityManager( 1019): Displayed Component not be shown by security: +688ms (total +791ms)
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{361f6d48 u0 com.test.thalitest/.MainActivity t2} time:80916
W/ActivityManager( 1019): mDVFSHelper.release()
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Icing   ( 1967): Indexing D2B2F813CD55909B17D100D9886DFA4C4B449F6E from com.google.android.googlequicksearchbox
I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
W/IInputConnectionWrapper( 5654): showStatusIcon on inactive InputConnection
I/SurfaceFlinger(  258): id=12 Removed uhalitest (-2/9)
I/Timeline( 5654): Timeline: Activity_idle id: android.os.BinderProxy@351755d1 time:80931
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SamsungIME( 1837): getCurrentCandidateView
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5709): MountEmulatedStorage()
E/Zygote  ( 5709): v2
I/libpersona( 5709): KNOX_SDCARD checking this for 1000
I/libpersona( 5709): KNOX_SDCARD not a persona
I/SELinux ( 5709): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5709): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5709): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5709 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
W/GAV2    ( 5483): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/TimaKeyStoreProvider( 5709): TimaSignature is unavailable
D/ActivityThread( 5709): Added TimaKeyStore provider
D/FilterInstaller( 5709): onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
W/ContextImpl( 5709): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
I/chromium( 5654): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5654): 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/Icing   ( 1967): Indexing done D2B2F813CD55909B17D100D9886DFA4C4B449F6E
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
I/Icing   ( 1967): Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/FilterInstaller( 5709): FilterPackageService : ACTION_CHANGED
I/ServiceManager(  335): Waiting for service AtCmdFwd...
E/Zygote  ( 5735): MountEmulatedStorage()
I/libpersona( 5735): KNOX_SDCARD checking this for 10098
E/Zygote  ( 5735): v2
I/libpersona( 5735): KNOX_SDCARD not a persona
I/SELinux ( 5735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/SamsungIME( 1837): Dismiss ExpandCandiate
,I/SELinux ( 5735): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5735): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5735 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/FilterInstaller( 5709): installFilters
,E/FilterInstaller( 5709): There is no requred permission
,I/ActivityManager( 1019): Killing 5085:com.sec.spp.push:RemoteDlcProcess/u0a32 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5735): TimaSignature is unavailable
,D/ActivityThread( 5735): Added TimaKeyStore provider
,I/SamsungIME( 1837): getDebugLevel  : 0x4f4c
,D/JsMessageQueue( 5654): Set native->JS mode to OnlineEventsBridgeMode,
W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_5085/cgroup.procs: No such file or directory
I/Icing   ( 1967): Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
,D/PackageIntentReceiver( 5735): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 5735): Not GearManger package! 
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5750): MountEmulatedStorage()
E/Zygote  ( 5750): v2
I/libpersona( 5750): KNOX_SDCARD checking this for 1000
I/libpersona( 5750): KNOX_SDCARD not a persona
,I/SELinux ( 5750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5750 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5750): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Killing 5105:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5750): TimaSignature is unavailable
,D/ActivityThread( 5750): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1837): getDebugLevel  : 0x4f4c
,W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_5105/cgroup.procs: No such file or directory
,I/SamsungIME( 1837): KeybaordView init() : load resources
,D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1967): Module APK com.google.android.play.games already loaded
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5264): Thread-883(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5264): Thread-883(ApacheHTTPLog):isShipBuild true
I/System.out( 5264): Thread-883(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5264): Thread-883(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5767): MountEmulatedStorage()
E/Zygote  ( 5767): v2,
I/libpersona( 5767): KNOX_SDCARD checking this for 1000
I/libpersona( 5767): KNOX_SDCARD not a persona
I/SELinux ( 5767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SamsungIME( 1837): getCurrentKeyboard,
I/SamsungIME( 1837): getTextKeyboard,
I/SELinux ( 5767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5767 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 5146:com.android.providers.calendar/u0a37 (adj 15): empty #31
E/SELinux ( 5767): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5767): TimaSignature is unavailable
D/ActivityThread( 5767): Added TimaKeyStore provider
D/SamsungIME( 1837): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/AcmsPackageEventListener( 5767): Received: android.intent.action.PACKAGE_ADDED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/ContextImpl( 5767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,W/libprocessgroup( 1019): failed to open /acct/uid_10037/pid_5146/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/AcmsService( 5767): Enter Oncreate
D/AcmsServiceMonitor( 5767): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5767): creating AcmsCore
D/AcmsCore( 5767): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5767): AcmsCore
,D/AcmsCore( 5767): init
D/AcmsCore( 5767): Looper handler is not null
D/AcmsCore( 5767): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5767): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5767): Incrementing - Counter value: 1
D/AcmsCore( 5767): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 5767): onStartCommand
D/AcmsService( 5767): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5767): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5767): Incrementing - Counter value: 2
D/AcmsService( 5767): Incremented Counter Value : onStartCommand
D/AcmsCertificateMngr( 5767): AcmsCertificateMngr
I/qtaguid ( 5264): Untagging socket 44
,D/ActivityThread( 5767): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/jxcore_app_log( 5654): JniHelper::setJavaVM(0xb7814448), pthread_self() = -1210476392
D/JX-Cordova( 5654): jxcore cordova android initializing
,I/qtaguid ( 5264): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5264): Untagging socket 44 failed errno=-22
D/AcmsRevocationMngr( 5767): AcmsRevocationMngr
,W/NetworkManagementSocketTagger( 5264): untagSocket(44) failed with errno -22
I/System.out( 5264): Thread-883 calls detatch()
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/art     ( 5264): Suspending all threads took: 18.090ms
,D/AcmsService( 5767): Inside handle Intent
,E/Zygote  ( 5787): MountEmulatedStorage()
E/Zygote  ( 5787): v2
I/libpersona( 5787): KNOX_SDCARD checking this for 10148
,I/libpersona( 5787): KNOX_SDCARD not a persona
,I/SELinux ( 5787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5787 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
E/SELinux ( 5787): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GAV2    ( 5483): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager( 1019): Killing 5164:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/AcmsService( 5767): App added - package name: com.test.thalitest
D/AcmsCore( 5767): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5767): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5767): Incrementing - Counter value: 3
D/AcmsCore( 5767): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5767): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5767): Decrementing - Counter value: 2
D/TimaKeyStoreProvider( 5787): TimaSignature is unavailable
D/ActivityThread( 5787): Added TimaKeyStore provider
,E/SQLiteLog( 5787): (284) automatic index on shooting_modes(title_id)
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5164/cgroup.procs: No such file or directory
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5803): MountEmulatedStorage(),
,E/Zygote  ( 5803): v2
I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5803 uid=10152 gids={50152, 9997} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 4759:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
I/libpersona( 5803): KNOX_SDCARD checking this for 10152
I/SELinux ( 5803): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/libpersona( 5803): KNOX_SDCARD not a persona
,I/SELinux ( 5803): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5803): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5803): TimaSignature is unavailable
,D/ActivityThread( 5803): Added TimaKeyStore provider
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5803): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5803): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/TapandpayWidget:Utils( 5803): Clear T&P info.
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5803): Widget is not attached.
,I/splitIntent( 1019): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1019): Killing 4961:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4759/cgroup.procs: No such file or directory
,D/KeyguardViewMediator( 1176): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1176): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1176): *** Keyguard wallpaper service already unbounded
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1019): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1019): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1019): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1776): callingUid 10011, callindPid: 1776
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1776): [255] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/LocationInitializer( 1967): Restart initialization of location
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1776): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1019): failed to open /acct/uid_10146/pid_4961/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5264): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5264): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 41383(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.635ms total 192.068ms
,W/GCoreFlp( 1776): No location to return for getLastLocation()
,W/FusedLocationProvider( 1776): location=null
,W/ResourcesManager( 5264): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5264): [1] DailyHygiene.access$600: Logging device features
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1019): waitForAlarm result :4
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1776): client connected with version: 8296000
,D/Finsky  ( 5264): [904] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5264): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5264): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5264): (HTTPLog)-Static: isShipBuild true
,I/System.out( 5264): (HTTPLog)-Thread-893-820377570: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5264): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  283): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  283): getNetworkForDns: using netid 502 for uid 10026
,I/art     ( 1776): Explicit concurrent mark sweep GC freed 30067(1935KB) AllocSpace objects, 16(256KB) LOS objects, 39% free, 9MB/16MB, paused 1.172ms total 72.728ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5264): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5264): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/System.out( 5264): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/AcmsKeyStoreHelper( 5767):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5767): Key Store exist
,I/AcmsKeyStoreHelper( 5767): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 5767):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 5767): getKeyStoreForApplication success 
D/AcmsCore( 5767): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5767): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5767): Decrementing - Counter value: 1
D/AcmsCore( 5767): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5767): This is NOT a valid MirrorLink app
D/AcmsCore( 5767): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5767): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5767): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5767): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5767): getSvcCounter - Counter value: 0
,D/AcmsService( 5767): Enter onDestroy
I/AcmsService( 5767): cleanUp(): inside service clean up
,D/AcmsCore( 5767): AcmsCore: inside DeInit
D/AcmsCore( 5767): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5767): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5767): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5767): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5767): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5767): getSvcCounter - Counter value: 0
D/AcmsService( 5767): killing acms process
I/Process ( 5767): Sending signal. PID: 5767 SIG: 9
,I/ActivityManager( 1019): Killing 5217:com.sec.knox.bridge/1000 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 5011:com.google.android.talk/u0a102 (adj 15): empty #32
,I/ActivityManager( 1019): Process ACMS.Process (pid 5767)(adj 0) has died(53,584)
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5217/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10102/pid_5011/cgroup.procs: No such file or directory
,W/jxcore-log( 5654): Initializing JXcore engine
W/jxcore-log( 5654): JXcore engine is ready
,W/jxcore-log( 5654): Starting JXcore engine
,E/audit   ( 1856): type=1400 msg=audit(1450655510.655:205): avc:  denied  { ioctl } for  pid=5654 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1856):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1856): type=1300 msg=audit(1450655510.655:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=be9fdd58 items=0 ppid=314 ppcomm=main pid=5654 auid=4294967295 uid=10326 gid=10326 euid=10326 suid=10326 fsuid=10326 egid=10326 sgid=10326 fsgid=10326 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1856): type=1320 msg=audit(1450655510.655:205): 
,I/DBG_POLICYDM( 5556): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5556): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,W/jxcore-log( 5654): Platform android
W/jxcore-log( 5654): 
W/jxcore-log( 5654): Process ARCH arm
W/jxcore-log( 5654): 
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 5654): JXcore Cordova bridge is ready!,
I/jxcore-log( 5654): 
W/jxcore-log( 5654): JXcore engine is started
,D/SSRM:n  ( 1019): SIOP:: AP = 400
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/CAR.SERVICE( 5467): mConnectedToCar = false, abort
,E/ActivityThread( 5467): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@ab2a334 that was originally bound here
E/ActivityThread( 5467): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@ab2a334 that was originally bound here
E/ActivityThread( 5467): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5467): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5467): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5467): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5467): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5467): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5467): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5467): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5467): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5467): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5467): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5467): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5467): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5467): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 5467): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 5467): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 5467): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5467): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5467): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5467): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5467): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5467): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5467): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 5467): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@24d86eff that was originally bound here
E/ActivityThread( 5467): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@24d86eff that was originally bound here
E/ActivityThread( 5467): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5467): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5467): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5467): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5467): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5467): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5467): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5467): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5467): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5467): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5467): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5467): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5467): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 5467): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 5467): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 5467): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5467): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5467): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5467): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5467): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5467): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5467): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1019): Unbind failed: could not find connection for android.os.BinderProxy@7a2095
,E/SMD     (  298): DCD OFF,
,I/jxcore-log( 5654): Toggling radios to true
I/jxcore-log( 5654): 
,D/BluetoothAdapter( 5654): enable()
,D/BluetoothAdapter( 5654): enable(): BT is already enabled..!
,D/SecContentProvider( 1019): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1019): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1019): mCursor = null
,D/WifiService( 1019): setWifiEnabled: true pid=5654, uid=10326
,W/ActivityManager( 1019): Permission Denial: getCurrentUser() from pid=5654, uid=10326 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1019): Failed getting userId using ActivityManagerNative
W/WifiService( 1019): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5654, uid=10326 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1019): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1019): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1019): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1019): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1019): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1019): name = wifi_on
,I/WifiService( 1019): disconnect: pid=5654, uid=10326
,I/wpa_supplicant( 1394): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 5654): Radios toggled
I/jxcore-log( 5654): 
,I/jxcore-log( 5654): Got Device Bluetooth address: 08:EC:A9:50:76:27
I/jxcore-log( 5654): 
,I/jxcore-log( 5654): Perf Test app loaded loaded
I/jxcore-log( 5654): 
,I/jxcore-log( 5654): check test folder
I/jxcore-log( 5654): 
,I/jxcore-log( 5654): found test : ./testFindPeers.js
I/jxcore-log( 5654): 
,I/wpa_supplicant( 1394): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1394): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1394): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1394): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 1394): Cmd 35605 not handled
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1019): InitialState.processMessage what=4
E/WifiStateMachine( 1019): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1394): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1394): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1394): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1394): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=,
I/wpa_supplicant( 1394): First Scan Start
,I/wpa_supplicant( 1394): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
E/WifiConfigStore( 1019): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Tethering( 1019): No numeric data
,I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1019): interfaceStatusChanged wlan0, false
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1019): clearTetheredNotification()
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
,I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
,D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1176): updateTetherState():false, false
I/jxcore-log( 5654): found test : ./testSendData.js
I/jxcore-log( 5654): 
,E/WifiNative-wlan0( 1019): do suspend true
,V/NetworkStats( 1019): performPollLocked() took 16ms
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/WifiP2pService( 1019): InactiveState{ what=143375 },
D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/CommandListener(  283): Clearing all IP addresses on wlan0
V/NativeCrypto( 1776): Read error: ssl=0xb7d09360: I/O error during system call, Connection timed out
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ConnectivityService( 1019): updateNetworkInfo()
,E/ConnectivityService( 1019): updateNetworkInfo()
,D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
E/WifiStateMachine( 1019): Start Disconnecting Watchdog 1
V/NativeCrypto( 1776): SSL shutdown failed: ssl=0xb7d09360: I/O error during system call, Broken pipe
I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
,I/wpa_supplicant( 1394): wlan0: Setting scan request: 0 sec 0 usec
,D/ConnectivityService( 1019): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Forcing reevaluation
E/WifiNative-wlan0( 1019): do suspend true
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiP2pService( 1019): InactiveState{ what=143375 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/ActivityManager( 1019): Killing 5248:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
I/System.out( 1019): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1019): Tagging socket 331 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1019, getuid(): 1000
,I/jxcore-log( 5654): found test : ./testSendData2.js
I/jxcore-log( 5654): 
,E/jxcore  ( 5654): Error!: unlabeled break must be inside loop or switch
,E/jxcore  ( 5654): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/qtaguid ( 1019): Untagging socket 331
I/System.out( 1019): (HTTPLog)-Static: isSBSettingEnabled false
I/Hs20UtilService( 1677): Starting #8
I/Hs20UtilService( 1677): Message received 5007
I/chromium( 5654): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
I/chromium( 5654): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/EnterpriseController(  283): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  283): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  283): Clearing all IP addresses on wlan0
D/ConnectivityService( 1019): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService( 1019): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Validated
D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524292,
D/ConnectivityService( 1019): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1464): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1019): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1464): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1019): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/WIFI_P2P( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1967): CM callback handler got msg 524292
I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/EntConnectivity( 1019): Not allowed due to - mEnabled false - primarySimSlot false
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/WifiNetworkAgent( 1019): NetworkAgent: NetworkAgent channel lost
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WIFI    ( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
D/Tethering( 1019): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService( 1019): nai.networkMonitor.doQuit()
D/Tethering( 1019): MasterInitialState.processMessage what=3
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): doQuit - quitNow()
D/EntConnectivity( 1019): Not allowed due to - mEnabled false - primarySimSlot false
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): updateIfacesLocked()
D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
V/NetworkStats( 1019): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
D/StatusBar.NetworkController( 1176): EthernetConnected: false
V/NetworkStats( 1019): performPollLocked() took 4ms
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 1677): Starting #9
D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
I/Hs20UtilService( 1677): Message received 5007
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/libprocessgroup( 1019): failed to open /acct/uid_10065/pid_5248/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3,
D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms,
,I/GAV2    ( 5483): Thread[GAThread,5,main]: No campaign data found.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1019): updateDataUsageMap
,D/GpsLocationProvider( 1019): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3192): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/PCWCLIENTTRACE_PushUtil( 5519): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5519): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5519): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5519): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 4352): type=WIFI subType= reason=null isConnected=false
,I/splitIntent( 1019): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
I/splitIntent( 1019): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5519): noConnectivity : true
,I/DBG_DM  ( 3192): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,I/KLMS-2.5.123: ( 3639): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 21 00:51:53 GMT+01:00 2015
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/accuweather( 1735): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/Zygote  ( 5857): MountEmulatedStorage()
I/libpersona( 5857): KNOX_SDCARD checking this for 10141
E/Zygote  ( 5857): v2
I/libpersona( 5857): KNOX_SDCARD not a persona
I/SELinux ( 5857): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=5857 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
I/SELinux ( 5857): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5857): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3639): KLMSAbstractReciever(): onReceive().END.
,D/daemonapp( 1793): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,I/KLMS-2.5.123: ( 3639): KLMSIntentService(): onCreate()
,D/accuweather( 1735): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1735): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1735): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,I/KLMS-2.5.123: ( 3639): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/accuweather( 1735): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3639): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3639): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/TimaKeyStoreProvider( 5857): TimaSignature is unavailable
D/ActivityThread( 5857): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3639): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3639): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,E/Zygote  ( 5873): MountEmulatedStorage()
,E/Zygote  ( 5873): v2
I/libpersona( 5873): KNOX_SDCARD checking this for 10031
I/libpersona( 5873): KNOX_SDCARD not a persona
,I/SELinux ( 5873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/KLMS-2.5.123: ( 3639): StateImplV2(): networkChangeListener().END
,E/SELinux ( 5873): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5873 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3639): KLMSIntentService(): onDestroy()
,D/accuweather( 1735): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1735): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5873): TimaSignature is unavailable,
D/ActivityThread( 5873): Added TimaKeyStore provider,
W/ResourcesManager( 5857): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
W/ResourcesManager( 5857): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,W/ResourcesManager( 5857): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 5888): MountEmulatedStorage()
,E/Zygote  ( 5888): v2
,I/libpersona( 5888): KNOX_SDCARD checking this for 10077,
,I/libpersona( 5888): KNOX_SDCARD not a persona,
I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5888 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5888): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5888): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5888): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5888): TimaSignature is unavailable
,D/ActivityThread( 5888): Added TimaKeyStore provider
,I/SO_AGENT( 5873): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5556): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 4056): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 5590): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5590): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 5590): [OR] == ACTION_CONNECTIVITY_CHANGE ==
D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
I/SA      ( 5590): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5556): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 5556): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5556): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5556): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/SA      ( 5590): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5590): [OR] == isSIMCardReady false ==
,E/SPPClientService( 4056): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 5590): [SCU] == networkStateCheck == false
,I/SA      ( 5590): [OR] onReceive END
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,V/DownloadManager( 1224): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1019): Killing 5279:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1394): nl80211: Received scan results (5 BSSes),
I/wpa_supplicant( 1394): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1394): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1394): Trying to associate with  'G700'
I/wpa_supplicant( 1394): Re-associate with C0.AA.48
I/wpa_supplicant( 1394): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1019): didn't find BSSID Trying to associate with SSID 'NG700'
,E/Zygote  ( 5912): MountEmulatedStorage()
E/Zygote  ( 5912): v2
I/libpersona( 5912): KNOX_SDCARD checking this for 10001
I/libpersona( 5912): KNOX_SDCARD not a persona
I/SELinux ( 5912): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5912): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=5912 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5912): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/art     (  314): Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 24.533ms
,D/TimaKeyStoreProvider( 5912): TimaSignature is unavailable
,D/ActivityThread( 5912): Added TimaKeyStore provider
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 21.094ms,
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 673us total 17.659ms
,E/Zygote  ( 5930): MountEmulatedStorage()
E/Zygote  ( 5930): v2
I/libpersona( 5930): KNOX_SDCARD checking this for 10110
I/libpersona( 5930): KNOX_SDCARD not a persona
,I/SELinux ( 5930): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5930 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 4909:com.google.android.gm/u0a99 (adj 15): empty #31,
,I/SELinux ( 5930): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5930): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/wpa_supplicant( 1394): Cmd 35605 not handled,
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1394): wlan0: State: ASSOCIATING -> ASSOCIATED
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false,
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1394): Associated with C0.AA.48
,I/wpa_supplicant( 1394): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48,
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
,I/wpa_supplicant( 1394): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, true
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
D/Tethering( 1019): interfaceLinkStateChanged wlan0, true
D/Tethering( 1019): interfaceStatusChanged wlan0, true
E/Tethering( 1019): No numeric data
,I/wpa_supplicant( 1394): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1394): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 1394): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/libpersona( 5940): KNOX_SDCARD checking this for 10068
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/libpersona( 5940): KNOX_SDCARD not a persona
I/wpa_supplicant( 1394): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/ActivityManager( 1019): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5940 uid=10068 gids={50068, 9997} abi=armeabi-v7a
I/wpa_supplicant( 1394): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1394): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1394): Blacklist: Clear (temp) 
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1019): interfaceLinkStateChanged wlan0, true
D/Tethering( 1019): interfaceStatusChanged wlan0, true
E/Zygote  ( 5940): MountEmulatedStorage()
E/Zygote  ( 5940): v2
D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
I/SELinux ( 5940): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5940): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5940): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/WifiNative-wlan0( 1019): callSECApiVoid - ID [50]
V/NetworkStats( 1019): performPollLocked(flags=0x1)
D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/Tethering( 1019): clearTetheredNotification()
D/HotspotTile( 1176): updateTetherState():false, false
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): performPollLocked() took 4ms
D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
E/WifiConfigStore( 1019): setLastSelectedConfiguration -1
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/ConnectivityService( 1019): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1019): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1019): updateNetworkInfo()
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
E/WifiConfigStore( 1019): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TimaKeyStoreProvider( 5930): TimaSignature is unavailable
,D/ActivityThread( 5930): Added TimaKeyStore provider
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 5940): TimaSignature is unavailable
D/ActivityThread( 5940): Added TimaKeyStore provider
,D/BadgeProvider( 5940): onCreate
D/BadgeProvider( 5940): DatabaseHelper
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5279/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10099/pid_4909/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 5940): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/Zygote  ( 5964): MountEmulatedStorage()
I/libpersona( 5964): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5964): v2
I/libpersona( 5964): KNOX_SDCARD not a persona
I/SELinux ( 5964): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=5964 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 5964): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Killing 4822:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,E/SELinux ( 5964): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5977): MountEmulatedStorage()
E/Zygote  ( 5977): v2
I/libpersona( 5977): KNOX_SDCARD checking this for 1000
I/libpersona( 5977): KNOX_SDCARD not a persona
,I/SELinux ( 5977): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/BadgeProvider( 5940): sendNotify entered. [uri] : content://com.sec.badge/apps/1,
D/BadgeProvider( 5940): sendNotify, [notify] : null
D/BadgeProvider( 5940): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5940): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5940): update, [UpdateCount] : 1
D/Launcher.Model( 1480): reloadBadges entered.
I/ActivityManager( 1019): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5977 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 5123:com.android.calendar/u0a131 (adj 15): empty #31
I/ActivityManager( 1019): Killing 4694:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #32
I/SELinux ( 5977): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5977): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/WifiConfigStore( 1019): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TimaKeyStoreProvider( 5964): TimaSignature is unavailable
,D/ActivityThread( 5964): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 5977): TimaSignature is unavailable
,D/ActivityThread( 5977): Added TimaKeyStore provider
,W/libprocessgroup( 1019): failed to open /acct/uid_10035/pid_4822/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10130/pid_4694/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10131/pid_5123/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 5964): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/CommandListener(  283): Setting iface cfg
,E/WifiStateMachine( 1019): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecurityLogAgent( 5977): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5977): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5977): StateMachine : Current State = 1
D/SecContentProvider2( 1019): mCursor = null
,D/SecurityLogAgent( 5977): StateMachine : Changed Current State = 1
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
,I/iu.Environment( 1967): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1967): num queued entries: 0
,I/iu.UploadsManager( 1967): num updated entries: 0
E/WifiNative-wlan0( 1019): do suspend false
I/iu.SyncManager( 1967): NEXT; no task
,D/WifiP2pService( 1019): InactiveState{ what=143375 }
D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 5412:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,I/DIAGMON_AGENT( 5964): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5964): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5964): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 5964): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 5964): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 5964): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=5998 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 4838:com.sec.android.gallery3d/u0a39 (adj 15): empty #31,
E/Zygote  ( 5998): MountEmulatedStorage()
E/Zygote  ( 5998): v2
I/libpersona( 5998): KNOX_SDCARD checking this for 10008
I/libpersona( 5998): KNOX_SDCARD not a persona
,I/SELinux ( 5998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5998): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5998): TimaSignature is unavailable
,D/ActivityThread( 5998): Added TimaKeyStore provider
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5930): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5930): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup( 1019): failed to open /acct/uid_10139/pid_5412/cgroup.procs: No such file or directory
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5930): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/libprocessgroup( 1019): failed to open /acct/uid_10039/pid_4838/cgroup.procs: No such file or directory
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5930): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager( 1019): Killing 4626:com.android.mms/u0a41 (adj 15): empty #31
,E/dhcpcd  ( 6020): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6020): version 5.5.6 starting
,E/dhcpcd  ( 6020): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/CountryDetector( 1019): No listener is left
,I/dhcpcd  ( 6020): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6020): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6020): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6020): bssid match
,I/dhcpcd  ( 6020): wlan0: rebinding lease of 192.168.1.133
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1019): failed to open /acct/uid_10041/pid_4626/cgroup.procs: No such file or directory
,I/WebViewFactory( 5930): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/LibraryLoader( 5930): Loading: webviewchromium
,I/LibraryLoader( 5930): Time to load native libraries: 4 ms (timestamps 7220-7224)
I/LibraryLoader( 5930): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5930): Binding Chromium to main looper Looper (main, tid 1) {ab2a334}
,I/LibraryLoader( 5930): Expected native library version number "",actual native library version number ""
,I/chromium( 5930): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5930): Initializing chromium process, renderers=0
,W/art     ( 5930): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 5930): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 5930): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 5930): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 5930): Requires BLUETOOTH permission
,I/Adreno-EGL( 5930): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5930): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5930): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5930): Local Branch: 
I/Adreno-EGL( 5930): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5930): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5930):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/NSApplication( 5930): Starting up...
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6058): MountEmulatedStorage(),
E/Zygote  ( 6058): v2
I/libpersona( 6058): KNOX_SDCARD checking this for 10121
,I/libpersona( 6058): KNOX_SDCARD not a persona
,I/SELinux ( 6058): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6058): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1019): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6058 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 6058): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Killing 5453:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6058): TimaSignature is unavailable
,D/ActivityThread( 6058): Added TimaKeyStore provider
,W/ResourcesManager( 6058): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6058): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6058): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6058): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect( 6058): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6058): PeriphStartReceiver.onReceive - no need to start
,I/splitIntent( 1019): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1019): Killing 5503:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1677): Starting #10
,I/Hs20UtilService( 1677): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
,W/libprocessgroup( 1019): failed to open /acct/uid_10014/pid_5453/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10042/pid_5503/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6020): wlan0: acknowledged 192.168.1.133 from 192.168.1.1
,I/dhcpcd  ( 6020): wlan0: leased 192.168.1.133 for 86400 seconds
,E/SMD     (  298): DCD OFF,
,E/WifiNative-wlan0( 1019): do suspend true,
,D/WifiP2pService( 1019): InactiveState{ what=143375 },
E/WifiStateMachine( 1019): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
E/WifiStateMachine( 1019): VerifyingLinkState enter
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiNative-wlan0( 1019): callSECApiInt - ID [210]
,E/ConnectivityService( 1019): updateNetworkInfo()
D/ConnectivityService( 1019): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1019): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1019): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 1677): Starting #11
I/Hs20UtilService( 1677): Message received 5007
D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 1019): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/ConnectivityService( 1019): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1019): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1019): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1019): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1019): LTETest block dns file not exists
,D/ConnectivityService( 1019): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1019): updateNetworkInfo()
,E/ConnectivityService( 1019): updateNetworkInfo()
D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1019): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1019): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1019): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  283): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  283): getNetworkForDns: using netid 503 for uid 1000
,I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
,D/ConnectivityService( 1019):    accepting network in place of null
,D/TelephonyNetworkFactory( 1464): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/TelephonyNetworkFactory( 1464): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1019): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/WIFI_P2P( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1019): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true,
D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1019): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1019): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,D/EntConnectivity( 1019): Not allowed due to - mEnabled false - primarySimSlot false
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/WIFI    ( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
I/Hs20UtilService( 1677): Starting #12
D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290,
I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
,D/ConnectivityManager.CallbackHandler( 1967): CM callback handler got msg 524290
I/WifiTrafficPoller( 1019): mBoosterFLAG : 0
I/WifiTrafficPoller( 1019): current booster mode : FullMode,
D/WifiNative-wlan0( 1019): callSECApiVoid - ID [212]
,I/Hs20UtilService( 1677): Message received 5007
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NetworkStats( 1019): updateIfacesLocked()
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): performPollLocked(flags=0x1)
,D/Tethering( 1019): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NetworkStats( 1019): performPollLocked() took 3ms
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
,D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1677): Starting #13
,I/Hs20UtilService( 1677): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1019): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1019): mCursor = null
,I/System.out( 1019): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SecContentProvider2( 1019): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1019): mCursor = null
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 20 Dec 2015 23:51:56 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450655516217], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450655516192]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Validated
,D/ConnectivityService( 1019): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1019): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1019): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1019): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290
,D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1967): CM callback handler got msg 524290
,D/PowerManagerService( 1019): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,D/SRIB_DCS( 1176): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
,D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/PowerManagerService( 1019): [PWL] Off : 15s ago
,I/PowerManagerService( 1019): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1019): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1019): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1019, ws=null) (elapsedTime=3215)
,D/PackageManager( 1019): [MSG] MCS_UNBIND
,I/ActivityManager( 1019): Killing 5226:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3192): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 4352): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5519): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5519): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5519): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5519): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1019): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
I/splitIntent( 1019): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,I/KLMS-2.5.123: ( 3639): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 21 00:51:56 GMT+01:00 2015
,D/accuweather( 1735): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3639): KLMSAbstractReciever(): onReceive().END.
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
,I/KLMS-2.5.123: ( 3639): KLMSIntentService(): onCreate()
,D/daemonapp( 1793): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,I/KLMS-2.5.123: ( 3639): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/SecurityLogAgent( 5977): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5977): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5977): StateMachine : Current State = 1
,D/SecurityLogAgent( 5977): StateMachine : Changed Current State = 1
D/accuweather( 1735): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1735): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1735): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1735): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3639): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3639): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3639): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/DIAGMON_AGENT( 5964): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 5964): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 5964): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 5964): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/KLMS-2.5.123: ( 3639): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,D/GpsLocationProvider( 1019): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1019): failed to open /acct/uid_10029/pid_5226/cgroup.procs: No such file or directory
,I/KLMS-2.5.123: ( 3639): StateImplV2(): networkChangeListener().START
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3639): NetworkChangeOperations(): uploadRequestLog().START 
,D/accuweather( 1735): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1735): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KLMS-2.5.123: ( 3639): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3639): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3639): KLMSIntentService(): onDestroy()
,I/iu.Environment( 1967): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1967): num queued entries: 0
,I/iu.UploadsManager( 1967): num updated entries: 0
,I/iu.SyncManager( 1967): NEXT; no task
,I/DBG_POLICYDM( 5556): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,D/QuickConnect( 6058): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5556): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5556): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5556): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/QuickConnect( 6058): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6058): PeriphStartReceiver.onReceive - no need to start
,D/EnterpriseController(  283): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  283): getNetworkForDns: using netid 503 for uid 10011
,E/SPPClientService( 4056): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/DBG_POLICYDM( 5556): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 5556): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5556): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5590): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5590): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 5590): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/DBG_POLICYDM( 5556): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5556): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5556): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5590): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/DBG_POLICYDM( 5556): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/SA      ( 5590): [OR] == isSIMCardReady false ==
,I/SA      ( 5590): [SCU] == networkStateCheck == true
,I/SA      ( 5590): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5590): isChinaCountryCode : false
I/SA      ( 5590): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5590): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 5556): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
D/WaitQueueForNetworkActivate( 5634): notifyNetworkActivated
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5556): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/DBG_POLICYDM( 5556): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,I/FOTA_Client( 5998): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 5998): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 5998): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 5998): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/DBG_POLICYDM( 5556): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5556): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,I/SA      ( 5590): [OR] GetMyCountryZoneTask
I/SA      ( 5590): [OR] onReceive END
,V/DownloadManager( 1224): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 5590): [SRS] prepareGetMyCountryZone
,D/SecContentProvider2( 1019): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1019): mCursor = null
,I/SA      ( 5590): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5590): [SSP] query invoked
,W/ContextImpl( 5634): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1019): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/SA      ( 5590): [TPMU] GetMccFromDB : null
,I/SA      ( 5590): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5590): [TPM] isNoProxy(default) : true
,E/File    ( 5590): fail readDirectory() errno=2
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/ConnectivityService( 1019): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/splitIntent( 1019): Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/hcjo    ( 5634): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5634): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5634): exit::IDLE
D/InitializeManagerStateMachine( 5634): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5634): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5634): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5634): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5634): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5634): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5634): entry::SUCCESS
D/hcjo    ( 5634): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5634): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5634): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5634): exit::SUCCESS
D/InitializeManagerStateMachine( 5634): entry::IDLE
,D/ConnectivityService( 1019): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1019): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524295
,D/ConnectivityService( 1019): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1967): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1967): CM callback handler got msg 524295
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SA      ( 5590): [RC New] Execute method=[GET] start
,I/SA      ( 5590): [RC New] Security=[true]
,I/System.out( 5590): Thread-940(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5590): Thread-940(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5590): Thread-940(ApacheHTTPLog):isShipBuild true
I/System.out( 5590): Thread-940(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5590): Thread-940(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  283): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  283): getNetworkForDns: using netid 503 for uid 10036
,I/SA      ( 5590): [RC New] [v2liruge] api execute + 645
,I/SA      ( 5590): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5590): AsyncTask #1 calls detatch()
,I/SA      ( 5590): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5590): [OCP] update openData : PL
,I/SA      ( 5590): [TPMU] getNetworkMcc : 
,I/SA      ( 5590): [SCU] saveMccToPreferece Start
,I/SA      ( 5590): [SCU] RegionMCC : 260
,I/SA      ( 5590): [SSP] query invoked
,I/SA      ( 5590): [TPMU] GetMccFromDB : null
,I/SA      ( 5590): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5590): [SCU] saveMccToPreferece End
,I/SA      ( 5590): [RC New] executeRequest [v2liruge] end. 702
I/SA      ( 5590): [RC New] Execute end
,I/SA      ( 5590): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5590): [OR] GetMyCountryZoneTask Success
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5654): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 5654): BLE supported!!
I/jxcore-log( 5654): 
,E/SMD     (  298): DCD OFF
,I/dhcpcd  ( 6020): wlan0: sending IPv6 Router Solicitation
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1019): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1019) eventTime = 91989
,D/PowerManagerService( 1019): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019 (0x0)
,D/PowerManagerService( 1019): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1019, ws=WorkSource{10049}) (elapsedTime=3477)
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 71790(3MB) AllocSpace objects, 7(160KB) LOS objects, 33% free, 22MB/34MB, paused 2.606ms total 176.021ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/GAV4    ( 5930): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1019): waitForAlarm result :8
,D/SSRM:n  ( 1019): SIOP:: AP = 350
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5519): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5519): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5519): [GetString-S]
,I/ReactiveServiceManager( 5519): Supported : 1
,D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 10
,D/QSEECOMAPI: ( 1019): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1019): QSEECom_shutdown_app, app_id = 10
E/terrier ( 1019): handleString: Failed to handle string(-4)
E/terrier ( 1019): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5519): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5519): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5519): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5519): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5519): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5519): [ensureRegistration] - No Samsung account
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{24838afc u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,E/SMD     (  298): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  ( 6020): wlan0: sending IPv6 Router Solicitation
,V/AlarmManager( 1019): waitForAlarm result :4
,V/AlarmManager( 1019): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManagerEXT( 1019): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1019): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/Finsky  ( 5264): [895] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5264): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,I/dhcpcd  ( 6020): wlan0: sending IPv6 Router Solicitation,
I/dhcpcd  ( 6020): wlan0: no IPv6 Routers available
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5634): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5634): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5634): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5634): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5634): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5634): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5634): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5634): entry::IDLE
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :4
,I/PowerManagerService( 1019): [PWL] Off : 30s ago
I/PowerManagerService( 1019): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1019): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1019): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1019, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=3)
,D/SSRM:n  ( 1019): SIOP:: AP = 320
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{127ed6d1 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1776): Vacuum at: now=1450655535119 tag=VacuumService
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Watchdog( 1019): !@Sync 3
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1776): Scheduling Phenotype for one-off execution 7928 seconds from now (1450655535423)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1776): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1776): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1776): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1019): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1776): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1776): (HTTPLog)-Static: isShipBuild true
I/System.out( 1776): (HTTPLog)-Thread-263-872508385: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  283): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  283): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1776): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10011
,I/qtaguid ( 1776): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10011
,D/LocationManagerService( 1019): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10011
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/FactoryTest( 5179): Not factory mode
,D/FactoryTest( 5179): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5179): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5179): still no open session command from host, so toast
,W/ContextImpl( 5179): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5179): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5179): Timeline: Activity_launch_request id:com.android.settings time:108329
,E/PersonaManagerService( 1019): inState():  stateMachine is null !!
,I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1019): mDVFSHelper.acquire()
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 5654
,E/MTPRx   ( 5179): started activity for popup
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/LocationManagerService( 1019): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10011
,W/ResourcesManager( 5179): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5179): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5179): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5179): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5179): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5179): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5179): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus entered window: 5654
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1019): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@175b78b3 attribute=null, token = android.os.BinderProxy@3f38abcb
,D/SettingsReceiverActivity( 5179): dev.kiessupport is : TRUE
,D/PhoneWindow( 5179): *FMB* installDecor mIsFloating : true
,D/PhoneWindow( 5179): *FMB* installDecor flags : 8388610
,D/LocationManagerService( 1019): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10011
,V/ActivityThread( 5654): updateVisibility : ActivityRecord{14500337 token=android.os.BinderProxy@351755d1 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 5654): Timeline: Activity_idle id: android.os.BinderProxy@351755d1 time:108537
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,D/LocationManagerService( 1019): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10011
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  298): DCD OFF
,W/ActivityManager( 1019): mDVFSHelper.release()
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 310
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1019): [PWL] Off : 50s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 300
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 300
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 4
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  298): DCD OFF
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 75s ago
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,V/AlarmManager( 1019): waitForAlarm result :8
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/SMD     (  298): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ClearcutLoggerApiImpl( 1776): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 5
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 105s ago
,E/SMD     (  298): DCD OFF,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1019): !@Sync 6
,E/SMD     (  298): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate,
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,V/AlarmManager( 1019): waitForAlarm result :8
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService( 1019): [PWL] Off : 140s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/SMD     (  298): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/Watchdog( 1019): !@Sync 7
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  298): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 180s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 8
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 280
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  298): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,E/SMD     (  298): DCD OFF,
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 9
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  298): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 225s ago
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1019): initializing...
,I/TLC_TIMA_PKM_initialize( 1019): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1019): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1019): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1019): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1019): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1019): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1019): Trustlet response is completed
,E/SMD     (  298): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 10
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 11
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1019): [PWL] Off : 275s ago
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 12
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,V/AlarmManager( 1019): waitForAlarm result :8,
V/AlarmManager( 1019): No more alarm at this time.nowELAPSED=392286 batch.start=799359
,E/SMD     (  298): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 270,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 330s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  298): DCD OFF,
,E/Watchdog( 1019): !@Sync 13,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  298): DCD OFF,
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  298): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  298): DCD OFF,
,E/Watchdog( 1019): !@Sync 14,
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  298): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  298): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 390s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 15
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF,
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/bootchecker(  330): bootchecker wake up!!,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/Watchdog( 1019): !@Sync 16
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 17
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1019): [PWL] Off : 455s ago
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,E/SMD     (  298): DCD OFF,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD OFF,
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 18
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,I/Atfwd_Daemon(  335): Stop the daemon....,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 19,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 525s ago
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 20,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged
E/SMD     (  298): DCD OFF
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/Watchdog( 1019): !@Sync 21,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 600s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/Watchdog( 1019): !@Sync 22
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 23,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 24,
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,I/PowerManagerService( 1019): [PWL] Off : 680s ago
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged,
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 25,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 26
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***,
,I/GoogleURLConnFactory( 1776): Using platform SSLCertificateSocketFactory,
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  283): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  283): getNetworkForDns: using netid 503 for uid 10011
,E/SMD     (  298): DCD OFF,
,I/System.out( 1776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1776): Tagging socket 77 with tag 40100000000{1025,0} for uid -1, pid: 1776, getuid(): 10011
,I/qtaguid ( 1776): Tagging socket 81 with tag 40100000000{1025,0} for uid -1, pid: 1776, getuid(): 10011
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,V/AlarmManager( 1019): waitForAlarm result :8,
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 27
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 765s ago
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 28
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 29
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 30,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 856s ago,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 31,
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 32
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged,
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 33,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1019): [PWL] Off : 951s ago,
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1019): stay LED for fully charged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 34,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 35,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 36
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 1051s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 37,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 38,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 39,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1019): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1019): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1019): Updating Usage Statistics in DB @ 1450656642960
,I/ApplicationPolicy( 1019): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1019): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1019): ::isTableExists: Table exists 
,I/ApplicationUsage( 1019): Done Updating Usage Statistics in DB @ 1450656643273
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 40,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 1156s ago
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 41,
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 42,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/Watchdog( 1019): !@Sync 43,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 44,
,I/PowerManagerService( 1019): [PWL] Off : 1266s ago,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 45,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 270,
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 46,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 47
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 1381s ago,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/Watchdog( 1019): !@Sync 48
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 49
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/Watchdog( 1019): !@Sync 50
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 51
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 1501s ago
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 52
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 53,
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 54,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 55,
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,I/art     ( 1019): Background partial concurrent mark sweep GC freed 46218(6MB) AllocSpace objects, 332(5MB) LOS objects, 33% free, 23MB/34MB, paused 2.407ms total 162.477ms,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 56
,I/PowerManagerService( 1019): [PWL] Off : 1626s ago
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 57
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  298): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 58,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 59
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 60,
D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 1756s ago
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,I/ActivityManager( 1019): Killing 5483:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
I/ActivityManager( 1019): Killing 4943:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #32
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
I/ActivityManager( 1019): Killing 3254:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): SPC_empty #33
,I/ActivityManager( 1019): Killing 5541:com.sec.android.app.soundalive/u0a48 (adj 15): empty #34
,I/ActivityManager( 1019): Killing 3192:com.wssyncmldm/1000 (adj 15): SPC_empty #35
I/ActivityManager( 1019): Killing 3975:com.sec.android.pagebuddynotisvc/u0a113 (adj 15): SPC_empty #36
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager( 1019): Killing 2651:com.sec.phone/1001 (adj 15): SPC_empty #37
,I/ActivityManager( 1019): Killing 3760:com.sec.bcservice/1000 (adj 15): SPC_empty #38
I/ActivityManager( 1019): Killing 3091:com.google.android.youtube/u0a161 (adj 15): SPC_empty #39
,I/ActivityManager( 1019): Killing 2986:com.samsung.android.providers.context/u0a2 (adj 15): SPC_empty #40
,I/ProcessStatsService( 1019): Prepared write state in 14ms
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): performPollLocked(flags=0x3)
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
,V/NetworkStats( 1019): performPollLocked() took 13ms
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,W/ActivityManager( 1019): Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 1000ms
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1019): Scheduling restart of crashed service com.sec.phone/.SecPhoneService in 10981ms
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1019): Scheduling restart of crashed service com.sec.bcservice/.BroadcastService in 10972ms
,W/ActivityManager( 1019): Scheduling restart of crashed service com.wssyncmldm/.XDMService in 20968ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GpsStatusListenerHelper( 1019): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@2541032a
,W/ActivityManager( 1019): Scheduling restart of crashed service com.samsung.android.providers.context/.ContextService in 3614376ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20947ms
,W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService in 20944ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1967): Aggregate from 1450654979005 (log), 1450654979005 (data)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  283): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  283): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1776): Tagging socket 74 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1776, getuid(): 10011
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2015-12-20-03-39-53.bin
W/libprocessgroup( 1019): failed to open /acct/uid_10048/pid_5541/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10113/pid_3975/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10087/pid_5483/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1001/pid_2651/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3760/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4943/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3192/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10002/pid_2986/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10052/pid_3254/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10161/pid_3091/cgroup.procs: No such file or directory
,I/qtaguid ( 1776): Tagging socket 77 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1776, getuid(): 10011
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 6872): MountEmulatedStorage(),
E/Zygote  ( 6872): v2
I/libpersona( 6872): KNOX_SDCARD checking this for 10113
I/libpersona( 6872): KNOX_SDCARD not a persona
,I/SELinux ( 6872): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6872): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1019): Start proc com.sec.android.pagebuddynotisvc for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc: pid=6872 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,E/SELinux ( 6872): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6872): TimaSignature is unavailable
,D/ActivityThread( 6872): Added TimaKeyStore provider
,I/PageBuddyNotiSvc( 6872): onCreate mCpBitFlag=0
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 61
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6892): MountEmulatedStorage(),
,E/Zygote  ( 6892): v2,
I/libpersona( 6892): KNOX_SDCARD checking this for 1000
I/libpersona( 6892): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.sec.bcservice for service com.sec.bcservice/.BroadcastService: pid=6892 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6892): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6892): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6892): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6892): TimaSignature is unavailable
,D/ActivityThread( 6892): Added TimaKeyStore provider
,W/ResourcesManager( 6892): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/F_PHONE ( 6892): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 6892): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6907): MountEmulatedStorage(),
,E/Zygote  ( 6907): v2
I/libpersona( 6907): KNOX_SDCARD checking this for 1001
I/libpersona( 6907): KNOX_SDCARD not a persona
,I/SELinux ( 6907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.phone for service com.sec.phone/.SecPhoneService: pid=6907 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,I/SELinux ( 6907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6907): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6907): TimaSignature is unavailable
D/ActivityThread( 6907): Added TimaKeyStore provider
,W/ResourcesManager( 6907): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/F_PHONE ( 6892): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 6892): default registerAction()
I/F_PHONE ( 6892): [[com.sec.bcservice]] sendPendingMessage()
,E/SMD     (  298): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  298): DCD OFF,
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6928): MountEmulatedStorage(),
E/Zygote  ( 6928): v2
I/libpersona( 6928): KNOX_SDCARD checking this for 10161
I/libpersona( 6928): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService: pid=6928 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6928): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6928): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6928): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6928): TimaSignature is unavailable
,D/ActivityThread( 6928): Added TimaKeyStore provider
,W/ResourcesManager( 6928): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6928): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6928): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6928): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/ActivityThread( 6928): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6928): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3043c711: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6928): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/YouTube MDX( 6928): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1019): getStreamVolume 3 index 70
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6928): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6928): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6928): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/ActivityManager( 1019): Killing 5709:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #31
,D/AndroidHttpClient( 6928): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,D/AndroidHttpClient( 6928): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 6928): Thread-1100(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6928): Thread-1100(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6928): Thread-1100(ApacheHTTPLog):isShipBuild true
I/System.out( 6928): Thread-1100(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6928): Thread-1100(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  283): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  283): getNetworkForDns: using netid 503 for uid 10161
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5709/cgroup.procs: No such file or directory
,I/System.out( 6928): Thread-1100 calls detatch()
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  298): DCD OFF
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 62
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,E/SMD     (  298): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2613): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2613): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 270,
,E/SMD     (  298): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,I/ActivityManager( 1019): Killing 5930:com.google.android.apps.magazines/u0a110 (adj 15): empty for 1800s
,I/ActivityManager( 1019): Killing 5888:com.android.chrome/u0a77 (adj 15): empty for 1800s
,I/ActivityManager( 1019): Killing 5873:com.sec.android.soagent/u0a31 (adj 15): empty for 1800s
,I/ActivityManager( 1019): Killing 5964:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
,I/ActivityManager( 1019): Killing 5977:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1800s
,I/ActivityManager( 1019): Killing 5912:com.sec.android.cloudagent/u0a1 (adj 15): empty for 1800s
I/ActivityManager( 1019): Killing 5857:com.android.email/u0a141 (adj 15): empty for 1800s
I/ActivityManager( 1019): Killing 4352:com.google.android.music:main/u0a108 (adj 15): empty for 1800s
,I/ActivityManager( 1019): Killing 5519:com.sec.pcw.device/1000 (adj 15): empty for 1800s
I/ActivityManager( 1019): Killing 5390:com.android.defcontainer/u0a3 (adj 15): empty for 1800s
,I/ActivityManager( 1019): Killing 5940:com.sec.android.provider.badge/u0a68 (adj 15): empty for 1802s
I/ActivityManager( 1019): Killing 5467:com.google.android.gms:car/u0a11 (adj 15): empty for 1807s
,I/ActivityManager( 1019): Killing 5803:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty for 1807s
I/ActivityManager( 1019): Killing 5787:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty for 1807s
,I/ActivityManager( 1019): Killing 5750:com.samsung.helphub/1000 (adj 15): empty for 1808s
I/ActivityManager( 1019): Killing 5735:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty for 1808s
,W/libprocessgroup( 1019): failed to open /acct/uid_10031/pid_5873/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10141/pid_5857/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5977/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10001/pid_5912/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10003/pid_5390/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10110/pid_5930/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10152/pid_5803/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10108/pid_4352/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10148/pid_5787/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5519/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10098/pid_5735/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5964/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10068/pid_5940/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10011/pid_5467/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10077/pid_5888/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5750/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  298): DCD OFF
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
V/AlarmManager( 1019): waitForAlarm result :8
D/AndroidRuntime( 7018): 
D/AndroidRuntime( 7018): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7018): CheckJNI is OFF
D/AndroidRuntime( 7018): readGMSProperty: start
D/AndroidRuntime( 7018): readGMSProperty: already setted!!
D/AndroidRuntime( 7018): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7018): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7018): readGMSProperty: end
D/AndroidRuntime( 7018): addProductProperty: start
E/AffinityControl( 7018): AffinityControl: registerfunction enter
D/AndroidRuntime( 7018): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1019): START PACKAGE DELETE: observer{551402166}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1019): !@killApplicatoin: 10326, uninstall pkg
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10326 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 5654:com.test.thalitest/u0a326 (adj 0): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1019): Skipping PackageSetting{1136d8fa com.example.hello/10334} due to missing metadata
I/ActivityManager( 1019):   Force finishing activity ActivityRecord{361f6d48 u0 com.test.thalitest/.MainActivity t2}
E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
D/InputDispatcher( 1019): Focus left window: 5654
I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
D/InputDispatcher( 1019): Focused application released
E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/FocusedStackFrame( 1019): Set to : 0
W/ActivityManager( 1019): mDVFSHelper.acquire()
V/WindowManager( 1019): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10326 user=0: pkg removed
W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
D/Launcher( 1480): onRestart, Launcher: 851849696
I/art     ( 3856): Explicit concurrent mark sweep GC freed 3165(189KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 762us total 28.798ms
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1837): mOCRHelper is null
W/GeofencerStateMachine( 1776): Ignoring removeGeofence because network location is disabled.
D/Launcher( 1480): onStart, Launcher: 851849696
D/Launcher.HomeView( 1480): onStart
D/Launcher( 1480): onResume, Launcher: 851849696
D/SettingsProvider( 1019): name = kids_home_mode
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10006
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/Launcher.HomeView( 1480): onResume
I/art     ( 1967): Explicit concurrent mark sweep GC freed 7044(423KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 11MB/14MB, paused 1.509ms total 88.786ms
D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/MenuAppsGridFragment( 1480): onResume
D/WallpaperManager( 1480): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/WallpaperManager( 1480): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
I/KLMS-2.5.123: ( 3639): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 21 01:22:02 GMT+01:00 2015
W/SQLiteConnectionPool( 1967): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/ActivityManager( 1019): handle home activity for 0
I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1019): post home show event for user 0
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/Launcher.HomeView( 1480): onPause
D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/UsageStatsService( 1019): User[0] Rolling over usage stats
I/UsageStatsService( 1019): User[0] Flushing usage stats to disk
I/KLMS-2.5.123: ( 3639): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1019): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=30, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 1 receivers.size=39
I/splitIntent( 1019): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/SurfaceFlinger(  258): id=15 createSurf (540x960),1 flag=4, Mauncher
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/KLMS-2.5.123: ( 3639): KLMSIntentService(): onCreate()
E/Zygote  ( 7032): MountEmulatedStorage()
E/Zygote  ( 7032): v2
I/libpersona( 7032): KNOX_SDCARD checking this for 10090
I/libpersona( 7032): KNOX_SDCARD not a persona
I/SELinux ( 7032): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7032): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7032 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 7032): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  314): Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 22.121ms
D/TimaKeyStoreProvider( 7032): TimaSignature is unavailable
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ActivityThread( 7032): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3639): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.510ms
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/SMD     (  298): DCD OFF
D/InputDispatcher( 1019): Focus entered window: 1480
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 16.352ms
I/KLMS-2.5.123: ( 3639): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/SRIB_DCS( 1480): log_dcs ThreadedRenderer::initialize entered! 
I/art     ( 1019): Explicit concurrent mark sweep GC freed 38568(3MB) AllocSpace objects, 91(1645KB) LOS objects, 33% free, 23MB/34MB, paused 3.596ms total 214.262ms
I/art     ( 1019): WaitForGcToComplete blocked for 194.458ms for cause Explicit
D/Launcher.HomeView( 1480): onStop
V/ActivityThread( 1480): updateVisibility : ActivityRecord{3d72041f token=android.os.BinderProxy@283acb38 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
E/Zygote  ( 7048): MountEmulatedStorage()
E/Zygote  ( 7048): v2
I/libpersona( 7048): KNOX_SDCARD checking this for 10041
I/libpersona( 7048): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7048 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3639): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/SELinux ( 7048): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/UsageStatsService( 1019): User[0] Rollover scheduled @ 2015-12-22 01:00:00(1450742400000)
I/UsageStatsService( 1019): User[0] Flushing usage stats to disk
I/SELinux ( 7048): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7048): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/KLMS-2.5.123: ( 3639): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3639): KLMSIntentService(): listeningToPackageRemoved().START
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/InputMethodManagerService( 1019): Got RemoteException sending setActive(false) notification to pid 5654 uid 10326
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/KLMS-2.5.123: ( 3639): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
D/TimaKeyStoreProvider( 7048): TimaSignature is unavailable
E/Zygote  ( 7059): MountEmulatedStorage()
I/libpersona( 7059): KNOX_SDCARD checking this for 10087
E/Zygote  ( 7059): v2
I/libpersona( 7059): KNOX_SDCARD not a persona
D/ActivityThread( 7048): Added TimaKeyStore provider
I/SELinux ( 7059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/SamsungIME( 1837): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
I/SELinux ( 7059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7059): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/RCPManagerService( 1019): PackageReceiver onReceive()
I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7059 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7078 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7078): MountEmulatedStorage()
E/Zygote  ( 7078): v2
I/libpersona( 7078): KNOX_SDCARD checking this for 10145
I/libpersona( 7078): KNOX_SDCARD not a persona
I/SELinux ( 7078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/RegisteredServicesCache( 1442): empty dynamic service
D/TimaKeyStoreProvider( 7059): TimaSignature is unavailable
D/ActivityThread( 7059): Added TimaKeyStore provider
E/SELinux ( 7078): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/UsageStatsService( 1019): User[0] Rolling over usage stats complete. Took 244 milliseconds
W/ActivityManager( 1019): mDVFSHelper.release()
I/KLMS-2.5.123: ( 3639): KLMSIntentService(): listeningToPackageRemoved().END
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{43a44c1 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1895192
W/ResourcesManager( 7048): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7048): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7048): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7048): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7048): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/elm:15121( 7032): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 7032): ELMEngine.ELMEngine( context ).
D/elm:15121( 7032): MDMBridge.setEnterpriseBridge()
I/KLMS-2.5.123: ( 3639): KLMSIntentService(): onDestroy()
D/TimaKeyStoreProvider( 7078): TimaSignature is unavailable
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/ActivityThread( 7078): Added TimaKeyStore provider
D/elm:15121( 7032): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 7032): ElmAgentService : onCreate()
D/elm:15121( 7032): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 7032): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 7032): MDMBridge.getInstance()
D/elm:15121( 7032): MDMBridge.getAllLicenseInfoFromSDK()
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10326
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
D/Mms/MmsApp( 7048): [start]    onCreate() consume time = 0.0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
D/elm:15121( 7032): MDMBridge.getAllLicenseInfoFromSDK()
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TaskPersister( 1019): removeObsoleteFile: deleting file=2_task.xml
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10326
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/ThemeInfoUtil( 7078): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 7078): isCurrentFestival = false
I/art     ( 1019): Explicit concurrent mark sweep GC freed 10815(624KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/34MB, paused 6.305ms total 301.433ms
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7097): MountEmulatedStorage()
E/Zygote  ( 7097): v2
I/libpersona( 7097): KNOX_SDCARD checking this for 10148
I/libpersona( 7097): KNOX_SDCARD not a persona
I/SELinux ( 7097): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7097): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7097): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7097 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 4512:com.google.android.apps.plus/u0a117 (adj 15): empty for 1806s
D/elm:15121( 7032): ElmAgentService : onDestroy().
D/TimaKeyStoreProvider( 7097): TimaSignature is unavailable
D/ActivityThread( 7097): Added TimaKeyStore provider
I/ActivityManager( 1019): Killing 6058:com.samsung.android.sconnect/u0a121 (adj 15): empty for 1806s
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/DocsApplication( 7059): Installing DEX configuration.
E/Zygote  ( 7112): MountEmulatedStorage()
E/Zygote  ( 7112): v2
I/libpersona( 7112): KNOX_SDCARD checking this for 1000
I/libpersona( 7112): KNOX_SDCARD not a persona
I/SELinux ( 7112): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7112 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7112): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7112): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/DexInstaller( 7059): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7059): Provided clientMode=RELEASE, packageInfo=PackageInfo{a448ce5 com.google.android.apps.docs}
D/TAG     ( 7059): onCreate()
E/SQLiteLog( 7097): (284) automatic index on shooting_modes(title_id)
D/CrossAppStateProvider( 7059): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1019): no available spell checker services found
D/TimaKeyStoreProvider( 7112): TimaSignature is unavailable
D/ActivityThread( 7112): Added TimaKeyStore provider
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 1019): delete codoeFile: 
E/Zygote  ( 7128): MountEmulatedStorage()
I/libpersona( 7128): KNOX_SDCARD checking this for 10152
E/Zygote  ( 7128): v2
I/libpersona( 7128): KNOX_SDCARD not a persona
I/AASA_removePackage( 1019): UID=10326 Target=com.test.thalitest
D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10326, packageName = com.test.thalitest
I/SELinux ( 7128): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PackageManager( 1019): result of delete: 1{551402166}
I/SELinux ( 7128): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7128): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7128 uid=10152 gids={50152, 9997} abi=armeabi-v7a
D/PersonaManager( 1019): isKioskContainerExistOnDevice
W/art     ( 7048): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 160.689ms
D/AndroidRuntime( 7018): Shutting down VM
I/ActivityManager( 1019): Killing 5556:com.policydm/1000 (adj 15): empty for 1806s
D/TimaKeyStoreProvider( 7128): TimaSignature is unavailable
D/ActivityThread( 7128): Added TimaKeyStore provider
I/PCWCLIENTTRACE_LOG( 7112): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7112): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7112): new DMDBOpenHelper instance
I/TapandpayWidget:TapandpayAppWidgetProvider( 7128): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 7128): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/PCWCLIENTTRACE_PushUtil( 7112): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7112): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7112): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7112): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/TapandpayWidget:Utils( 7128): Clear T&P info.
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/TapandpayWidget:TapandpayAppWidgetProvider( 7128): Widget is not attached.
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1019): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7144 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 5590:com.osp.app.signin/u0a36 (adj 15): empty for 1806s
E/Zygote  ( 7144): MountEmulatedStorage()
E/Zygote  ( 7144): v2
I/libpersona( 7144): KNOX_SDCARD checking this for 10029
I/libpersona( 7144): KNOX_SDCARD not a persona
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1019): Killing 5998:com.sec.android.fotaclient/u0a8 (adj 15): empty for 1806s
I/SELinux ( 7144): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7144): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 7144): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/art     ( 7048): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 106.616ms
D/Mms/TelephonyPermission( 7048): start operation mode monitor
D/PackageBroadcastService( 1967): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1967): Clearing selected account for com.test.thalitest
W/ResourcesManager( 7048): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1967): Module APK com.google.android.play.games already loaded
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1967): Module APK com.google.android.play.games already loaded
I/Choreographer( 1480): Skipped 32 frames!  The application may be doing too much work on its main thread.
I/Timeline( 1480): Timeline: Activity_idle id: android.os.BinderProxy@283acb38 time:1895628
D/Mms/TelephonyPermission( 7048): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 7048): isDefault true
D/Mms/MmsApp( 7048): onCreate() com.android.mms
D/Mms/ArtClassLoader( 7048): init before art
D/TimaKeyStoreProvider( 7144): TimaSignature is unavailable
D/ActivityThread( 7144): Added TimaKeyStore provider
E/NetworkScheduler.SchedulerReceiver( 1776): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1776): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/LocationSettingsChecker( 1967): Removing dialog suppression flag for package com.test.thalitest
W/art     ( 7018): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/FeatureConfig( 7144): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/Mms/MmsApp( 7048): [start]    initCountryIso consume time = 394.968959
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/CountryDetector( 1019): The first listener is added
D/Mms/MmsApp( 7048): [end]    initCountryIso consume time = 14.124531
D/Mms/MmsConfig( 7048): [start]    MmsConfig.init() consume time = 0.099323
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0

```
