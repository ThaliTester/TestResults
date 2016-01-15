#### Test 56204092c98eeae_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
,V/GLSActivity( 1798): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
I/System.out( 5248): Thread-882(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5248): Thread-882(ApacheHTTPLog):isShipBuild true
I/System.out( 5248): Thread-882(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5248): Thread-882(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
--------- beginning of system
I/ActivityManager( 1017): Killing 4864:com.sec.smartcard.manager/u0a149 (adj 15): empty #31
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/Finsky  ( 5248): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/DBG_POLICYDM( 5526): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 5526): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 5526): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/DBG_POLICYDM( 5526): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 5526): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
I/DBG_POLICYDM( 5526): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
I/DBG_POLICYDM( 5526): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 5526): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 5526): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
W/libprocessgroup( 1017): failed to open /acct/uid_10149/pid_4864/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 5526): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 5526): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 5526): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 5526): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 5526): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
I/qtaguid ( 5248): Untagging socket 44
I/DBG_POLICYDM( 5526): [com.policydm.XSPPReceiver(53/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
I/qtaguid ( 5248): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5248): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5248): untagSocket(44) failed with errno -22
I/System.out( 5248): Thread-882 calls detatch()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5606 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5030:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
E/Zygote  ( 5606): MountEmulatedStorage()
I/libpersona( 5606): KNOX_SDCARD checking this for 10036
E/Zygote  ( 5606): v2
I/libpersona( 5606): KNOX_SDCARD not a persona
I/SELinux ( 5606): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5606): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5606): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5606): TimaSignature is unavailable
D/ActivityThread( 5606): Added TimaKeyStore provider
I/DBG_POLICYDM( 5526): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/DBG_POLICYDM( 5526): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 5526): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 5526): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
I/DBG_POLICYDM( 5526): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
I/DBG_POLICYDM( 5526): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
D/AndroidRuntime( 5604): 
D/AndroidRuntime( 5604): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5604): CheckJNI is OFF
D/AndroidRuntime( 5604): readGMSProperty: start
D/AndroidRuntime( 5604): readGMSProperty: already setted!!
D/AndroidRuntime( 5604): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5604): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5604): readGMSProperty: end
D/AndroidRuntime( 5604): addProductProperty: start
I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5030/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
I/DBG_POLICYDM( 5526): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 5526): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
I/DBG_POLICYDM( 5526): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 5526): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 5526): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/01/18/16:30:29
I/DBG_POLICYDM( 5526): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/01/15/19:44:51
I/DBG_POLICYDM( 5526): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 5526): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
I/DBG_POLICYDM( 5526): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5526): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5526): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 5526): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 5526): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5526): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 5526): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
W/art     ( 2016): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 288.538ms
E/AffinityControl( 5604): AffinityControl: registerfunction enter
I/DBG_POLICYDM( 5526): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/AndroidRuntime( 5604): Calling main entry com.android.commands.am.Am
I/SA      ( 5606): [SSP] onCreated
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/DBG_POLICYDM( 5526): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
I/SA      ( 5606): [TPM] There is no property file
I/SA      ( 5606): [SCU] isHaveSA() - false
I/SA      ( 5606): [TPM] getModelProperty : null
I/SA      ( 5606): [TPM] getCSCProperty : null
I/SA      ( 5606): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5606): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5606): [DM] TFT FEATURE: false
W/ActivityManager( 1017): mDVFSHelper.acquire()
I/SA      ( 5606): [PMR] Received action : android.intent.action.PACKAGE_ADDED
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5526): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
E/Zygote  ( 5635): MountEmulatedStorage()
I/libpersona( 5635): KNOX_SDCARD checking this for 10167
E/Zygote  ( 5635): v2
I/libpersona( 5635): KNOX_SDCARD not a persona
I/SELinux ( 5635): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5635): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5635): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5635 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 3111
I/ServiceManager(  331): Waiting for service AtCmdFwd...
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, uhalitest
D/AndroidRuntime( 5604): Shutting down VM
I/SA      ( 5606): [DM] init START
D/TimaKeyStoreProvider( 5635): TimaSignature is unavailable
D/ActivityThread( 5635): Added TimaKeyStore provider
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
I/SA      ( 5606): [DM] This device is not a Vodafone
V/ActivityManager( 1017): Display changed displayId=0
I/DBG_POLICYDM( 5526): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
I/art     (  318): Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 660us total 65.651ms
V/ActivityThread( 3111): updateVisibility : ActivityRecord{1cb57ab8 token=android.os.BinderProxy@27d89e4e {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 18.052ms
W/ResourceType( 5606): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 17.748ms
W/ResourceType( 5606): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 5606): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
I/SurfaceFlinger(  259): id=11 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  259): id=11 Removed YUIInstallC (-2/9)
I/Icing   ( 2016): Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
W/ResourceType( 5606): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5606): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 5606): [SCU] isHaveSA() - false
I/SA      ( 5606): support phone number id : false
I/SA      ( 5606): [DM] Supports Ref Jpn : true
I/SA      ( 5606): [DM] init END
I/SA      ( 5606): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5606): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10167 extra.user_handle.:0 ]
I/ActivityManager( 1017): Killing 5050:com.sec.android.app.sns3/u0a30 (adj 15): empty #31
I/DBG_POLICYDM( 5526): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
D/ChimeraCfgMgr( 2016): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2016): Module APK com.google.android.play.games already loaded
I/DBG_POLICYDM( 5526): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5526): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
W/art     ( 5604): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/libprocessgroup( 1017): failed to open /acct/uid_10030/pid_5050/cgroup.procs: No such file or directory
I/Icing   ( 2016): Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 5248): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5248): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/WebViewFactory( 5635): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
I/LibraryLoader( 5635): Loading: webviewchromium
I/LibraryLoader( 5635): Time to load native libraries: 5 ms (timestamps 1516-1521)
I/LibraryLoader( 5635): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5635): Binding Chromium to main looper Looper (main, tid 1) {2a9a4148}
W/ResourcesManager( 5248): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/LibraryLoader( 5635): Expected native library version number "",actual native library version number ""
I/chromium( 5635): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/GAV2    ( 5473): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/Zygote  ( 5665): MountEmulatedStorage()
E/Zygote  ( 5665): v2
I/libpersona( 5665): KNOX_SDCARD checking this for 1000
I/SELinux ( 5665): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 5665): KNOX_SDCARD not a persona
I/SELinux ( 5665): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5665): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5665 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/BrowserStartupController( 5635): Initializing chromium process, renderers=0
W/art     ( 5635): Attempt to remove local handle scope entry from IRT, ignoring
D/TimaKeyStoreProvider( 5665): TimaSignature is unavailable
D/ActivityThread( 5665): Added TimaKeyStore provider
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/Finsky  ( 5248): [1] DailyHygiene.access$600: Logging device features
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
D/FilterInstaller( 5665): onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
W/ContextImpl( 5665): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
V/AlarmManager( 1017): waitForAlarm result :4
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/FilterInstaller( 5665): FilterPackageService : ACTION_CHANGED
E/Zygote  ( 5683): MountEmulatedStorage()
E/Zygote  ( 5683): v2
I/libpersona( 5683): KNOX_SDCARD checking this for 10098
I/libpersona( 5683): KNOX_SDCARD not a persona
I/SELinux ( 5683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5683 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 5683): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
E/FilterInstaller( 5665): installFilters
E/FilterInstaller( 5665): There is no requred permission
I/ActivityManager( 1017): Killing 5079:com.sec.spp.push:RemoteDlcProcess/u0a32 (adj 15): empty #31
D/TimaKeyStoreProvider( 5683): TimaSignature is unavailable
D/ActivityThread( 5683): Added TimaKeyStore provider
D/PackageIntentReceiver( 5683): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5683): Not GearManger package! 
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{3d16d457 u0 com.test.thalitest/.MainActivity t8}
I/ActivityManager( 1017): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5703 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5099:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
E/Zygote  ( 5703): MountEmulatedStorage()
I/libpersona( 5703): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5703): v2
I/libpersona( 5703): KNOX_SDCARD not a persona
I/SELinux ( 5703): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5703): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5703): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/chromium( 5635): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5635): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 5635): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/DeviceConnectionService( 1798): client connected with version: 8296000
D/TimaKeyStoreProvider( 5703): TimaSignature is unavailable
D/ActivityThread( 5703): Added TimaKeyStore provider
W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_5079/cgroup.procs: No such file or directory
I/Adreno-EGL( 5635): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5635): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5635): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5635): Local Branch: 
I/Adreno-EGL( 5635): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5635): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5635):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Finsky  ( 5248): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5248): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager( 1017): Killing 5136:com.android.providers.calendar/u0a37 (adj 15): empty #31
I/ActivityManager( 1017): Killing 5121:com.sec.android.diagmonagent/1000 (adj 15): empty #32
W/GAV2    ( 5473): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1017): Killing 4745:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_5099/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10037/pid_5136/cgroup.procs: No such file or directory
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5729): MountEmulatedStorage()
E/Zygote  ( 5729): v2
I/libpersona( 5729): KNOX_SDCARD checking this for 1000
I/libpersona( 5729): KNOX_SDCARD not a persona
I/SELinux ( 5729): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5729 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5174:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
I/SELinux ( 5729): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5729): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5729): TimaSignature is unavailable
D/ActivityThread( 5729): Added TimaKeyStore provider
W/chromium( 5635): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 5635): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/AcmsPackageEventListener( 5729): Received: android.intent.action.PACKAGE_ADDED
W/art     ( 5635): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
W/AwContents( 5635): onDetachedFromWindow called when already detached. Ignoring
W/ContextImpl( 5729): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
D/PhoneWindow( 5635): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5635): *FMB* installDecor flags : 8456448
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/SystemWebViewEngine( 5635): CordovaWebView is running on device made by: samsung
D/AcmsService( 5729): Enter Oncreate
D/AcmsServiceMonitor( 5729): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5729): creating AcmsCore
D/AcmsCore( 5729): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5729): AcmsCore
D/AcmsCore( 5729): init
D/AcmsCore( 5729): Looper handler is not null
D/AcmsCore( 5729): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5729): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5729): Incrementing - Counter value: 1
D/AcmsCore( 5729): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 5729): onStartCommand
D/AcmsService( 5729): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5729): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5729): Incrementing - Counter value: 2
D/AcmsService( 5729): Incremented Counter Value : onStartCommand
D/AcmsCertificateMngr( 5729): AcmsCertificateMngr
D/AcmsRevocationMngr( 5729): AcmsRevocationMngr
W/art     ( 5635): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5635): Attempt to remove local handle scope entry from IRT, ignoring
D/ActivityThread( 5729): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/AcmsService( 5729): Inside handle Intent
D/AcmsService( 5729): App added - package name: com.test.thalitest
D/AcmsCore( 5729): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5729): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5729): Incrementing - Counter value: 3
D/AcmsCore( 5729): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5729): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5729): Decrementing - Counter value: 2
D/OpenGLRenderer( 5635): Render dirty regions requested: true
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5757): MountEmulatedStorage()
E/Zygote  ( 5757): v2
I/libpersona( 5757): KNOX_SDCARD checking this for 10148
I/libpersona( 5757): KNOX_SDCARD not a persona
I/SELinux ( 5757): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5757): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5757): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5757 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
V/ActivityThread( 5635): updateVisibility : ActivityRecord{3e29e3b6 token=android.os.BinderProxy@18048c78 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5121/cgroup.procs: No such file or directory
D/PhoneWindow( 5635): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5635): *FMB* isFloatingMenuEnabled return false
W/libprocessgroup( 1017): failed to open /acct/uid_10139/pid_5174/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4745/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5757): TimaSignature is unavailable
D/ActivityThread( 5757): Added TimaKeyStore provider
I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1017): Focus entered window: 5635
D/SRIB_DCS( 5635): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
I/OpenGLRenderer( 5635): Initialized EGL, version 1.4
D/OpenGLRenderer( 5635): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5635): Enabling debug mode 0
E/SMD     (  297): DCD OFF
I/ServiceManager(  331): Waiting for service AtCmdFwd...
E/SQLiteLog( 5757): (284) automatic index on shooting_modes(title_id)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5778): MountEmulatedStorage()
I/libpersona( 5778): KNOX_SDCARD checking this for 10152
E/Zygote  ( 5778): v2
I/libpersona( 5778): KNOX_SDCARD not a persona
I/SELinux ( 5778): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/SELinux ( 5778): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5778): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5778 uid=10152 gids={50152, 9997} abi=armeabi-v7a
I/StatusBar( 1174): Icon Only
I/ActivityManager( 1017): Killing 4999:com.google.android.talk/u0a102 (adj 15): empty #31
D/PanelView( 1174): There is/are notification(s) 
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 1017): Displayed Component not be shown by security: +1s15ms (total +1s103ms)
W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{3d16d457 u0 com.test.thalitest/.MainActivity t8} time:82300
I/SurfaceFlinger(  259): id=13 Removed uhalitest (7/9)
I/SurfaceFlinger(  259): id=13 Removed uhalitest (-2/9)
W/IInputConnectionWrapper( 5635): showStatusIcon on inactive InputConnection
I/Timeline( 5635): Timeline: Activity_idle id: android.os.BinderProxy@18048c78 time:82312
I/SamsungIME( 1823): getCurrentCandidateView
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/TimaKeyStoreProvider( 5778): TimaSignature is unavailable
D/ActivityThread( 5778): Added TimaKeyStore provider
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5778): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5778): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,D/SamsungIME( 1823): Dismiss ExpandCandiate
,W/libprocessgroup( 1017): failed to open /acct/uid_10102/pid_4999/cgroup.procs: No such file or directory
,I/TapandpayWidget:Utils( 5778): Clear T&P info.
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5778): Widget is not attached.
,I/splitIntent( 1017): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1017): Killing 5208:com.sec.knox.bridge/1000 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5248): [904] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1798): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SamsungIME( 1823): getDebugLevel  : 0x4f4c
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5208/cgroup.procs: No such file or directory
,I/System.out( 5248): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5248): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5248): (HTTPLog)-Static: isShipBuild true
I/System.out( 5248): (HTTPLog)-Thread-893-364592463: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5248): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10026
,I/chromium( 5635): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5635): 
,I/SamsungIME( 1823): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1823): KeybaordView init() : load resources
,I/SamsungIME( 1823): getCurrentKeyboard
,I/SamsungIME( 1823): getTextKeyboard
,D/SamsungIME( 1823): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/System.out( 5248): KnoxVpnUidStorageknoxVpnSupported API value returned is false
D/JsMessageQueue( 5635): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5635): JniHelper::setJavaVM(0xb8345448), pthread_self() = -1198566824
,D/JX-Cordova( 5635): jxcore cordova android initializing
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1017): SIOP:: AP = 370
,W/jxcore-log( 5635): Initializing JXcore engine
W/jxcore-log( 5635): JXcore engine is ready
,W/jxcore-log( 5635): Starting JXcore engine
,E/audit   ( 1847): type=1400 msg=audit(1452883494.731:205): avc:  denied  { ioctl } for  pid=5635 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1847):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1847): type=1300 msg=audit(1452883494.731:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bee94d58 items=0 ppid=318 ppcomm=main pid=5635 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1847): type=1320 msg=audit(1452883494.731:205): 
,D/AcmsKeyStoreHelper( 5729):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5729): Key Store exist
,I/AcmsKeyStoreHelper( 5729): Hence loading the keystore file
,W/jxcore-log( 5635): Platform android
W/jxcore-log( 5635): 
W/jxcore-log( 5635): Process ARCH arm
W/jxcore-log( 5635): 
,D/AcmsKeyStoreHelper( 5729):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 5729): getKeyStoreForApplication success 
D/AcmsCore( 5729): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5729): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5729): Decrementing - Counter value: 1
D/AcmsCore( 5729): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5729): This is NOT a valid MirrorLink app
D/AcmsCore( 5729): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5729): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5729): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5729): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5729): getSvcCounter - Counter value: 0
,D/AcmsService( 5729): Enter onDestroy
I/AcmsService( 5729): cleanUp(): inside service clean up
,D/AcmsCore( 5729): AcmsCore: inside DeInit
D/AcmsCore( 5729): AcmsCore: mLooperHandler is not null and making it null
,D/AcmsCertificateMngr( 5729): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5729): AcmsRevocationMngr: inside cleanup
,D/AcmsKeyStoreHelper( 5729): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5729): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5729): getSvcCounter - Counter value: 0
D/AcmsService( 5729): killing acms process
,I/Process ( 5729): Sending signal. PID: 5729 SIG: 9
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/DBG_POLICYDM( 5526): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/ActivityManager( 1017): Process ACMS.Process (pid 5729)(adj 0) has died(30,581)
,I/DBG_POLICYDM( 5526): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/CAR.SERVICE( 5423): mConnectedToCar = false, abort
,E/ActivityThread( 5423): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@9fb7b87 that was originally bound here
E/ActivityThread( 5423): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@9fb7b87 that was originally bound here
E/ActivityThread( 5423): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5423): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5423): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5423): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5423): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5423): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5423): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5423): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5423): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5423): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5423): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5423): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5423): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5423): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 5423): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 5423): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 5423): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5423): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5423): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5423): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5423): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5423): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5423): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 5423): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@996919e that was originally bound here
E/ActivityThread( 5423): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@996919e that was originally bound here
E/ActivityThread( 5423): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5423): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5423): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5423): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5423): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5423): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5423): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5423): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5423): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5423): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5423): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5423): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5423): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 5423): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 5423): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 5423): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5423): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5423): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5423): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5423): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5423): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5423): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1017): Unbind failed: could not find connection for android.os.BinderProxy@a270535
,I/jxcore-log( 5635): JXcore Cordova bridge is ready!
I/jxcore-log( 5635): 
,W/jxcore-log( 5635): JXcore engine is started
,E/SMD     (  297): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 5473): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 5635): Toggling radios to true
I/jxcore-log( 5635): 
,D/BluetoothAdapter( 5635): enable()
D/BluetoothAdapter( 5635): enable(): BT is already enabled..!,
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/WifiService( 1017): setWifiEnabled: true pid=5635, uid=10167
,W/ActivityManager( 1017): Permission Denial: getCurrentUser() from pid=5635, uid=10167 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1017): Failed getting userId using ActivityManagerNative
W/WifiService( 1017): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5635, uid=10167 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1017): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1017): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1017): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1017): name = wifi_on
I/WifiService( 1017): disconnect: pid=5635, uid=10167
,I/wpa_supplicant( 1386): [wpa_supplicant_ctrl_iface_process] : DISCONNECT,
,I/jxcore-log( 5635): Radios toggled
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): Got Device Bluetooth address: 08:EC:A9:50:76:27
I/jxcore-log( 5635): 
I/jxcore-log( 5635): Perf Test app loaded loaded
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): check test folder
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): found test : ./testFindPeers.js
I/jxcore-log( 5635): 
,I/wpa_supplicant( 1386): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
I/wpa_supplicant( 1386): wlan0: State: COMPLETED -> DISCONNECTED
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1386): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1386): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1386): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/Tethering( 1017): InitialState.processMessage what=4
I/wpa_supplicant( 1386): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 1386): wlan0: Setting scan request: 0 sec 0 usec
E/wpa_supplicant( 1386): Cmd 35605 not handled
I/wpa_supplicant( 1386): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1386): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1386): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1386): First Scan Start
I/wpa_supplicant( 1386): Scan requested (ret=0) - scan timeout 30 seconds
,E/Tethering( 1017): No numeric data
,I/jxcore-log( 5635): found test : ./testSendData.js,
I/jxcore-log( 5635): 
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/Tethering( 1017): clearTetheredNotification()
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED,
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/HotspotTile( 1174): updateTetherState():false, false
,D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,V/NetworkStats( 1017): performPollLocked() took 19ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiNative-wlan0( 1017): do suspend true
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1798): Read error: ssl=0xb88f0908: I/O error during system call, Connection timed out
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
E/ConnectivityService( 1017): updateNetworkInfo()
,E/ConnectivityService( 1017): updateNetworkInfo()
E/WifiStateMachine( 1017): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1386): wlan0: Setting scan request: 0 sec 0 usec
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,E/WifiNative-wlan0( 1017): do suspend true
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1671): Starting #8
,I/Hs20UtilService( 1671): Message received 5007
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null,
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1305): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1305): MountReceiver.mPrefHandler - 7002
,I/art     ( 1798): Explicit concurrent mark sweep GC freed 32898(2013KB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 9MB/16MB, paused 1.216ms total 83.997ms
,V/NativeCrypto( 1798): SSL shutdown failed: ssl=0xb88f0908: I/O error during system call, Broken pipe,
,D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1017): Tagging socket 339 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityManager.CallbackHandler( 2016): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524292
,D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
D/TelephonyNetworkFactory( 1445): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1445): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/qtaguid ( 1017): Untagging socket 339
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-12ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1017): MasterInitialState.processMessage what=3
D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
V/NetworkStats( 1017): updateIfacesLocked()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false,
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
V/NetworkStats( 1017): performPollLocked() took 2ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
,I/chromium( 5635): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1671): Starting #9
,I/Hs20UtilService( 1671): Message received 5007
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1305): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1305): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3
,D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3
,D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3
,D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3,
D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3,
,D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3
,D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3
,D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3
,D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3
,D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3
,D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3
,D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3
,D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3
,D/PhoneApp( 1445): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1445): FileWriteThread : threadType = 3
,I/chromium( 5635): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1017): updateDataUsageMap
,I/DBG_DM  ( 3111): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/NetworkMonitor( 4367): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 5510): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5510): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5510): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5510): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3111): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5510): noConnectivity : true
,I/splitIntent( 1017): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,I/splitIntent( 1017): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,I/KLMS-2.5.123: ( 3581): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 19:44:58 GMT+01:00 2016
,D/accuweather( 1712): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5834): MountEmulatedStorage(),
E/Zygote  ( 5834): v2
I/libpersona( 5834): KNOX_SDCARD checking this for 10141
I/libpersona( 5834): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=5834 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3581): KLMSAbstractReciever(): onReceive().END.
,I/SELinux ( 5834): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5834): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5834): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3581): KLMSIntentService(): onCreate()
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,I/KLMS-2.5.123: ( 3581): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3581): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.123: ( 3581): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3581): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
E/Zygote  ( 5847): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5847 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 5847): v2
I/libpersona( 5847): KNOX_SDCARD checking this for 10031
I/SELinux ( 5847): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 5847): KNOX_SDCARD not a persona
I/SELinux ( 5847): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5847): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3581): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
D/TimaKeyStoreProvider( 5834): TimaSignature is unavailable
D/ActivityThread( 5834): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3581): StateImplV2(): networkChangeListener().END
D/accuweather( 1712): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1712): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1712): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1712): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3581): KLMSIntentService(): onDestroy()
,D/accuweather( 1712): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 5847): TimaSignature is unavailable
D/accuweather( 1712): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/ActivityThread( 5847): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5834): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
W/ResourcesManager( 5834): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5834): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5834): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 5865): MountEmulatedStorage()
E/Zygote  ( 5865): v2
I/libpersona( 5865): KNOX_SDCARD checking this for 10077
I/libpersona( 5865): KNOX_SDCARD not a persona
I/SELinux ( 5865): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5865): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5865 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5865): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5865): TimaSignature is unavailable
,D/ActivityThread( 5865): Added TimaKeyStore provider
,I/SO_AGENT( 5847): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5526): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/SPPClientService( 4266): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
I/DBG_POLICYDM( 5526): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 5526): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5526): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
I/SA      ( 5606): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5606): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5606): [OR] == ACTION_CONNECTIVITY_CHANGE ==
E/DBG_POLICYDM( 5526): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 5606): [SLFUCHKMGR] constructor called
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SA      ( 5606): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5606): [OR] == isSIMCardReady false ==
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/SA      ( 5606): [SCU] == networkStateCheck == false
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/SPPClientService( 4266): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 5606): [OR] onReceive END
,V/DownloadManager( 1222): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/wpa_supplicant( 1386): nl80211: Received scan results (7 BSSes),
I/wpa_supplicant( 1386): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1386): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1386): Trying to associate with  'G700'
I/wpa_supplicant( 1386): Re-associate with C0.AA.48
I/wpa_supplicant( 1386): wlan0: State: SCANNING -> ASSOCIATING,
I/wpa_supplicant( 1386): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1017): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,I/ActivityManager( 1017): Killing 5229:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5890): MountEmulatedStorage()
E/Zygote  ( 5890): v2
I/libpersona( 5890): KNOX_SDCARD checking this for 10110
I/libpersona( 5890): KNOX_SDCARD not a persona
,I/SELinux ( 5890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5890 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 5890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5890): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 5270:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 5890): TimaSignature is unavailable
,D/ActivityThread( 5890): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5907): MountEmulatedStorage(),
E/Zygote  ( 5907): v2
I/libpersona( 5907): KNOX_SDCARD checking this for 10068
I/libpersona( 5907): KNOX_SDCARD not a persona
I/SELinux ( 5907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5907): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5907 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/art     (  318): Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 638us total 21.500ms
,E/wpa_supplicant( 1386): Cmd 35605 not handled
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false,
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1386): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1386): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030,
I/wpa_supplicant( 1386): Associated with C0.AA.48
I/wpa_supplicant( 1386): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1386): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1386): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false,
D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/TimaKeyStoreProvider( 5907): TimaSignature is unavailable,
D/ActivityThread( 5907): Added TimaKeyStore provider
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1017): interfaceStatusChanged wlan0, true
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
,E/Tethering( 1017): No numeric data
,I/wpa_supplicant( 1386): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1386): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1386): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
,I/wpa_supplicant( 1386): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030,
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
,I/wpa_supplicant( 1386): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5270/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1386): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1386): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1386): Blacklist: Clear (temp) 
I/wpa_supplicant( 1386): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030,
D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceStatusChanged wlan0, true
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.017ms total 19.397ms
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled,
D/SecContentProvider2( 1017): mCursor = null
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 19.390ms
,E/Zygote  ( 5922): MountEmulatedStorage()
E/Zygote  ( 5922): v2
I/libpersona( 5922): KNOX_SDCARD checking this for 10001
I/ActivityManager( 1017): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=5922 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 5922): KNOX_SDCARD not a persona
,I/SELinux ( 5922): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5922): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5922): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1017): clearTetheredNotification()
,D/WifiNative-wlan0( 1017): callSECApiVoid - ID [50]
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1174): updateTetherState():false, false
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
E/WifiConfigStore( 1017): setLastSelectedConfiguration -1
,D/TimaKeyStoreProvider( 5922): TimaSignature is unavailable
V/NetworkStats( 1017): performPollLocked() took 8ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/ActivityThread( 5922): Added TimaKeyStore provider
,D/ConnectivityService( 1017): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1017): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/libprocessgroup( 1017): failed to open /acct/uid_10065/pid_5229/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/BadgeProvider( 5907): onCreate
D/BadgeProvider( 5907): DatabaseHelper
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider( 5907): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SMD     (  297): DCD OFF,
,E/Zygote  ( 5941): MountEmulatedStorage()
,E/Zygote  ( 5941): v2
I/libpersona( 5941): KNOX_SDCARD checking this for 1000
I/libpersona( 5941): KNOX_SDCARD not a persona
,I/SELinux ( 5941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=5941 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 4976:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
I/SELinux ( 5941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5941): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Zygote  ( 5951): MountEmulatedStorage()
E/Zygote  ( 5951): v2
I/libpersona( 5951): KNOX_SDCARD checking this for 1000
I/libpersona( 5951): KNOX_SDCARD not a persona
,I/SELinux ( 5951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5951 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 5951): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 4681:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 4808:com.sec.android.app.music:service/u0a35 (adj 15): empty #32
,D/TimaKeyStoreProvider( 5941): TimaSignature is unavailable
,D/ActivityThread( 5941): Added TimaKeyStore provider
,D/BadgeProvider( 5907): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5907): sendNotify, [notify] : null
D/BadgeProvider( 5907): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5907): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5907): update, [UpdateCount] : 1
,D/Launcher.Model( 1476): reloadBadges entered.
,D/TimaKeyStoreProvider( 5951): TimaSignature is unavailable
,D/ActivityThread( 5951): Added TimaKeyStore provider
D/CommandListener(  280): Setting iface cfg
E/WifiStateMachine( 1017): Start Dhcp Watchdog 2
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1017): mCursor = null
,E/WifiNative-wlan0( 1017): do suspend false
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,I/DIAGMON_AGENT( 5941): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/SecurityLogAgent( 5951): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5951): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 5951): StateMachine : Current State = 1
,D/SecurityLogAgent( 5951): StateMachine : Changed Current State = 1
,W/libprocessgroup( 1017): failed to open /acct/uid_10146/pid_4976/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10130/pid_4681/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_4808/cgroup.procs: No such file or directory
,I/iu.Environment( 2016): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2016): num queued entries: 0
,I/iu.UploadsManager( 2016): num updated entries: 0
,I/iu.SyncManager( 2016): NEXT; no task
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5890): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5890): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/DIAGMON_AGENT( 5941): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5890): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/DIAGMON_AGENT( 5941): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5890): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/DIAGMON_AGENT( 5941): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 5941): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 5941): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 5941): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 5980): MountEmulatedStorage(),
E/Zygote  ( 5980): v2
I/libpersona( 5980): KNOX_SDCARD checking this for 10008
I/libpersona( 5980): KNOX_SDCARD not a persona
,I/SELinux ( 5980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=5980 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 4011:com.android.calendar/u0a131 (adj 15): empty #31,
,I/SELinux ( 5980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5980): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/PowerManagerService( 1017): [PWL] Off : 15s ago
I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
,D/TimaKeyStoreProvider( 5980): TimaSignature is unavailable
,I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=1477)
D/ActivityThread( 5980): Added TimaKeyStore provider
,E/dhcpcd  ( 6007): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6007): version 5.5.6 starting
,E/dhcpcd  ( 6007): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10131/pid_4011/cgroup.procs: No such file or directory
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 273400(17MB) AllocSpace objects, 8(4MB) LOS objects, 33% free, 23MB/35MB, paused 3.268ms total 279.823ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 6007): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 6007): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6007): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/ActivityManager( 1017): Killing 4903:com.google.android.gm/u0a99 (adj 15): empty #31
,I/dhcpcd  ( 6007): bssid match
,I/dhcpcd  ( 6007): wlan0: rebinding lease of 192.168.1.133,
,I/WebViewFactory( 5890): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/LibraryLoader( 5890): Loading: webviewchromium
,I/LibraryLoader( 5890): Time to load native libraries: 4 ms (timestamps 8695-8699)
I/LibraryLoader( 5890): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5890): Binding Chromium to main looper Looper (main, tid 1) {9fb7b87}
,I/LibraryLoader( 5890): Expected native library version number "",actual native library version number ""
,I/chromium( 5890): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5890): Initializing chromium process, renderers=0
,W/art     ( 5890): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid( 5890): Requires BLUETOOTH permission
W/chromium( 5890): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 5890): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 5890): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/libprocessgroup( 1017): failed to open /acct/uid_10099/pid_4903/cgroup.procs: No such file or directory
,I/Adreno-EGL( 5890): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5890): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5890): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5890): Local Branch: 
I/Adreno-EGL( 5890): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5890): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5890):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/NSApplication( 5890): Starting up...
,I/ActivityManager( 1017): Killing 4826:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6036): MountEmulatedStorage()
,E/Zygote  ( 6036): v2
I/libpersona( 6036): KNOX_SDCARD checking this for 10121
I/libpersona( 6036): KNOX_SDCARD not a persona
I/SELinux ( 6036): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6036): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6036 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 6036): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 4644:com.android.mms/u0a41 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6036): TimaSignature is unavailable
,D/ActivityThread( 6036): Added TimaKeyStore provider
,W/ResourcesManager( 6036): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6036): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6036): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6036): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6036): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6036): PeriphStartReceiver.onReceive - no need to start
,I/splitIntent( 1017): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1017): Killing 5458:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,D/CountryDetector( 1017): No listener is left
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 1671): Starting #10
,I/Hs20UtilService( 1671): Message received 5007
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1305): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1305): MountReceiver.mPrefHandler - 7002
,W/libprocessgroup( 1017): failed to open /acct/uid_10039/pid_4826/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10041/pid_4644/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10014/pid_5458/cgroup.procs: No such file or directory
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1017): waitForAlarm result :8
,I/dhcpcd  ( 6007): wlan0: acknowledged 192.168.1.133 from 192.168.1.1
,I/dhcpcd  ( 6007): wlan0: leased 192.168.1.133 for 86400 seconds,
,E/WifiNative-wlan0( 1017): do suspend true,
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null,
E/WifiStateMachine( 1017): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/WifiStateMachine( 1017): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,D/ConnectivityService( 1017): Adding iface wlan0 to network 503,
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1017): callSECApiInt - ID [210]
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/WifiWatchdogStateMachine( 1017): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1017): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1017): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
E/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/PackageManager( 1017): [MSG] MCS_UNBIND
I/Hs20UtilService( 1671): Starting #11
,D/ConnectivityService( 1017): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1017): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1017): Setting Dns servers for network 503 to [/192.168.1.1]
,I/Hs20UtilService( 1671): Message received 5007
D/ConnectivityService( 1017): LTETest block dns file not exists
D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1305): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1017): updateNetworkInfo()
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1017): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 1017):    accepting network in place of null,
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1445): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1445): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/CSLegacyTypeTracker( 1017): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/CSLegacyTypeTracker( 1017): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/ConnectivityService( 1017): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 2016): CM callback handler got msg 524290
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): updateIfacesLocked()
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---,
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
V/NetworkStats( 1017): performPollLocked() took 5ms
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1017): mBoosterFLAG : 0
I/WifiTrafficPoller( 1017): current booster mode : FullMode
,D/WifiNative-wlan0( 1017): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ActivityManager( 1017): Killing 5493:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1671): Starting #12
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1671): Message received 5007
V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1305): MountReceiver.onReceive - Keep current state
,I/System.out( 1017): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1671): Starting #13
,I/Hs20UtilService( 1671): Message received 5007
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1305): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1017): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1017): mCursor = null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 18:45:00 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452883500886], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452883500866]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/ConnectivityService( 1017): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 2016): CM callback handler got msg 524290
,I/SurfaceFlinger(  259): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1017): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,D/SRIB_DCS( 1174): log_dcs ThreadedRenderer::initialize entered! 
,W/libprocessgroup( 1017): failed to open /acct/uid_10042/pid_5493/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 4367): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5510): SPPPushClient is installed : true
,I/DBG_DM  ( 3111): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/PCWCLIENTTRACE_PushUtil( 5510): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5510): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5510): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
I/splitIntent( 1017): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/accuweather( 1712): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3581): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 19:45:01 GMT+01:00 2016
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/KLMS-2.5.123: ( 3581): KLMSAbstractReciever(): onReceive().END.
,D/SecurityLogAgent( 5951): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5951): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5951): StateMachine : Current State = 1
,D/accuweather( 1712): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1712): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1712): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1712): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/SecurityLogAgent( 5951): StateMachine : Changed Current State = 1
,I/KLMS-2.5.123: ( 3581): KLMSIntentService(): onCreate()
D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,I/KLMS-2.5.123: ( 3581): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3581): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/accuweather( 1712): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3581): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/accuweather( 1712): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KLMS-2.5.123: ( 3581): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3581): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3581): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3581): NetworkChangeOperations(): uploadRequestLog().START 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3581): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3581): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3581): KLMSIntentService(): onDestroy()
,I/DIAGMON_AGENT( 5941): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 5941): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 5941): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 5941): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/iu.Environment( 2016): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2016): num queued entries: 0
,I/iu.UploadsManager( 2016): num updated entries: 0
,I/iu.SyncManager( 2016): NEXT; no task
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5526): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10011
,D/WaitQueueForNetworkActivate( 5583): notifyNetworkActivated
,I/DBG_POLICYDM( 5526): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,E/SPPClientService( 4266): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/DBG_POLICYDM( 5526): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5526): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,D/QuickConnect( 6036): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6036): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6036): PeriphStartReceiver.onReceive - no need to start
,I/DBG_POLICYDM( 5526): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5606): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5606): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5606): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5606): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5606): [OR] == isSIMCardReady false ==
,I/SA      ( 5606): [SCU] == networkStateCheck == true
I/SA      ( 5606): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5606): isChinaCountryCode : false
I/SA      ( 5606): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5606): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 5526): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5526): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5526): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5526): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/SA      ( 5606): [OR] GetMyCountryZoneTask
I/SA      ( 5606): [OR] onReceive END
,I/DBG_POLICYDM( 5526): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,V/DownloadManager( 1222): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/DBG_POLICYDM( 5526): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,W/ContextImpl( 5583): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1017): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1017): mCursor = null
,I/SA      ( 5606): [SRS] prepareGetMyCountryZone
,I/FOTA_Client( 5980): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 5980): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 5980): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,E/DBG_POLICYDM( 5526): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,W/FOTA_Client( 5980): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/SA      ( 5606): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5606): [SSP] query invoked
,I/DBG_POLICYDM( 5526): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/SA      ( 5606): [TPMU] GetMccFromDB : null
I/SA      ( 5606): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5606): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 5526): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,E/File    ( 5606): fail readDirectory() errno=2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1017): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,I/splitIntent( 1017): Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/hcjo    ( 5583): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5583): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5583): exit::IDLE
D/InitializeManagerStateMachine( 5583): entry::NETWORK_CHECK
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/InitializeManagerStateMachine( 5583): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5583): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5583): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5583): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5583): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5583): entry::SUCCESS
D/hcjo    ( 5583): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5583): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5583): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5583): exit::SUCCESS
D/InitializeManagerStateMachine( 5583): entry::IDLE
,E/SMD     (  297): DCD OFF
,I/SA      ( 5606): [RC New] Execute method=[GET] start
,I/SA      ( 5606): [RC New] Security=[true]
,I/System.out( 5606): Thread-940(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5606): Thread-940(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5606): Thread-940(ApacheHTTPLog):isShipBuild true
I/System.out( 5606): Thread-940(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5606): Thread-940(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10036
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 5635): BLE supported!!
I/jxcore-log( 5635): 
,I/SA      ( 5606): [RC New] [v2liruge] api execute + 613
,I/SA      ( 5606): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5606): AsyncTask #1 calls detatch()
,I/SA      ( 5606): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5606): [OCP] update openData : PL
,I/SA      ( 5606): [TPMU] getNetworkMcc : 
,I/SA      ( 5606): [SCU] saveMccToPreferece Start
,I/SA      ( 5606): [SCU] RegionMCC : 260
,I/SA      ( 5606): [SSP] query invoked
,I/SA      ( 5606): [TPMU] GetMccFromDB : null
,I/SA      ( 5606): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5606): [SCU] saveMccToPreferece End
,I/SA      ( 5606): [RC New] executeRequest [v2liruge] end. 673
I/SA      ( 5606): [RC New] Execute end
,I/SA      ( 5606): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5606): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6007): wlan0: sending IPv6 Router Solicitation
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/GAV4    ( 5890): Thread[GAThread,5,main]: No campaign data found.
,D/SSRM:n  ( 1017): SIOP:: AP = 350
,I/SurfaceFlinger(  259): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  259): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1017): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 93684
,D/PowerManagerService( 1017): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0)
D/PowerManagerService( 1017): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10049}) (elapsedTime=3487)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SMD     (  297): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{1200ce77 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService},
,V/AlarmManager( 1017): waitForAlarm result :4
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5510): mConnectivityHandler : connected
,V/AlarmManager( 1017): ___SyncScheduler (v3) ACTIVATED___
,W/PCWCLIENTTRACE_AccountUtil( 5510): [hasSamungAccount] - No Samsung Account
,V/AlarmManagerEXT( 1017): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1017): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5510): [GetString-S]
,I/ReactiveServiceManager( 5510): Supported : 1
,D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 11
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1017): handleString: Failed to handle string(-4)
E/terrier ( 1017): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5510): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5510): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5510): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5510): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5510): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5510): [ensureRegistration] - No Samsung account
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/Finsky  ( 5248): [895] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5248): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,I/dhcpcd  ( 6007): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,I/dhcpcd  ( 6007): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6007): wlan0: no IPv6 Routers available
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5583): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5583): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5583): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5583): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5583): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5583): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5583): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5583): entry::IDLE
,E/SMD     (  297): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/SSRM:n  ( 1017): SIOP:: AP = 310
,I/PowerManagerService( 1017): [PWL] Off : 30s ago
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{15b387ad u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  297): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1798): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1798): Vacuum at: now=1452883517913 tag=VacuumService
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Watchdog( 1017): !@Sync 3
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/FactoryTest( 5154): Not factory mode,
D/FactoryTest( 5154): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 5154): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 5154): still no open session command from host, so toast,
,W/ContextImpl( 5154): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5154): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5154): Timeline: Activity_launch_request id:com.android.settings time:108395
,E/PersonaManagerService( 1017): inState():  stateMachine is null !!
,I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus left window: 5635
,E/MTPRx   ( 5154): started activity for popup
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101,
,W/ResourcesManager( 5154): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5154): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5154): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5154): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5154): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5154): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5154): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus entered window: 5635
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1017): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@30f48253 attribute=null, token = android.os.BinderProxy@100e4441
,D/SettingsReceiverActivity( 5154): dev.kiessupport is : TRUE
,D/PhoneWindow( 5154): *FMB* installDecor mIsFloating : true
,D/PhoneWindow( 5154): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,I/Timeline( 5635): Timeline: Activity_idle id: android.os.BinderProxy@18048c78 time:108591
,V/ActivityThread( 5635): updateVisibility : ActivityRecord{3e29e3b6 token=android.os.BinderProxy@18048c78 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,E/SMD     (  297): DCD OFF
,W/ActivityManager( 1017): mDVFSHelper.release()
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  297): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/PowerManagerService( 1017): [PWL] Off : 50s ago
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 4
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  297): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 75s ago
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/SSRM:n  ( 1017): SIOP:: AP = 280
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,I/ClearcutLoggerApiImpl( 1798): disconnect managed GoogleApiClient
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 5
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 105s ago
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1017): !@Sync 6
,E/SMD     (  297): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService( 1017): [PWL] Off : 140s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/Watchdog( 1017): !@Sync 7
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  297): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 180s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1017): !@Sync 8
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 9
,E/SMD     (  297): DCD OFF
,I/jxcore-log( 5635): Connected to the server!
I/jxcore-log( 5635): 
,I/chromium( 5635): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  297): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 225s ago
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 1017): initializing...
,I/TLC_TIMA_PKM_initialize( 1017): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1017): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE,
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1017): Trustlet response is completed
,E/SMD     (  297): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/Watchdog( 1017): !@Sync 10
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  297): DCD OFF
,E/Watchdog( 1017): !@Sync 11,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1017): [PWL] Off : 275s ago
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,E/Watchdog( 1017): !@Sync 12,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  297): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :8
,V/AlarmManager( 1017): No more alarm at this time.nowELAPSED=389290 batch.start=991051
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 330s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  297): DCD OFF
,I/jxcore-log( 5635): --- start :testFindPeers.js---
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): testFindPeers created [object Object]
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): serverPort is 8876
I/jxcore-log( 5635): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): start: Peer ID: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT7121
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5635): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5635): initialize: My bluetooth address is 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5635): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 5635): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5635): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,D/BluetoothSocket( 5635): bindListen(), new LocalSocket 
D/BluetoothSocket( 5635): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5635): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@119e0f92
D/BluetoothSocket( 5635): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): start: OK
,I/io.jxcore.node.ConnectionHelper( 5635): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): start: Peer ID: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT7121
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5635): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5635): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): start: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5635): start: Identity string: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5635): start: OK
,I/jxcore-log( 5635): StartBroadcasting started ok
I/jxcore-log( 5635): 
,D/WifiP2pService( 1017): P2pEnabledState add service
,I/io.jxcore.node.ConnectionHelper( 5635): onConnectionManagerStateChanged: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper( 5635): onDiscoveryManagerStateChanged: RUNNING
,D/WifiP2pService( 1017): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5635): Local service added successfully
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
,I/chromium( 5635): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): P2P device discovery started successfully,
D/WifiP2pService( 1017): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/Watchdog( 1017): !@Sync 13,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/WifiDisplayController( 1017): Received list of peers.
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 5635): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service request added successfully
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 },
,D/WifiDisplayController( 1017): Received list of peers.,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac,
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 4 device(s) discovered
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1386): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service discovery started successfully
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/wpa_supplicant( 1386): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1386): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  297): DCD OFF
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 5 device(s) discovered
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3965","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
,D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] is available
,I/jxcore-log( 5635): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT3965","peerAvailable":true}]
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): weAreDoneNow,
I/jxcore-log( 5635): 
I/jxcore-log( 5635): done, now sending data to server
I/jxcore-log( 5635): 
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
,D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] is available
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254] is available
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4558","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558] is available
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,E/Watchdog( 1017): !@Sync 14,
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 1386): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped,
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): P2P device discovery started successfully
D/WifiP2pService( 1017): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/SMD     (  297): DCD OFF
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 },
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 6 device(s) discovered,
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): restart: Restarting...
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 6 device(s) discovered
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/WifiP2pService( 1017): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/WifiP2pManager( 5635): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service request added successfully
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
I/wpa_supplicant( 1386): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 7 device(s) discovered
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service discovery started successfully
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT3213","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] is available
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033],
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] is available
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1017): stay LED for fully charged
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  297): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 390s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  297): DCD OFF
,E/Watchdog( 1017): !@Sync 15
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,I/io.jxcore.node.ConnectionHelper( 5635): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] removed
,D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] not available
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 1386): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  297): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): Start timer timeout, starting now...
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiP2pService( 1017): InactiveState{ what=139265 }
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1017): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): InactiveState{ what=139301 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/WifiP2pService( 1017): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): restart: Restarting...
,D/WifiP2pManager( 5635): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service request added successfully
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service discovery started successfully
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1017): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] is available
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/bootchecker(  326): bootchecker wake up!!,
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF,
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  297): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  297): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,E/Watchdog( 1017): !@Sync 16,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/io.jxcore.node.ConnectionHelper( 5635): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] removed
D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] not available,
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/SMD     (  297): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 1386): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped,
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1017): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): P2P device discovery started successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 }
I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 },
D/WifiDisplayController( 1017): Received list of peers.,
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): restart: Restarting...
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23,
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): P2pEnabledState add service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/WifiP2pManager( 5635): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service request added successfully
,E/SMD     (  297): DCD OFF
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 }
I/wpa_supplicant( 1386): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
,D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558],
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LG,E-Nexus 5_PT4558]
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service discovery started successfully
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4558","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558],
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] is available
,E/SMD     (  297): DCD OFF,
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0,
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 7:8709
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2608): db_query_execute: result 1
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 7:8709
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2608): db_query_execute: result 1
W/bt-btif ( 2608): info:x10
,D/        ( 2608): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2608): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,I/jxcore-log( 5635): teardown
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): testFindPeers stopped,
I/jxcore-log( 5635): 
I/io.jxcore.node.ConnectionHelper( 5635): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): shutdown
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@50992de, channel: 6, state: LISTENING
D/BluetoothSocket( 5635): close() this: android.bluetooth.BluetoothSocket@50992de, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@119e0f92, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@5875cbfmSocket: android.net.LocalSocket@139edf8c impl:android.net.LocalSocketImpl@350a06d5 fd:FileDescriptor[111]
D/BluetoothSocket( 5635): Closing mSocket: android.net.LocalSocket@139edf8c impl:android.net.LocalSocketImpl@350a06d5 fd:FileDescriptor[111]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5635): release: No more listeners, de-initializing...,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): stop: Stopping peer discovery...
D/WifiP2pService( 1017): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): stop: Stopping services
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
D/WifiP2pService( 1017): P2pEnabledState clear service,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): stop: Stopping P2P device discovery...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5635): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5635): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5635): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): setState: NOT_STARTED
I/jxcore-log( 5635): StopBroadcasting went ok
I/jxcore-log( 5635): ,
I/io.jxcore.node.ConnectionHelper( 5635): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5635): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5635): Local services cleared successfully
D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 1386): P2P-FIND-STOPPED 
,I/chromium( 5635): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): P2P device discovery stopped successfully
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState clear service request
D/WifiP2pService( 1017): remove channel information from framework
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service requests cleared successfully
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,I/jxcore-log( 5635): --- start :testSendData.js---
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":15}bt-address length : 0
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): daya100000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): check server
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): serverPort is 46977
I/jxcore-log( 5635): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): start: Peer ID: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT7121,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5635): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5635): initialize: My bluetooth address is 08:EC:A9:50:76:27,
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5635): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 5635): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5635): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,D/BluetoothSocket( 5635): bindListen(), new LocalSocket 
,D/BluetoothSocket( 5635): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5635): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19df05db
,D/BluetoothSocket( 5635): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): start: OK
I/io.jxcore.node.ConnectionHelper( 5635): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): start: Peer ID: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT7121
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5635): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5635): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): start: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5635): start: Identity string: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5635): start: OK
,I/jxcore-log( 5635): StartBroadcasting started ok
I/jxcore-log( 5635): 
D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState add service
,I/jxcore-log( 5635): null
I/jxcore-log( 5635): 
,E/Watchdog( 1017): !@Sync 17
,D/WifiP2pService( 1017): add a new client
,I/jxcore-log( 5635): 2016-01-15T18:52:18.323Z SendDataTCPServer.js: TCP/IP server is bound to port: 46977
I/jxcore-log( 5635): 
,I/io.jxcore.node.ConnectionHelper( 5635): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper( 5635): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
I/chromium( 5635): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5635): Local service added successfully
,D/WifiP2pService( 1017): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: STARTED
,I/wpa_supplicant( 1386): P2P-FIND-STOPPED 
D/WifiP2pService( 1017): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): P2P device discovery stopped successfully
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.CLASS_CHANGED
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2608): check_cod: remote_cod = 0x5a020c,
,I/BluetoothBondStateMachine( 2608): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
,I/BluetoothBondStateMachine( 2608): Entering PendingCommandState State,
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5683): jangil::setProperties()
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10098
,D/GMFPReceiver( 5683): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10098
,D/GMFPReceiver( 5683): ::::::::Wearable0002::false
,D/GMFPReceiver( 5683): onServiceConnected() : 1
,D/GMFPReceiver( 5683): mBluetoothHeadset = true
,D/btif_config_util( 2608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2608): Failed to remove device: E0:DB:10:14:E2:C0
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
I/BluetoothBondStateMachine( 2608): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11,
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit,
D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED,
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5683): jangil::setProperties()
D/HidService( 2608): getHidService(): returning com.android.bluetooth.hid.HidService@236e1a1
,D/SettingsProvider( 1017): name = bluetooth_input_device_priority_E0:DB:10:14:E2:C0
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/HidService( 2608): Saved priority E0:DB:10:14:E2:C0 = -1
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_E0:DB:10:14:E2:C0
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_E0:DB:10:14:E2:C0
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/BluetoothBondStateMachine( 2608): StableState(): Entering Off State
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5683): ::::::::Wearable0002::false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/GMFPReceiver( 5683): onServiceConnected() : 1
D/GMFPReceiver( 5683): mBluetoothHeadset = true
,W/bt-btif ( 2608): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2608): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2608): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket( 5635): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@15ef1fb6
,E/BluetoothRemoteDevices( 2608): setRfcommConnected true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Incoming connection initialized (thread ID: 963),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Entering thread (ID: 963)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): onBytesRead: Read 82 bytes successfully (thread ID: 963)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): onBytesWritten: 83 bytes successfully written (thread ID: 963)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): removeThreadFromList: Removing thread with ID 963
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Handshake thread disposed (thread ID: 963)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Exiting thread (ID: 963)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
,I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Incoming connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
,D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] is available
,I/jxcore-log( 5635): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT8999","peerAvailable":true}]
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): Found peer : samsung-SM-N910C_PT8999, Available: true
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): startWithNextDevice
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): device[1]: E0:DB:10:14:E2:C0
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:19.267Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:19.268Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:19.269Z SendDataConnector.js: do connect now
I/jxcore-log( 5635): 
,I/io.jxcore.node.ConnectionHelper( 5635): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): connect: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnecting: Note4-1 E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 5635): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 964)
,I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Incoming socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], created successfully
,D/io.jxcore.node.ConnectionHelper( 5635): onConnected: The total number of connections is now 1
D/BluetoothUtils( 5635): isSocketAllowedBySecurityPolicy start : device null
W/BluetoothAdapter( 5635): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 5635): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,D/io.jxcore.node.IncomingSocketThread( 5635): Entering thread (ID: 965)
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10167
,I/io.jxcore.node.IncomingSocketThread( 5635): Local host address: localhost/127.0.0.1, port: 46977
D/io.jxcore.node.IncomingSocketThread( 5635): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 5635): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 5635): Exiting thread (ID: 965)
,D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 966, name: Sender)
,I/jxcore-log( 5635): 2016-01-15T18:52:19.294Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 5635): 
D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 967, name: Receiver)
,I/PowerManagerService( 1017): [PWL] Off : 455s ago
I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=2608, ws=null) (elapsedTime=1477)
,W/bt-sdp  ( 2608): process_service_search_attr_rsp
,W/bt-btif ( 2608): new conn_srvc id:26, app_id:1
W/bt-btif ( 2608): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2608): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2608): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2608): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onSocketConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 964),
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): onBytesWritten: 83 bytes successfully written (thread ID: 968)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Outgoing connection initialized (*handshake* thread ID: 968)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Exiting thread (thread ID: 964)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Entering thread (ID: 968)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): onBytesRead: Read 82 bytes successfully (thread ID: 968)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onHandshakeSucceeded: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Exiting thread (ID: 968)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Outgoing connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: We have an incoming connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 5635): onConnected: Already connected with peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Outgoing socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 5635): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 5635): Entering thread (ID: 969)
,D/io.jxcore.node.OutgoingSocketThread( 5635): Server socket local port: 58788
,I/io.jxcore.node.OutgoingSocketThread( 5635): Now accepting connections...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,I/io.jxcore.node.ConnectionHelper( 5635): onListeningForIncomingConnections: Outgoing connection is using port 58788 (peer ID: E0:DB:10:14:E2:C0)
,I/jxcore-log( 5635): 2016-01-15T18:52:19.749Z SendDataConnector.js: CLIENT connected to 58788, error: null
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:19.750Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:19.757Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 5635): 
,I/io.jxcore.node.OutgoingSocketThread( 5635): Incoming data from address: /127.0.0.1, port: 58788
,D/io.jxcore.node.OutgoingSocketThread( 5635): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 5635): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 5635): Exiting thread (ID: 969)
,D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 971, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 970, name: Sender)
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/jxcore-log( 5635): 2016-01-15T18:52:20.163Z SendDataTCPServer.js: TCP/IP server has received 78936 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.177Z SendDataTCPServer.js: TCP/IP server has received 80960 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.212Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.216Z SendDataTCPServer.js: TCP/IP server has received 93104 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.219Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.274Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.278Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.326Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.401Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.405Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.431Z SendDataTCPServer.js: TCP/IP server has received 95128 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.462Z SendDataTCPServer.js: TCP/IP server has received 99176 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.481Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.485Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.520Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 5635): 
,W/bt-btif ( 2608): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 967, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 5635): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 965
,D/io.jxcore.node.OutgoingSocketThread( 5635): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 967
D/io.jxcore.node.OutgoingSocketThread( 5635): close: Stopping sending thread...,
I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 966
,D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local input stream...,
D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 5635): closeBluetoothSocketAndStreams
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@2f3e24b7, channel: 6, state: CONNECTED
,D/BluetoothSocket( 5635): close() this: android.bluetooth.BluetoothSocket@2f3e24b7, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@292f9424, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d3b8dmSocket: android.net.LocalSocket@1e458142 impl:android.net.LocalSocketImpl@c065553 fd:FileDescriptor[111]
D/BluetoothSocket( 5635): Closing mSocket: android.net.LocalSocket@1e458142 impl:android.net.LocalSocketImpl@c065553 fd:FileDescriptor[111]
,D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@2f3e24b7, channel: 6, state: CLOSED
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@2f3e24b7, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 967, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 966, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 5635): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 966, name: Sender)
,I/jxcore-log( 5635): 2016-01-15T18:52:20.555Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.559Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.559Z SendDataConnector.js: got all data for this round
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): oneRoundDownNow
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.561Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:20.562Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5635): 
,D/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0,
,I/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 5635): close
D/io.jxcore.node.OutgoingSocketThread( 5635): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 971
D/io.jxcore.node.OutgoingSocketThread( 5635): close: Stopping sending thread...,
,I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 970
,D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 5635): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@1de3ce90, channel: 6, state: CONNECTED
,D/BluetoothSocket( 5635): close() this: android.bluetooth.BluetoothSocket@1de3ce90, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@364f0389, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37ae6f8emSocket: android.net.LocalSocket@3116f3af impl:android.net.LocalSocketImpl@d5f43bc fd:FileDescriptor[117]
D/BluetoothSocket( 5635): Closing mSocket: android.net.LocalSocket@3116f3af impl:android.net.LocalSocketImpl@d5f43bc fd:FileDescriptor[117],
W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 970, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 5635): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 971, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 5635): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@1de3ce90, channel: 6, state: CLOSED
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@1de3ce90, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
E/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 971, name: Receiver)
I/jxcore-log( 5635): 2016-01-15T18:52:20.566Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 5635): 
E/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0,
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 970, name: Sender)
,I/jxcore-log( 5635): ---- round done--------
I/jxcore-log( 5635): 
I/jxcore-log( 5635): startWithNextDevice
I/jxcore-log( 5635): 
,W/bt-btif ( 2608): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1017): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/bt-btm  ( 2608): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2608): btm_sec_disconnected - Clearing Pending flag
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1305): ACTION_ACL_DISCONNECTED
D/KeyguardViewMediator( 1174): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1174): isGear1: device is not B1!
,D/BluetoothAdapterService( 2608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2d2fc7
,D/BtConfig.SecureMode( 2608): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 3214): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3214): Bluetooth Device Name: Note4-1
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2608): db_query_execute: result 1
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 7:8709
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2608): db_query_execute: result 1
,W/bt-btif ( 2608): info:x10
,D/        ( 2608): remote version info [7c:f9:0e:51:18:22]: 7, f, 2205
,E/BluetoothRemoteDevices( 2608): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,E/SMD     (  297): DCD OFF
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 5635): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service request added successfully
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1,
D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2608): check_cod: remote_cod = 0x5a020c
V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.CLASS_CHANGED
,I/BluetoothBondStateMachine( 2608): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
I/BluetoothBondStateMachine( 2608): Entering PendingCommandState State
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive,
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5683): jangil::setProperties()
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5683): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5683): ::::::::Wearable0002::false
D/GMFPReceiver( 5683): onServiceConnected() : 1
D/GMFPReceiver( 5683): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1386): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service discovery started successfully
,I/wpa_supplicant( 1386): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1386): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/btif_config_util( 2608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2608): Failed to remove device: 7C:F9:0E:51:18:22
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2608): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive,
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
D/HidService( 2608): getHidService(): returning com.android.bluetooth.hid.HidService@236e1a1
V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
D/SettingsProvider( 1017): name = bluetooth_input_device_priority_7C:F9:0E:51:18:22
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/BluetoothTile( 1174):  handleUpdatestate:false name:null
D/SettingsProvider( 1017): ret = -1
D/HidService( 2608): Saved priority 7C:F9:0E:51:18:22 = -1,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_7C:F9:0E:51:18:22
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_7C:F9:0E:51:18:22
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/BluetoothNotiBroadcastReceiver( 1305): onReceive
I/BluetoothBondStateMachine( 2608): StableState(): Entering Off State
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
,D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5683): jangil::setProperties()
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5683): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0002::false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/GMFPReceiver( 5683): onServiceConnected() : 1
D/GMFPReceiver( 5683): mBluetoothHeadset = true
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,W/bt-btif ( 2608): new conn_srvc id:26, app_id:255
,D/BluetoothSocket( 5635): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@179b4f45
W/bt-btif ( 2608): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2608): bta_dm_pm_ssr:2, lat:1200
E/BluetoothRemoteDevices( 2608): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Incoming connection initialized (thread ID: 972)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Entering thread (ID: 972)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): onBytesRead: Read 83 bytes successfully (thread ID: 972)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): onBytesWritten: 83 bytes successfully written (thread ID: 972)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): removeThreadFromList: Removing thread with ID 972
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Handshake thread disposed (thread ID: 972)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Incoming connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
,W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Incoming socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], created successfully
,D/io.jxcore.node.ConnectionHelper( 5635): onConnected: The total number of connections is now 1
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Exiting thread (ID: 972)
,D/io.jxcore.node.IncomingSocketThread( 5635): Entering thread (ID: 973)
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10167
,I/jxcore-log( 5635): 2016-01-15T18:52:27.642Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 5635): 
,I/io.jxcore.node.IncomingSocketThread( 5635): Local host address: localhost/127.0.0.1, port: 46977
,D/io.jxcore.node.IncomingSocketThread( 5635): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 5635): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 5635): Exiting thread (ID: 973)
,D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 975, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 974, name: Sender)
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
,I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT858","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT858], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT858], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT858] is available
,I/jxcore-log( 5635): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT858","peerAvailable":true}]
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): Found peer : motorola-XT1072_PT858, Available: true
I/jxcore-log( 5635): 
I/jxcore-log( 5635): startWithNextDevice
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): device[2]: 44:80:EB:7B:5A:05
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:28.119Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 5635): 
I/jxcore-log( 5635): 2016-01-15T18:52:28.120Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:28.121Z SendDataConnector.js: do connect now
I/jxcore-log( 5635): 
,I/io.jxcore.node.ConnectionHelper( 5635): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
,D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): connect: [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 5635): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 976)
,D/BluetoothUtils( 5635): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5635): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 5635): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1017): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] already in the list, will not add again
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05,
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2608): db_query_execute: result 1
,E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45cc7f4 rs_disc_pending=1
W/bt-btif ( 2608): bta_dm_check_av:0
,W/bt-btif ( 2608): btif_dm_cback : unhandled event (14),
,I/jxcore-log( 5635): 2016-01-15T18:52:28.471Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:28.477Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:28.483Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:28.615Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:28.865Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log( 5635): 
,E/SMD     (  297): DCD OFF
,I/jxcore-log( 5635): 2016-01-15T18:52:29.490Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 5635): 
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT858], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged,
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,I/jxcore-log( 5635): 2016-01-15T18:52:30.116Z SendDataTCPServer.js: TCP/IP server has received 14168 bytes of data
I/jxcore-log( 5635): 
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT858], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/jxcore-log( 5635): 2016-01-15T18:52:30.992Z SendDataTCPServer.js: TCP/IP server has received 16192 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:31.591Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 5635): 
,E/SMD     (  297): DCD OFF
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2608): db_query_execute: result 1
,W/bt-btif ( 2608): info:x10
D/        ( 2608): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2608): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 2608): process_service_search_attr_rsp
,E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45cc7f4 rs_disc_pending=0
,W/bt-btif ( 2608): bta_dm_check_av:0
W/bt-btif ( 2608): btif_dm_cback : unhandled event (14)
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2608): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2608): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 2608): isSecureModeOn:false
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,I/BluetoothBondStateMachine( 2608): Entering PendingCommandState State
D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5683): jangil::setProperties()
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5683): ::::::::Wearable0001::false
D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5683): ::::::::Wearable0002::false
D/GMFPReceiver( 5683): onServiceConnected() : 1
D/GMFPReceiver( 5683): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2608): Failed to remove device: 44:80:EB:7B:5A:05
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2608): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/HidService( 2608): getHidService(): returning com.android.bluetooth.hid.HidService@236e1a1
,D/SettingsProvider( 1017): name = bluetooth_input_device_priority_44:80:EB:7B:5A:05
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/HidService( 2608): Saved priority 44:80:EB:7B:5A:05 = -1
D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_44:80:EB:7B:5A:05
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_44:80:EB:7B:5A:05
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,I/BluetoothBondStateMachine( 2608): StableState(): Entering Off State
W/bt-btif ( 2608): new conn_srvc id:26, app_id:1
W/bt-btif ( 2608): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2608): bta_dm_pm_ssr:2, lat:1200
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,E/BluetoothRemoteDevices( 2608): setRfcommConnected true
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5683): jangil::setProperties()
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onSocketConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 976)
D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0002::false
D/GMFPReceiver( 5683): onServiceConnected() : 1
D/GMFPReceiver( 5683): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): onBytesWritten: 83 bytes successfully written (thread ID: 977)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Outgoing connection initialized (*handshake* thread ID: 977)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Exiting thread (thread ID: 976)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Entering thread (ID: 977)
,E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45cc7f4 rs_disc_pending=1,
W/bt-btif ( 2608): bta_dm_check_av:0
W/bt-btif ( 2608): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): onBytesRead: Read 80 bytes successfully (thread ID: 977)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onHandshakeSucceeded: [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Exiting thread (ID: 977)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Outgoing connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
,D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05,
,W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT858] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Outgoing socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT858], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 5635): onConnected: The total number of connections is now 2
,I/jxcore-log( 5635): 2016-01-15T18:52:33.748Z SendDataTCPServer.js: TCP/IP server has received 18408 bytes of data
I/jxcore-log( 5635): 
,D/io.jxcore.node.OutgoingSocketThread( 5635): Entering thread (ID: 978)
,D/io.jxcore.node.OutgoingSocketThread( 5635): Server socket local port: 33911
,I/io.jxcore.node.OutgoingSocketThread( 5635): Now accepting connections...
,I/jxcore-log( 5635): 2016-01-15T18:52:33.757Z SendDataTCPServer.js: TCP/IP server has received 20432 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:33.767Z SendDataTCPServer.js: TCP/IP server has received 22456 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:33.807Z SendDataTCPServer.js: TCP/IP server has received 24480 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:33.884Z SendDataTCPServer.js: TCP/IP server has received 26504 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:33.892Z SendDataTCPServer.js: TCP/IP server has received 28528 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:34.041Z SendDataTCPServer.js: TCP/IP server has received 30552 bytes of data
I/jxcore-log( 5635): 
,I/io.jxcore.node.ConnectionHelper( 5635): onListeningForIncomingConnections: Outgoing connection is using port 33911 (peer ID: 44:80:EB:7B:5A:05)
,I/jxcore-log( 5635): 2016-01-15T18:52:34.055Z SendDataConnector.js: CLIENT connected to 33911, error: null
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:34.056Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5635): 
,I/io.jxcore.node.OutgoingSocketThread( 5635): Incoming data from address: /127.0.0.1, port: 33911
,D/io.jxcore.node.OutgoingSocketThread( 5635): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 5635): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 5635): Exiting thread (ID: 978)
D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 979, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 980, name: Receiver)
,I/jxcore-log( 5635): 2016-01-15T18:52:34.065Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 5635): 
,D/        ( 2608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3786
,E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45cc7f4 rs_disc_pending=0
,W/bt-btif ( 2608): bta_dm_check_av:0
W/bt-btif ( 2608): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 5635): 2016-01-15T18:52:34.646Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 5635): 
,D/        ( 2608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18320
,I/jxcore-log( 5635): 2016-01-15T18:52:34.805Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:34.854Z SendDataTCPServer.js: TCP/IP server has received 32576 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:34.892Z SendDataTCPServer.js: TCP/IP server has received 40864 bytes of data,
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:34.960Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 5635): 
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/        ( 2608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8420
,I/jxcore-log( 5635): 2016-01-15T18:52:35.070Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 5635): 
,D/        ( 2608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1490
,I/jxcore-log( 5635): 2016-01-15T18:52:35.115Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 5635): 
,E/SMD     (  297): DCD OFF
,I/jxcore-log( 5635): 2016-01-15T18:52:35.282Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:35.324Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:35.405Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:35.452Z SendDataTCPServer.js: TCP/IP server has received 42888 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:35.492Z SendDataTCPServer.js: TCP/IP server has received 50984 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:35.497Z SendDataTCPServer.js: TCP/IP server has received 53008 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:35.504Z SendDataTCPServer.js: TCP/IP server has received 55032 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:35.549Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:35.625Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 5635): 
I/jxcore-log( 5635): 2016-01-15T18:52:35.626Z SendDataConnector.js: got all data for this round
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): oneRoundDownNow
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:35.628Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 5635): 
I/jxcore-log( 5635): 2016-01-15T18:52:35.628Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5635): 
,D/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05,
I/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 5635): close
D/io.jxcore.node.OutgoingSocketThread( 5635): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 980
D/io.jxcore.node.OutgoingSocketThread( 5635): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 979
D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 979, thread name: Sender): Socket closed,
E/io.jxcore.node.OutgoingSocketThread( 5635): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT858] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 5635): closeBluetoothSocketAndStreams
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@33a5f69a, channel: 5, state: CONNECTED
D/BluetoothSocket( 5635): close() this: android.bluetooth.BluetoothSocket@33a5f69a, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@23e91bcb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1abadfa8mSocket: android.net.LocalSocket@35a69ac1 impl:android.net.LocalSocketImpl@d5ce266 fd:FileDescriptor[116]
D/BluetoothSocket( 5635): Closing mSocket: android.net.LocalSocket@35a69ac1 impl:android.net.LocalSocketImpl@d5ce266 fd:FileDescriptor[116],
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 980, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 5635): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT858] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@33a5f69a, channel: 5, state: CLOSED
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@33a5f69a, channel: 5, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
E/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 979, name: Sender)
E/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 980, name: Receiver)
,I/jxcore-log( 5635): 2016-01-15T18:52:35.642Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): ---- round done--------
I/jxcore-log( 5635): 
I/jxcore-log( 5635): startWithNextDevice
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:35.896Z SendDataTCPServer.js: TCP/IP server has received 57056 bytes of data
I/jxcore-log( 5635): 
,W/bt-btif ( 2608): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45cc7f4 rs_disc_pending=1
,W/bt-btif ( 2608): bta_dm_check_av:0
W/bt-btif ( 2608): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 5635): 2016-01-15T18:52:36.260Z SendDataTCPServer.js: TCP/IP server has received 59080 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:36.267Z SendDataTCPServer.js: TCP/IP server has received 61104 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:36.277Z SendDataTCPServer.js: TCP/IP server has received 63128 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:36.312Z SendDataTCPServer.js: TCP/IP server has received 67176 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:36.331Z SendDataTCPServer.js: TCP/IP server has received 69200 bytes of data
I/jxcore-log( 5635): 
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1386): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,I/jxcore-log( 5635): 2016-01-15T18:52:36.343Z SendDataTCPServer.js: TCP/IP server has received 71224 bytes of data
I/jxcore-log( 5635): 
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,I/jxcore-log( 5635): 2016-01-15T18:52:36.352Z SendDataTCPServer.js: TCP/IP server has received 73248 bytes of data
I/jxcore-log( 5635): 
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, ,groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT919","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919] is available
I/jxcore-log( 5635): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT919","peerAvailable":true}]
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): Found peer : samsung-SM-G900F_PT919, Available: true
I/jxcore-log( 5635): 
I/jxcore-log( 5635): startWithNextDevice
I/jxcore-log( 5635): 
I/jxcore-log( 5635): device[3]: 7C:F9:0E:34:8A:A0
I/jxcore-log( 5635): 
I/jxcore-log( 5635): 2016-01-15T18:52:36.388Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 5635): 
I/jxcore-log( 5635): 2016-01-15T18:52:36.389Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 5635): 
I/jxcore-log( 5635): 2016-01-15T18:52:36.390Z SendDataConnector.js: do connect now
I/jxcore-log( 5635): 
I/io.jxcore.node.ConnectionHelper( 5635): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): connect: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 5635): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 981)
I/jxcore-log( 5635): 2016-01-15T18:52:36.399Z SendDataTCPServer.js: TCP/IP server has received 75272 bytes of data
I/jxcore-log( 5635): 
D/BluetoothUtils( 5635): isSocketAllowedBySecurityPolicy start : device null
W/BluetoothAdapter( 5635): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/BluetoothSocket( 5635): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,I/jxcore-log( 5635): 2016-01-15T18:52:36.432Z SendDataTCPServer.js: TCP/IP server has received 77296 bytes of data
I/jxcore-log( 5635): 
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0,
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 2608): db_query_execute: result 1
E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45cc7f4 rs_disc_pending=1
W/bt-btif ( 2608): bta_dm_check_av:0
W/bt-btif ( 2608): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 5635): 2016-01-15T18:52:37.035Z SendDataTCPServer.js: TCP/IP server has received 79320 bytes of data,
I/jxcore-log( 5635): 
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
,D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): restart: Restarting...
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 5635): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service request added successfully
,E/SMD     (  297): DCD OFF
,I/jxcore-log( 5635): 2016-01-15T18:52:38.317Z SendDataTCPServer.js: TCP/IP server has received 81344 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:38.325Z SendDataTCPServer.js: TCP/IP server has received 83368 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:38.362Z SendDataTCPServer.js: TCP/IP server has received 85392 bytes of data
I/jxcore-log( 5635): 
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service discovery started successfully,
,I/jxcore-log( 5635): 2016-01-15T18:52:38.929Z SendDataTCPServer.js: TCP/IP server has received 87416 bytes of data
I/jxcore-log( 5635): 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/bt-btm  ( 2608): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2608): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1174): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 2608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2d2fc7
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
,E/BluetoothEventManager( 1305): ACTION_ACL_DISCONNECTED
D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/KeyguardViewMediator( 1174): isGear1: device is not B1!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 3214): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3214): Bluetooth Device Name: XT1072
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2608): db_query_execute: result 1
W/bt-btif ( 2608): info:x10
,D/        ( 2608): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2608): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 5635): 2016-01-15T18:52:40.118Z SendDataTCPServer.js: TCP/IP server has received 89440 bytes of data
I/jxcore-log( 5635): 
,E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45cc7f4 rs_disc_pending=1
,W/bt-btif ( 2608): bta_dm_check_av:0
,W/bt-btif ( 2608): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45ccb7c rs_disc_pending=1
,W/bt-btif ( 2608): bta_dm_check_av:0
,W/bt-btif ( 2608): btif_dm_cback : unhandled event (14)
V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2608): db_query_execute: result 1
,E/SMD     (  297): DCD OFF
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2608): db_query_execute: result 1
,W/bt-btif ( 2608): info:x10
D/        ( 2608): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2608): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45ccb7c rs_disc_pending=1
,W/bt-btif ( 2608): bta_dm_check_av:0
W/bt-btif ( 2608): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 5635): 2016-01-15T18:52:41.347Z SendDataTCPServer.js: TCP/IP server has received 91464 bytes of data
I/jxcore-log( 5635): 
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,I/jxcore-log( 5635): 2016-01-15T18:52:41.657Z SendDataTCPServer.js: TCP/IP server has received 93488 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:41.692Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 5635): 
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2608): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2608): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
,I/BluetoothBondStateMachine( 2608): Entering PendingCommandState State
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5683): jangil::setProperties()
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0001::false
D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5683): ::::::::Wearable0002::false
,D/GMFPReceiver( 5683): onServiceConnected() : 1
D/GMFPReceiver( 5683): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 2608): Failed to remove device: F8:95:C7:87:3C:51
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote,
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
I/BluetoothBondStateMachine( 2608): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/HidService( 2608): getHidService(): returning com.android.bluetooth.hid.HidService@236e1a1
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/SettingsProvider( 1017): name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/HidService( 2608): Saved priority F8:95:C7:87:3C:51 = -1
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_F8:95:C7:87:3C:51
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/BluetoothBondStateMachine( 2608): StableState(): Entering Off State
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5683): jangil::setProperties()
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5683): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,W/bt-btif ( 2608): new conn_srvc id:26, app_id:255
W/bt-btif ( 2608): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2608): bta_dm_pm_ssr:2, lat:1200
D/BluetoothSocket( 5635): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@3e6ba9a7
,E/BluetoothRemoteDevices( 2608): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Incoming connection accepted
,D/GMFPReceiver( 5683): ::::::::Wearable0002::false
,D/GMFPReceiver( 5683): onServiceConnected() : 1
,D/GMFPReceiver( 5683): mBluetoothHeadset = true
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Incoming connection initialized (thread ID: 982)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Entering thread (ID: 982)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): onBytesRead: Read 77 bytes successfully (thread ID: 982)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): onBytesWritten: 83 bytes successfully written (thread ID: 982)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): removeThreadFromList: Removing thread with ID 982
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Handshake thread disposed (thread ID: 982)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771],
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Exiting thread (ID: 982)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771] is available,
I/jxcore-log( 5635): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT4771","peerAvailable":true}]
I/jxcore-log( 5635): 
I/jxcore-log( 5635): Found peer : LGE-LG-H815_PT4771, Available: true
I/jxcore-log( 5635): 
,I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771], created successfully
,D/io.jxcore.node.ConnectionHelper( 5635): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 5635): Entering thread (ID: 983)
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10167
,I/io.jxcore.node.IncomingSocketThread( 5635): Local host address: localhost/127.0.0.1, port: 46977
,E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45cc7f4 rs_disc_pending=0
,W/bt-btif ( 2608): bta_dm_check_av:0
,I/jxcore-log( 5635): 2016-01-15T18:52:42.055Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 5635): 
,W/bt-btif ( 2608): btif_dm_cback : unhandled event (14)
,D/io.jxcore.node.IncomingSocketThread( 5635): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
,D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 984, name: Sender)
,I/io.jxcore.node.IncomingSocketThread( 5635): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 5635): Exiting thread (ID: 983)
,D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 985, name: Receiver)
,E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45ccb7c rs_disc_pending=1
,W/bt-btif ( 2608): bta_dm_check_av:0
,W/bt-btif ( 2608): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2608): process_service_search_attr_rsp
,I/jxcore-log( 5635): 2016-01-15T18:52:42.759Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:42.768Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:42.773Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:42.785Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:42.788Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:42.822Z SendDataTCPServer.js: TCP/IP server has received 20240 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:42.826Z SendDataTCPServer.js: TCP/IP server has received 22264 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:42.862Z SendDataTCPServer.js: TCP/IP server has received 32384 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:42.896Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:42.932Z SendDataTCPServer.js: TCP/IP server has received 46936 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:42.936Z SendDataTCPServer.js: TCP/IP server has received 48960 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:42.942Z SendDataTCPServer.js: TCP/IP server has received 50984 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:42.949Z SendDataTCPServer.js: TCP/IP server has received 53008 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:42.982Z SendDataTCPServer.js: TCP/IP server has received 61104 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:43.014Z SendDataTCPServer.js: TCP/IP server has received 63128 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:43.057Z SendDataTCPServer.js: TCP/IP server has received 65152 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:43.062Z SendDataTCPServer.js: TCP/IP server has received 67176 bytes of data
I/jxcore-log( 5635): 
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,I/jxcore-log( 5635): 2016-01-15T18:52:43.074Z SendDataTCPServer.js: TCP/IP server has received 71224 bytes of data
I/jxcore-log( 5635): 
,E/bt-btif ( 2608): check_cod: remote_cod = 0x5a020c
,I/jxcore-log( 5635): 2016-01-15T18:52:43.079Z SendDataTCPServer.js: TCP/IP server has received 73248 bytes of data
I/jxcore-log( 5635): 
I/BluetoothBondStateMachine( 2608): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
I/BluetoothBondStateMachine( 2608): Entering PendingCommandState State
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/BluetoothTile( 1174):  handleUpdatestate:false name:null
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5683): jangil::setProperties()
,D/btif_config_util( 2608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 5635): 2016-01-15T18:52:43.112Z SendDataTCPServer.js: TCP/IP server has received 85392 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:43.118Z SendDataTCPServer.js: TCP/IP server has received 87416 bytes of data
I/jxcore-log( 5635): 
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5683): ::::::::Wearable0001::false
,I/jxcore-log( 5635): 2016-01-15T18:52:43.122Z SendDataTCPServer.js: TCP/IP server has received 89440 bytes of data
I/jxcore-log( 5635): 
D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0002::false
D/GMFPReceiver( 5683): onServiceConnected() : 1
D/GMFPReceiver( 5683): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 5635): 2016-01-15T18:52:43.153Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 5635): 
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2608): Failed to remove device: 7C:F9:0E:34:8A:A0
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
I/BluetoothBondStateMachine( 2608): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/HidService( 2608): getHidService(): returning com.android.bluetooth.hid.HidService@236e1a1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,D/SettingsProvider( 1017): name = bluetooth_input_device_priority_7C:F9:0E:34:8A:A0
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
D/HidService( 2608): Saved priority 7C:F9:0E:34:8A:A0 = -1
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_7C:F9:0E:34:8A:A0
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_7C:F9:0E:34:8A:A0
D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/BluetoothBondStateMachine( 2608): StableState(): Entering Off State
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
,D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5683): jangil::setProperties()
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0002::false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
D/GMFPReceiver( 5683): onServiceConnected() : 1
D/GMFPReceiver( 5683): mBluetoothHeadset = true
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45ccd40 rs_disc_pending=0
,W/bt-btif ( 2608): bta_dm_check_av:0
W/bt-btif ( 2608): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2608): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2608): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2608): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2608): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onSocketConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 981)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): onBytesWritten: 83 bytes successfully written (thread ID: 986)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Entering thread (ID: 986)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Outgoing connection initialized (*handshake* thread ID: 986)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Exiting thread (thread ID: 981)
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 975, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 5635): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/bt-btif ( 2608): invalid rfc slot id: 6
W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 973
D/io.jxcore.node.IncomingSocketThread( 5635): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 975
D/io.jxcore.node.IncomingSocketThread( 5635): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 974
,D/io.jxcore.node.IncomingSocketThread( 5635): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local output stream...
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 974, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 5635): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 5635): closeLocalSocketAndStreams: Closing the localhost socket...
W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
I/io.jxcore.node.IncomingSocketThread( 5635): closeBluetoothSocketAndStreams
,I/jxcore-log( 5635): 2016-01-15T18:52:43.634Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 5635): 
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@3fb24e54, channel: 6, state: CONNECTED
D/BluetoothSocket( 5635): close() this: android.bluetooth.BluetoothSocket@3fb24e54, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1bc121fd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3044bef2mSocket: android.net.LocalSocket@209f3943 impl:android.net.LocalSocketImpl@340ffbc0 fd:FileDescriptor[111]
,D/BluetoothSocket( 5635): Closing mSocket: android.net.LocalSocket@209f3943 impl:android.net.LocalSocketImpl@340ffbc0 fd:FileDescriptor[111]
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@3fb24e54, channel: 6, state: CLOSED
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@3fb24e54, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 975, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 974, name: Sender)
,W/bt-btif ( 2608): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 985, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 5635): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 983
D/io.jxcore.node.IncomingSocketThread( 5635): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 985
D/io.jxcore.node.IncomingSocketThread( 5635): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 984
D/io.jxcore.node.IncomingSocketThread( 5635): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 984, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 5635): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 5635): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 5635): closeBluetoothSocketAndStreams
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@2e0f9, channel: 6, state: CONNECTED
D/BluetoothSocket( 5635): close() this: android.bluetooth.BluetoothSocket@2e0f9, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b5bd83e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ff2269fmSocket: android.net.LocalSocket@1fd913ec impl:android.net.LocalSocketImpl@80793b5 fd:FileDescriptor[115]
D/BluetoothSocket( 5635): Closing mSocket: android.net.LocalSocket@1fd913ec impl:android.net.LocalSocketImpl@80793b5 fd:FileDescriptor[115]
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@2e0f9, channel: 6, state: CLOSED
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@2e0f9, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 985, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 984, name: Sender)
,I/jxcore-log( 5635): 2016-01-15T18:52:43.955Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 5635): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): onBytesRead: Read 81 bytes successfully (thread ID: 986)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onHandshakeSucceeded: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Exiting thread (ID: 986)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Outgoing connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Outgoing socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 5635): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 5635): Entering thread (ID: 987)
,D/io.jxcore.node.OutgoingSocketThread( 5635): Server socket local port: 42359
,I/io.jxcore.node.OutgoingSocketThread( 5635): Now accepting connections...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  297): DCD OFF
,I/io.jxcore.node.ConnectionHelper( 5635): onListeningForIncomingConnections: Outgoing connection is using port 42359 (peer ID: 7C:F9:0E:34:8A:A0)
,I/jxcore-log( 5635): 2016-01-15T18:52:44.334Z SendDataConnector.js: CLIENT connected to 42359, error: null
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:44.335Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5635): 
,I/io.jxcore.node.OutgoingSocketThread( 5635): Incoming data from address: /127.0.0.1, port: 42359
,D/io.jxcore.node.OutgoingSocketThread( 5635): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 5635): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 5635): Exiting thread (ID: 987)
,I/jxcore-log( 5635): 2016-01-15T18:52:44.343Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 5635): 
,D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 988, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 989, name: Receiver)
,W/bt-rfcomm( 2608): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 2608): RFCOMM_DisconnectInd LCID:0x49
,D/        ( 2608): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:2244
,I/jxcore-log( 5635): 2016-01-15T18:52:44.870Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:44.917Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:44.923Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 5635): 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 5635): 2016-01-15T18:52:44.999Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 5635): 
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,I/jxcore-log( 5635): 2016-01-15T18:52:45.071Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:45.083Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:45.218Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:45.224Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:45.639Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:45.955Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:45.956Z SendDataConnector.js: got all data for this round
I/jxcore-log( 5635): 
I/jxcore-log( 5635): oneRoundDownNow
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:45.957Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 5635): 
I/jxcore-log( 5635): 2016-01-15T18:52:45.957Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5635): 
,D/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
,I/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.OutgoingSocketThread( 5635): close
D/io.jxcore.node.OutgoingSocketThread( 5635): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 989
,D/io.jxcore.node.OutgoingSocketThread( 5635): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 988
D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 988, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 5635): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 5635): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@2d393a4a, channel: 6, state: CONNECTED
D/BluetoothSocket( 5635): close() this: android.bluetooth.BluetoothSocket@2d393a4a, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@105c8dbb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@43982d8mSocket: android.net.LocalSocket@1d6ab631 impl:android.net.LocalSocketImpl@24d8b116 fd:FileDescriptor[116]
D/BluetoothSocket( 5635): Closing mSocket: android.net.LocalSocket@1d6ab631 impl:android.net.LocalSocketImpl@24d8b116 fd:FileDescriptor[116]
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 989, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 5635): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@2d393a4a, channel: 6, state: CLOSED
,D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@2d393a4a, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 988, name: Sender)
E/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
,D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 989, name: Receiver)
,I/jxcore-log( 5635): 2016-01-15T18:52:45.972Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): ---- round done--------
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): startWithNextDevice
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): device[4]: F8:95:C7:87:3C:51
I/jxcore-log( 5635): 
I/jxcore-log( 5635): 2016-01-15T18:52:45.975Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:45.976Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 5635): 
I/jxcore-log( 5635): 2016-01-15T18:52:45.976Z SendDataConnector.js: do connect now
I/jxcore-log( 5635): 
,I/io.jxcore.node.ConnectionHelper( 5635): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnecting: G4-1 F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 5635): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 990)
,D/BluetoothUtils( 5635): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5635): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,D/BluetoothSocket( 5635): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45cc7f4 rs_disc_pending=1
,W/bt-btif ( 2608): bta_dm_check_av:0
,W/bt-btif ( 2608): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2608): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,E/SMD     (  297): DCD OFF
,E/Watchdog( 1017): !@Sync 18
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged,
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF
,E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45ccd40 rs_disc_pending=1
,E/bt-btif ( 2608): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 2608): Reset sec_bd_name and name flag. (BR/EDR link)
W/bt-btif ( 2608): invalid rfc slot id: 12
,E/bt-btm  ( 2608): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2608): bta_dm_check_av:0
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2608): db_query_execute: result 1
,W/bt-btif ( 2608): btif_dm_cback : unhandled event (14)
,D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@33c4a97, channel: -1, state: INIT
D/BluetoothSocket( 5635): close() this: android.bluetooth.BluetoothSocket@33c4a97, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@72ff484, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e03846dmSocket: android.net.LocalSocket@2326c8a2 impl:android.net.LocalSocketImpl@17f0f933 fd:FileDescriptor[113]
D/BluetoothSocket( 5635): Closing mSocket: android.net.LocalSocket@2326c8a2 impl:android.net.LocalSocketImpl@17f0f933 fd:FileDescriptor[113]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 990)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Maximum number of allowed retries (0) reached, giving up... (thread ID: 990)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Exiting thread (thread ID: 990)
,I/jxcore-log( 5635): 2016-01-15T18:52:50.235Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771] failed
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:50.235Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771] failed
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:50.237Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5635): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/KeyguardViewMediator( 1174): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): shutdown (thread ID: 990)
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@33c4a97, channel: -1, state: CLOSED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1305): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1174): isGear1: device is not B1!
,D/BluetoothAdapterService( 2608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2d2fc7
,D/BtConfig.SecureMode( 2608): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothPbapService( 2608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 3214): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3214): Bluetooth Device Name: G4-1
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2608): db_query_execute: result 1
W/bt-btif ( 2608): info:x10
D/        ( 2608): remote version info [08:ec:a9:50:75:41]: 7, f, 6109
,E/BluetoothRemoteDevices( 2608): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btm  ( 2608): tBTM_SEC_DEV:0xa45cc7f4 rs_disc_pending=1
,E/bt-btm  ( 2608): Reset sec_bd_name and name flag. (BR/EDR link)
E/bt-btm  ( 2608): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2608): bta_dm_check_av:0
,W/bt-btif ( 2608): btif_dm_cback : unhandled event (14)
,D/KeyguardViewMediator( 1174): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.ACL_DISCONNECTED,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/BluetoothEventManager( 1305): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1174): isGear1: device is not B1!
,D/BluetoothAdapterService( 2608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2d2fc7
,D/BtConfig.SecureMode( 2608): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 3214): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3214): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2608): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 2608): isSecureModeOn:false
E/bt-btif ( 2608): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2608): Entering PendingCommandState State
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
,D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5683): jangil::setProperties()
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0001::false
D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0002::false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/GMFPReceiver( 5683): onServiceConnected() : 1
D/GMFPReceiver( 5683): mBluetoothHeadset = true
,D/btif_config_util( 2608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2608): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2608): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2608): Failed to remove device: 08:EC:A9:50:75:41
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
I/BluetoothBondStateMachine( 2608): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/BluetoothTile( 1174):  handleUpdatestate:false name:null
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/HidService( 2608): getHidService(): returning com.android.bluetooth.hid.HidService@236e1a1
,D/SettingsProvider( 1017): name = bluetooth_input_device_priority_08:EC:A9:50:75:41
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/HidService( 2608): Saved priority 08:EC:A9:50:75:41 = -1
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_08:EC:A9:50:75:41
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_08:EC:A9:50:75:41
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/BluetoothBondStateMachine( 2608): StableState(): Entering Off State
D/KeyguardViewMediator( 1174): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1305): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1174): isGear1: device is not B1!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
,D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5683): jangil::setProperties()
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0001::false
D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5683): ::::::::Wearable0002::false
,D/GMFPReceiver( 5683): onServiceConnected() : 1
D/GMFPReceiver( 5683): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2d2fc7
,D/BtConfig.SecureMode( 2608): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 3214): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3214): Bluetooth Device Name: S5-1
,W/bt-btif ( 2608): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2608): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2608): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket( 5635): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@df9d4f0
,E/BluetoothRemoteDevices( 2608): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Incoming connection initialized (thread ID: 992)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Entering thread (ID: 992)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): onBytesRead: Read 83 bytes successfully (thread ID: 992)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): onBytesWritten: 83 bytes successfully written (thread ID: 992)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): removeThreadFromList: Removing thread with ID 992
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Handshake thread disposed (thread ID: 992)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Exiting thread (ID: 992),
,I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], created successfully
D/io.jxcore.node.ConnectionHelper( 5635): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 5635): Entering thread (ID: 993)
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10167
,I/io.jxcore.node.IncomingSocketThread( 5635): Local host address: localhost/127.0.0.1, port: 46977
D/io.jxcore.node.IncomingSocketThread( 5635): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 5635): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 5635): Exiting thread (ID: 993)
I/jxcore-log( 5635): 2016-01-15T18:52:52.167Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 5635): ,
D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 995, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 994, name: Sender)
,I/jxcore-log( 5635): 2016-01-15T18:52:52.994Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.002Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.006Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.009Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.014Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.017Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.052Z SendDataTCPServer.js: TCP/IP server has received 20240 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.078Z SendDataTCPServer.js: TCP/IP server has received 22264 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.112Z SendDataTCPServer.js: TCP/IP server has received 24288 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.122Z SendDataTCPServer.js: TCP/IP server has received 26312 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.126Z SendDataTCPServer.js: TCP/IP server has received 28336 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.129Z SendDataTCPServer.js: TCP/IP server has received 30360 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.134Z SendDataTCPServer.js: TCP/IP server has received 32384 bytes of data
I/jxcore-log( 5635): 
,E/SMD     (  297): DCD OFF
,I/jxcore-log( 5635): 2016-01-15T18:52:53.173Z SendDataTCPServer.js: TCP/IP server has received 52624 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.179Z SendDataTCPServer.js: TCP/IP server has received 56672 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.212Z SendDataTCPServer.js: TCP/IP server has received 62744 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.275Z SendDataTCPServer.js: TCP/IP server has received 64768 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.313Z SendDataTCPServer.js: TCP/IP server has received 74888 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.316Z SendDataTCPServer.js: TCP/IP server has received 76912 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.322Z SendDataTCPServer.js: TCP/IP server has received 78936 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.352Z SendDataTCPServer.js: TCP/IP server has received 89056 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.424Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:53.462Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 5635): 
,W/bt-btif ( 2608): invalid rfc slot id: 11
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 995, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 5635): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 993
D/io.jxcore.node.IncomingSocketThread( 5635): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 995
,D/io.jxcore.node.IncomingSocketThread( 5635): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 994
,D/io.jxcore.node.IncomingSocketThread( 5635): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 994, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 5635): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 5635): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 5635): closeBluetoothSocketAndStreams
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@33e0fa69, channel: 6, state: CONNECTED
D/BluetoothSocket( 5635): close() this: android.bluetooth.BluetoothSocket@33e0fa69, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@394cccee, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3a37f58fmSocket: android.net.LocalSocket@123f501c impl:android.net.LocalSocketImpl@2105d425 fd:FileDescriptor[111]
D/BluetoothSocket( 5635): Closing mSocket: android.net.LocalSocket@123f501c impl:android.net.LocalSocketImpl@2105d425 fd:FileDescriptor[111]
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@33e0fa69, channel: 6, state: CLOSED
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@33e0fa69, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 995, name: Receiver)
,W/bt-rfcomm( 2608): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 2608): RFCOMM_DisconnectInd LCID:0x4d
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 994, name: Sender)
I/jxcore-log( 5635): 2016-01-15T18:52:53.504Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 5635): 
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,I/jxcore-log( 5635): 2016-01-15T18:52:55.238Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:52:55.239Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 5635): 
,E/SMD     (  297): DCD OFF
,E/bt-btm  ( 2608): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2608): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1174): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1305): ACTION_ACL_DISCONNECTED
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2d2fc7
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/KeyguardViewMediator( 1174): isGear1: device is not B1!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 3214): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3214): Bluetooth Device Name: A3-1
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,D/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:3C:51), either no such connection or failed to close the connection
,I/jxcore-log( 5635): 2016-01-15T18:53:00.243Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:00.244Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 5635): 
I/jxcore-log( 5635): 2016-01-15T18:53:00.245Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:00.245Z SendDataConnector.js: do connect now
I/jxcore-log( 5635): 
,I/io.jxcore.node.ConnectionHelper( 5635): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnecting: G4-1 F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 5635): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 996)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 5635): createBluetoothSocketToServiceRecord: Socket created with channel/port 1,
W/BluetoothAdapter( 5635): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 2608): db_query_execute: result 1
D/BluetoothSocket( 5635): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,E/SMD     (  297): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  297): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 1386): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): P2P device discovery started successfully,
D/WifiP2pService( 1017): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: STARTED,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/Atfwd_Daemon(  331): Stop the daemon....,
,E/SMD     (  297): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnectionTimeout: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771],
I/jxcore-log( 5635): 2016-01-15T18:53:15.252Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771] timed out
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:15.253Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771] timed out
I/jxcore-log( 5635): 
I/jxcore-log( 5635): 2016-01-15T18:53:15.254Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5635): 
,E/SMD     (  297): DCD OFF
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 },
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
,D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07,
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1017): P2pEnabledState add service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): restart: Restarting...
D/WifiP2pManager( 5635): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service request added successfully
,E/Watchdog( 1017): !@Sync 19,
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc,
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13],
I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service discovery started successfully,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/SViewCoverView( 1174): level :100 plugged : 2
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  297): DCD OFF
,I/jxcore-log( 5635): 2016-01-15T18:53:20.254Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:20.255Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 5635): 
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,D/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:3C:51), either no such connection or failed to close the connection
,I/jxcore-log( 5635): 2016-01-15T18:53:25.259Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:25.260Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:25.261Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:25.262Z SendDataConnector.js: do connect now
I/jxcore-log( 5635): 
,I/io.jxcore.node.ConnectionHelper( 5635): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): setInsecureRfcommSocketPort: Using port 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnecting: G4-1 F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 5635): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 998)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 5635): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 5635): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 5635): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[114]}
,E/SMD     (  297): DCD OFF,
,E/SMD     (  297): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 525s ago
,I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=2608, ws=null) (elapsedTime=29080)
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,W/bt-sdp  ( 2608): SDP - Rcvd conn cnf with error: 0x8  CID 0x4e
,E/bt-btif ( 2608): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@fbcc9fa, channel: 1, state: INIT
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 7:24841
W/bt-btif ( 2608): invalid rfc slot id: 14
D/BluetoothSocket( 5635): close() this: android.bluetooth.BluetoothSocket@fbcc9fa, channel: 1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a485bab, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1dff5208mSocket: android.net.LocalSocket@ae48da1 impl:android.net.LocalSocketImpl@31fd8bc6 fd:FileDescriptor[113]
D/BluetoothSocket( 5635): Closing mSocket: android.net.LocalSocket@ae48da1 impl:android.net.LocalSocketImpl@31fd8bc6 fd:FileDescriptor[113]
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@fbcc9fa, channel: 1, state: CLOSED
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2608): db_query_execute: result 1
,D/BluetoothUtils( 5635): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5635): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 5635): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2608): db_query_execute: result 1
,W/bt-btif ( 2608): info:x10
,D/        ( 2608): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,D/KeyguardViewMediator( 1174): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_CONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/KeyguardViewMediator( 1174): isGear1: device is not B1!
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 3214): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,W/bt-sdp  ( 2608): process_service_search_attr_rsp
,I/BluetoothClassifier( 3214): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 2608): process_service_search_attr_rsp
,E/bt-rfcomm( 2608): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:1
,E/bt-btif ( 2608): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2608): invalid rfc slot id: 16
,D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@2aaf0787, channel: 7, state: INIT
,D/BluetoothSocket( 5635): close() this: android.bluetooth.BluetoothSocket@2aaf0787, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a3b86b4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@319b62ddmSocket: android.net.LocalSocket@b369e52 impl:android.net.LocalSocketImpl@2fea9523 fd:FileDescriptor[113]
,D/BluetoothSocket( 5635): Closing mSocket: android.net.LocalSocket@b369e52 impl:android.net.LocalSocketImpl@2fea9523 fd:FileDescriptor[113]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): shutdown (thread ID: 996)
,D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@2aaf0787, channel: 7, state: CLOSED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Exiting thread (thread ID: 996)
,E/SMD     (  297): DCD OFF,
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1,
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote,
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btif ( 2608): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2608): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
I/BluetoothBondStateMachine( 2608): Entering PendingCommandState State
V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.CLASS_CHANGED
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
,D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5683): jangil::setProperties()
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0002::false
D/GMFPReceiver( 5683): onServiceConnected() : 1
D/GMFPReceiver( 5683): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2608): Failed to remove device: F8:95:C7:87:3C:51
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
I/BluetoothBondStateMachine( 2608): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/HidService( 2608): getHidService(): returning com.android.bluetooth.hid.HidService@236e1a1
,D/SettingsProvider( 1017): name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/HidService( 2608): Saved priority F8:95:C7:87:3C:51 = -1
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_F8:95:C7:87:3C:51,
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,I/BluetoothBondStateMachine( 2608): StableState(): Entering Off State
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
,D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5683): jangil::setProperties()
,W/bt-btif ( 2608): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2608): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2608): bta_dm_pm_ssr:2, lat:1200
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,E/BluetoothRemoteDevices( 2608): setRfcommConnected true
,D/SettingsProvider( 1017): name = Wearable0001
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0002::false
,D/GMFPReceiver( 5683): onServiceConnected() : 1
D/GMFPReceiver( 5683): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onSocketConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 998)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): onBytesWritten: 83 bytes successfully written (thread ID: 999)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Outgoing connection initialized (*handshake* thread ID: 999)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Exiting thread (thread ID: 998)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Entering thread (ID: 999)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): onBytesRead: Read 77 bytes successfully (thread ID: 999)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onHandshakeSucceeded: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
,I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Outgoing connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
,W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Exiting thread (ID: 999)
,I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 5635): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 5635): Entering thread (ID: 1000)
,D/io.jxcore.node.OutgoingSocketThread( 5635): Server socket local port: 40025
I/io.jxcore.node.OutgoingSocketThread( 5635): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 5635): onListeningForIncomingConnections: Outgoing connection is using port 40025 (peer ID: F8:95:C7:87:3C:51)
,I/jxcore-log( 5635): 2016-01-15T18:53:32.799Z SendDataConnector.js: CLIENT connected to 40025, error: null
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:32.800Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:32.804Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 5635): 
,I/io.jxcore.node.OutgoingSocketThread( 5635): Incoming data from address: /127.0.0.1, port: 40025
,D/io.jxcore.node.OutgoingSocketThread( 5635): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
,D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 1001, name: Sender),
,I/io.jxcore.node.OutgoingSocketThread( 5635): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 5635): Exiting thread (ID: 1000)
,D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 1002, name: Receiver)
,I/jxcore-log( 5635): 2016-01-15T18:53:33.374Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:33.399Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:33.437Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:33.474Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:33.481Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:33.560Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:33.564Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:33.595Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:33.632Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:33.635Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:33.636Z SendDataConnector.js: got all data for this round
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): oneRoundDownNow
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:33.638Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:33.639Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5635): 
,D/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
,I/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 5635): close
,D/io.jxcore.node.OutgoingSocketThread( 5635): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 1002
,D/io.jxcore.node.OutgoingSocketThread( 5635): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 1001
D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 1001, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 5635): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 5635): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@1c645a20, channel: 7, state: CONNECTED
,D/BluetoothSocket( 5635): close() this: android.bluetooth.BluetoothSocket@1c645a20, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ef04fd9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1f7c4d9emSocket: android.net.LocalSocket@2dc7607f impl:android.net.LocalSocketImpl@1e84f84c fd:FileDescriptor[114]
D/BluetoothSocket( 5635): Closing mSocket: android.net.LocalSocket@2dc7607f impl:android.net.LocalSocketImpl@1e84f84c fd:FileDescriptor[114]
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 1002, thread name: Receiver): bt socket closed, read return: -1,
E/io.jxcore.node.OutgoingSocketThread( 5635): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@1c645a20, channel: 7, state: CLOSED
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@1c645a20, channel: 7, state: CLOSED
,D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
,I/jxcore-log( 5635): 2016-01-15T18:53:33.652Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): ---- round done--------,
I/jxcore-log( 5635): 
I/jxcore-log( 5635): startWithNextDevice
I/jxcore-log( 5635): 
E/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 1002, name: Receiver)
E/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 1001, name: Sender)
,W/bt-btif ( 2608): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND,
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  297): DCD OFF
,E/bt-btm  ( 2608): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2608): btm_sec_disconnected - Clearing Pending flag
D/KeyguardViewMediator( 1174): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive,
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1305): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1174): isGear1: device is not B1!
,D/BluetoothAdapterService( 2608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2d2fc7
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 3214): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3214): Bluetooth Device Name: G4-1
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  297): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  297): DCD OFF
,E/Watchdog( 1017): !@Sync 20
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: RESTARTING
D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 1386): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  297): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  297): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): P2P device discovery started successfully
D/WifiP2pService( 1017): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  297): DCD OFF
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): restart: Restarting...
,D/WifiP2pManager( 5635): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service request added successfully
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service discovery started successfully
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3965","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1017): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 5635): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] is available
,I/jxcore-log( 5635): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT3965","peerAvailable":true}]
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): Found peer : LGE-LG-D722_PT3965, Available: true
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): startWithNextDevice
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): device[5]: F8:95:C7:87:85:54
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:58.236Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:58.236Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 5635): 
I/jxcore-log( 5635): 2016-01-15T18:53:58.237Z SendDataConnector.js: do connect now
,I/jxcore-log( 5635): 
I/io.jxcore.node.ConnectionHelper( 5635): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): connect: Trying to start connecting to null in address F8:95:C7:87:85:54,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 5635): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 1003)
,D/BluetoothUtils( 5635): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5635): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54,
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2608): db_query_execute: result 1
,D/BluetoothSocket( 5635): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] already in the list, will not add again
,I/jxcore-log( 5635): timeout now,
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): weAreDoneNow, resultArray.length: 4
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): sendReportNow
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): done, now sending data to server
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:53:58.353Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 5635): 
,D/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
,D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
,I/jxcore-log( 5635): 2016-01-15T18:53:58.358Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 5635): 
,D/IOP_DB_BT( 2608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2608): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 2608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2608): db_query_execute: result 1
,W/bt-btif ( 2608): info:x10
,D/        ( 2608): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2608): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 2608): process_service_search_attr_rsp
,E/SMD     (  297): DCD OFF
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
I/BluetoothBondStateMachine( 2608): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 2608): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
I/BluetoothBondStateMachine( 2608): Entering PendingCommandState State
D/BluetoothTile( 1174):  handleUpdatestate:false name:null
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
E/bt-btif ( 2608): check_cod: remote_cod = 0x5a020c
V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
,D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5683): jangil::setProperties()
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0002::false
,D/GMFPReceiver( 5683): onServiceConnected() : 1
D/GMFPReceiver( 5683): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/btif_config_util( 2608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2608): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2608): Failed to remove device: F8:95:C7:87:85:54
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
I/BluetoothBondStateMachine( 2608): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/HidService( 2608): getHidService(): returning com.android.bluetooth.hid.HidService@236e1a1
,D/SettingsProvider( 1017): name = bluetooth_input_device_priority_F8:95:C7:87:85:54
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/HidService( 2608): Saved priority F8:95:C7:87:85:54 = -1
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_F8:95:C7:87:85:54
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
D/SettingsProvider( 1017): ret = -1
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_F8:95:C7:87:85:54
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/BluetoothBondStateMachine( 2608): StableState(): Entering Off State
,E/BluetoothHeadset( 5683): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5683): BluetoothHeadset service is binded
,D/GMFPReceiver( 5683): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5683): jangil::setProperties()
,D/GMFPReceiver( 5683): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5683): ::::::::Wearable0002::false
,D/GMFPReceiver( 5683): onServiceConnected() : 1
D/GMFPReceiver( 5683): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryMan,ager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
,D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254] already in the list, will not add again
,W/bt-btif ( 2608): new conn_srvc id:26, app_id:1,
W/bt-btif ( 2608): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2608): bta_dm_pm_ssr:2, lat:1200,
E/BluetoothRemoteDevices( 2608): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onSocketConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1003)
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): onBytesWritten: 83 bytes successfully written (thread ID: 1004)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Outgoing connection initialized (*handshake* thread ID: 1004)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Exiting thread (thread ID: 1003)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Entering thread (ID: 1004)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): onBytesRead: Read 77 bytes successfully (thread ID: 1004)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5635): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onHandshakeSucceeded: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 5635): Exiting thread (ID: 1004)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
D/io.jxcore.node.ConnectionHelper( 5635): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 5635): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 5635): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 5635): Entering thread (ID: 1005)
,D/io.jxcore.node.OutgoingSocketThread( 5635): Server socket local port: 53531
,I/io.jxcore.node.OutgoingSocketThread( 5635): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 5635): onListeningForIncomingConnections: Outgoing connection is using port 53531 (peer ID: F8:95:C7:87:85:54)
,I/jxcore-log( 5635): 2016-01-15T18:54:00.741Z SendDataConnector.js: CLIENT connected to 53531, error: null
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:54:00.742Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:54:00.745Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 5635): 
,I/io.jxcore.node.OutgoingSocketThread( 5635): Incoming data from address: /127.0.0.1, port: 53531
D/io.jxcore.node.OutgoingSocketThread( 5635): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 5635): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 5635): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 5635): Exiting thread (ID: 1005)
,D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 1006, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 5635): Entering thread (ID: 1007, name: Receiver)
,I/jxcore-log( 5635): 2016-01-15T18:54:01.209Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:54:01.259Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:54:01.263Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 5635): 
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 },
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,I/jxcore-log( 5635): 2016-01-15T18:54:01.306Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 5635): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/jxcore-log( 5635): 2016-01-15T18:54:01.336Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:54:01.355Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:54:01.400Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:54:01.404Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:54:01.450Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:54:01.486Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:54:01.487Z SendDataConnector.js: got all data for this round
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): oneRoundDownNow
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:54:01.495Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:54:01.496Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5635): 
,D/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
,I/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
,I/io.jxcore.node.OutgoingSocketThread( 5635): close
D/io.jxcore.node.OutgoingSocketThread( 5635): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 1007
D/io.jxcore.node.OutgoingSocketThread( 5635): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 5635): doStop: Thread ID: 1006
D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 5635): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 5635): closeBluetoothSocketAndStreams
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@190d1095, channel: 8, state: CONNECTED
D/BluetoothSocket( 5635): close() this: android.bluetooth.BluetoothSocket@190d1095, channel: 8, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ddba5aa, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e7b859bmSocket: android.net.LocalSocket@e2f4d38 impl:android.net.LocalSocketImpl@24fb2111 fd:FileDescriptor[113]
D/BluetoothSocket( 5635): Closing mSocket: android.net.LocalSocket@e2f4d38 impl:android.net.LocalSocketImpl@24fb2111 fd:FileDescriptor[113]
,D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@190d1095, channel: 8, state: CLOSED
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@190d1095, channel: 8, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 5635): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 1006, thread name: Sender): Socket closed
I/jxcore-log( 5635): 2016-01-15T18:54:01.503Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 5635): 
,E/io.jxcore.node.OutgoingSocketThread( 5635): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
E/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 1006, name: Sender)
,W/io.jxcore.node.StreamCopyingThread( 5635): Either failed to read from the output stream or write to the input stream (thread ID: 1007, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 5635): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 5635): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
E/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
,D/io.jxcore.node.ConnectionHelper( 5635): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 5635): Exiting thread (ID: 1007, name: Receiver)
,W/bt-btif ( 2608): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,E/SMD     (  297): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1017): SIOP:: AP = 270,
,E/SMD     (  297): DCD OFF
,E/bt-btm  ( 2608): Reset sec_bd_name and name flag. (BR/EDR link),
E/bt-btm  ( 2608): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1174): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1305): ACTION_ACL_DISCONNECTED,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/KeyguardViewMediator( 1174): isGear1: device is not B1!
,D/BluetoothAdapterService( 2608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2d2fc7
D/BtConfig.SecureMode( 2608): isSecureModeOn:false
D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 3214): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3214): Bluetooth Device Name: G3s-1
,E/SMD     (  297): DCD OFF
,I/ActivityManager( 1017): Killing 5196:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): restart: Restarting...
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 5635): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service request added successfully
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,W/libprocessgroup( 1017): failed to open /acct/uid_10029/pid_5196/cgroup.procs: No such file or directory,
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1386): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 1386): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service discovery started successfully
,I/wpa_supplicant( 1386): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1386): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/io.jxcore.node.ConnectionHelper( 5635): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 5635): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] already in the list, will not add again
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2608): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  297): DCD OFF
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 }
I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  297): DCD OFF
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  297): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,I/wpa_supplicant( 1386): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 },
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): onP2pDeviceListChanged: 12 device(s) discovered
,D/WifiDisplayController( 1017):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/jxcore-log( 5635): teardown
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): testSendData stopped
I/jxcore-log( 5635): 
,I/io.jxcore.node.ConnectionHelper( 5635): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): shutdown
D/BluetoothSocket( 5635): close() in, this: android.bluetooth.BluetoothSocket@27267276, channel: 6, state: LISTENING
D/BluetoothSocket( 5635): close() this: android.bluetooth.BluetoothSocket@27267276, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19df05db, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1f82e077mSocket: android.net.LocalSocket@1e2804e4 impl:android.net.LocalSocketImpl@34dfbd4d fd:FileDescriptor[112]
D/BluetoothSocket( 5635): Closing mSocket: android.net.LocalSocket@1e2804e4 impl:android.net.LocalSocketImpl@34dfbd4d fd:FileDescriptor[112]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5635): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5635): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5635): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5635): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5635): stop: Stopping services
,D/WifiP2pService( 1017): InactiveState{ what=139298 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
D/WifiP2pService( 1017): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): onIsWifiPeerDiscoveryStartedChanged: false,
D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5635): release: No more listeners, de-initializing...
I/wpa_supplicant( 1386): P2P-FIND-STOPPED 
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5635): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5635): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5635): setState: NOT_STARTED,
I/jxcore-log( 5635): StopBroadcasting went ok
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): 2016-01-15T18:54:17.779Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 5635): ,
I/io.jxcore.node.ConnectionHelper( 5635): onConnectionManagerStateChanged: NOT_STARTED,
D/WifiP2pService( 1017): InactiveState{ what=147493 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5635): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 5635): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5635): P2P device discovery stopped successfully
,I/chromium( 5635): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 },
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/WifiP2pService( 1017): remove channel information from framework
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5635): Service requests cleared successfully
,I/jxcore-log( 5635): ****TEST TOOK:  ms ****
I/jxcore-log( 5635): 
,I/jxcore-log( 5635): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5635): 
,D/AndroidRuntime( 6405): ,
D/AndroidRuntime( 6405): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6405): CheckJNI is OFF,
D/AndroidRuntime( 6405): readGMSProperty: start
,D/AndroidRuntime( 6405): readGMSProperty: already setted!!
D/AndroidRuntime( 6405): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6405): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6405): readGMSProperty: end
D/AndroidRuntime( 6405): addProductProperty: start
,E/Watchdog( 1017): !@Sync 21,
,E/AffinityControl( 6405): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6405): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1017): START PACKAGE DELETE: observer{425315843}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER,
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1017): !@killApplicatoin: 10167, uninstall pkg,
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 5635:com.test.thalitest/u0a167 (adj 0): stop com.test.thalitest cause uninstall pkg
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{3d16d457 u0 com.test.thalitest/.MainActivity t8}
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,W/InputDispatcher( 1017): channel ~ Consumer closed input channel or an error occurred.  events=0x9,
E/InputDispatcher( 1017): channel ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher( 1017): Attempted to unregister already unregistered input channel
,I/WindowState( 1017): WIN DEATH: Window{3a250de6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  259): id=14 Removed NainActivit (6/8)
I/SurfaceFlinger(  259): id=14 Removed NainActivit (-2/8)
,I/SurfaceFlinger(  259): id=14 Removed NainActivit (-2/8),
D/InputDispatcher( 1017): Focus left window: 5635
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{3d16d457 u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager( 1017): Duplicate finish request for ActivityRecord{3d16d457 u0 com.test.thalitest/.MainActivity t8 f}
,I/art     ( 3214): Explicit concurrent mark sweep GC freed 8362(359KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 5MB/7MB, paused 911us total 27.138ms
,I/art     ( 3895): Explicit concurrent mark sweep GC freed 3117(187KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 772us total 27.879ms
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,D/InputDispatcher( 1017): Focused application released
,I/DBG_DM  ( 3111): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3111): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 9
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1823): mOCRHelper is null
,I/DBG_DM  ( 3111): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,W/GeofencerStateMachine( 1798): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 3111): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3111): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 9
,W/SQLiteConnectionPool( 2016): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/DBG_DM  ( 3111): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/art     ( 2016): Explicit concurrent mark sweep GC freed 4597(246KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 10MB/14MB, paused 2.522ms total 82.195ms
,W/ResourcesManager( 1445): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3111): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3111): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/KLMS-2.5.123: ( 3581): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 19:54:18 GMT+01:00 2016
I/DBG_DM  ( 3111): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3581): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1017): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=30, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 1 receivers.size=39
,I/splitIntent( 1017): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6418 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 6418): MountEmulatedStorage()
E/Zygote  ( 6418): v2
I/libpersona( 6418): KNOX_SDCARD checking this for 10090
I/libpersona( 6418): KNOX_SDCARD not a persona
,I/SELinux ( 6418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6418): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/KLMS-2.5.123: ( 3581): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3581): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/DBG_DM  ( 3111): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 9
,I/DBG_DM  ( 3111): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,E/Zygote  ( 6433): MountEmulatedStorage()
E/Zygote  ( 6433): v2
I/libpersona( 6433): KNOX_SDCARD checking this for 10041
I/libpersona( 6433): KNOX_SDCARD not a persona
,I/SELinux ( 6433): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6433): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/KLMS-2.5.123: ( 3581): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/SELinux ( 6433): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6433 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/DBG_DM  ( 3111): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/KLMS-2.5.123: ( 3581): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/DBG_DM  ( 3111): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,D/TimaKeyStoreProvider( 6418): TimaSignature is unavailable
I/DBG_DM  ( 3111): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] ,
D/ActivityThread( 6418): Added TimaKeyStore provider
,I/DBG_DM  ( 3111): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 61202(6MB) AllocSpace objects, 50(800KB) LOS objects, 33% free, 23MB/35MB, paused 11.631ms total 234.070ms
,I/art     ( 1017): WaitForGcToComplete blocked for 215.452ms for cause Explicit
,D/TimaKeyStoreProvider( 6433): TimaSignature is unavailable
,D/ActivityThread( 6433): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3581): KLMSIntentService(): PACKAGE_REMOVED
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3581): KLMSIntentService(): listeningToPackageRemoved().START
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.123: ( 3581): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,E/Zygote  ( 6448): MountEmulatedStorage()
,E/Zygote  ( 6448): v2
I/libpersona( 6448): KNOX_SDCARD checking this for 10145
I/libpersona( 6448): KNOX_SDCARD not a persona
,I/SELinux ( 6448): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6448 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6448): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6448): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/RegisteredServicesCache( 1435): empty dynamic service
I/DBG_DM  ( 3111): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/SurfaceFlinger(  259): id=16 createSurf (540x960),1 flag=404, YUIInstallC
,D/FilterInstaller( 5665): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
W/ContextImpl( 5665): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1017): Focus entered window: 3111
,D/TimaKeyStoreProvider( 6448): TimaSignature is unavailable
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/SRIB_DCS( 3111): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/ActivityThread( 6448): Added TimaKeyStore provider
,W/ResourcesManager( 6433): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6433): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6433): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6433): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6433): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 5635 uid 10167
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,D/RCPManagerService( 1017): PackageReceiver onReceive()
,I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/FilterInstaller( 5665): FilterPackageService : ACTION_PACKAGE_REMOVED
,I/FilterInstaller( 5665): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5665): before removeFromFS
,V/ActivityThread( 3111): updateVisibility : ActivityRecord{1cb57ab8 token=android.os.BinderProxy@27d89e4e {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,I/Timeline( 3111): Timeline: Activity_idle id: android.os.BinderProxy@27d89e4e time:648340
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED,
,D/elm:15121( 6418): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6418): ELMEngine.ELMEngine( context ).
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:15121( 6418): MDMBridge.setEnterpriseBridge()
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3581): KLMSIntentService(): listeningToPackageRemoved().END
,E/Zygote  ( 6466): MountEmulatedStorage()
E/Zygote  ( 6466): v2
I/libpersona( 6466): KNOX_SDCARD checking this for 10095
I/libpersona( 6466): KNOX_SDCARD not a persona
,I/SELinux ( 6466): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6466): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6466): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6466 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,D/SamsungIME( 1823): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3581): KLMSIntentService(): onDestroy()
,E/Zygote  ( 6479): MountEmulatedStorage(),
I/libpersona( 6479): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6479): v2,
I/libpersona( 6479): KNOX_SDCARD not a persona
I/SELinux ( 6479): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6479): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6479 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
E/SELinux ( 6479): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:15121( 6418): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.,
W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{1b8770f9 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t7} time:648422,
,D/elm:15121( 6418): ElmAgentService : onCreate()
,D/Mms/MmsApp( 6433): [start]    onCreate() consume time = 0.0
,D/elm:15121( 6418): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/TimaKeyStoreProvider( 6466): TimaSignature is unavailable
,D/elm:15121( 6418): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6418): MDMBridge.getInstance()
D/elm:15121( 6418): MDMBridge.getAllLicenseInfoFromSDK()
D/ActivityThread( 6466): Added TimaKeyStore provider
,D/elm:15121( 6418): MDMBridge.getAllLicenseInfoFromSDK()
,D/TimaKeyStoreProvider( 6479): TimaSignature is unavailable
,D/ActivityThread( 6479): Added TimaKeyStore provider
,D/ThemeInfoUtil( 6448): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6448): isCurrentFestival = false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5778): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5778): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 5778): Clear T&P info.
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5778): Widget is not attached.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 14983(839KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.297ms total 297.622ms
,D/elm:15121( 6418): ElmAgentService : onDestroy().
,D/PackageBroadcastService( 2016): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2016): Clearing selected account for com.test.thalitest
,D/PreloadFilterInstaller( 6466): uses FILTER_DB_VER_1
,E/SQLiteLog( 6466): (284) automatic index on titles(filter_id)
,W/ContextImpl( 6479): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 6466): (284) automatic index on titles(filter_id)
,E/Zygote  ( 6504): MountEmulatedStorage()
E/Zygote  ( 6504): v2
I/libpersona( 6504): KNOX_SDCARD checking this for 1000
I/libpersona( 6504): KNOX_SDCARD not a persona
I/SELinux ( 6504): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6504): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6504): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6504 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 20.297ms
,D/TimaKeyStoreProvider( 6504): TimaSignature is unavailable
,W/art     ( 6433): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 160.681ms
,D/ActivityThread( 6504): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageManager( 1017): delete codoeFile: 
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10167, packageName = com.test.thalitest
,I/LocationSettingsChecker( 2016): Removing dialog suppression flag for package com.test.thalitest
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 17.498ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 5542:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 16.955ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2016): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2016): Module APK com.google.android.play.games already loaded
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,I/AASA_removePackage( 1017): UID=10167 Target=com.test.thalitest
D/PackageManager( 1017): result of delete: 1{425315843}
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/gH_CompatibleDatabase( 2016): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2016): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 2016): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 2016): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2016): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2016): Module APK com.google.android.play.games already loaded
,D/AndroidRuntime( 6405): Shutting down VM
D/AcmsPackageEventListener( 6504): Received: android.intent.action.PACKAGE_REMOVED
,E/NetworkScheduler.SchedulerReceiver( 1798): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1798): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,D/gH_CompatibleDatabase( 2016): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 2016): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 2016): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/ContextImpl( 6504): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/AcmsService( 6504): Enter Oncreate
D/AcmsServiceMonitor( 6504): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6504): creating AcmsCore
,D/AcmsCore( 6504): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6504): AcmsCore
,D/AcmsCore( 6504): init
D/AcmsCore( 6504): Looper handler is not null
D/AcmsCore( 6504): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6504): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6504): Incrementing - Counter value: 1
D/AcmsCore( 6504): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6504): onStartCommand
D/AcmsService( 6504): Action: android.intent.action.PACKAGE_REMOVED
D/AcmsServiceMonitor( 6504): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6504): Incrementing - Counter value: 2
D/AcmsService( 6504): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr( 6504): AcmsCertificateMngr
,D/gH_CompatibleDatabase( 2016): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 2016): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 2016): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 2016): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 2016): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 2016): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/ActivityThread( 6504): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsRevocationMngr( 6504): AcmsRevocationMngr
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6527): MountEmulatedStorage()
,E/Zygote  ( 6527): v2
I/libpersona( 6527): KNOX_SDCARD checking this for 1000
W/art     ( 6433): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 146.561ms,
I/libpersona( 6527): KNOX_SDCARD not a persona
,I/SELinux ( 6527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6527 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 6527): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/TelephonyPermission( 6433): start operation mode monitor
,D/Mms/ArtClassLoader( 6433): init before art
,D/TimaKeyStoreProvider( 6527): TimaSignature is unavailable
,D/ActivityThread( 6527): Added TimaKeyStore provider
,W/ResourcesManager( 6433): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/BaseAppContext( 2016): Using Auth Proxy for data requests.
,D/AcmsService( 6504): Inside handle Intent
D/AcmsService( 6504): App removed - package name: com.test.thalitest
D/AcmsCore( 6504): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6504): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6504): Incrementing - Counter value: 3
D/AcmsCore( 6504): Incremented Counter Value: postToAcmsCoreHandler =>5
D/AcmsService( 6504): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6504): Decrementing - Counter value: 2
,D/Mms/TelephonyPermission( 6433): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 6433): isDefault true
,D/Mms/MmsApp( 6433): onCreate() com.android.mms
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/BaseAppContext( 2016): Using Auth Proxy for data requests.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1017): Killing 4959:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/FilterUnInstaller( 5665): FilterUninstaller.java : removeFromDB()
,D/PopupuiReceiver( 6527): onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,D/SecContentProvider2( 1017): uri = -1 selection = getSealedState
D/SecContentProvider2( 1017): mCursor = null
,I/PopupuiReceiver_KNOX( 6527): getSealedState : true
,D/SecContentProvider2( 1017): uri = 15 selection = getSealedHideNotificationMessages
,D/SecContentProvider2( 1017): mCursor = null
,I/PopupuiReceiver_KNOX( 6527): getSealedHideNotificationMessages : 1
,D/SecContentProvider2( 1017): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2( 1017): mCursor = null
,I/PopupuiReceiver_KNOX( 6527): getCheckCoverPopupState : true
D/PopupuiReceiver( 6527): Action package removed
,D/FilterProvider( 6466): delete when PACKAGE_NAME : 2002 
D/FilterProvider( 6466): packageName : com.test.thalitest
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
,W/ContextImpl( 5665): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters:48 com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage:152 android.os.Handler.dispatchMessage:102 
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10167
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/MmsApp( 6433): [start]    initCountryIso consume time = 460.238437
W/art     ( 6405): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10167
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1017): Killing 5423:com.google.android.gms:car/u0a11 (adj 15): empty #31
,D/UsbSettingsManager( 1017): clearDefaults: com.test.thalitest
,I/GMPM-SVC( 2016): App measurement is starting up, version: 8489
I/GMPM-SVC( 2016): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/CrashAnrDetector( 1017): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1017): failed to open /acct/uid_10048/pid_5542/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4959/cgroup.procs: No such file or directory
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
,D/CountryDetector( 1017): The first listener is added
,I/ActivityManager( 1017): Killing 5907:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,D/Mms/MmsApp( 6433): [end]    initCountryIso consume time = 47.369531
,D/Mms/MmsConfig( 6433): [start]    MmsConfig.init() consume time = 0.535938
,D/Mms/MmsConfig( 6433): before partial update
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=8_task.xml
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=7_task.xml
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PCWCLIENTTRACE_PushUtil( 5510): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5510): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5510): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5510): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/Mms/MmsConfig( 6433): Load Resize quality : 80
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EasySignUpManager_1.0.1( 6433): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 6433): isAuth is false
D/Mms/MmsConfig( 6433): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
,I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/FileUtils( 2016): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 2016): doRemovePackageData com.test.thalitest
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Icing   ( 2016): Failed to open Apps corpus file.
,E/Zygote  ( 6551): MountEmulatedStorage()
,E/Zygote  ( 6551): v2
I/libpersona( 6551): KNOX_SDCARD checking this for 10029
I/libpersona( 6551): KNOX_SDCARD not a persona
,I/SELinux ( 6551): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6551): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6551): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6551 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/Icing   ( 2016): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 2016): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1445): query,matched:2117, calling pid = 6433
,D/TP/MmsSmsProvider( 1445): match 2117:Elapsed time : 1.810 ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/TimaKeyStoreProvider( 6551): TimaSignature is unavailable
,D/ActivityThread( 6551): Added TimaKeyStore provider
,D/EasySignUpManager_1.0.1( 6433): isAuth is false
,D/EasySignUpManager_1.0.1( 6433): getServiceStatus : serviceId (1) is OFF
,E/SQLiteLog( 2016): (28) failed to open "/data/data/com.google.android.gms/databases/google_app_measurement.db" with flag (131138) and mode_t (0) due to error (30)
,E/CscParser( 6433): mps_code.dat does not exist
E/CscParser( 6433): customer_path =/system/csc/customer.xml
E/CscParser( 6433): fileName + /system/csc/customer.xml
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/CscParser( 6433): mps_code.dat does not exist
E/CscParser( 6433): customer_path =/system/csc/customer.xml
E/CscParser( 6433): fileName + /system/csc/customer.xml
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1017): failed to open /acct/uid_10068/pid_5907/cgroup.procs: No such file or directory

```
