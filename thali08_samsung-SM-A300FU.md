#### Test 506502784dae475_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1866): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/DBG_POLICYDM( 4926): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
I/DBG_POLICYDM( 4926): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
I/DBG_POLICYDM( 4926): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 4926): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 4926): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
D/AsyncTaskServiceImpl( 1866): Submit a task: k
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4926): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
D/ChimeraCfgMgr( 1866): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/DBG_POLICYDM( 4926): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
D/ChimeraCfgMgr( 1866): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/DBG_POLICYDM( 4926): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 4926): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 4926): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
W/ActivityManager( 1021): userId = 0, bbcId = -10000
I/DBG_POLICYDM( 4926): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 1866): Using Auth Proxy for data requests.
W/BaseAppContext( 1866): Using Auth Proxy for data requests.
I/DBG_POLICYDM( 4926): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 4926): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 4926): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 4926): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 4926): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/k       ( 1866): Processing package: com.test.thalitest
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 4926): [com.policydm.XSPPReceiver(53/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
--------- beginning of system
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Watchdog( 1021): !@Sync 2
E/Zygote  ( 4966): MountEmulatedStorage()
E/Zygote  ( 4966): v2
I/libpersona( 4966): KNOX_SDCARD checking this for 10036
I/SELinux ( 4966): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4966): KNOX_SDCARD not a persona
I/SELinux ( 4966): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4966): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4966): TimaSignature is unavailable
D/ActivityThread( 4966): Added TimaKeyStore provider
I/ActivityManager( 1021): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=4966 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GassUtils( 1866): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 1866): Found info for package com.test.thalitest in db.
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1021): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=4982 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
W/ActivityManager( 1021): userId = 0, bbcId = -10000
I/libpersona( 4982): KNOX_SDCARD checking this for 10009
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
I/libpersona( 4982): KNOX_SDCARD not a persona
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/Zygote  ( 4982): MountEmulatedStorage()
E/Zygote  ( 4982): v2
I/SELinux ( 4982): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 4982): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4982): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 4926): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     (  304): Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 619us total 37.300ms
D/TimaKeyStoreProvider( 4982): TimaSignature is unavailable
D/ActivityThread( 4982): Added TimaKeyStore provider
I/DBG_POLICYDM( 4926): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 16.760ms
I/DBG_POLICYDM( 4926): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.536ms
E/DBG_POLICYDM( 4926): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 1866): Using Auth Proxy for data requests.
I/ActivityManager( 1021): Killing 4346:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
W/BaseAppContext( 1866): Using Auth Proxy for data requests.
I/UpdateIcingCorporaServi( 2929): UpdateCorporaTask done [took 433 ms] updated apps [took 433 ms] 
W/BaseAppContext( 1866): Using Auth Proxy for data requests.
I/PeopleDatabaseHelper( 1866): cleanUpNonGplusAccounts done.
I/SA      ( 4966): [SSP] onCreated
V/AlarmManager( 1021): waitForAlarm result :4
I/SA      ( 4966): [TPM] There is no property file
I/SA      ( 4966): [SCU] isHaveSA() - false
D/AndroidRuntime( 4964): 
D/AndroidRuntime( 4964): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/Finsky  ( 4615): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/SA      ( 4966): [TPM] getModelProperty : null
I/SA      ( 4966): [TPM] getCSCProperty : null
D/AndroidRuntime( 4964): CheckJNI is OFF
I/SA      ( 4966): [DM] FLOATING AMOLED FEATURE: true
D/AndroidRuntime( 4964): readGMSProperty: start
D/AndroidRuntime( 4964): readGMSProperty: already setted!!
D/AndroidRuntime( 4964): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4964): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4964): readGMSProperty: end
I/SA      ( 4966): [DM] PRODUCT AMOLED FEATURE: false
D/AndroidRuntime( 4964): addProductProperty: start
I/SA      ( 4966): [DM] TFT FEATURE: false
I/SA      ( 4966): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4966): [DM] init START
W/libprocessgroup( 1021): failed to open /acct/uid_10146/pid_4346/cgroup.procs: No such file or directory
I/SA      ( 4966): [DM] This device is not a Vodafone
W/ResourceType( 4966): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 4966): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 4966): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4966): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 4966): [SCU] isHaveSA() - false
I/SA      ( 4966): support phone number id : false
I/SA      ( 4966): [DM] Supports Ref Jpn : true
I/SA      ( 4966): [DM] init END
I/SA      ( 4966): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4966): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10326 extra.user_handle.:0 ]
V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/BaseAppContext( 1866): Using Auth Proxy for data requests.
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1021): Killing 4409:com.sec.android.app.sns3/u0a30 (adj 15): empty #31
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/Finsky  ( 4615): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
W/libprocessgroup( 1021): failed to open /acct/uid_10030/pid_4409/cgroup.procs: No such file or directory
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/AffinityControl( 4964): AffinityControl: registerfunction enter
D/AndroidRuntime( 4964): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1021): inState():  stateMachine is null !!
I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/System.out( 4615): Thread-768(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 4615): Thread-768(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4615): Thread-768(ApacheHTTPLog):isShipBuild true
I/System.out( 4615): Thread-768(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4615): Thread-768(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10026
I/System.out( 4615): Thread-768 calls detatch()
W/ActivityManager( 1021): mDVFSHelper.acquire()
W/Finsky  ( 4615): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/SurfaceFlinger(  257): id=9 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  257): id=10 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1021): Set to : 0
D/PhoneWindow( 1021): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1021): *FMB* installDecor flags : 25362712
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled return false
E/Zygote  ( 5014): MountEmulatedStorage()
E/Zygote  ( 5014): v2
I/libpersona( 5014): KNOX_SDCARD checking this for 10326
I/libpersona( 5014): KNOX_SDCARD not a persona
I/SELinux ( 5014): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SurfaceFlinger(  257): id=11 createSurf (540x960),1 flag=404, uhalitest
I/SELinux ( 5014): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5014): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5014 uid=10326 gids={50326, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 1463
D/AndroidRuntime( 4964): Shutting down VM
V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 5014): TimaSignature is unavailable
D/ActivityThread( 5014): Added TimaKeyStore provider
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
V/WindowManager( 1021): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1021): Display changed displayId=0
D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/ServiceManager(  313): Waiting for service AtCmdFwd...
D/PersonaManager( 1021): isKioskContainerExistOnDevice
I/System.out( 4615): Thread-767(ApacheHTTPLog):isSBSettingEnabled false
D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/System.out( 4615): Thread-767(ApacheHTTPLog):isShipBuild true
I/System.out( 4615): Thread-767(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4615): Thread-767(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4615): Thread-767 calls detatch()
I/SurfaceFlinger(  257): id=7 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=7 Removed Mauncher (-2/9)
V/ActivityThread( 1463): updateVisibility : ActivityRecord{18793d72 token=android.os.BinderProxy@2f470633 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1463): onTrimMemory. Level: 20
W/art     ( 4964): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5030): MountEmulatedStorage(),
E/Zygote  ( 5030): v2
I/libpersona( 5030): KNOX_SDCARD checking this for 10011
I/libpersona( 5030): KNOX_SDCARD not a persona
I/SELinux ( 5030): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1021): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5030 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 5030): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5030): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5030): TimaSignature is unavailable,
D/ActivityThread( 5030): Added TimaKeyStore provider
E/Process ( 1021): Error getting pid for '0'
,W/ResourcesManager( 5030): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5030): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/art     ( 1866): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 277.765ms
,I/System.out( 4615): Thread-768(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4615): Thread-768(ApacheHTTPLog):isShipBuild true
I/System.out( 4615): Thread-768(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4615): Thread-768(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 4615): Thread-768 calls detatch()
,W/Finsky  ( 4615): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/MultiDex( 5030): VM with version 2.1.0 has multidex support
I/MultiDex( 5030): install
I/MultiDex( 5030): VM has multidex support, MultiDex support library is disabled.
,I/WebViewFactory( 5014): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/LibraryLoader( 5014): Loading: webviewchromium
,V/JNIHelp ( 5030): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5030): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 5030): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14468f27: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 5030): Installed default security provider GmsCore_OpenSSL
,I/LibraryLoader( 5014): Time to load native libraries: 86 ms (timestamps 8564-8650),
I/LibraryLoader( 5014): Expected native library version number "",actual native library version number ""
,D/ChimeraCfgMgr( 5030): Reading stored module config
,I/Icing   ( 1866): Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,V/WebViewChromiumFactoryProvider( 5014): Binding Chromium to main looper Looper (main, tid 1) {25df985f}
,I/LibraryLoader( 5014): Expected native library version number "",actual native library version number ""
,I/chromium( 5014): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ChimeraCfgMgr( 5030): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/BrowserStartupController( 5014): Initializing chromium process, renderers=0
W/art     ( 5014): Attempt to remove local handle scope entry from IRT, ignoring
D/ChimeraCfgMgr( 1866): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1866): Module APK com.google.android.play.games already loaded
W/ActivityManager( 1021): Activity pause timeout for ActivityRecord{d918972 u0 com.test.thalitest/.MainActivity t2}
I/Icing   ( 1866): Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
I/Icing   ( 1866): Indexing D2B2F813CD55909B17D100D9886DFA4C4B449F6E from com.google.android.googlequicksearchbox
W/chromium( 5014): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
D/BluetoothAdapter( 5014): 958071468: getState() :  mService = null. Returning STATE_OFF
W/chromium( 5014): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5014): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 5014): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/NativeLibraryUtils( 5030): Install completed successfully. count=14 extracted=0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
I/Adreno-EGL( 5014): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5014): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5014): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5014): Local Branch: 
I/Adreno-EGL( 5014): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5014): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5014):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/GAV2    ( 4837): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5074): MountEmulatedStorage()
E/Zygote  ( 5074): v2
I/libpersona( 5074): KNOX_SDCARD checking this for 1000
I/libpersona( 5074): KNOX_SDCARD not a persona
I/SELinux ( 5074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5074): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Icing   ( 1866): Indexing done D2B2F813CD55909B17D100D9886DFA4C4B449F6E
I/ActivityManager( 1021): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5074 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 5074): TimaSignature is unavailable
D/ActivityThread( 5074): Added TimaKeyStore provider
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/FilterInstaller( 5074): onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
W/ContextImpl( 5074): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/FilterInstaller( 5074): FilterPackageService : ACTION_CHANGED
E/Zygote  ( 5094): MountEmulatedStorage()
I/ActivityManager( 1021): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5094 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/Zygote  ( 5094): v2
I/libpersona( 5094): KNOX_SDCARD checking this for 10098
I/libpersona( 5094): KNOX_SDCARD not a persona
I/SELinux ( 5094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/FilterInstaller( 5074): installFilters
I/SELinux ( 5094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/FilterInstaller( 5074): There is no requred permission
E/SELinux ( 5094): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5094): TimaSignature is unavailable
D/ActivityThread( 5094): Added TimaKeyStore provider
W/chromium( 5014): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 5014): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/PackageIntentReceiver( 5094): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5094): Not GearManger package! 
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5111): MountEmulatedStorage()
E/Zygote  ( 5111): v2
I/libpersona( 5111): KNOX_SDCARD checking this for 1000
I/libpersona( 5111): KNOX_SDCARD not a persona
I/SELinux ( 5111): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5111): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5111): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5111 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1021): Killing 4449:com.sec.spp.push:RemoteDlcProcess/u0a32 (adj 15): empty #31
W/art     ( 5014): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5014): onDetachedFromWindow called when already detached. Ignoring
D/CAR.SERVICE( 5030): Connecting to CarCallService...
D/PhoneWindow( 5014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5014): *FMB* installDecor flags : 8456448
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SystemWebViewEngine( 5014): CordovaWebView is running on device made by: samsung
D/TimaKeyStoreProvider( 5111): TimaSignature is unavailable
D/ActivityThread( 5111): Added TimaKeyStore provider
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     ( 5030): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5030): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/art     ( 5014): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5014): Attempt to remove local handle scope entry from IRT, ignoring
D/CAR.SERVICE( 5030): com.google.android.projection.gearhead isn't installed.
I/ActivityManager( 1021): Killing 4469:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
D/CAR.TEL.Service( 5030): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 5030): Creating a new PhoneAdapter instance
W/ActivityManager( 1021): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5030): setListener: com.google.android.gms.car.dn@2eccec22
W/ActivityManager( 1021): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5030): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5030): Starting CarCallService with initial phone null
E/SMD     (  288): DCD OFF
D/OpenGLRenderer( 5014): Render dirty regions requested: true
D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1021): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5136 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 5136): MountEmulatedStorage()
E/Zygote  ( 5136): v2
V/ActivityThread( 5014): updateVisibility : ActivityRecord{7bbe6ba token=android.os.BinderProxy@263a6edc {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/libpersona( 5136): KNOX_SDCARD checking this for 1000
I/libpersona( 5136): KNOX_SDCARD not a persona
W/libprocessgroup( 1021): failed to open /acct/uid_10032/pid_4449/cgroup.procs: No such file or directory
D/PhoneWindow( 5014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
W/libprocessgroup( 1021): failed to open /acct/uid_10032/pid_4469/cgroup.procs: No such file or directory
D/PhoneWindow( 5014): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 5136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ServiceManager(  313): Waiting for service AtCmdFwd...
I/SELinux ( 5136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5136): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1021): Focus entered window: 5014
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5136): TimaSignature is unavailable
D/ActivityThread( 5136): Added TimaKeyStore provider
I/ActivityManager( 1021): Killing 4487:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
D/SRIB_DCS( 5014): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5014): Initialized EGL, version 1.4
D/OpenGLRenderer( 5014): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5014): Enabling debug mode 0
D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4487/cgroup.procs: No such file or directory
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
D/CAR.SERVICE( 5030): Package validated; name: com.android.vending
D/AcmsPackageEventListener( 5136): Received: android.intent.action.PACKAGE_ADDED
W/IInputConnectionWrapper( 5014): showStatusIcon on inactive InputConnection
I/Timeline( 5014): Timeline: Activity_idle id: android.os.BinderProxy@263a6edc time:79376
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 5136): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
I/ActivityManager( 1021): Displayed Component not be shown by security: +1s153ms (total +1s259ms)
W/ActivityManager( 1021): mDVFSHelper.release()
I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{d918972 u0 com.test.thalitest/.MainActivity t2} time:79429
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/AcmsService( 5136): Enter Oncreate
D/AcmsServiceMonitor( 5136): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5136): creating AcmsCore
D/AcmsCore( 5136): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5136): AcmsCore
I/SurfaceFlinger(  257): id=11 Removed uhalitest (7/9)
I/SurfaceFlinger(  257): id=11 Removed uhalitest (-2/9)
D/AcmsCore( 5136): init
D/AcmsCore( 5136): Looper handler is not null
D/AcmsCore( 5136): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5136): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5136): Incrementing - Counter value: 1
D/AcmsCore( 5136): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 5136): onStartCommand
D/AcmsCertificateMngr( 5136): AcmsCertificateMngr
D/AcmsService( 5136): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5136): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5136): Incrementing - Counter value: 2
D/AcmsService( 5136): Incremented Counter Value : onStartCommand
I/SamsungIME( 1755): getCurrentCandidateView
D/AcmsRevocationMngr( 5136): AcmsRevocationMngr
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5165): MountEmulatedStorage()
E/Zygote  ( 5165): v2
I/libpersona( 5165): KNOX_SDCARD checking this for 10148
I/libpersona( 5165): KNOX_SDCARD not a persona
I/SELinux ( 5165): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5165): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5165): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5165 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
D/ActivityThread( 5136): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
W/GAV2    ( 4837): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/TimaKeyStoreProvider( 5165): TimaSignature is unavailable
D/ActivityThread( 5165): Added TimaKeyStore provider
D/SamsungIME( 1755): Dismiss ExpandCandiate
E/SQLiteLog( 5165): (284) automatic index on shooting_modes(title_id)
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 223190(14MB) AllocSpace objects, 2(4MB) LOS objects, 33% free, 22MB/33MB, paused 24.447ms total 271.564ms
,D/AcmsService( 5136): Inside handle Intent
D/AcmsService( 5136): App added - package name: com.test.thalitest
D/AcmsCore( 5136): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5136): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5136): Incrementing - Counter value: 3
D/AcmsCore( 5136): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5136): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5136): Decrementing - Counter value: 2
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5184): MountEmulatedStorage()
E/Zygote  ( 5184): v2
I/libpersona( 5184): KNOX_SDCARD checking this for 10152
I/libpersona( 5184): KNOX_SDCARD not a persona
,I/SELinux ( 5184): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5184): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5184): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5184 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 4502:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #31
I/ActivityManager( 1021): Killing 3817:com.android.calendar/u0a131 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5184): TimaSignature is unavailable
,D/ActivityThread( 5184): Added TimaKeyStore provider
,D/JsMessageQueue( 5014): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1755): getDebugLevel  : 0x4f4c
,V/Finsky  ( 4615): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5184): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5184): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/TapandpayWidget:Utils( 5184): Clear T&P info.
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5184): Widget is not attached.
,I/splitIntent( 1021): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1021): Killing 4137:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
,I/SamsungIME( 1755): getDebugLevel  : 0x4f4c
,D/NtpTrustedTime( 1021): forceRefresh() from cache miss
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1021): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1021): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1021): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1021): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,W/libprocessgroup( 1021): failed to open /acct/uid_10130/pid_4502/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10131/pid_3817/cgroup.procs: No such file or directory
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1649): callingUid 10011, callindPid: 1649
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,E/MDM     ( 1649): [223] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000,
,D/NtpTrustedTime( 1021): forceRefresh Fail.
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1866): Restart initialization of location
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1649): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1755): KeybaordView init() : load resources
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1755): getCurrentKeyboard
I/SamsungIME( 1755): getTextKeyboard
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1649): No location to return for getLastLocation()
,W/FusedLocationProvider( 1649): location=null
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4137/cgroup.procs: No such file or directory
,D/SamsungIME( 1755): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 5014): JniHelper::setJavaVM(0xb86e2448), pthread_self() = -1194739424
,D/JX-Cordova( 5014): jxcore cordova android initializing
,V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 4615): Thread-767(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 4615): Thread-767(ApacheHTTPLog):isShipBuild true
I/System.out( 4615): Thread-767(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4615): Thread-767(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10026
I/System.out( 4615): Thread-767 calls detatch()
W/Finsky  ( 4615): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 4615): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 4615): [1] DailyHygiene.access$600: Logging device features
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1021): waitForAlarm result :4
,D/Finsky  ( 4615): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/DeviceConnectionService( 1649): client connected with version: 8296000
,D/Finsky  ( 4615): [789] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4615): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 4615): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 4615): (HTTPLog)-Static: isShipBuild true
I/System.out( 4615): (HTTPLog)-Thread-778-744792664: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 4615): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10026
,I/ActivityManager( 1021): Killing 4552:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/ActivityManager( 1021): Killing 3828:com.android.providers.calendar/u0a37 (adj 15): empty #32
,V/AlarmManager( 1021): waitForAlarm result :4
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4552/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10037/pid_3828/cgroup.procs: No such file or directory
,D/SSRM:n  ( 1021): SIOP:: AP = 370
,D/AcmsKeyStoreHelper( 5136):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5136): Key Store exist
I/AcmsKeyStoreHelper( 5136): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 5136):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5136): getKeyStoreForApplication success 
D/AcmsCore( 5136): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5136): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5136): Decrementing - Counter value: 1
D/AcmsCore( 5136): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5136): This is NOT a valid MirrorLink app
D/AcmsCore( 5136): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5136): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5136): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5136): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5136): getSvcCounter - Counter value: 0
,D/AcmsService( 5136): Enter onDestroy
I/AcmsService( 5136): cleanUp(): inside service clean up
D/AcmsCore( 5136): AcmsCore: inside DeInit
D/AcmsCore( 5136): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5136): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5136): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5136): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5136): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5136): getSvcCounter - Counter value: 0
D/AcmsService( 5136): killing acms process
I/Process ( 5136): Sending signal. PID: 5136 SIG: 9
,I/ActivityManager( 1021): Process ACMS.Process (pid 5136)(adj 0) has died(36,619)
,I/PowerManagerService( 1021): [PWL] Off : 30s ago
,W/jxcore-log( 5014): Initializing JXcore engine
W/jxcore-log( 5014): JXcore engine is ready
,W/jxcore-log( 5014): Starting JXcore engine
,E/audit   ( 1779): type=1400 msg=audit(1449751010.362:203): avc:  denied  { ioctl } for  pid=5014 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1779):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1779): type=1300 msg=audit(1449751010.362:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=be84bd58 items=0 ppid=304 ppcomm=main pid=5014 auid=4294967295 uid=10326 gid=10326 euid=10326 suid=10326 fsuid=10326 egid=10326 sgid=10326 fsgid=10326 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1779): type=1320 msg=audit(1449751010.362:203): 
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/jxcore-log( 5014): Platform android
W/jxcore-log( 5014): 
,W/jxcore-log( 5014): Process ARCH arm
W/jxcore-log( 5014): 
,I/jxcore-log( 5014): JXcore Cordova bridge is ready!
I/jxcore-log( 5014): 
,W/jxcore-log( 5014): JXcore engine is started
I/chromium( 5014): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5014): 
,I/jxcore-log( 5014): Toggling radios to true
I/jxcore-log( 5014): 
,D/BluetoothAdapter( 5014): enable()
,W/ActivityManager( 1021): Permission Denial: getCurrentUser() from pid=5014, uid=10326 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 1021): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 1021): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5014, uid=10326 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 1021): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/BluetoothManagerService( 1021): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
W/BluetoothManagerService( 1021): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
W/BluetoothManagerService( 1021): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/BluetoothManagerService( 1021): 	at android.os.Binder.execTransact(Binder.java:461)
,E/DevicePolicyManagerService( 1021): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1021): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 1021): name = bluetooth_on
,E/DevicePolicyManagerService( 1021): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1021): getAllowBluetoothMode - value retunrs : 2
,E/SMD     (  288): DCD OFF
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5220): MountEmulatedStorage()
,E/Zygote  ( 5220): v2
I/libpersona( 5220): KNOX_SDCARD checking this for 1002
I/libpersona( 5220): KNOX_SDCARD not a persona
,I/ActivityManager( 1021): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5220 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/SELinux ( 5220): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
D/SecContentProvider( 1021): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1021): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1021): mCursor = null
,I/SELinux ( 5220): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5220): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiService( 1021): setWifiEnabled: true pid=5014, uid=10326
W/ActivityManager( 1021): Permission Denial: getCurrentUser() from pid=5014, uid=10326 requires android.permission.INTERACT_ACROSS_USERS,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/WifiService( 1021): Failed getting userId using ActivityManagerNative
W/WifiService( 1021): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5014, uid=10326 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1021): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1021): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1021): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1021): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1021): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1021): name = wifi_on
,I/WifiService( 1021): disconnect: pid=5014, uid=10326
E/WifiHW  ( 1021): ##################### set firmware type 0 #####################
,I/jxcore-log( 5014): Radios toggled
I/jxcore-log( 5014): 
,D/TimaKeyStoreProvider( 5220): TimaSignature is unavailable
,D/ActivityThread( 5220): Added TimaKeyStore provider
,W/ResourcesManager( 5220): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 5220): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni( 5220): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 5220): Adding GattService
,D/BtSettings.ProfileConfig( 5220): Adding HeadsetService
,D/BtSettings.ProfileConfig( 5220): Adding A2dpService
,D/BtSettings.ProfileConfig( 5220): Adding HidService
,D/BtSettings.ProfileConfig( 5220): Adding HealthService
,D/BtSettings.ProfileConfig( 5220): Adding PanService
,D/BtSettings.ProfileConfig( 5220): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 5220): Adding SapService
D/BtSettings.ProfileConfig( 5220): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 5220): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 5220): Adding SapClientService
,D/BtSettings.ProfileConfig( 5220): Adding HidDevService
I/BtSettings.ProfileConfig( 5220): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 1021): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 1002
,D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1021): ret = -1
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1021): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 1002
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1021): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 1002
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1021): name = bt_svcst_com.android.bluetooth.hid.HidService
,D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 1002
,D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/SettingsProvider( 1021): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 1002
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1021): ret = -1
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1021): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 1002
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1021): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 1002
,D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/SettingsProvider( 1021): ret = -1
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/SettingsProvider( 1021): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 1002
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1021): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
,D/SettingsProvider( 1021): selectionArgs: 1002
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1021): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 1002
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1021): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
,D/SettingsProvider( 1021): selectionArgs: 1002
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1021): name = bt_svcst_com.android.bluetooth.hid.HidDevService,
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false,
D/SettingsProvider( 1021): selectionArgs: 1002
,D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1021): ret = -1
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/BluetoothAdapterState( 5220): make
,I/bluedroid( 5220): init
,I/BluetoothAdapterState( 5220): Entering OffState
,I/bte_conf( 5220): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5220): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5220): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5220): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 5220): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 5220): get_profile_interface socket
I/bluedroid( 5220): get_profile_interface map_client
,D/BluetoothAdapterService( 5220): checkAddrForIOP: Loading from conf
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/GKI_LINUX( 5220): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 5220): Address is:08:EC:A9:50:76:27
,E/BluetoothServiceJni( 5220): populateRssiValuesNative
I/bluedroid( 5220): getModelRssiValues
E/BluetoothServiceJni( 5220): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/BluetoothAdapterProperties( 5220): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 5220): Name is: Thali Test (Galaxy A3)
,I/bluedroid( 5220): config_hci_snoop_log
,D/BluetoothManagerService( 1021): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothManagerService( 1021): Ble is always on enable gatt
,I/BluetoothManagerService( 1021): enableGattForLeMode, doBind called
,E/DevicePolicyManagerService( 1021): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1021): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 1021): uri = 3 selection = isBluetoothEnabled
,I/BtGatt.JNI( 5220): classInitNative(L900): classInitNative: Success!
,D/SettingsProvider( 1021): name = bluetooth_name
,D/BluetoothManagerService( 1021): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/BluetoothAdapterState( 5220): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 5220): Setting state to 11
,I/BluetoothAdapterState( 5220): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5220): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5220): updateAdapterState state is 11
,D/BluetoothAdapterService( 5220): Autoconnection is available 
D/BluetoothAdapterService( 5220): updateAdapterState prevState = 10newState = 11
D/BluetoothSecureManager( 5220): getInstant: null
D/BluetoothSecureManager( 5220): calling getMethod for getService
D/BluetoothSecureManager( 5220): calling getService
,W/InputMethodManagerService( 1021): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1021): [BT Setting State] State =11
,D/BluetoothSecureManager( 5220): getService return binder: android.os.BinderProxy@28f7bef3
,D/BluetoothTile( 1173):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1173): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1173):  getBluetoothState : 11
,D/BluetoothSecureManagerService( 1021): isSecureModeEnabled
D/BluetoothSecureManagerService( 1021): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode( 5220): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5220): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,I/SamsungIME( 1755): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
W/BluetoothAdapterService( 5220): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5220): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5220): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5220): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5220): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5220): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5220): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5220): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,D/StatusBarManagerService( 1021): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,W/BluetoothAdapterService( 5220): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,D/BluetoothTile( 1173):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1173): onStateChanged: Bluetooth
,W/BluetoothAdapterService( 5220): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5220): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 5220): make
D/StatusBarManagerService( 1021): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1173): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,I/BluetoothBondStateMachine( 5220): StableState(): Entering Off State
W/BluetoothAdapterService( 5220): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5220): Not skipping com.android.bluetooth.gatt.GattService
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5220): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5220): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 5220): handleDebugAction() action=null
D/BtGatt.GattService( 5220): Received start request. Starting profile...
D/BtGatt.GattService( 5220): start()
D/BtGatt.GattService( 5220): start()
I/bluedroid( 5220): get_profile_interface gatt
,D/BluetoothAdapterService( 5220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@863a70a
D/BtGatt.AdvertiseManager( 5220): advertise manager created
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5220): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5220): Not skipping com.android.bluetooth.a2dp.A2dpService
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BtGatt.GattService( 5220): mStartError = false
D/BluetoothAdapterService( 5220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@863a70a
,W/BluetoothAdapterService( 5220): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5220): Not skipping com.android.bluetooth.hid.HidService
D/HeadsetService( 5220): Received start request. Starting profile...
D/HeadsetService( 5220): start()
I/BluetoothHeadsetServiceJni( 5220): classInitNative: succeeds
D/HeadsetStateMachine( 5220): make
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
E/HeadsetStateMachine( 5220): # of Max HF connection is 2
W/BluetoothAdapterService( 5220): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothNotiBroadcastReceiver( 1303): onReceive
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5220): Not skipping com.android.bluetooth.hdp.HealthService
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5220): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5220): Not skipping com.android.bluetooth.pan.PanService
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
V/BluetoothStatusReceiver( 1173): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1173): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5220): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5220): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,I/bluedroid( 5220): get_profile_interface handsfree
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5220): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5220): Not skipping com.broadcom.bt.service.sap.SapService
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/art     ( 1649): Explicit concurrent mark sweep GC freed 31362(1880KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 9MB/16MB, paused 1.384ms total 97.232ms,
,E/Zygote  ( 5261): MountEmulatedStorage()
I/libpersona( 5261): KNOX_SDCARD checking this for 10055
E/Zygote  ( 5261): v2,
I/libpersona( 5261): KNOX_SDCARD not a persona
I/SELinux ( 5261): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5261): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1021): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5261 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
E/SELinux ( 5261): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5220): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5220): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5220): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5220): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5220): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5220): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5220): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5220): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5220): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 5220): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/DualScoManager( 5220): Instantiating Dual Sco Manager
,I/DualScoManager( 5220): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 5220): createCMTIContentObservers
,D/SettingsProvider( 1021): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 1002
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/TimaKeyStoreProvider( 5261): TimaSignature is unavailable
,D/HeadsetStateMachine( 5220): Enter Disconnected: -2
,D/ActivityThread( 5261): Added TimaKeyStore provider
,D/HeadsetStateMachine( 5220): Clear mHeadsetBrsf
,D/HeadsetService( 5220): mStartError = false
D/BluetoothAdapterService( 5220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@863a70a
E/BluetoothAdapterService(140748554)( 5220): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,D/HeadsetStateMachine( 5220): map size, before remove : 0
D/HeadsetStateMachine( 5220): map size, after remove: 0
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/BluetoothA2dp( 1021): Proxy object connected
,D/A2dpService( 5220): Received start request. Starting profile...
D/A2dpService( 5220): start()
,I/BluetoothAvrcpServiceJni( 5220): classInitNative: succeeds
I/bluedroid( 5220): get_profile_interface avrcp
,D/Tethering( 1021): interfaceAdded wlan0
,E/Tethering( 1021): No numeric data
,I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, false
D/Tethering( 1021): interfaceLinkStateChanged wlan0, false
D/Tethering( 1021): interfaceStatusChanged wlan0, false
,D/Tethering( 1021): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1021): clearTetheredNotification()
,D/Tethering( 1021): interfaceAdded p2p0
,D/Tethering( 1021): InitialState.processMessage what=4
D/NtpTrustedTime( 1021): forceRefresh() from cache miss
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/HotspotTile( 1173): onReceive : android.net.conn.TETHER_STATE_CHANGED,
D/HotspotTile( 1173): updateTetherState():false, false
,E/Tethering( 1021): No numeric data
,D/Tethering( 1021): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1021): clearTetheredNotification()
,D/Tethering( 1021): p2p0 is not a tetherable iface, ignoring
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
I/Nat464Xlat( 1021): interfaceLinkStateChanged p2p0, false
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/Tethering( 1021): interfaceLinkStateChanged p2p0, false
D/Tethering( 1021): interfaceStatusChanged p2p0, false
,D/HotspotTile( 1173): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1173): updateTetherState():false, false
,D/NtpTrustedTime( 1021): forceRefresh Fail.
,V/NetworkStats( 1021): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1021): UpdateStatsForKnox main else ---
,D/UserAnalysis.PlaceProvider( 5261): PlaceProvider onCreate()
,I/WifiHW  (  278): wifi_change_fw_path(): fwpath = sta,
,D/SoftapController(  278): Softap fwReload - Ok
,V/NetworkStats( 1021): performPollLocked() took 28ms
,D/NtpTrustedTime( 1021): forceRefresh() from cache miss
,D/NtpTrustedTime( 1021): forceRefresh Fail.
,D/NtpTrustedTime( 1021): forceRefresh() from cache miss
,D/NtpTrustedTime( 1021): forceRefresh Fail.
,V/NetworkStats( 1021): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1021): UpdateStatsForKnox main else ---
,V/NetworkStats( 1021): performPollLocked() took 3ms
,D/NtpTrustedTime( 1021): forceRefresh() from cache miss
,D/NtpTrustedTime( 1021): forceRefresh Fail.
,D/UserAnalysis.SecureDbManager( 5261): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5261): SecurePlaceDbHelper() 
D/UserAnalysis( 5261): Create SecureDbHelper
,D/CommandListener(  278): Setting iface cfg
D/CommandListener(  278): Trying to bring down wlan0
,E/RemoteController( 5220): Cannot set synchronization mode on an unregistered RemoteController
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,E/WifiHW  ( 1021): supplicant_name : p2p_supplicant
,D/WifiMonitor( 1021): startMonitoring(wlan0) with mConnected = false
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1173): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1173): Wifi onReceive(2)
D/STATUSBAR-QSTileView( 1173): onStateChanged: Wi-Fi
,D/HotspotTile( 1173): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1173): onReceive : 2, 0
,I/Avrcp   ( 5220):  Updating now playing list upon AVRCP Start
,D/BluetoothMediaBrowser( 5220):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 5220): classInitNative: succeeds
D/A2dpStateMachine( 5220): make
,I/bluedroid( 5220): get_profile_interface a2dp,
I/GKI_LINUX( 5220): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 5220): warning : media task started media_task_refcnt 1 
D/A2dpService( 5220): mStartError = false
,D/BluetoothAdapterService( 5220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@863a70a
D/BluetoothMediaBrowser( 5220): no now playing list
,D/BluetoothMediaBrowser( 5220):  getNowPlayingId now playing id : -1
,D/A2dpStateMachine( 5220): Enter Disconnected: -2,
,D/WifiCredService( 1303): Action received :android.net.wifi.WIFI_STATE_CHANGED
,I/BluetoothHidServiceJni( 5220): classInitNative: succeeds
,D/IntelligenceServiceApplication( 5261): onCreate()
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/HidService( 5220): Received start request. Starting profile...
D/HidService( 5220): start()
I/bluedroid( 5220): get_profile_interface hidhost
D/HidService( 5220): setHidService(): set to: null
D/HidService( 5220): mStartError = false
D/BluetoothAdapterService( 5220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@863a70a
,I/BluetoothHealthServiceJni( 5220): classInitNative: succeeds
,D/HealthService( 5220): Received start request. Starting profile...
I/ActivityManager( 1021): Killing 4295:com.google.android.gm/u0a99 (adj 15): empty #31
D/HealthService( 5220): start()
,I/bluedroid( 5220): get_profile_interface health
,D/HealthService( 5220): mStartError = false
D/BluetoothAdapterService( 5220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@863a70a
,I/BluetoothPanServiceJni( 5220): classInitNative(L105): succeeds
,D/IntelligenceServiceApplication( 5261): no applications having user consent for prediction
,D/PanService( 5220): Received start request. Starting profile...
D/PanService( 5220): start()
D/BluetoothPanServiceJni( 5220): initializeNative(L110): pan
I/bluedroid( 5220): get_profile_interface pan
D/PanService( 5220): mStartError = false
D/BluetoothAdapterService( 5220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@863a70a
,D/HeadsetStateMachine( 5220): Try to query the phonestate on bind
,D/BluetoothPan( 1021): BluetoothPAN Proxy object connected
,V/PlaceDetection v1.0.19 ( 5261): [PlaceDetection::stopService] Service stopped.
,I/wpa_supplicant( 5280): [wpa_supplicant_init]: use SECRIL,
I/wpa_supplicant( 5280): Successfully initialized wpa_supplicant
,I/SecureStorage( 5280): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,I/Telecom ( 1415): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1415): BluetoothPhoneService: handleMessage(7) / param 0
I/Telecom ( 1415): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1415): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1415): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,I/SecureStorage( 5280): [INFO]: SPID(0x00000000)This device supports Secure Storage
V/PlaceDetection v1.0.19 ( 5261): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,I/Telecom ( 1415): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1415): Proxy not attached to service
,I/Telecom ( 1415): BluetoothPhoneService: Result of Message : true
D/HeadsetStateMachine( 5220): Proxy object connected
,I/SecureStorage(  361): [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5280
I/SecureStorage(  361): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 5280): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 5280): ssSupport state is = 1
I/wpa_supplicant( 5280): >>>>> GET KEY, IV <<<<<
I/SecureStorage( 5280): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  361): [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5280
I/SecureStorage(  361): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
,D/BluetoothMapService( 5220): Received start request. Starting profile...,
D/BluetoothMapService( 5220): start()
,D/BluetoothMapService( 5220): mStartError = false
,D/BluetoothAdapterService( 5220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@863a70a
,D/HeadsetPhoneState( 5220): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine( 5220): Disconnected process message: 11
,I/BluetoothSAPServiceJni( 5220): classInitNative(L204): succeeds
,D/SapService( 5220): Received start request. Starting profile...
D/SapService( 5220): start()
D/BluetoothSAPServiceJni( 5220): initializeNative(L209): sap
I/bluedroid( 5220): get_profile_interface sap
D/SapService( 5220): mStartError = false
D/BluetoothAdapterService( 5220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@863a70a
D/HeadsetPhoneState( 5220): sendDeviceDataStateChanged
D/HeadsetPhoneState( 5220): Signal level : previous=0 curr=0
E/BluetoothAdapterService(140748554)( 5220): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService( 5220): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 5220): Proxy object connected
D/BluetoothAdapterService( 5220): Bluetooth A2dp source service connected
D/HeadsetStateMachine( 5220): Disconnected process message: 18
D/HeadsetStateMachine( 5220): Disconnected process message: 10
E/BluetoothAdapterService(140748554)( 5220): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/HeadsetPhoneState( 5220): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5220): Disconnected process message: 11
,E/BluetoothAdapterService(140748554)( 5220): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(140748554)( 5220): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(140748554)( 5220): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/AuthorizationBluetoothService( 1649): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1021): failed to open /acct/uid_10099/pid_4295/cgroup.procs: No such file or directory
I/ActivityManager( 1021): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5288 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/Zygote  ( 5288): MountEmulatedStorage()
E/Zygote  ( 5288): v2
I/libpersona( 5288): KNOX_SDCARD checking this for 10141
I/libpersona( 5288): KNOX_SDCARD not a persona
I/SELinux ( 5288): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5288): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5288): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3261): Starting #2
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/art     (  304): Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 728us total 24.666ms
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 5288): TimaSignature is unavailable
D/ActivityThread( 5288): Added TimaKeyStore provider
I/Hs20UtilService( 3261): Message received 5011
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 17.995ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 765us total 17.447ms,
,E/Zygote  ( 5303): MountEmulatedStorage(),
,E/Zygote  ( 5303): v2
,I/SELinux ( 5303): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1021): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5303 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 5303): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/libpersona( 5303): KNOX_SDCARD checking this for 1000
I/libpersona( 5303): KNOX_SDCARD not a persona
,E/SELinux ( 5303): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 5288): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5288): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5288): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5288): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5303): TimaSignature is unavailable
D/ActivityThread( 5303): Added TimaKeyStore provider
W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId,
I/SecureStorage(  361): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 5280): [INFO]: SPID(0x00000001)Processing data has been completed
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 5303): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5303): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5303): StateMachine : Current State = 1
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 5303): StateMachine : Changed Current State = 1
D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,I/ActivityManager( 1021): Killing 4209:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,I/wpa_supplicant( 5280): Ctrl_iface: loading cred from phone
,I/SecureStorage( 5280): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,E/BluetoothAdapterService(140748554)( 5220): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(140748554)( 5220): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,I/SecureStorage( 5280): [INFO]: SPID(0x00000001)This device supports Secure Storage
,I/SecureStorage(  361): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5280
I/SecureStorage(  361): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5280): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5280): ssSupport state is = 1
,I/wpa_supplicant( 5280): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5280): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5280): SIM READ ERROR
I/wpa_supplicant( 5280): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5280): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5280): SIM READ ERROR
I/wpa_supplicant( 5280): Blacklist: Clear (all) 
I/wpa_supplicant( 5280): wpa_default_ap_write_once
I/wpa_supplicant( 5280): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5280): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5280): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 5280): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5280): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant( 5280): rfkill: Cannot open RFKILL control device
,I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, false,
D/Tethering( 1021): interfaceLinkStateChanged wlan0, false
D/Tethering( 1021): interfaceStatusChanged wlan0, false,
,E/Zygote  ( 5328): MountEmulatedStorage()
E/Zygote  ( 5328): v2
I/libpersona( 5328): KNOX_SDCARD checking this for 10068
I/libpersona( 5328): KNOX_SDCARD not a persona
,I/SELinux ( 5328): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5328 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 4379:com.google.android.talk/u0a102 (adj 15): empty #31
,I/SELinux ( 5328): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5328): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/BluetoothAdapterState( 5220): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5220): enable
,I/bt_hci_bdroid( 5220): init
,I/GKI_LINUX( 5220): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor( 5220): bt-vendor : init
,I/bt_vendor( 5220): bt-vendor : get_bt_soc_type
E/bt_vendor( 5220): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 5220): init: Local BD Address : 27:76:50:a9:ec:08
,D/bt_userial_mct( 5220): userial_init
,I/bt_vendor( 5220): bt-vendor : BT_VND_OP_POWER_CTRL: Off
,I/bt_vendor( 5220): Starting hciattach daemon
,I/bt_vendor( 5220): try to set false
,I/bt_vendor( 5220): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 5220): Starting hciattach daemon
I/bt_vendor( 5220): try to set true
,I/wpa_supplicant( 5280): wlan0: Setting scan request: 0 sec 100000 usec
,I/qcom-bluetooth( 5344): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/TimaKeyStoreProvider( 5328): TimaSignature is unavailable,
D/ActivityThread( 5328): Added TimaKeyStore provider
,I/ActivityManager( 1021): Killing 4598:com.sec.knox.bridge/1000 (adj 15): empty #31,
,I/qcom-bluetooth( 5353): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 5354): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/BadgeProvider( 5328): onCreate
,D/BadgeProvider( 5328): DatabaseHelper
,I/qcom-bluetooth( 5356): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,W/libprocessgroup( 1021): failed to open /acct/uid_10035/pid_4209/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10102/pid_4379/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4598/cgroup.procs: No such file or directory
,D/BadgeProvider( 5328): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/qcom-bluetooth( 5357): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 5358): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5359): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,I/wpa_supplicant( 5280): wlan0: State: DISCONNECTED -> DISCONNECTED,
I/SecureStorage( 5280): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,D/BadgeProvider( 5328): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5328): sendNotify, [notify] : null
D/BadgeProvider( 5328): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5328): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5328): update, [UpdateCount] : 1,
D/Launcher.Model( 1463): reloadBadges entered.
,I/SecureStorage( 5280): [INFO]: SPID(0x00000001)This device supports Secure Storage
,I/SecureStorage(  361): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5280
I/SecureStorage(  361): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5280): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5280): ssSupport state is = 1
,I/wpa_supplicant( 5280): Ctrl_iface: loading cred from phone
I/SecureStorage( 5280): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,I/SecureStorage( 5280): [INFO]: SPID(0x00000001)This device supports Secure Storage,
I/SecureStorage(  361): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5280
I/SecureStorage(  361): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5280): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5280): ssSupport state is = 1
I/wpa_supplicant( 5280): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5280): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5280): SIM READ ERROR
I/wpa_supplicant( 5280): wpa_default_ap_write_once
I/wpa_supplicant( 5280): There is no /data/misc/wifi/default_ap.check. Start copy default ap
,I/wpa_supplicant( 5280): rfkill: Cannot open RFKILL control device
I/Nat464Xlat( 1021): interfaceLinkStateChanged p2p0, false
D/Tethering( 1021): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1021): interfaceLinkStateChanged p2p0, false
D/Tethering( 1021): interfaceStatusChanged p2p0, false
D/Tethering( 1021): interfaceLinkStateChanged p2p0, false
D/Tethering( 1021): interfaceStatusChanged p2p0, false
,W/ActivityManager( 1021): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 4837): Thread[GAThread,5,main]: No campaign data found.
,I/wpa_supplicant( 5280): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 5280): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 5280): p2p0: State: INACTIVE -> DISCONNECTED,
I/wpa_supplicant( 5280): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 5280): Skip scan - bUseNetwork false
,E/WifiStateMachine( 1021): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-wlan0( 1021): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 5280): HOTSPOT20_ENABLE called
I/wpa_supplicant( 5280): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5280): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5280): SIM READ ERROR
I/wpa_supplicant( 5280): Blacklist: Clear (all) 
,I/Nat464Xlat( 1021): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1021): interfaceLinkStateChanged p2p0, false
D/Tethering( 1021): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 5280): wlan0: Setting scan request: 0 sec 0 usec,
I/wpa_supplicant( 5280): Skip scan - bUseNetwork false
,D/WifiNative-wlan0( 1021): callSECApiInt - ID [210],
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,I/qcom-bluetooth( 5368): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/STATUSBAR-QSTileView( 1173): onStateChanged: Wi-Fi,
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/HotspotTile( 1173): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1173): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1173): Wifi onReceive(3)
D/HotspotTile( 1173): onReceive : 3, 0
,D/WifiConfigStore( 1021): Loading config and enabling all networks 
,D/WifiCredService( 1303): Action received :android.net.wifi.WIFI_STATE_CHANGED
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/qcom-bluetooth( 5370): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/Hs20UtilService( 3261): Starting #3,
I/Hs20UtilService( 3261): Message received 5011
,D/SecurityLogAgent( 5303): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5303): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5303): StateMachine : Current State = 1
D/SecurityLogAgent( 5303): StateMachine : Changed Current State = 1
,E/WifiConfigStore( 1021): Not a HS20
,E/WifiConfigStore( 1021): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-wlan0( 1021): callSECApiInt - ID [65]
,D/WifiNative-wlan0( 1021): callSECApiBoolean - ID [13]
,I/bt_vendor( 5220): bluetooth satus is on
D/bt_userial_mct( 5220): userial_open(port:0)
I/wpa_supplicant( 5280): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 5280): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 5280): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5280): P2P: Current p2p state = IDLE
I/wpa_supplicant( 5280): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 5280): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5280): First Scan Start
I/wpa_supplicant( 5280): Scan requested (ret=0) - scan timeout 30 seconds
I/bt_vendor( 5220): bt-vendor : BT_VND_OP_USERIAL_OPEN
,D/WifiNative-wlan0( 1021): Setting external_sim to 1,
D/WifiStateMachine( 1021): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1021): startHal
E/wifi    ( 1021): getStaticLongField sWifiHalHandle 0x9d4e788c
I/WifiNative-HAL( 1021): Could not start hal
,I/bt_vendor( 5220): Done intiailizing UART
,I/bt_vendor( 5220): Done intiailizing UART
I/bt_userial_mct( 5220): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 5220): Bluetooth Firmware and transport layer are initialized
E/WifiNative-wlan0( 1021): do suspend true
,D/bt_userial_mct( 5220): Entering userial_read_thread()
,D/WifiP2pService( 1021): P2pDisabledState{ what=131203 }
,E/WifiStateMachine( 1021): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,D/CommandListener(  278): Setting iface cfg
D/CommandListener(  278): Trying to bring up p2p0
,D/WifiScanningService( 1021): SCAN_AVAILABLE : 3
,D/WifiScanningService( 1021): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1021): startHal
E/wifi    ( 1021): getStaticLongField sWifiHalHandle 0x9e68a9bc
I/WifiNative-HAL( 1021): Could not start hal
E/WifiScanningService( 1021): could not start HAL
E/WifiStateMachine( 1021): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1021): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1021): invaild command id : 215
D/RttService( 1021): SCAN_AVAILABLE : 3
D/RttService( 1021): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1021): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1021): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1021): invaild command id : 215
,D/WifiMonitor( 1021): startMonitoring(p2p0) with mConnected = true
,D/WifiP2pService( 1021): P2pEnablingState
,I/wpa_supplicant( 5280): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/WifiP2pService( 1021): P2pEnablingState{ what=147457 }
I/wpa_supplicant( 5280): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/WifiP2pService( 1021): P2p socket connection successful
,D/WifiP2pService( 1021): P2pEnabledState
,E/wpa_supplicant( 5280): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine( 1021): Failed to set frequency band 0
,D/WifiP2pService( 1021): sending p2p connection changed broadcast: IDLE
I/        ( 5220): BTE_InitTraceLevels -- TRC_HCI
I/        ( 5220): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5220): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5220): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5220): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5220): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5220): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5220): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5220): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5220): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5220): BTE_InitTraceLevels -- TRC_SAP
I/        ( 5220): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5220): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5220): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5220): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5220): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 5220): BTE_InitTraceLevels -- TRC_PROTOCOL
,D/WifiDisplayController( 1021): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,E/WifiStateMachine( 1021): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 1021): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayController( 1021): disconnect
D/WifiDisplayController( 1021): updateConnection
,D/WifiDisplayController( 1021): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1173): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1173): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/WifiP2pService( 1021): create mNetworkAgent
,D/SecContentProvider2( 1021): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1021): mCursor = null
,D/ConnectivityService( 1021): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1021): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 1021): updateNetworkInfo()
,D/ConnectivityService( 1021): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/CSLegacyTypeTracker( 1021): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,D/WifiDisplayController( 1021): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiNative-p2p0( 1021): p2pGetDeviceAddress
,D/WifiNative-p2p0( 1021): p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiP2pService( 1021): DeviceAddress: 0a:76:28
,D/WifiDisplayController( 1021): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
D/WifiDisplayController( 1021):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiDisplayController( 1021):  primary type: 10-0050F204-5
D/WifiDisplayController( 1021):  secondary type: null
D/WifiDisplayController( 1021):  wps: 0
D/WifiDisplayController( 1021):  grpcapab: 0
D/WifiDisplayController( 1021):  devcapab: 0
D/WifiDisplayController( 1021):  status: 3
D/WifiDisplayController( 1021):  wfdInfo: null
D/WifiDisplayController( 1021):  groupownerAddress: null
D/WifiDisplayController( 1021):  GOdeviceName: null
D/WifiDisplayController( 1021):  interfaceAddress: 
D/WifiDisplayController( 1021):  SConnectInfo : null
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/WifiP2pService( 1021): sending p2p persistent groups changed broadcast
,W/bt-l2cap( 5220): l2c_link_processs_ble_num_bufs 16
,E/bt-btm  ( 5220): BTM_SecRegister:p_cb_info->p_le_callback == 0xa4520ead 
,E/bt-btm  ( 5220): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4520ead 
,E/Zygote  ( 5377): MountEmulatedStorage()
,E/Zygote  ( 5377): v2
I/libpersona( 5377): KNOX_SDCARD checking this for 10064
I/libpersona( 5377): KNOX_SDCARD not a persona
,I/SELinux ( 5377): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5377): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5377): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BluetoothAdapterProperties( 5220): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,I/ActivityManager( 1021): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5377 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/bt-btif ( 5220): Calling BTA_HhEnable
,E/bt-btif ( 5220): btif_storage_get_adapter_property service_mask:0x2120048
,D/BluetoothAdapterProperties( 5220): Address is:08:EC:A9:50:76:27
E/BluetoothServiceJni( 5220): populateRssiValuesNative
I/bluedroid( 5220): getModelRssiValues
E/BluetoothServiceJni( 5220): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5220): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/WifiP2pService( 1021): InactiveState
,D/WifiP2pService( 1021): InactiveState{ what=143376 }
D/WifiP2pService( 1021): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 5280): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/SettingsProvider( 1021): name = bluetooth_name
D/BluetoothAdapterProperties( 5220): Name is: Thali Test (Galaxy A3)
,D/WifiP2pService( 1021): InactiveState{ what=143376 }
E/ConnectivityService( 1021): updateNetworkInfo()
,D/WifiP2pService( 1021): P2pEnabledState{ what=143376 }
,D/BluetoothAdapterProperties( 5220): Scan Mode:20
,D/BluetoothAdapterProperties( 5220): Discoverable Timeout:120
D/BluetoothAdapterProperties( 5220): LE Address is:C8:D9:53:A0:EC:4E
E/bt-btif ( 5220): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 5220): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif ( 5220): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 5220): btif_sock_init: !vhci_init
D/IOP_DB_BT( 5220): db_open: file /etc/bluetooth/iop_bt.db
,E/bt_mct  ( 5220): hci lib postload completed
,D/IOP_DB_BT( 5220): db_open: db_open : handle 3028226064l, read 13894 bytes onto local cache
D/IOP_DB_BT( 5220): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5220): db_query: result 1
I/        ( 5220): iop_db_open: iop_db_open status 0
,D/bte_conf( 5220): Device ID record 1 : primary
,D/bte_conf( 5220):   vendorId            = 0075
D/bte_conf( 5220):   vendorIdSource      = 0001
D/bte_conf( 5220):   product             = 0100
D/bte_conf( 5220):   version             = 0200
D/bte_conf( 5220):   clientExecutableURL = 
D/bte_conf( 5220):   serviceDescription  = 
D/bte_conf( 5220):   documentationURL    = 
D/bte_conf( 5220): bte_load_did_conf no section named DID2.
,D/BluetoothPanServiceJni( 5220): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState( 5220): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5220): ScanMode =  20
D/BluetoothAdapterProperties( 5220): State =  11
,D/SecContentProvider( 1021): uri = 3 selection = isDiscoverableEnabled,
D/BluetoothAdapterProperties( 5220): Setting state to 12
I/BluetoothAdapterState( 5220): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties( 5220): Scan Mode:21
D/BluetoothAdapterProperties( 5220): Discoverable Timeout:120
,D/SettingsProvider( 1021): name = bluetooth_a2dp_sink_mode
,D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 1002
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,D/TimaKeyStoreProvider( 5377): TimaSignature is unavailable
,D/ActivityThread( 5377): Added TimaKeyStore provider
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 5220): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5220): updateAdapterState state is 12
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothA2dp( 1021): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 5220): Autoconnection is available 
D/BluetoothAdapterService( 5220): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 5220): starting service from this receiver
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothAdapterState( 5220): Entering On State from state = 11
D/BluetoothAdapter( 1415): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1415): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1021): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1021): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1430): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1430): onBluetoothStateChange: Bluetooth is on
,I/BluetoothPbapService( 5220): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothA2dp( 5220): onBluetoothStateChange: up=true,
D/BluetoothAdapter( 5014): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5014): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1439): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1439): onBluetoothStateChange: Bluetooth is on
W/ResourcesManager( 5377): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/BluetoothAdapter( 1173): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1173): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1649): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1649): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 5220): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5220): onBluetoothStateChange: Bluetooth is on
,W/InputMethodManagerService( 1021): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1021): [BT Setting State] State =12
,I/InputMethodManagerService( 1021): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothTile( 1173):  onBluetoothStateChange:
,D/BluetoothHeadset( 1415): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2497b2d3, true
,I/SamsungIME( 1755): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothHeadset( 1415): registerMessageListener
,D/BluetoothTile( 1173): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1173):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1173):  getBluetoothState : 12
,D/HeadsetService( 5220): registerMessageListener
,D/BluetoothTile( 1173):  handleUpdatestate:false name:null
,D/HeadsetService( 5220): registerMessageListener
D/HeadsetStateMachine( 5220): Disconnected process message: 70
I/Telecom ( 1415): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1415): BluetoothPhoneService: updateHeadsetWithCallState
,D/HeadsetStateMachine( 5220): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@36e5ede6
,I/BluetoothPbapService( 5220): Handler(): got msg=1
D/FileShare-Client( 5377): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/SecContentProvider( 1021): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/FileShare-Client( 5377): ClientBroadcastReceiver.onReceive - disconnected
,I/Telecom ( 1415): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1415): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,D/StatusBarManagerService( 1021): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,I/Telecom ( 1415): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/StatusBarManagerService( 1021): setIconVisibility slot=bluetooth visible=true
,D/PhoneStatusBar( 1173): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/BluetoothTile( 1173):  handleUpdatestate:false name:null
,D/HeadsetStateMachine( 5220): Disconnected process message: 9
,D/HeadsetStateMachine( 5220): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/BluetoothTile( 1173):  handleUpdatestate:false name:null
V/BluetoothPbapService( 5220): PBAP Service initSocket try: 0
,D/audio_hw_primary(  283): adev_set_parameters: enter: A2dpSuspended=false
,V/voice   (  283): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
,D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
E/HeadsetStateMachine( 5220): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothMapMasInstance( 5220): set MAP SDP message type : 1
,W/BluetoothAdapter( 5220): getBluetoothService() called with no BluetoothManagerCallback
,W/BluetoothAdapter( 5220): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5220): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]},
D/BluetoothSocket( 5220): bindListen(), new LocalSocket 
D/BluetoothSocket( 5220): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5220): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d305d4
,D/BluetoothSocket( 5220): channel: 5
D/BluetoothSocket( 5220): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 5220): bindListen(), new LocalSocket 
D/BluetoothSocket( 5220): bindListen(), new LocalSocket.getInputStream() ,
D/BluetoothSocket( 5220): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b98437d
D/BluetoothSocket( 5220): channel: 19
D/BluetoothPbapService( 5220): PBAP Socket is BluetoothServerSocket
,D/FileShare-Client( 5377): Outbound.stopDelayTimer - 
,D/FileShare-Server( 4628): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1021): Killing 4648:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/LocalBluetoothProfileManager( 1303): Adding local A2DP profile
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1303): Adding local HEADSET profile
,E/BluetoothHeadset( 1303): BTStateChangeCB is registed
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 1303): BluetoothHeadset service is binded
,D/BluetoothMap( 1303): Create BluetoothMap proxy object
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/Bluetoothsap( 1303): bindService called to Bluetooth SAP Service
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1303): PANU : true
,W/LocalBluetoothProfileManager( 1303): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1303): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1303): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1303): onReceive
,D/BluetoothA2dp( 1303): Proxy object connected
D/A2dpProfile( 1303): Bluetooth service connected
,V/BluetoothStatusReceiver( 1173): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1173): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,D/HeadsetProfile( 1303): Bluetooth service connected
,D/BluetoothMap( 1303): Proxy object connected
D/MapProfile( 1303): Bluetooth service connected
D/BluetoothMap( 1303): getConnectedDevices()
,D/BluetoothAdapterService( 5220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@863a70a
,D/BtConfig.SecureMode( 5220): isSecureModeOn:false
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/AuthorizationBluetoothService( 1649): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4648/cgroup.procs: No such file or directory
,D/BluetoothPbap( 1303): Proxy object connected
,D/PbapServerProfile( 1303): Bluetooth service connected
,D/Bluetoothsap( 1303): BluetoothSAP Proxy object connected
D/SapProfile( 1303): Bluetooth service connected
D/Bluetoothsap( 1303): getConnectedDevices()
,D/BluetoothInputDevice( 1303): Proxy object connected
,D/HidProfile( 1303): Bluetooth service connected
,D/BluetoothPan( 1303): BluetoothPAN Proxy object connected
,D/PanProfile( 1303): Bluetooth service connected
,D/SecContentProvider( 1021): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/BluetoothAdapter( 5220): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5220): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
D/BluetoothSocket( 5220): bindListen(), new LocalSocket 
D/BluetoothSocket( 5220): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5220): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e943c1f
,D/BluetoothSocket( 5220): channel: 12
I/BtOppRfcommListener( 5220): Accept thread started.
,D/CAR.SERVICE( 5030): mConnectedToCar = false, abort
,E/ActivityThread( 5030): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1d1c6dca that was originally bound here
E/ActivityThread( 5030): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1d1c6dca that was originally bound here
E/ActivityThread( 5030): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5030): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5030): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5030): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5030): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5030): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5030): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5030): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5030): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5030): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5030): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5030): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5030): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5030): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 5030): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 5030): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 5030): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5030): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5030): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5030): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5030): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5030): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5030): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 5030): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@10a605ed that was originally bound here
E/ActivityThread( 5030): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@10a605ed that was originally bound here
E/ActivityThread( 5030): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5030): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5030): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5030): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5030): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5030): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5030): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5030): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5030): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5030): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5030): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5030): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5030): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 5030): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 5030): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 5030): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5030): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5030): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5030): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5030): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5030): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5030): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 40698(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 22MB/33MB, paused 2.463ms total 138.374ms
W/ActivityManager( 1021): Unbind failed: could not find connection for android.os.BinderProxy@f82db47
,I/ActivityManager( 1021): Killing 4155:com.google.android.music:main/u0a108 (adj 15): empty #31
,I/wpa_supplicant( 5280): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 5280): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5280): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 5280): Trying to associate with  'G700'
I/wpa_supplicant( 5280): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 5280): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,I/WifiNative-HAL( 1021): startHal
,D/WifiMonitor( 1021): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wifi    ( 1021): getStaticLongField sWifiHalHandle 0x9d4e78ac
,I/WifiNative-HAL( 1021): Could not start hal
,D/SecContentProvider2( 1021): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1021): mCursor = null
,E/wpa_supplicant( 5280): Cmd 35605 not handled
,I/wpa_supplicant( 5280): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 5280): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 5280): Associated with C0.AA.48
I/wpa_supplicant( 5280): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 5280): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 5280): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1021): interfaceLinkStateChanged wlan0, false
D/Tethering( 1021): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1021): interfaceLinkStateChanged wlan0, false
D/Tethering( 1021): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1021): interfaceLinkStateChanged wlan0, false
D/Tethering( 1021): interfaceStatusChanged wlan0, false
,D/SecContentProvider2( 1021): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1021): mCursor = null
,I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, true
D/Tethering( 1021): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1021): interfaceStatusChanged wlan0, true
,D/SecContentProvider2( 1021): uri = 20 selection = getPromptCredentialsEnabled
I/wpa_supplicant( 5280): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/SecContentProvider2( 1021): mCursor = null
I/wpa_supplicant( 5280): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 5280): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 5280): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 5280): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5280): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 5280): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 5280): Blacklist: Clear (temp) 
I/wpa_supplicant( 5280): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, true
D/Tethering( 1021): interfaceLinkStateChanged wlan0, true
D/Tethering( 1021): interfaceStatusChanged wlan0, true
,E/Tethering( 1021): No numeric data
,D/Tethering( 1021): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1021): clearTetheredNotification()
,D/WifiNative-wlan0( 1021): callSECApiVoid - ID [50]
,D/NtpTrustedTime( 1021): forceRefresh() from cache miss
,D/HotspotTile( 1173): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1173): updateTetherState():false, false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,E/WifiConfigStore( 1021): setLastSelectedConfiguration -1
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1021): forceRefresh Fail.
,V/NetworkStats( 1021): performPollLocked(flags=0x1)
,D/ConnectivityService( 1021): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1021): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1021): updateNetworkInfo()
D/ConnectivityService( 1021): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox main else ---
,E/WifiConfigStore( 1021): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/NetworkStats( 1021): performPollLocked() took 13ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NtpTrustedTime( 1021): forceRefresh() from cache miss
,D/NtpTrustedTime( 1021): forceRefresh Fail.
,W/libprocessgroup( 1021): failed to open /acct/uid_10108/pid_4155/cgroup.procs: No such file or directory
,I/Hs20UtilService( 3261): Starting #4
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 3261): Message received 5007
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,E/WifiConfigStore( 1021): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  278): Setting iface cfg
,E/WifiStateMachine( 1021): Start Dhcp Watchdog 1
,D/SecContentProvider2( 1021): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1021): mCursor = null
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiNative-wlan0( 1021): do suspend false
,D/WifiP2pService( 1021): InactiveState{ what=143375 }
,D/WifiP2pService( 1021): P2pEnabledState{ what=143375 }
,D/SecContentProvider2( 1021): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1021): mCursor = null
,E/SMD     (  288): DCD OFF
,E/dhcpcd  ( 5410): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5410): version 5.5.6 starting
,E/dhcpcd  ( 5410): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 5410): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 5410): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 5410): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 5410): bssid match,
I/dhcpcd  ( 5410): wlan0: rebinding lease of 192.168.1.133
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5220): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5220): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,I/dhcpcd  ( 5410): wlan0: acknowledged 192.168.1.133 from 192.168.1.1
,I/dhcpcd  ( 5410): wlan0: leased 192.168.1.133 for 86400 seconds
,D/PackageManager( 1021): [MSG] MCS_UNBIND,
,I/ActivityManager( 1021): Killing 4760:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31,
,E/WifiNative-wlan0( 1021): do suspend true
,D/WifiP2pService( 1021): InactiveState{ what=143375 }
,D/WifiP2pService( 1021): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/WifiStateMachine( 1021): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1021): VerifyingLinkState enter
,D/WifiNative-wlan0( 1021): callSECApiInt - ID [210]
,E/ConnectivityService( 1021): updateNetworkInfo()
,D/ConnectivityService( 1021): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7628/64,192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1021): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 1021): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1021): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7628/64,192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1021): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7628/64,192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1021): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7628/64,192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1021): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7628/64,192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,W/libprocessgroup( 1021): failed to open /acct/uid_10139/pid_4760/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1021): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1021): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService( 1021): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ConnectivityService( 1021): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,I/Hs20UtilService( 3261): Starting #5
,E/ConnectivityService( 1021): Unexpected mtu value: 0, wlan0
,I/Hs20UtilService( 3261): Message received 5007
,D/ConnectivityService( 1021): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService( 1021): LTETest block dns file not exists
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1021): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,E/ConnectivityService( 1021): updateNetworkInfo()
,E/ConnectivityService( 1021): updateNetworkInfo()
,D/ConnectivityService( 1021): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1021): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1021): rematching NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1021): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
E/WifiStateMachine( 1021): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/WifiTrafficPoller( 1021): evaluateTrafficStatsPolling,
,D/ConnectivityService( 1021):    accepting network in place of null
,D/ConnectivityService( 1021): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,D/WIFI_P2P( 1021): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1439): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1439): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    ( 1021): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,E/CSLegacyTypeTracker( 1021): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7628/64,192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1021): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1021): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/WifiTrafficPoller( 1021): evaluateTrafficStatsPolling
,I/WifiTrafficPoller( 1021): mBoosterFLAG : 0
I/WifiTrafficPoller( 1021): current booster mode : FullMode
,D/WifiNative-wlan0( 1021): callSECApiVoid - ID [212]
,I/System.out( 1021): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1021): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1021): (HTTPLog)-Static: isShipBuild true
I/System.out( 1021): (HTTPLog)-Thread-168-281114580: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1021): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 1000
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1021): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7628/64,192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} },
,D/ConnectivityService( 1021): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1021): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524290
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,V/NetworkStats( 1021): updateIfacesLocked()
V/NetworkStats( 1021): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1021): UpdateStatsForKnox main else ---
D/NtpTrustedTime( 1021): forceRefresh() from cache miss
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 1000
,V/NetworkStats( 1021): performPollLocked() took 5ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3261): Starting #6
,D/StatusBar.NetworkController( 1173): EthernetConnected: false
,D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1173): updateDataNetType()
D/StatusBar.NetworkController( 1173): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1173): updateLTEICONDataNetType:0
,I/Hs20UtilService( 3261): Message received 5007
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,D/StatusBar.NetworkController( 1173): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
I/Hs20UtilService( 3261): Starting #7
,I/Hs20UtilService( 3261): Message received 5007
,D/WifiStateMachine( 1021): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1021): mCursor = null
,D/NtpTrustedTime( 1021): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449751016785 mCachedNtpElapsedRealtime : 87430 mCachedNtpCertainty : 12
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1021): mCursor = null
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravityYOffset
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
V/NetworkStats( 1021): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/SecContentProvider2( 1021): mCursor = null
,I/System.out( 1021): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SecContentProvider2( 1021): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1021): mCursor = null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 12:36:56 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449751016593], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449751016574]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): Validated
,D/ConnectivityService( 1021): Validated NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1021): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1021): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService( 1021): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1021): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524290
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1021): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1021
,D/SRIB_DCS( 1173): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBar.NetworkController( 1173): EthernetConnected: false
,D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1173): updateDataNetType()
,D/StatusBar.NetworkController( 1173): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1173): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1173): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1021): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1021): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/AlarmManagerService( 1021): Setting time of day to sec=1449751017
D/AlarmManagerService( 1021): Trying to open a file
,D/AlarmManagerService( 1021): File Open Success
D/AlarmManagerService( 1021): File Close Success
I/AlarmManagerService( 1021): DRM_TIME_PATH CHMOD 666 for resetState done 
W/AlarmManagerService( 1021): Unable to set rtc to 1449751017: Invalid argument
,V/AlarmManager( 1021): waitForAlarm result :65536
,V/AlarmManager( 1021): No more alarm at this time.nowELAPSED=87876 batch.start=90650
,I/DBG_DM  ( 2848): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/PCWCLIENTTRACE_PushUtil( 4889): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4889): sales region : global
D/WifiStateMachine( 1021): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
I/PCWCLIENTTRACE_PushUtil( 4889): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4889): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,I/DBG_DM  ( 2848): [com.wssyncmldm.llllIIIllIlIIIIllllI(230/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,I/DowntimeConditions( 1021): android.intent.action.TIME_SET ignored because schedule turned off.
,I/DBG_DM  ( 2848): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_SET
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1173): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/splitIntent( 1021): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
I/splitIntent( 1021): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/SettingsProvider( 1021): name = lockscreen_zoom_panning_effect
,D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10049
,D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,E/Zygote  ( 5453): MountEmulatedStorage()
I/libpersona( 5453): KNOX_SDCARD checking this for 10108
E/Zygote  ( 5453): v2
I/libpersona( 5453): KNOX_SDCARD not a persona
I/SELinux ( 5453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=5453 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5453): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 2848): [IlIlllIlllllIlIllllI(403/llIIllllIIlllIIIIlll)] Check completed.
,I/DBG_DM  ( 2848): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,W/Settings( 1021): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DBG_DM  ( 2848): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,D/accuweather( 1688): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,I/DBG_DM  ( 2848): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
D/KeyguardEffectViewUtil( 1173): isStrongPowerSavingMode() :false
,I/DrmEventService( 1021):  no response from SecureClock 
,I/KLMS-2.5.123: ( 3313): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 13:36:57 GMT+01:00 2015
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/KeyguardEffectViewController( 1173): isPreloadedWallpaper=true
,I/GeometricMosaic_Keyguard( 1173): update
,D/KeyguardEffectViewUtil( 1173): getCurrentWallpaper() mWallpaperPath :null
,D/TimaKeyStoreProvider( 5453): TimaSignature is unavailable
,I/KLMS-2.5.123: ( 3313): KLMSAbstractReciever(): onReceive().END.
,D/ActivityThread( 5453): Added TimaKeyStore provider
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,D/daemonapp( 1727): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,I/KLMS-2.5.123: ( 3313): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3313): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/SecurityLogAgent( 5303): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5303): KnoxConfiguration : Current State Mapping Found 
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent( 5303): StateMachine : Current State = 1
,I/ActivityManager( 1021): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5470 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 5470): MountEmulatedStorage()
I/libpersona( 5470): KNOX_SDCARD checking this for 10031
E/Zygote  ( 5470): v2
I/libpersona( 5470): KNOX_SDCARD not a persona
,I/SELinux ( 5470): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/SELinux ( 5470): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5470): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecurityLogAgent( 5303): StateMachine : Changed Current State = 1
,D/accuweather( 1688): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1688): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1688): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1688): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3313): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KeyguardEffectViewUtil( 1173): set current wallpaper info
,I/DBG_DM  ( 2848): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/KLMS-2.5.123: ( 3313): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/SettingsProvider( 1021): name = keyguard_current_wallpaper_type
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10049
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,I/KLMS-2.5.123: ( 3313): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,D/TimaKeyStoreProvider( 5470): TimaSignature is unavailable
,D/ActivityThread( 5470): Added TimaKeyStore provider
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
I/KLMS-2.5.123: ( 3313): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,D/SettingsProvider( 1021): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10049
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,I/KLMS-2.5.123: ( 3313): StateImplV2(): networkChangeListener().START
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/SettingsProvider( 1021): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10049
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/accuweather( 1688): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1688): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/DBG_DM  ( 2848): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 8
,I/DBG_DM  ( 2848): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,I/DBG_DM  ( 2848): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
I/DBG_DM  ( 2848): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [8]
,I/KLMS-2.5.123: ( 3313): NetworkChangeOperations(): uploadRequestLog().START ,
,I/KLMS-2.5.123: ( 3313): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3313): StateImplV2(): networkChangeListener().END
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/TEST    ( 1173): run!!!
,E/Zygote  ( 5491): MountEmulatedStorage()
E/Zygote  ( 5491): v2
I/libpersona( 5491): KNOX_SDCARD checking this for 10077
I/libpersona( 5491): KNOX_SDCARD not a persona
,I/SELinux ( 5491): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text,
I/SELinux ( 5491): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5491): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5491 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GeometricMosaic_Renderer( 1173): setBackgroundBitmap
,E/SMD     (  288): DCD OFF
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text,
D/TimaKeyStoreProvider( 5491): TimaSignature is unavailable
D/ActivityThread( 5491): Added TimaKeyStore provider
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/DBG_DM  ( 2848): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 0
,I/DBG_DM  ( 2848): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 2848): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 2848): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,D/KeyguardEffectViewController( 1173): isPreloadedWallpaper=true
,I/DBG_DM  ( 2848): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/KLMS-2.5.123: ( 3313): KLMSIntentService(): onDestroy()
,I/DBG_DM  ( 2848): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 2848): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 2848): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:362673799
,I/DBG_DM  ( 2848): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,I/DBG_POLICYDM( 4926): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 2848): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,I/DBG_DM  ( 2848): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,I/DBG_POLICYDM( 4926): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4926): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 4926): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,E/DBG_POLICYDM( 4926): [com.policydm.XDMBroadcastReceiver(240/xdmNotInitSetResume)] DM Not Init
,I/DBG_POLICYDM( 4926): [com.policydm.XDMApplication(246/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_POLICYDM( 4926): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 4926): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_DM  ( 2848): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,I/DBG_DM  ( 2848): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 705624899
,I/System.out( 2869): Thread-403(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 2869): Thread-403(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 2869): Thread-403(ApacheHTTPLog):isShipBuild true
I/System.out( 2869): Thread-403(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 2869): Thread-403(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/DBG_DM  ( 2848): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,I/MusicStore( 5453): Database version: 104
,I/DBG_POLICYDM( 4926): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 4926): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 4926): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 4926): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 4926): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 4926): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,E/SPPClientService( 3732): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/DBG_POLICYDM( 4926): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_DM  ( 2848): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 2848): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/DBG_POLICYDM( 4926): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 4926): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 4926): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4926): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 4926): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 4926): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 4926): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2015/12/17/09:21:32
,I/DBG_DM  ( 2848): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
I/DBG_POLICYDM( 4926): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2015/12/10/13:36:57
,I/SA      ( 4966): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/DBG_POLICYDM( 4926): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
I/DBG_DM  ( 2848): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,I/DBG_DM  ( 2848): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
I/DBG_POLICYDM( 4926): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
E/DBG_DM  ( 2848): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,I/SA      ( 4966): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 4966): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10161
,E/GpsLocationProvider( 1021): No APN found to select.
,E/DBG_DM  ( 2848): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@38601fb1
,I/DBG_DM  ( 2848): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/DBG_DM  ( 2848): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,I/qtaguid ( 2869): Tagging socket 51 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 2869, getuid(): 10161
,I/SA      ( 4966): [SLFUCHKMGR] constructor called
,I/DBG_DM  ( 2848): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,W/ResourcesManager( 5453): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5453): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5527): MountEmulatedStorage()
,E/Zygote  ( 5527): v2
I/libpersona( 5527): KNOX_SDCARD checking this for 10110
I/libpersona( 5527): KNOX_SDCARD not a persona
,I/SELinux ( 5527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1021): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5527 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5527): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/SA      ( 4966): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4966): [OR] == isSIMCardReady false ==
,I/SA      ( 4966): [SCU] == networkStateCheck == true
,V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SA      ( 4966): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4966): isChinaCountryCode : false
I/SA      ( 4966): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 4966): [OR] == networkStateCheck true ==
,I/DBG_DM  ( 2848): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_POLICYDM( 4926): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,D/TimaKeyStoreProvider( 5527): TimaSignature is unavailable
,D/ActivityThread( 5527): Added TimaKeyStore provider
,I/SA      ( 4966): [OR] GetMyCountryZoneTask
,I/SA      ( 4966): [OR] onReceive END
,D/DelayedSyncController( 5491): Delaying sync.
,E/ActivityThread( 1866): Failed to find provider info for com.android.contacts.metadata
,V/JNIHelp ( 5453): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/SA      ( 4966): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1234): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 2848): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1021): mCursor = null
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_DM  ( 2848): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/SecContentProvider2( 1021): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1021): mCursor = null
,D/WindowManager( 1021): showStatusBarByNotification() mOpenByNotification=false,
W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager( 1173): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1021): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1021): mCursor = null
,I/SA      ( 4966): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/DBG_DM  ( 2848): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 2848): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 2848): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,I/iu.SyncManager( 1866): SYNC; picasa accounts
,I/SA      ( 4966): [SSP] query invoked
,D/SyncManager( 1021): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 21740, reason: UserStart, SyncResult: databaseError: true stats [],
,D/SyncManager( 1021): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 121503, reason: UserStart
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false,
,D/NetworkLogImpl( 1866): Loaded NetworkSpeedPredictor,
,I/DBG_POLICYDM( 4926): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1,
,I/SA      ( 4966): [TPMU] GetMccFromDB : null
,I/SA      ( 4966): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4966): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 4926): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/KnoxNotification( 1173): ----- inflateViews : modified publicViewLocal -----
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/KnoxNotification( 1173): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1173): PersonaID is invalid or persona doesn't exists. : 0
I/DBG_POLICYDM( 4926): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
D/PersonaManager( 1173): isKioskContainerExistOnDevice
,W/ActivityThread( 5453): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5453): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@48ad3be: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5453): Installed default security provider GmsCore_OpenSSL
,I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) ,
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice,
I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1021): mCursor = null
,I/iu.Environment( 1866): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/AndroidMusic( 5453): GMSCore installation verified
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/File    ( 4966): fail readDirectory() errno=2
,I/iu.UploadsManager( 1866): num queued entries: 0
,I/iu.UploadsManager( 1866): num updated entries: 0
,I/iu.SyncManager( 1866): NEXT; no task
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10011
,D/WaitQueueForNetworkActivate( 4982): notifyNetworkActivated
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ContextImpl( 4982): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1021): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/GCM     ( 1649): GCM config loaded,
,I/ConfigStore( 5453): Config Database version: 1
,E/Auth.Api.Credentials( 1866): [CredentialSyncAdapter] Unknown sync event.
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5527): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5527): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,I/qtaguid ( 2869): Untagging socket 51
I/System.out( 2869): Thread-403 calls detatch()
,W/ContextImpl( 5453): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5527): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5527): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 4982): AutoUpdateManager:IDLE:execute
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5453): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/InitializeManagerStateMachine( 4982): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 4982): exit::IDLE
D/InitializeManagerStateMachine( 4982): entry::NETWORK_CHECK
,W/ContextImpl( 5453): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/InitializeManagerStateMachine( 4982): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4982): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4982): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4982): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4982): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4982): entry::SUCCESS
D/hcjo    ( 4982): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4982): AutoUpdateTriggerManager:IDLE:setInterval:345600000,
W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/hcjo    ( 4982): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4982): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4982): exit::SUCCESS
,D/InitializeManagerStateMachine( 4982): entry::IDLE
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1021): getStreamVolume 3 index 70
,I/MediaRouter( 5453): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/dhcpcd  ( 5410): wlan0: sending IPv6 Router Solicitation
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/PicasaService( 4227): start picasa sync
,I/WebViewFactory( 5527): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/PicasaService( 4227): end picasa sync
,I/NetworkMonitor( 5453): type=WIFI subType= reason=null isConnected=true
,E/Zygote  ( 5590): MountEmulatedStorage()
E/Zygote  ( 5590): v2
I/libpersona( 5590): KNOX_SDCARD checking this for 10001
I/libpersona( 5590): KNOX_SDCARD not a persona
,I/SELinux ( 5590): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5590): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=5590 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5590): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5590): TimaSignature is unavailable
,D/ActivityThread( 5590): Added TimaKeyStore provider
,I/LibraryLoader( 5527): Loading: webviewchromium
,I/LibraryLoader( 5527): Time to load native libraries: 5 ms (timestamps 9779-9784)
I/LibraryLoader( 5527): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5527): Binding Chromium to main looper Looper (main, tid 1) {2c64a258}
,I/LibraryLoader( 5527): Expected native library version number "",actual native library version number ""
,I/chromium( 5527): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 62611(3MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 22MB/34MB, paused 4.598ms total 209.009ms
,I/BrowserStartupController( 5527): Initializing chromium process, renderers=0
,W/art     ( 5527): Attempt to remove local handle scope entry from IRT, ignoring
,D/DelayedSyncController( 5491): Delaying sync.
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor( 5453): type=WIFI subType= reason=null isConnected=true
,W/chromium( 5527): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 5527): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 5527): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/ActivityManager( 1021): Killing 4075:com.android.mms/u0a41 (adj 15): empty #31
,W/AudioManagerAndroid( 5527): Requires BLUETOOTH permission
,D/CountryDetector( 1021): No listener is left
,I/Adreno-EGL( 5527): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5527): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5527): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5527): Local Branch: 
I/Adreno-EGL( 5527): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5527): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5527):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 1866): Suspending all threads took: 19.680ms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1021): failed to open /acct/uid_10041/pid_4075/cgroup.procs: No such file or directory
,E/Zygote  ( 5630): MountEmulatedStorage(),
I/libpersona( 5630): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5630): v2
,I/libpersona( 5630): KNOX_SDCARD not a persona
I/SELinux ( 5630): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5630): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1021): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=5630 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1021): Killing 4845:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,E/SELinux ( 5630): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/NSApplication( 5527): Starting up...
,I/ActivityManager( 1021): Killing 4871:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5630): TimaSignature is unavailable
,D/ActivityThread( 5630): Added TimaKeyStore provider
,D/btif_config_util( 5220): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/ConnectivityManager( 1866): CallingUid : 10011, CallingPid : 1866
,D/ConnectivityService( 1021): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1021): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,D/ConnectivityService( 1021): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1021): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1866): CM callback handler got msg 524290
,I/DIAGMON_AGENT( 5630): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1021): failed to open /acct/uid_10042/pid_4871/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10014/pid_4845/cgroup.procs: No such file or directory
,E/Zygote  ( 5652): MountEmulatedStorage(),
,E/Zygote  ( 5652): v2,
,I/libpersona( 5652): KNOX_SDCARD checking this for 10121
I/libpersona( 5652): KNOX_SDCARD not a persona
,I/SELinux ( 5652): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1021): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=5652 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 5652): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5652): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5652): TimaSignature is unavailable
,D/ActivityThread( 5652): Added TimaKeyStore provider
,I/ActivityManager( 1021): Killing 4665:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,W/ResourcesManager( 5652): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5652): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5652): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup( 1021): failed to open /acct/uid_10029/pid_4665/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 5630): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5630): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5630): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 5630): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 5630): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 5630): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/QuickConnect( 5652): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 5652): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 5652): PeriphStartReceiver.onReceive - no need to start
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,I/DBG_POLICYDM( 4926): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4926): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,W/DriveInitializer( 1866): Awaiting to be initialized
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,W/DriveInitializer( 1866): Background init thread started
,I/DBG_POLICYDM( 4926): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4926): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5672): MountEmulatedStorage(),
E/Zygote  ( 5672): v2
I/libpersona( 5672): KNOX_SDCARD checking this for 10008
I/libpersona( 5672): KNOX_SDCARD not a persona
I/SELinux ( 5672): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5672): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1021): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=5672 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5672): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5672): TimaSignature is unavailable
,D/ActivityThread( 5672): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 8688(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 622us total 25.976ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 17.070ms
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1866): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 16.715ms
,I/ActivityManager( 1021): Killing 4908:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,I/FOTA_Client( 5672): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 5672): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 5672): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 5672): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/splitIntent( 1021): Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,I/ActivityManager( 1021): Killing 4329:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/splitIntent( 1021): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 1021): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/SSRM:n  ( 1021): SIOP:: AP = 400
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5698): MountEmulatedStorage(),
I/libpersona( 5698): KNOX_SDCARD checking this for 10058
E/Zygote  ( 5698): v2
I/libpersona( 5698): KNOX_SDCARD not a persona
I/SELinux ( 5698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1021): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=5698 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 5698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5698): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,V/AlarmManager( 1021): waitForAlarm result :8
,I/ActivityManager( 1021): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5707 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/Zygote  ( 5707): MountEmulatedStorage()
I/libpersona( 5707): KNOX_SDCARD checking this for 10131
E/Zygote  ( 5707): v2
I/libpersona( 5707): KNOX_SDCARD not a persona
,I/SELinux ( 5707): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/TimaKeyStoreProvider( 5698): TimaSignature is unavailable
,I/SELinux ( 5707): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/ActivityThread( 5698): Added TimaKeyStore provider
,E/SELinux ( 5707): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/FOTA_Client( 5672): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1727): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1727): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/TimaKeyStoreProvider( 5707): TimaSignature is unavailable
,D/ActivityThread( 5707): Added TimaKeyStore provider
,D/daemonapp( 1727): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4329/cgroup.procs: No such file or directory
,D/daemonapp( 1727): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1727): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/libprocessgroup( 1021): failed to open /acct/uid_10048/pid_4908/cgroup.procs: No such file or directory
,D/daemonapp( 1727): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,W/DriveInitializer( 1866): Background init thread ended
,D/comsamsunglog( 1727): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1727): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1727): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1727): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1727): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1727): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1727): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,W/ResourcesManager( 5707): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5707): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5707): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1727): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,I/FOTA_Client( 5672): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/daemonapp( 1727): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1727): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,I/KLMS-2.5.123: ( 3313): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Dec 10 13:37:00 GMT+01:00 2015
,D/daemonapp( 1727): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3313): KLMSAbstractReciever(): onReceive().END.
,E/daemonapp( 1727): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/SA      ( 4966): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/KLMS-2.5.123: ( 3313): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3313): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3313): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/comdaemonstockapp( 1727): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 1727): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
I/KLMS-2.5.123: ( 3313): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/KLMS-2.5.123: ( 3313): KLMSIntentService(): TIME_CHANGED,
I/KLMS-2.5.123: ( 3313): StateImplV2(): dateTimeChanged().START : Thu Dec 10 13:37:00 GMT+01:00 2015,
,I/ExternalOEMControlProvider( 5698): onCreate
,D/accuweather( 1688): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,I/KLMS-2.5.123: ( 3313): StateImplV2(): dateTimeChanged().END
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/accuweather( 1688): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/Zygote  ( 5736): MountEmulatedStorage(),
E/Zygote  ( 5736): v2
I/libpersona( 5736): KNOX_SDCARD checking this for 10041
,I/libpersona( 5736): KNOX_SDCARD not a persona
,I/SELinux ( 5736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1021): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=5736 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
,I/SELinux ( 5736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5736): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/ Time Manager ( 5698): Time Difference not stored. TIME_DIFFERENCE,
,E/Zygote  ( 5746): MountEmulatedStorage(),
E/Zygote  ( 5746): v2
I/libpersona( 5746): KNOX_SDCARD checking this for 10081
,I/libpersona( 5746): KNOX_SDCARD not a persona
,I/SELinux ( 5746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1021): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=5746 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5746): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  257): id=13 Removed Uoast (8/9),
D/PowerManagerService( 1021): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1021) eventTime = 90970
I/SurfaceFlinger(  257): id=13 Removed Uoast (-2/9)
D/PowerManagerService( 1021): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1021 (0x0)
D/TimaKeyStoreProvider( 5736): TimaSignature is unavailable
D/ActivityThread( 5736): Added TimaKeyStore provider,
D/daemonapp( 1727): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/PowerManagerService( 1021): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1021, ws=WorkSource{10049}) (elapsedTime=3469)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/KLMS-2.5.123: ( 3313): KLMSIntentService(): onDestroy()
V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 5746): TimaSignature is unavailable
,D/ActivityThread( 5746): Added TimaKeyStore provider
,D/OpenGLRenderer( 2848): Render dirty regions requested: true
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=4, Uoast
,W/ResourcesManager( 5736): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.,
W/ResourcesManager( 5736): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5736): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5736): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5736): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.,
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PowerManagerService( 1021): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1021
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ResourcesManager( 5746): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5746): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5746): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5746): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5746): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/CheckinService( 1866): Checkin interval check for package: unspecified last checkin: 1449590985142 min interval config: 0 actual interval: 160035327
,D/SRIB_DCS( 2848): log_dcs ThreadedRenderer::initialize entered! 
,I/Adreno-EGL( 2848): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2848): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2848): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2848): Local Branch: 
I/Adreno-EGL( 2848): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2848): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2848):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/OpenGLRenderer( 2848): Initialized EGL, version 1.4
,D/Mms/MmsApp( 5736): [start]    onCreate() consume time = 0.0
,I/ActivityManager( 1021): Killing 4837:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,D/OpenGLRenderer( 2848): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2848): Enabling debug mode 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1021): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5775 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 5775): MountEmulatedStorage(),
E/SMD     (  288): DCD OFF
,E/Zygote  ( 5775): v2
I/libpersona( 5775): KNOX_SDCARD checking this for 10037
I/libpersona( 5775): KNOX_SDCARD not a persona
,I/SELinux ( 5775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/SELinux ( 5775): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SecurityLogAgent( 5303): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5303): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5303): StateMachine : Current State = 1
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4966): [RC New] Execute method=[GET] start,
,W/libprocessgroup( 1021): failed to open /acct/uid_10087/pid_4837/cgroup.procs: No such file or directory,
E/Zygote  ( 5786): MountEmulatedStorage(),
E/Zygote  ( 5786): v2
I/libpersona( 5786): KNOX_SDCARD checking this for 10153
I/libpersona( 5786): KNOX_SDCARD not a persona
,I/SELinux ( 5786): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5786): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=5786 uid=10153 gids={50153, 9997} abi=armeabi-v7a
E/SELinux ( 5786): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SA      ( 4966): [RC New] Security=[true]
I/System.out( 4966): Thread-830(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 4966): Thread-830(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4966): Thread-830(ApacheHTTPLog):isShipBuild true
I/System.out( 4966): Thread-830(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4966): Thread-830(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10036
,W/art     ( 5736): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 178.694ms
,D/TimaKeyStoreProvider( 5775): TimaSignature is unavailable
,D/ActivityThread( 5775): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 5786): TimaSignature is unavailable
,D/ActivityThread( 5786): Added TimaKeyStore provider
,I/art     ( 1619): Explicit concurrent mark sweep GC freed 2384(95KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 1.561ms total 54.554ms
,D/SettingsProvider( 1021): name = next_alarm_formatted
,D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10081
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,W/ResourcesManager( 5786): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5775): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Mms/ArtClassLoader( 5736): init before art
,D/Mms/TelephonyPermission( 5736): start operation mode monitor
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5810): MountEmulatedStorage(),
E/Zygote  ( 5810): v2
I/CalendarProvider2( 5775): CalendarProvider2.onCreate() called
,I/libpersona( 5810): KNOX_SDCARD checking this for 1000
I/libpersona( 5810): KNOX_SDCARD not a persona
,I/SELinux ( 5810): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5810): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5810): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5810 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 5074:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #31,
,W/ResourcesManager( 5736): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/art     ( 5746): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 160.544ms
,D/TimaKeyStoreProvider( 5810): TimaSignature is unavailable
,D/Mms/TelephonyPermission( 5736): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 5736): isDefault true
,D/Mms/MmsApp( 5736): onCreate() com.android.mms
,D/ActivityThread( 5810): Added TimaKeyStore provider
,D/Mms/MmsApp( 5736): [start]    initCountryIso consume time = 445.392761
,D/CountryDetector( 1021): The first listener is added
,D/Mms/MmsApp( 5736): [end]    initCountryIso consume time = 8.102135
D/Mms/MmsConfig( 5736): [start]    MmsConfig.init() consume time = 0.108073
,D/Mms/MmsConfig( 5736): before partial update
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/TimeService( 5810): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449751020976
D/        ( 5810): TimeServiceNative: User Time to be set is 1449751020976
D/QC-time-services( 5810): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5810): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5810): Lib:time_genoff_operation: pargs->ts_val = 1449751020976
,D/QC-time-services( 5810): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  316): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  316): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449751020976
D/QC-time-services(  316): Daemon:genoff_opr: Base = 2, val = 1449751020976, operation = 0,
,D/QC-time-services(  316): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/6/70 16:14:30,
,D/QC-time-services(  316): Daemon:Value read from RTC seconds = 13536870000
,D/QC-time-services(  316): Daemon:new time 1449751020976 
D/QC-time-services(  316): Daemon: delta 1436214150976 genoff 1436214150976 
D/QC-time-services(  316): Daemon:genoff_persistent_update: Writing genoff = 1436214150976 to memory
,D/QC-time-services(  316): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  316): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
,D/Mms/MmsConfig( 5736): Load Resize quality : 80,
,D/QC-time-services(  316): Updating the TOD offset,
D/QC-time-services(  316): Daemon:genoff_persistent_update: Writing genoff = 1436214150976 to memory
D/QC-time-services(  316): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  316): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/Zygote  ( 5831): MountEmulatedStorage(),
E/Zygote  ( 5831): v2
I/libpersona( 5831): KNOX_SDCARD checking this for 10090,
I/libpersona( 5831): KNOX_SDCARD not a persona
,I/SELinux ( 5831): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5831): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/QC-time-services(  316): Daemon:Update to modem bit set
D/QC-time-services(  316): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  316): Daemon: Base = 2, Value being sent to MODEM = 1120249350976
,E/QC-time-services(  316): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40,
D/EasySignUpManager_1.0.1( 5736): serviceId : 1, features : -1
I/ActivityManager( 1021): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5831 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
E/QC-time-services(  316): Daemon: Time-services: Waiting to acceptconnection
,D/EasySignUpManager_1.0.1( 5736): isAuth is false
E/QC-time-services( 5810): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/SELinux ( 5831): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Killing 5094:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,D/Mms/MmsConfig( 5736): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
D/TP/MmsSmsProvider( 1439): query,matched:2117, calling pid = 5736
,D/TP/MmsSmsProvider( 1439): match 2117:Elapsed time : 3.045 ms
,D/EasySignUpManager_1.0.1( 5736): isAuth is false
,D/EasySignUpManager_1.0.1( 5736): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5736): mps_code.dat does not exist
,E/CscParser( 5736): customer_path =/system/csc/customer.xml
E/CscParser( 5736): fileName + /system/csc/customer.xml
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_5074/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5831): TimaSignature is unavailable
,D/ActivityThread( 5831): Added TimaKeyStore provider
,W/libprocessgroup( 1021): failed to open /acct/uid_10098/pid_5094/cgroup.procs: No such file or directory
,E/CscParser( 5736): mps_code.dat does not exist
E/CscParser( 5736): customer_path =/system/csc/customer.xml
E/CscParser( 5736): fileName + /system/csc/customer.xml
,I/ActivityManager( 1021): Killing 5111:com.samsung.helphub/1000 (adj 15): empty #31
,D/CscParser( 5736): getInstance fileName =/system/csc/customer.xml
,D/Mms/ArtClassLoader( 5736): init [DONE] art
,D/Mms/MmsConfig( 5736):  enable multiwindow = false
,W/art     ( 4682): Attempt to remove local handle scope entry from IRT, ignoring
,E/Mms/MessageUtils( 5736): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 5736): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 5736): [end]    init() consume time = 189.219844
,D/Mms/Contact( 5736): [start]    init() consume time = 1.660625
,D/TP/MmsSmsProvider( 1439): query,matched:13, calling pid = 5736
,D/Mms/Contact( 5736): [end]    init consume time = 14.327291
,D/TP/MmsSmsProvider( 1439): match 13:Elapsed time : 1.947 ms
,D/elm:15121( 5831): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15121( 5831): ELMEngine.ELMEngine( context ).
,D/elm:15121( 5831): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/Mms/DraftCache( 5736): [start]    rebuildCache consume time = 7.064688
D/Mms/MethodReflector( 5736): getSubId is called
D/Mms/TelephonyUtils( 5736): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5736): getTelephonyProperty is called
D/Mms/DownloadManager( 5736): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5736): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5736): auto download without roaming -> true
D/Mms/DownloadManager( 5736): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 5736): getSubId is called
,D/elm:15121( 5831): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/Mms/MethodReflector( 5736): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5736): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5736): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5736): getTelephonyProperty is called
D/Mms/DownloadManager( 5736): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5736): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5736): auto download without roaming -> true
D/Mms/DownloadManager( 5736): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5736): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5736): mAutoDownload ------> true
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/elm:15121( 5831): ElmAgentService : onCreate()
,D/elm:15121( 5831): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:15121( 5831): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15121( 5831): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:15121( 5831): ModuleBase.ModifySetAlarm()
D/elm:15121( 5831): MDMBridge.getInstance()
,D/elm:15121( 5831): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 5856): MountEmulatedStorage(),
I/libpersona( 5856): KNOX_SDCARD checking this for 10130
E/Zygote  ( 5856): v2
I/libpersona( 5856): KNOX_SDCARD not a persona
I/SELinux ( 5856): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5856): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1021): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5856 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,E/SELinux ( 5856): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_5111/cgroup.procs: No such file or directory
,D/elm:15121( 5831): ElmAgentService : onDestroy().
,I/ActivityManager( 1021): Killing 5165:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,D/TP/MmsSmsProvider( 1439): query,matched:12, calling pid = 5736
,D/TimaKeyStoreProvider( 5856): TimaSignature is unavailable
,D/ActivityThread( 5856): Added TimaKeyStore provider
,D/ComposerPerformance( 5736): 1449751021229 ms / [DONE] Composer constructor
,E/CII     ( 5736): CommonIMSInterface: VoLTE CSC feature disabled.,
,I/Mms/ReservationManager( 5736): ReservationManager()
,I/Mms/ReservationManager( 5736): resetAfterConnected()
,D/Mms/Conversation( 5736): [start]    init() consume time = 81.950885
,D/TP/MmsSmsProvider( 1439): query,matched:7, calling pid = 5736,
,D/TP/MmsSmsProvider( 1439): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1439): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1439): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1439): sUpgradeVersion = 0, db.getVersion() = 81
,D/TP/MmsSmsProvider( 1439): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1439): need read changed broadcast:false
,D/Mms/Conversation( 5736): [end]    init consume time = 16.96099
,D/Mms/MessagingNotification( 5736): [start]    init() consume time = 3.426302
,W/libprocessgroup( 1021): failed to open /acct/uid_10148/pid_5165/cgroup.procs: No such file or directory
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 24019(1172KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 22MB/34MB, paused 2.609ms total 153.292ms
,D/TP/MmsSmsProvider( 1439): match 7:Elapsed time : 116.424 ms
,D/TP/MmsSmsProvider( 1439): match 12:Elapsed time : 119.647 ms
,D/Mms/MessagingNotification( 5736): [end]    init consume time = 106.545416
,D/Mms/Synchronizer( 5736): [start]    doSync consume time = 7.430782
,I/Mms/ReservationManager( 5736): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/SpamFilter( 5736): [start]    SpamFilter fill() begin consume time = 1.664531
,D/Mms/DraftCache( 5736): [end]    rebuildCache consume time = 3.784531
D/TP/MmsSmsProvider( 1439): query,matched:0, calling pid = 5736
V/TP/MmsSmsProvider( 1439): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1439): match 0:Elapsed time : 0.715 ms
,D/TP/MmsSmsProvider( 1439): query,matched:400, calling pid = 5736
,D/TP/MmsSmsProvider( 1439): update, matched:300, calling pid = 5736
V/TP/MmsSmsProvider( 1439): syncDBData start
,V/TP/MmsSmsProvider( 1439): syncDBData sms end
,V/TP/MmsSmsProvider( 1439): syncDBData mms end
,V/TP/MmsSmsProvider( 1439): syncDBData end
,D/Mms/Synchronizer( 5736): [end]    doSync consume time = 7.42724
D/Mms/MmsApp( 5736): [end]    onCreate() consume time = 0.184323
,D/Mms/SpamFilter( 5736): [end]    SpamFilter fill() finished consume time = 1.307656
,W/ResourcesManager( 5856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5856): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/ActivityManager( 1021): Killing 5184:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,D/Mms/DownloadManager( 5736): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 5736): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 5736): getSubId is called
D/Mms/TelephonyUtils( 5736): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5736): getTelephonyProperty is called
D/Mms/DownloadManager( 5736): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5736): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5736): auto download without roaming -> true
D/Mms/DownloadManager( 5736): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 5736): mAutoDownload ------> true
,I/DBG_POLICYDM( 4926): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/Mms/MessagingNotification( 5736): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1439): query,matched:26, calling pid = 5736
,D/TP/SmsProvider( 1439): match 26:Elapsed time : 0.946 ms
I/SA      ( 4966): [RC New] [v2liruge] api execute + 742
I/SA      ( 4966): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4966): AsyncTask #1 calls detatch()
,D/TP/MmsSmsProvider( 1439): query,matched:6, calling pid = 5736
,D/TP/MmsSmsProvider( 1439): match 6:Elapsed time : 2.432 ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/DBG_POLICYDM( 4926): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/SA      ( 4966): [ODM] saveOpenData( GEO_IP, PL )
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10117
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/SA      ( 4966): [OCP] update openData : PL
,I/DBG_POLICYDM( 4926): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/Zygote  ( 5887): MountEmulatedStorage(),
E/Zygote  ( 5887): v2
I/libpersona( 5887): KNOX_SDCARD checking this for 10023
,I/libpersona( 5887): KNOX_SDCARD not a persona
,I/SELinux ( 5887): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1021): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5887 uid=10023 gids={50023, 9997} abi=armeabi-v7a,
E/DBG_POLICYDM( 4926): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,I/SELinux ( 5887): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5887): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1021): failed to open /acct/uid_10152/pid_5184/cgroup.procs: No such file or directory
,I/splitIntent( 1021): Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1021): Killing 5030:com.google.android.gms:car/u0a11 (adj 15): empty #31
,I/SA      ( 4966): [TPMU] getNetworkMcc : 
,I/SA      ( 4966): [SCU] saveMccToPreferece Start
,I/SA      ( 4966): [SCU] RegionMCC : 260
I/SA      ( 4966): [SSP] query invoked
,D/TimaKeyStoreProvider( 5887): TimaSignature is unavailable
,D/ActivityThread( 5887): Added TimaKeyStore provider
,I/SA      ( 4966): [TPMU] GetMccFromDB : null
,I/SA      ( 4966): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4966): [SCU] saveMccToPreferece End
,I/SA      ( 4966): [RC New] executeRequest [v2liruge] end. 953
I/SA      ( 4966): [RC New] Execute end
I/SA      ( 4966): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 4966): [OR] GetMyCountryZoneTask Success
,I/DBG_POLICYDM( 4926): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/ActivityManager( 1021): Killing 4615:com.android.vending/u0a26 (adj 15): empty #31
,I/DBG_POLICYDM( 4926): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,I/ActivityManager( 1021): Killing 5377:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
,I/OMACP   ( 5887): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 5736): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/OMACP   ( 5887): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 5887): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 5887): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 5887): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 5887): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/ActivityManager( 1021): Waited long enough for: ServiceRecord{350d0dba u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/OMACP   ( 5887): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 5887): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,W/libprocessgroup( 1021): failed to open /acct/uid_10011/pid_5030/cgroup.procs: No such file or directory
I/OMACP   ( 5887): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,W/libprocessgroup( 1021): failed to open /acct/uid_10026/pid_4615/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10064/pid_5377/cgroup.procs: No such file or directory
I/OMACP   ( 5887): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 5887): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 5887): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 5887): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 5887): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false,
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4889): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 4889): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 4889): [GetString-S]
,I/ReactiveServiceManager( 4889): Supported : 1
,D/QSEECOMAPI: ( 1021): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1021): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1021): Loaded image: APP id = 9
,D/QSEECOMAPI: ( 1021): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1021): QSEECom_shutdown_app, app_id = 9
,E/terrier ( 1021): handleString: Failed to handle string(-4)
E/terrier ( 1021): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 4889): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 4889): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 4889): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 4889): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4889): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 4889): [ensureRegistration] - No Samsung account
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/AclDataUtils( 4682): Circle ID not found for type: 9
,I/CalendarProvider2( 5775): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/ActivityManager( 1021): Killing 4628:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1021): Killing 4802:com.android.defcontainer/u0a3 (adj 15): empty #31
,I/ActivityManager( 1021): Killing 5261:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #32
,W/libprocessgroup( 1021): failed to open /acct/uid_10065/pid_4628/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10055/pid_5261/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10003/pid_4802/cgroup.procs: No such file or directory
,I/dhcpcd  ( 5410): wlan0: sending IPv6 Router Solicitation
,I/Mms/MmsApp( 5736):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5736): [start]    fillCache consume time = 2000.353593
,D/Mms/ComposeMessageFragment( 5736): fillCache, easy = false
,D/AbsListView( 5736): Get MotionRecognitionManager
,D/MotionRecognitionService( 1021):  ssp status : false
,D/Mms/ComposeMessageFragment( 5736): [end]    fillCache consume time = 62.436823
,I/jxcore-log( 5014): Test app app.js loaded
I/jxcore-log( 5014): 
,I/Choreographer( 5014): Skipped 720 frames!  The application may be doing too much work on its main thread.
,D/Mms/BubbleViewCache( 5736): fillCache bubble = 1
,I/chromium( 5014): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 5014): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  288): DCD OFF
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/GAV4    ( 5527): Thread[GAThread,5,main]: No campaign data found.
,I/SurfaceFlinger(  257): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1021): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1021) eventTime = 94480
,D/PowerManagerService( 1021): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1021 (0x0)
,D/PowerManagerService( 1021): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1021, ws=WorkSource{1000}) (elapsedTime=3404)
,V/AlarmManager( 1021): waitForAlarm result :4
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5911): MountEmulatedStorage()
,E/Zygote  ( 5911): v2
I/libpersona( 5911): KNOX_SDCARD checking this for 10026
,I/libpersona( 5911): KNOX_SDCARD not a persona
,I/SELinux ( 5911): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5911 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager( 1021): ___SyncScheduler (v3) ACTIVATED___
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
V/AlarmManagerEXT( 1021): <AppSync3 Whitelist>
D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
V/AlarmManagerEXT( 1021): (AppSync) ### 0 added ###
I/SELinux ( 5911): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5911): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main,
I/art     (  304): Explicit concurrent mark sweep GC freed 8663(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 2.305ms total 42.299ms
,D/TimaKeyStoreProvider( 5911): TimaSignature is unavailable
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityThread( 5911): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 741us total 22.624ms
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 678us total 20.189ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1173): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1649): callingUid 10011, callindPid: 1649
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5453): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5453): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 5453): Using the GMSCore's GoogleHttpClient
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 5453): Conditions not met for autocaching.
,I/MusicLeanback( 5453): Stop autocaching.
,D/Finsky  ( 5911): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/WearableClient( 5453): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 5453): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 5453): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 5453): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 5453): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5453): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread( 5453): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2e729fdf that was originally bound here
E/ActivityThread( 5453): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2e729fdf that was originally bound here
E/ActivityThread( 5453): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5453): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5453): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5453): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5453): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5453): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 5453): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 5453): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 5453): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 5453): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 5453): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 5453): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 5453): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 5453): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 5453): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 5453): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 5453): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 5453): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 5453): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5453): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5453): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5453): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5453): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5453): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5453): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/Finsky  ( 5911): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5911): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5911): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 5911): Skipping gmscore version check
,D/Finsky  ( 5911): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5911): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5911): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5911): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Finsky  ( 5911): [1015] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5911): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager( 1021): Killing 4889:com.sec.pcw.device/1000 (adj 15): empty #31
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4889/cgroup.procs: No such file or directory
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1021): Plugged
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5220): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5220): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  288): DCD OFF,
,I/dhcpcd  ( 5410): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 5410): wlan0: no IPv6 Routers available
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 4982): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4982): exit::IDLE
D/PreloadUpdateManagerStateMachine( 4982): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4982): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 4982): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4982): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4982): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4982): entry::IDLE
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 360
,I/PowerManagerService( 1021): [PWL] Off : 50s ago
,V/AlarmManager( 1021): waitForAlarm result :4
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1649): Vacuum at: now=1449751031741 tag=VacuumService
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/FactoryTest( 4521): Not factory mode
D/FactoryTest( 4521): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4521): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 4521): still no open session command from host, so toast
,W/ContextImpl( 4521): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4521): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4521): Timeline: Activity_launch_request id:com.android.settings time:102715
,E/PersonaManagerService( 1021): inState():  stateMachine is null !!
,I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1021): mDVFSHelper.acquire()
,D/PersonaManager( 1021): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1021): Focused application set to: xxxx
,D/InputDispatcher( 1021): Focus left window: 5014
,E/MTPRx   ( 4521): started activity for popup
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1649): Scheduling Phenotype for one-off execution 6470 seconds from now (1449751032154)
,W/ResourcesManager( 4521): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4521): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4521): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4521): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4521): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4521): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1649): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,E/SettingsReceiverActivity( 4521): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1021): Focused application set to: xxxx
,D/InputDispatcher( 1021): Focus entered window: 5014
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1021): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1d4da71a attribute=null, token = android.os.BinderProxy@1dcf783d
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1649): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1649): Using platform SSLCertificateSocketFactory
,D/SettingsReceiverActivity( 4521): dev.kiessupport is : TRUE
,D/PhoneWindow( 4521): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4521): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
,D/LocationManagerService( 1021): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/ActivityThread( 5014): updateVisibility : ActivityRecord{7bbe6ba token=android.os.BinderProxy@263a6edc {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 5014): Timeline: Activity_idle id: android.os.BinderProxy@263a6edc time:102967
,D/PersonaManager( 1021): isKioskContainerExistOnDevice
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1649): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1649): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1649): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1649): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1649): (HTTPLog)-Thread-242-651947123: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1649): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10011
,I/System.out( 1649): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1649): Tagging socket 84 with tag 1000120100000000{268440065,0} for uid -1, pid: 1649, getuid(): 10011
,I/qtaguid ( 1649): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1649, getuid(): 10011
,E/SMD     (  288): DCD OFF
,D/LocationManagerService( 1021): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1649): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1649): Tagging socket 84 with tag 1000120100000000{268440065,0} for uid -1, pid: 1649, getuid(): 10011
,D/LocationManagerService( 1021): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1649): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1649): Tagging socket 84 with tag 1000120100000000{268440065,0} for uid -1, pid: 1649, getuid(): 10011
,D/LocationManagerService( 1021): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1649): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1649): Tagging socket 84 with tag 1000120100000000{268440065,0} for uid -1, pid: 1649, getuid(): 10011
,D/LocationManagerService( 1021): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1649): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1649): Tagging socket 84 with tag 1000120100000000{268440065,0} for uid -1, pid: 1649, getuid(): 10011
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): mDVFSHelper.release()
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5220): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5220): Disconnected process message: 10
,E/SMD     (  288): DCD OFF
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/Watchdog( 1021): !@Sync 3
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,D/SSRM:n  ( 1021): SIOP:: AP = 330
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager( 1021): waitForAlarm result :4
,D/SSRM:n  ( 1021): SIOP:: AP = 310
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1021): [PWL] Off : 75s ago
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,D/SSRM:n  ( 1021): SIOP:: AP = 310
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 4
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 300
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,E/ActivityThread( 1866): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 1021): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 121503, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 1021): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 213667, reason: UserStart
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1021): mCursor = null
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,V/AlarmManager( 1021): waitForAlarm result :8
,D/SSRM:n  ( 1021): SIOP:: AP = 300
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 105s ago
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5220): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5220): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  288): DCD OFF,
,I/ClearcutLoggerApiImpl( 1649): disconnect managed GoogleApiClient
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 5
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1173): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  288): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,I/PowerManagerService( 1021): [PWL] Off : 140s ago
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 6
,V/AlarmManager( 1021): waitForAlarm result :4
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.,
,V/AlarmManager( 1021): waitForAlarm result :8
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 290,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/Watchdog( 1021): !@Sync 7
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,D/SSRM:n  ( 1021): SIOP:: AP = 290,
,I/PowerManagerService( 1021): [PWL] Off : 180s ago,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5220): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5220): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1173): level :100 plugged : 2
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,D/SSRM:n  ( 1021): SIOP:: AP = 290,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5220): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5220): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/Watchdog( 1021): !@Sync 8
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 225s ago
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1021): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5220): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5220): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/Watchdog( 1021): !@Sync 9
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 1021): initializing...
,I/TLC_TIMA_PKM_initialize( 1021): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1021): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1021): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1021): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1021): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1021): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1021): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1021): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: ( 1021): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1021): Loaded image: APP id = 10
,I/TZ: qc_tlc_communication( 1021): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1021): Trustlet response is completed
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1021): !@Sync 10
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5220): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5220): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2

```
