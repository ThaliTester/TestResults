#### Test 625090944a5472b_thali01_samsung-SM-A500FU Logs


```
--------- beginning of system
W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1016): startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
--------- beginning of main
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
D/NPS_WSSNPS( 3602): [] Service onCreate!!
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3656): MountEmulatedStorage()
E/Zygote  ( 3656): v2
I/SELinux ( 3656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3656): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/NPS_WSSNPS( 3602): [] NpsServiceTask Start
I/ActivityManager( 1016): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3656 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 3656): KNOX_SDCARD checking this for 1000
I/libpersona( 3656): KNOX_SDCARD not a persona
V/OneTimeInitializerReceiver( 3637): OneTimeInitializerReceiver.onReceive
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
I/ActivityManager( 1016): Killing 2969:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
D/ActivityManager( 1016): startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2370/cgroup.procs: No such file or directory
V/OneTimeService( 3637): OneTimeService.onHandleIntent
D/TimaKeyStoreProvider( 3656): TimaSignature is unavailable
D/ActivityThread( 3656): Added TimaKeyStore provider
W/ContextImpl( 3301): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/NPS_WSSNPS( 3602): [50.150621] smlDBHelper
D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 3656): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/NPS_WSSNPS( 3602): [50.150621] AsyncBulkFlagCheck
W/libprocessgroup( 1016): failed to open /acct/uid_1101/pid_2969/cgroup.procs: No such file or directory
I/NPS_WSSNPS( 3602): [50.150621] IsRemain_AsyncBulkCheck
I/NPS_WSSNPS( 3602): [50.150621] IsRemain_Asyncing nothing
W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
D/NPS_WSSNPS( 3602): [50.150621] Service onDestroy
D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 2590): Starting #2
I/Hs20UtilService( 2590): Message received 5003
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3687): MountEmulatedStorage()
I/libpersona( 3687): KNOX_SDCARD checking this for 10019
E/Zygote  ( 3687): v2
I/libpersona( 3687): KNOX_SDCARD not a persona
I/SELinux ( 3687): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3687 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3687): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3687): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3687): TimaSignature is unavailable
D/ActivityThread( 3687): Added TimaKeyStore provider
I/NPS_WSSNPS( 3602): [50.150621] smlBRConfigurationDelete
I/NPS_WSSNPS( 3602): [50.150621] smlBRMessageDelete
I/NPS_WSSNPS( 3602): [50.150621] smlBREmailDelete
I/NPS_WSSNPS( 3602): [50.150621] smlBRNetworkDelete
I/NPS_WSSNPS( 3602): [50.150621] smlBRCallLogDelete
I/NPS_WSSNPS( 3602): [50.150621] smlBRMiniDiaryDelete
I/ActivityManager( 1016): Killing 2949:com.sec.knox.bridge/1000 (adj 15): empty #31
I/NPS_WSSNPS( 3602): [50.150621] smlBRPenMemoMDelete
I/NPS_WSSNPS( 3602): [50.150621] smlBRSMemoDelete
I/NPS_WSSNPS( 3602): [50.150621] verifier installed? false
I/NPS_WSSNPS( 3602): [50.150621] cpuBooster release : false
V/EmergencyMode( 1443): [EmergencyBase] setBootTime
V/EmergencyMode( 1443): [EmergencyFactory] No Recovery State, kill my self.
D/NPS_WSSNPS( 3602): [50.150621] dsServerSocket close
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3687): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 14 08:50:02 GMT+01:00 2016
E/Zygote  ( 3709): MountEmulatedStorage()
E/Zygote  ( 3709): v2
I/libpersona( 3709): KNOX_SDCARD checking this for 1000
I/libpersona( 3709): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3709 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3709): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Killing 2338:com.android.mms/u0a46 (adj 15): empty #31
I/SELinux ( 3709): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
E/SELinux ( 3709): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
I/KLMS-2.5.183: ( 3687): KLMSAbstractReciever(): onReceive().END.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/TimaKeyStoreProvider( 3709): TimaSignature is unavailable
D/ActivityThread( 3709): Added TimaKeyStore provider
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
I/KLMS-2.5.183: ( 3687): KLMSIntentService(): onCreate()
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3687): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.183: ( 3687): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.183: ( 3687): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/Zygote  ( 3726): MountEmulatedStorage()
I/libpersona( 3726): KNOX_SDCARD checking this for 10022
E/Zygote  ( 3726): v2
I/libpersona( 3726): KNOX_SDCARD not a persona
I/SELinux ( 3726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3726): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3726 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3687): KLMSIntentService(): BOOT_COMPLETED
D/AndroidRuntime( 3693): 
D/AndroidRuntime( 3693): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3693): CheckJNI is OFF
D/AndroidRuntime( 3693): readGMSProperty: start
D/AndroidRuntime( 3693): readGMSProperty: already setted!!
D/AndroidRuntime( 3693): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3693): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3693): readGMSProperty: end
D/AndroidRuntime( 3693): addProductProperty: start
D/TimaKeyStoreProvider( 3726): TimaSignature is unavailable
D/ActivityThread( 3726): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3687): KLMSIntentService(): onDestroy()
I/RlzPingService( 3368): Setting next ping for 1458546602316
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3755): MountEmulatedStorage()
E/Zygote  ( 3755): v2
I/libpersona( 3755): KNOX_SDCARD checking this for 1000
I/libpersona( 3755): KNOX_SDCARD not a persona
I/CameraApp( 3709): CameraApp.onCreate()... mFeature : null
I/testFeature( 3709): Feature.Feature(context)
I/testFeature( 3709): Feature.readInternalDefaultXml()
I/testFeature( 3709): ResetFeatureValue
I/DBG_DM  ( 3174): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
I/ActivityManager( 1016): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3755 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/CameraFirmware_broadcast( 3709): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3709): CameraApp.getAppFeature()...
I/ActivityManager( 1016): Killing 3024:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
E/AffinityControl( 3693): AffinityControl: registerfunction enter
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/SELinux ( 3755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3755): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 3693): Calling main entry com.android.commands.am.Am
D/btif_config_util( 2663): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
E/Zygote  ( 3770): MountEmulatedStorage()
E/Zygote  ( 3770): v2
I/libpersona( 3770): KNOX_SDCARD checking this for 1000
I/libpersona( 3770): KNOX_SDCARD not a persona
I/SELinux ( 3770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3770 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/TimaKeyStoreProvider( 3755): TimaSignature is unavailable
I/ActivityManager( 1016): Killing 3039:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
D/ActivityThread( 3755): Added TimaKeyStore provider
E/SELinux ( 3770): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
D/CountryDetector( 1016): No listener is left
E/Zygote  ( 3782): MountEmulatedStorage()
I/libpersona( 3782): KNOX_SDCARD checking this for 10100
E/Zygote  ( 3782): v2
I/libpersona( 3782): KNOX_SDCARD not a persona
I/SELinux ( 3782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3782 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3073:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
I/SELinux ( 3782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3782): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TimaKeyStoreProvider( 3770): TimaSignature is unavailable
D/ActivityThread( 3770): Added TimaKeyStore provider
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2949/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 3782): TimaSignature is unavailable
D/ActivityThread( 3782): Added TimaKeyStore provider
D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/FocusedStackFrame( 1016): Set to : 0
D/Launcher.HomeView( 1506): onPause
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 1506
D/Launcher( 1506): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : -2122120936
D/AndroidRuntime( 3693): Shutting down VM
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, uhalitest
E/MTPRx   ( 3770): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3806): MountEmulatedStorage()
E/Zygote  ( 3806): v2
I/libpersona( 3806): KNOX_SDCARD checking this for 10155
I/libpersona( 3806): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3806 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3097:com.sec.usbsettings/1000 (adj 15): empty #31
I/SELinux ( 3806): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3806): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3806): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/SettingsProvider( 1016): name = access_control_enabled
V/ActivityThread( 1506): updateVisibility : ActivityRecord{1c63c1bc token=android.os.BinderProxy@2c0f9996 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PackageIntentReceiver( 3782): ACTION_BOOT_COMPLETED
D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
D/SecContentProvider2( 1016): mCursor = null
D/SecContentProvider2( 1016): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1016): mCursor = null
V/MTPRx   ( 3770): sealedState: false
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/PackageIntentReceiver( 3782): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
V/MTPRx   ( 3770): sealedUsbMassStorageState: false
E/Zygote  ( 3817): MountEmulatedStorage()
E/Zygote  ( 3817): v2
I/libpersona( 3817): KNOX_SDCARD checking this for 10069
I/libpersona( 3817): KNOX_SDCARD not a persona
I/SELinux ( 3817): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3817 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3058:com.sec.dsm.system/1000 (adj 15): empty #31
I/SELinux ( 3817): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3817): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SettingsProvider( 1016): name = mtp_usb_connection_status
I/AudioService( 1016): getStreamVolume 3 index 0
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3806): TimaSignature is unavailable
D/ActivityThread( 3806): Added TimaKeyStore provider
I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
D/SettingsProvider( 1016): name = media_player_mode
D/SettingsProvider( 1016): name = mtp_usb_conditions_met
E/Zygote  ( 3835): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3835 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 3835): v2
I/libpersona( 3835): KNOX_SDCARD checking this for 10101
I/SELinux ( 3835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3835): KNOX_SDCARD not a persona
I/SELinux ( 3835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Killing 3114:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/SettingsProvider( 1016): name = mtp_running_status
D/SettingsProvider( 1016): name = media_mount_count
D/Launcher.HomeView( 1506): onStop
I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
V/ActivityThread( 1506): updateVisibility : ActivityRecord{1c63c1bc token=android.os.BinderProxy@2c0f9996 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
E/SELinux ( 3835): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/SettingsProvider( 1016): name = mtp_sync_alive
I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
D/TimaKeyStoreProvider( 3817): TimaSignature is unavailable
D/SettingsProvider( 1016): name = sdcard_launch
D/ActivityThread( 3817): Added TimaKeyStore provider
I/art     (  303): Explicit concurrent mark sweep GC freed 8726(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 669us total 31.920ms
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/SettingsProvider( 1016): name = boot_time_connected
I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
D/PersonaManager( 1016): isKioskContainerExistOnDevice
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 18.332ms
D/SettingsProvider( 1016): name = mtp_open_session
I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
W/art     ( 3693): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 19.200ms
,D/Launcher( 1506): onTrimMemory. Level: 20
I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 3835): TimaSignature is unavailable
,D/ActivityThread( 3835): Added TimaKeyStore provider
,D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1016): [SO] activate (ident=0xb86b3fa8, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/SensorManager( 1016): unregisterListener ::   
I/PCWCLIENTTRACE_PushUtil( 3487): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3487): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3487): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3487): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3487): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3487): ACTION_BOOTUP - Push type: [SPP, GCM]
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1016): [SO] changed settle time [1]
D/SensorService( 1016): [SO] setDelay [66000000]
D/SensorService( 1016): [SO] activate (ident=0xb86b3fa8, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/FactoryTestApp( 2644): [DummyFtClient$onDestroy](2644) Destroy DummyFtClient service
,D/FactoryTestApp( 2644): [Support$Values.getString](2644) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2644): [ModuleCommon$isConnectionModeNone](2644) mConnectionMode = gsm
I/FactoryTestApp( 2644): [ModuleCommon$isRunningFtClient](2644) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2644): [DummyFtClient$onDestroy](2644) kill process
I/Process ( 2644): Sending signal. PID: 2644 SIG: 9
,W/libprocessgroup( 1016): failed to open /acct/uid_10046/pid_2338/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10159/pid_3073/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10048/pid_3039/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10157/pid_3024/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3097/cgroup.procs: No such file or directory
,I/System.out( 3324): pool-10-thread-1 calls detatch()
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3058/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3114/cgroup.procs: No such file or directory
,W/PCWCLIENTTRACE_AccountUtil( 3487): [hasSamungAccount] - No Samsung Account
,D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,I/ActivityManager( 1016): Process com.sec.factory (pid 2644)(adj 0) has died(150,1104)
,D/FileShare-Server( 3817): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3487): [GetString-S]
,D/SensorService( 1016): [SO] 0.134 0.402 10.132
D/SensorService( 1016): [SO] [100 -> 255]
,I/ReactiveServiceManager( 3487): Supported : 1
,I/WebViewFactory( 3806): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/,
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,W/ContextImpl( 3301): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3301): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3301): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,I/LibraryLoader( 3806): Time to load native libraries: 2 ms (timestamps 2036-2038)
I/LibraryLoader( 3806): Expected native library version number "",actual native library version number ""
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,V/WebViewChromiumFactoryProvider( 3806): Binding Chromium to main looper Looper (main, tid 1) {9038f3d}
,I/LibraryLoader( 3806): Expected native library version number "",actual native library version number ""
,I/chromium( 3806): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/BrowserStartupController( 3806): Initializing chromium process, singleProcess=true
,W/art     ( 3806): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3806): ApplicationContext is null in ApplicationStatus
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 9
,D/QSEECOMAPI: ( 1016): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1016): QSEECom_shutdown_app, app_id = 9
,E/terrier ( 1016): handleString: Failed to handle string(-4)
E/terrier ( 1016): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 3487): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3487): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 3487): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3487): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3487): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 3487): [ensureRegistration] - No Samsung account
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3893): MountEmulatedStorage()
E/Zygote  ( 3893): v2
I/libpersona( 3893): KNOX_SDCARD checking this for 10031
I/libpersona( 3893): KNOX_SDCARD not a persona
I/SELinux ( 3893): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3893): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3893 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3008:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,E/SELinux ( 3893): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/chromium( 3806): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 3806): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 3806): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/Adreno-EGL( 3806): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3806): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3806): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3806): Local Branch: 
I/Adreno-EGL( 3806): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3806): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3806):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/TimaKeyStoreProvider( 3893): TimaSignature is unavailable
,D/ActivityThread( 3893): Added TimaKeyStore provider
,I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/8)
,W/libprocessgroup( 1016): failed to open /acct/uid_10085/pid_3008/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ResourcesManager( 3893): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Killing 3157:com.sec.android.diagmonagent/1000 (adj 15): empty #31,
,W/ContextImpl( 1939): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,D/SecUISvc( 1939): Service started flags 0 startId 1
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SecUISvc( 1939): Thread created.
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3929): MountEmulatedStorage()
E/Zygote  ( 3929): v2
I/libpersona( 3929): KNOX_SDCARD checking this for 10028
I/libpersona( 3929): KNOX_SDCARD not a persona
I/SELinux ( 3929): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
D/AndroidHttpClient( 3301): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
D/AndroidHttpClient( 3301): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 3301): Thread-496(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 3301): Thread-496(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3301): Thread-496(ApacheHTTPLog):isShipBuild true
I/System.out( 3301): Thread-496(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3301): Thread-496(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SELinux ( 3929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/EnterpriseController(  274): uids 10166
D/EnterpriseController(  274): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0,
D/Netd    (  274): getNetworkForDns: using netid 502 for uid 10166
,E/SELinux ( 3929): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3929 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3157/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3929): TimaSignature is unavailable
,D/ActivityThread( 3929): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 3192:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,I/DBG_DM  ( 3174): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup( 1016): failed to open /acct/uid_10150/pid_3192/cgroup.procs: No such file or directory
,I/VlingoApplication( 3893): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,I/VlingoAndroidCore( 3893): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,W/chromium( 3806): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/VlingoApplication( 3893): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3893): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/ActivityManager( 1016): Killing 1594:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/DialogFlow( 3893): initQueue()
,W/art     ( 3806): Attempt to remove local handle scope entry from IRT, ignoring
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1016): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3955): MountEmulatedStorage(),
E/Zygote  ( 3955): v2
I/libpersona( 3955): KNOX_SDCARD checking this for 1000
I/libpersona( 3955): KNOX_SDCARD not a persona
,I/SELinux ( 3955): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3955 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3955): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3955): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/AwContents( 3806): onDetachedFromWindow called when already detached. Ignoring
,D/TimaKeyStoreProvider( 3955): TimaSignature is unavailable
,D/ActivityThread( 3955): Added TimaKeyStore provider
E/Zygote  ( 3971): MountEmulatedStorage()
E/Zygote  ( 3971): v2
I/libpersona( 3971): KNOX_SDCARD checking this for 10032
I/System.out( 3301): Thread-496 calls detatch()
I/libpersona( 3971): KNOX_SDCARD not a persona
I/SELinux ( 3971): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3971): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3971): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3971 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3222:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,D/PhoneWindow( 3806): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3806): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 3806): CordovaWebView is running on device made by: samsung
,D/TimaKeyStoreProvider( 3971): TimaSignature is unavailable
,D/ActivityThread( 3971): Added TimaKeyStore provider
,W/art     ( 3806): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3806): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_1594/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3222/cgroup.procs: No such file or directory
,I/Gmail   ( 3835): getAccountsCursor
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 3835): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 3955): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 ,
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3999): MountEmulatedStorage()
E/Zygote  ( 3999): v2
I/libpersona( 3999): KNOX_SDCARD checking this for 1000
I/libpersona( 3999): KNOX_SDCARD not a persona
,I/SELinux ( 3999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3999): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3999 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/OpenGLRenderer( 3806): Render dirty regions requested: true
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,D/TimaKeyStoreProvider( 3999): TimaSignature is unavailable
,D/ActivityThread( 3999): Added TimaKeyStore provider
,D/PhoneWindow( 3806): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3806): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3999): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,D/InputDispatcher( 1016): Focus entered window: 3806
,E/Zygote  ( 4018): MountEmulatedStorage()
E/Zygote  ( 4018): v2
I/libpersona( 4018): KNOX_SDCARD checking this for 10033
I/libpersona( 4018): KNOX_SDCARD not a persona
,I/SELinux ( 4018): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4018): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4018): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4018 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3277:com.policydm/1000 (adj 15): empty #31
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3806): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 3806): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3806): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 3806): Enabling debug mode 0
,D/TimaKeyStoreProvider( 4018): TimaSignature is unavailable
,D/ActivityThread( 4018): Added TimaKeyStore provider
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1181): There is/are notification(s) 
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 3806): Timeline: Activity_idle id: android.os.BinderProxy@36cd652e time:43064
,I/SamsungIME( 1827): getCurrentCandidateView
,I/ActivityManager( 1016): Displayed Component not be shown by security: +1s435ms
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1016): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{361c2c44 u0 com.test.thalitest/.MainActivity t12} time:43078
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3277/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/Gmail   ( 3835): Error finding the version of the Email provider.....
E/Gmail   ( 3835): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3835): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3835): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3835): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3835): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3835): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3835): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3835): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 3835): We do not support migrating this version of the Email provider.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,I/Gmail   ( 3835): getAccountsCursor
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4051): MountEmulatedStorage(),
,I/libpersona( 4051): KNOX_SDCARD checking this for 10104
E/Zygote  ( 4051): v2
,I/libpersona( 4051): KNOX_SDCARD not a persona
I/SELinux ( 4051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4051): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4051): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4051 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/GoogleHttpClient( 1668): GMS http client unavailable, use old client
,D/Finsky  ( 3929): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/TimaKeyStoreProvider( 4051): TimaSignature is unavailable
,D/ActivityThread( 4051): Added TimaKeyStore provider
,W/ResourcesManager( 4051): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SurfaceFlinger(  257): id=10 Removed uhalitest (7/8)
,I/SurfaceFlinger(  257): id=10 Removed uhalitest (-2/8)
,D/SamsungIME( 1827): Dismiss ExpandCandiate
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,I/DBG_DM  ( 3174): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 36928(1955KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 26MB/40MB, paused 2.677ms total 165.794ms
,W/BindingManager( 3806): Cannot call determinedVisibility() - never saw a connection for the pid: 3806
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 3835): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@77375de that was originally bound here
E/ActivityThread( 3835): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@77375de that was originally bound here
E/ActivityThread( 3835): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3835): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3835): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3835): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3835): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3835): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3835): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3835): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3835): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3835): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3835): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3835): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3835): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3835): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3835): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3835): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1016): Unbind failed: could not find connection for android.os.BinderProxy@29cdc4ad
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 3835): Observing account changes for notifications
,D/TimaService( 1016): TIMA: in getTimaVersion
,D/TimaService( 1016): TIMA3: KeyStore3_init
,D/TimaService( 1016): TIMA: in getTimaVersion
E/TLC_TZ_KEYSTORE: ( 1016): Inside TZ_KEYSTORE_initialize()
I/TLC_TZ_KEYSTORE: ( 1016): creating new keystore context...
,I/TLC_TZ_KEYSTORE: ( 1016): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1016): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1016): process = tima_key, process_strlen = 8
,I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 1088 = 0x440
,I/TZ: qc_tlc_communication( 1016): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x880
,D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 10
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1016): ctx = 0xb88d9198, comm = 0xb89daa38, sendmsg = 0xa0543000, recvmsg = 0xa0543440
I/TZ_init: ( 1016): TZ_init: sending initialization request...
,D/Finsky  ( 3929): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/ResourcesManager( 4018): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4018): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/TZ_init: ( 1016): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1016): trustlet initialization failed
I/TZ_init: ( 1016): TZ_init_START...
,E/SQLiteLog( 3835): (283) recovered 85 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/TZ_init: ( 1016): TZ_init_with_data: sending initialization request...
,I/TZ_init: ( 1016): TZ_init: successful initialization
D/QSEECOMAPI: ( 1016): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1016): QSEECom_shutdown_app, app_id = 10
,E/TLC_TZ_KEYSTORE: ( 1016): Count : 1, Ret : 0
,W/art     ( 3893): Suspending all threads took: 12.141ms
,E/SMD     (  286): DCD OFF,
,D/JsMessageQueue( 3806): Set native->JS mode to OnlineEventsBridgeMode
,W/ResourcesManager( 4018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Settings( 3929): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4018): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4018): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4018): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/Settings( 3929): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SamsungIME( 1827): getDebugLevel  : 0x4f4c
,W/ContextImpl( 3999): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4098): MountEmulatedStorage(),
E/Zygote  ( 4098): v2
I/libpersona( 4098): KNOX_SDCARD checking this for 1000
I/libpersona( 4098): KNOX_SDCARD not a persona,
I/SELinux ( 4098): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4098 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 4098): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4098): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/System.out( 3893): INFO:Resource not found:/Common.properties Using default values
,E/File    ( 3835): fail readDirectory() errno=2
,D/TimaKeyStoreProvider( 4098): TimaSignature is unavailable
,D/ActivityThread( 4098): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3955): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3955): Resource data:2131165186
,W/ResourcesManager( 3955): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3955): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3955): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,I/Gmail   ( 3835): notifyAccountChanged
,W/ResourcesManager( 4098): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/art     ( 1668): Explicit concurrent mark sweep GC freed 4471(197KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 795us total 28.704ms
,I/AMMetaDataParserService( 3955): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,D/jxcore_app_log( 3806): JniHelper::setJavaVM(0xb7f7f450), pthread_self() = -1202817336
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3806): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3806):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3806):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3806):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3806):     - Handshake required: true
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3806): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39b85d5 added. We now have 1 listener(s)
I/AMMetaDataParserService( 3955): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,W/SQLiteConnectionPool( 1668): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Gmail   ( 3835): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/SEAMService( 1016):  hashset_to_int_array returning null
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/SEAMService( 1016):  hashset_to_int_array returning null
,I/AMMetaDataParserService( 3955): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,D/Volley  ( 3929): [578] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3929): [571] DiskBasedCache.clear: Cache cleared.
,I/Gmail   ( 3835): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806): setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3806): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3806): setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,E/SQLiteLog( 3999): (284) automatic index on seams_container_info(seams_container_id)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3806): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3806): setHandshakeRequired: true -> false
E/SQLiteLog( 3999): (284) automatic index on seams_container_info(sp_id)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806):     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806):     - Scan report delay in milliseconds: 500
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3433378 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3806): addListener: New listener added - the number of listeners is now 1
,W/SEAMService( 1016):  hashset_to_int_array returning null
,V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Ads     ( 3929): Skipping gmscore version check
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1827): getDebugLevel  : 0x4f4c
,V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 4098): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
W/ContextImpl( 3955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,I/ActivityManager( 1016): Killing 3240:com.google.android.configupdater/u0a86 (adj 15): empty #31
,I/Gmail   ( 3835): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3835): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/ActivityManager( 1016): startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3806): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3806): setScanMode: 1 -> 2
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1827): KeybaordView init() : load resources
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955): Resource data:2131034113
,I/F_PHONE ( 4098): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 4098): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,I/Babel   ( 4051): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4051): MmsConfig.loadMmsSettings
I/Babel   ( 4051): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 4051): MmsConfig.loadFromDatabase
,I/SamsungIME( 1827): getCurrentKeyboard
,I/SamsungIME( 1827): getTextKeyboard
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ResourcesManager( 3955): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3955): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,E/Babel   ( 4051): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4051): MmsConfig.loadFromResources
,E/Babel   ( 4051): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4051): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/chromium( 3806): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3955): took 2.370000ms for 0*0 texture 0
,D/Finsky  ( 3929): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3929): [1] Libraries$2.run: Finished loading 1 libraries.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,I/GFX generate_partition_tables( 3955): took 6.131302ms for 0*0 texture 0
,I/GFX raster( 3955): took 9.919323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb833c2c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8353870 counterpartCT=4 counterpartW=96 counterparth=96
,D/SamsungIME( 1827): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/DBG_DM  ( 3174): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/F_PHONE ( 4098): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 4098): default registerAction()
I/F_PHONE ( 4098): [[com.sec.bcservice]] sendPendingMessage()
,D/FileApkUtils( 2077): Optimizing (staging complete)
D/FileApkUtils( 2077): Optimizing: DynamiteModules-prod.apk [0224a548494bce36274e23f9f1b42d4fbe3d4d8de53a7872e503f8974e43c3c3]
,I/art     ( 2077): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Settings( 4051): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DexOptUtils( 2077): Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk appears to be unoptimized.
D/DexOptUtils( 2077): Lollipop platform, using <isa> directory.
,D/DexOptUtils( 2077): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 2077): Primary ABI of odexing process is armeabi-v7a
I/AMMetaDataParserService( 3955): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/Finsky  ( 3929): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ChimeraCfgMgr( 1857): Reading stored module config
,D/SSRM:n  ( 1016): SIOP:: AP = 360
,D/WearableService( 1857): callingUid 10012, callindPid: 1857
,D/Finsky  ( 3929): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/GmsWearableNodeHelper( 1857): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 1.121250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb833c2c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb835b968 counterpartCT=4 counterpartW=96 counterparth=96
,I/Babel_StickerModule( 4051): App launched.
,I/AMMetaDataParserService( 3955): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/dex2oat ( 4144): ----------------------------------------------------,
I/dex2oat ( 4144): <SS>: S T A R T I N G . . .
I/dex2oat ( 4144): <SS>: Zip is absent. Canceled.
I/dex2oat ( 4144): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk --oat-fd=40 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3955): took 2.654167ms for 0*0 texture 0
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GFX generate_partition_tables( 3955): took 7.782084ms for 0*0 texture 0
,I/GFX raster( 3955): took 11.483854ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8358338 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8358490 counterpartCT=4 counterpartW=96 counterparth=96
,I/Process ( 4018): Sending signal. PID: 4018 SIG: 9
,I/AMMetaDataParserService( 3955): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/InstanceID/Rpc( 2077): Found 10012
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3487): unregister AuthInfo UpdateReceiver v2.0
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.707656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb835cd00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb835ce58 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/ActivityManager( 1016): Process com.sec.android.app.sns3 (pid 4018)(adj 0) has died(42,1157)
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/GFX raster( 3955): took 1.128386ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb835ab68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb835ac30 counterpartCT=4 counterpartW=96 counterparth=96
,V/Babel   ( 4051): babel boot account: SMS
,I/AMMetaDataParserService( 3955): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532,
,W/Babel   ( 4051): EsDatabaseHelper.static should not be called on main thread [called on main thread],
,W/Babel   ( 4051): java.lang.Exception,
W/Babel   ( 4051): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4051): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 4051): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4051): 	at ckh.a(SourceFile:67)
W/Babel   ( 4051): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4051): 	at bhn.a(SourceFile:301)
W/Babel   ( 4051): 	at bhn.a(SourceFile:137)
W/Babel   ( 4051): 	at bhn.a(SourceFile:126)
,W/Babel   ( 4051): 	at bhn.a(SourceFile:159)
W/Babel   ( 4051): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4051): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4051): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4051): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4051): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4051): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4051): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4051): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4051): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4051): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4051): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/Babel   ( 4051): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
W/Babel   ( 4051): java.lang.Exception
W/Babel   ( 4051): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4051): 	at aes.a(SourceFile:145)
W/Babel   ( 4051): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4051): 	at ckh.a(SourceFile:67)
W/Babel   ( 4051): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4051): 	at bhn.a(SourceFile:301)
W/Babel   ( 4051): 	at bhn.a(SourceFile:137)
W/Babel   ( 4051): 	at bhn.a(SourceFile:126)
W/Babel   ( 4051): 	at bhn.a(SourceFile:159)
W/Babel   ( 4051): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4051): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4051): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4051): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4051): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4051): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4051): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4051): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4051): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4051): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4051): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/Zygote  ( 4156): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4156 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
E/Zygote  ( 4156): v2
,I/libpersona( 4156): KNOX_SDCARD checking this for 10034
I/libpersona( 4156): KNOX_SDCARD not a persona
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 4156): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4156): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4156): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.626823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb835c3f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb835c548 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4156): TimaSignature is unavailable
,D/ActivityThread( 4156): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3955): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.777552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb835ae90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb835af58 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3955): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.700886ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb835ab08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb833c388 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955): Resource data:2131034113
,I/AMMetaDataParserService( 3955): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,I/GFX raster( 3955): took 0.810209ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb833c2c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb833c388 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3955): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,V/Babel   ( 4051): babel boot account: thalitester@gmail.com
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.822970ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb833c2c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb833c388 counterpartCT=4 counterpartW=96 counterparth=96
,D/ChimeraCfgMgr( 2077): Reading stored module config
,I/AMMetaDataParserService( 3955): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/Babel   ( 4051): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/ResourcesManager( 3971): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.782656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8358338 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb833c388 counterpartCT=4 counterpartW=96 counterparth=96
,W/Babel   ( 4051): java.lang.Exception
W/Babel   ( 4051): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4051): 	at aes.a(SourceFile:145)
W/Babel   ( 4051): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4051): 	at ckh.a(SourceFile:67)
W/Babel   ( 4051): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4051): 	at bhn.a(SourceFile:301)
W/Babel   ( 4051): 	at bhn.a(SourceFile:137)
W/Babel   ( 4051): 	at bhn.a(SourceFile:126)
W/Babel   ( 4051): 	at bhn.a(SourceFile:159)
W/Babel   ( 4051): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4051): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4051): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4051): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4051): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4051): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4051): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4051): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4051): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4051): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4051): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/AMMetaDataParserService( 3955): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/libprocessgroup( 1016): failed to open /acct/uid_10086/pid_3240/cgroup.procs: No such file or directory
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BootCompletedReceiver( 2077): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 2077): Got an BootCompleted event.
,I/DBG_DM  ( 3174): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/GFX raster( 3955): took 0.782812ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb835cd00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb833c388 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/GCM     ( 2077): COMPAT: Multi user not supported
,I/AMMetaDataParserService( 3955): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/libpersona( 4180): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4180): MountEmulatedStorage()
I/libpersona( 4180): KNOX_SDCARD not a persona
E/Zygote  ( 4180): v2
,I/SELinux ( 4180): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4180): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4180): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1016): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4180 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 3324:com.dropbox.android/u0a92 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BootCompletedReceiver( 2077): Will NOT schedule AdAttestation signal task because it's disabled.
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,I/GFX raster( 3955): took 0.876458ms for 96*96 texture 0
,D/GCM     ( 1857): COMPAT: Multi user not supported
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb835ab68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb833c388 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 4180): TimaSignature is unavailable
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4180): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3955): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.621666ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb835c3f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb833c388 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4311, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GCoreUlr( 2077): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GFX raster( 3955): took 1.230000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb835ae90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb833c388 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1443): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1443): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/AMMetaDataParserService( 3955): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 2663): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2663): Disconnected process message: 10
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.529791ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb833c388 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb835aac8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,I/AMMetaDataParserService( 3955): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4197): MountEmulatedStorage(),
,E/Zygote  ( 4197): v2,
I/libpersona( 4197): KNOX_SDCARD checking this for 1000
I/libpersona( 4197): KNOX_SDCARD not a persona,
I/SELinux ( 4197): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4197): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4197): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4197 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/art     (  303): Explicit concurrent mark sweep GC freed 8764(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 38.623ms
,D/TimaKeyStoreProvider( 4197): TimaSignature is unavailable
D/ActivityThread( 4197): Added TimaKeyStore provider
,I/Gmail   ( 3835): getAccountsCursor
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 17.188ms
,W/QCamera2Factory(  280): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  280): getCameraInfo: X
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 17.366ms
,I/art     ( 3806): Background sticky concurrent mark sweep GC freed 23153(2MB) AllocSpace objects, 0(0B) LOS objects, 9% free, 18MB/20MB, paused 1.265ms total 101.625ms
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3955): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3955): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955): Resource data:2131034112
W/QCamera2Factory(  280): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  280): getCameraInfo: X
I/AMMetaDataParserService( 3955): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.647916ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb831ebe0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83181a8 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3324/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3955): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,W/jxcore-log( 3806): Initializing JXcore engine
W/jxcore-log( 3806): JXcore engine is ready
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.609062ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb831ebe0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80c7800 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 4051): Unrecognized profile 2130706433 for video/avc
,I/CheckinService( 2077): Disabling old GoogleServicesFramework version
,W/AudioCapabilities( 4051): Unsupported mime audio/evrc
,W/AudioCapabilities( 4051): Unsupported mime audio/qcelp
,I/AMMetaDataParserService( 3955): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.650625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb833c120 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83181a8 counterpartCT=4 counterpartW=96 counterparth=96
,E/audit   ( 1885): type=1400 msg=audit(1457941806.975:205): avc:  denied  { ioctl } for  pid=4128 comm="Thread-569" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1885):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1885): type=1300 msg=audit(1457941806.975:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9c2a98f8 items=0 ppid=303 ppcomm=main pid=4128 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-569" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1885): type=1320 msg=audit(1457941806.975:205): 
,D/SystemUpdateService( 2077): onCreate
,I/DBG_POLICYDM( 4180): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4180): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/AMMetaDataParserService( 3955): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,W/jxcore-log( 3806): Starting JXcore engine
,W/ResourcesManager( 3971): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3955): took 0.632083ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb835c3f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80c7800 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528,
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3971): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,E/Zygote  ( 4222): MountEmulatedStorage(),
E/Zygote  ( 4222): v2,
W/ResourcesManager( 3971): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 1016): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4222 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3260:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/libpersona( 4222): KNOX_SDCARD checking this for 1000
I/libpersona( 4222): KNOX_SDCARD not a persona,
,I/SELinux ( 4222): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4222): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4222): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955): Resource data:2131034113
,D/SystemUpdateService( 2077): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/AMMetaDataParserService( 3955): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.825521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb83181a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb831c2c8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4222): TimaSignature is unavailable
,D/ActivityThread( 4222): Added TimaKeyStore provider
,W/AudioCapabilities( 4051): Unsupported mime audio/mpeg-L1
,I/AMMetaDataParserService( 3955): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 1.376145ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb83181a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb80c7800 counterpartCT=4 counterpartW=96 counterparth=96
,W/jxcore-log( 3806): Platform android
W/jxcore-log( 3806): 
,W/jxcore-log( 3806): Process ARCH arm
W/jxcore-log( 3806): 
,I/AMMetaDataParserService( 3955): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/DBG_POLICYDM( 4180): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4180): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4180): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.600625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb831c2c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80c7800 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/AudioCapabilities( 4051): Unsupported mime audio/mpeg-L2
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/AudioCapabilities( 4051): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4051): Unsupported mime audio/x-ima
,W/AudioCapabilities( 4051): Unsupported mime audio/qcelp
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/AudioCapabilities( 4051): Unsupported mime audio/evrc
,I/DBG_POLICYDM( 4180): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/KnoxSetupWizardDbHelper( 4222): dbMigrationFlag : false
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.624792ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb831ebe0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80c7800 counterpartCT=4 counterpartW=96 counterparth=96
,V/AuthZen ( 2077): Handling intent: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ShortcutReceiver( 4222):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_3260/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4180): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/AMMetaDataParserService( 3955): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/KnoxShortcutUtil( 4222): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4222):  KnoxContainerVersion 2.4.0
,D/ShortcutReceiver( 4222):  shortcut migration not required 
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,I/DBG_POLICYDM( 4180): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 4180): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4180): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 4180): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/ActivityManager( 1016): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4243 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 3405:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,E/Zygote  ( 4243): MountEmulatedStorage(),
I/libpersona( 4243): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4243): v2
I/libpersona( 4243): KNOX_SDCARD not a persona,
I/SELinux ( 4243): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4243): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4243): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.916667ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb80c7800 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8508210 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4258 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 3417:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,E/Zygote  ( 4258): MountEmulatedStorage(),
D/TimaKeyStoreProvider( 4243): TimaSignature is unavailable
,D/ActivityThread( 4243): Added TimaKeyStore provider
E/Zygote  ( 4258): v2
I/libpersona( 4258): KNOX_SDCARD checking this for 10035
I/libpersona( 4258): KNOX_SDCARD not a persona
I/SELinux ( 4258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4258): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3955): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/DBG_DM  ( 3174): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,D/TimaKeyStoreProvider( 4258): TimaSignature is unavailable
,D/ActivityThread( 4258): Added TimaKeyStore provider
,W/VideoCapabilities( 4051): Unsupported mime video/wvc1
,W/VideoCapabilities( 4051): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 4051): Unrecognized profile/level 32768/2 for video/mp4v-es
,E/KnoxSetupWizardClient( 4243): isShipMode : 1
I/KnoxSetupWizardClient( 4243): onReceive : android.intent.action.BOOT_COMPLETED
,W/VideoCapabilities( 4051): Unsupported mime video/wvc1
,W/VideoCapabilities( 4051): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 4051): Unsupported mime video/x-ms-wmv7,
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.744792ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb835c3f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb833a4a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528,
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.747447ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb835ae90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb833bcc8 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 4051): Unsupported mime video/x-ms-wmv8
,I/AMMetaDataParserService( 3955): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast,
W/VideoCapabilities( 4051): Unsupported mime video/mp43
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4278): MountEmulatedStorage(),
E/Zygote  ( 4278): v2
I/libpersona( 4278): KNOX_SDCARD checking this for 10107
I/libpersona( 4278): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4278 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 1250:com.android.defcontainer/u0a4 (adj 15): empty #31
I/SELinux ( 4278): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4278): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3955): took 0.662760ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb833c388 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8508048 counterpartCT=4 counterpartW=96 counterparth=96
,E/SELinux ( 4278): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3955): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
W/ContextImpl( 3955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.sdk.cover.MODE
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
E/SMD     (  286): DCD OFF
,D/AuthZenEventHandler( 2077): Handling event: android.intent.action.BOOT_COMPLETED
,I/jxcore-log( 3806): JXcore Cordova bridge is ready!
I/jxcore-log( 3806): 
,W/jxcore-log( 3806): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 3806): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955,): Resource data:2131165203
I/chromium( 3806): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,I/SystemUpdateService( 2077): cancelUpdate (empty URL)
I/SystemUpdateService( 2077): active receiver: disabled
,W/libprocessgroup( 1016): failed to open /acct/uid_10003/pid_3417/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3405/cgroup.procs: No such file or directory
,W/VideoCapabilities( 4051): Unsupported mime video/sorenson
,W/ResourcesManager( 3955): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3955): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3955): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,E/SPPClientService( 4258): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4258): [PushClientApplication] Push log off : This is Ship build version
,D/TimaKeyStoreProvider( 4278): TimaSignature is unavailable
,D/ActivityThread( 4278): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10004/pid_1250/cgroup.procs: No such file or directory
,W/System.err( 4243): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 4243): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4243): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4243): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4243): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 4243): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4243): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,E/SPPClientService( 4258): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3955): took 2.923697ms for 0*0 texture 0
,W/VideoCapabilities( 4051): Unsupported mime video/mp4v-esdp
,I/GFX generate_partition_tables( 3955): took 10.708433ms for 0*0 texture 0
,I/GFX raster( 3955): took 14.531245ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb83539e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb83313c8 counterpartCT=4 counterpartW=96 counterparth=96
,D/SPPClientService( 4258): PushLog.txt file is not deleted.
,D/SPPClientService( 4258): PushLog.txt file is not deleted.
,D/SPPClientService( 4258): ============PushLog. stop!
,I/CheckinService( 2077): Checking schedule, now: 1457941807873 next: 1458246240395
I/CheckinService( 2077): active receiver: disabled
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,I/AMMetaDataParserService( 3955): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4296): MountEmulatedStorage()
E/Zygote  ( 4296): v2
I/libpersona( 4296): KNOX_SDCARD checking this for 10041
I/libpersona( 4296): KNOX_SDCARD not a persona
,I/SELinux ( 4296): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4296): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4296): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4296 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3445:com.fmm.dm/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4296): TimaSignature is unavailable
,W/BaseAppContext( 2077): Using Auth Proxy for data requests.
,D/ActivityThread( 4296): Added TimaKeyStore provider
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.763854ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb86b3920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8509090 counterpartCT=4 counterpartW=96 counterparth=96
,I/SecDataIO(  256): Write to block
,I/VideoCapabilities( 4051): Unsupported profile 4 for video/mp4v-es
,I/AMMetaDataParserService( 3955): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,D/GCM     ( 1857): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ContextImpl( 2628): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,D/EnterpriseController(  274): uids 10012
D/EnterpriseController(  274): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  274): getNetworkForDns: using netid 502 for uid 10012
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3174): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS,
,I/DBG_DM  ( 3174): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1,
,E/DBG_DM  ( 3174): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/DBG_POLICYDM( 4180): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT,
I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/DBG_POLICYDM( 4180): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/GFX raster( 3955): took 0.806145ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb86b3920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb86b4c28 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4180): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 4180): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,D/SystemUpdateService( 2077): onDestroy
,I/AMMetaDataParserService( 3955): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,I/Process ( 2628): Sending signal. PID: 2628 SIG: 9
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3445/cgroup.procs: No such file or directory
,I/GCoreUlr( 1857): DispatchingService.onCreate()
,W/art     ( 3893): Suspending all threads took: 34.822ms
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/DBG_POLICYDM( 4180): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.782344ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb86b3920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb86b5da0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,I/art     ( 1668): Explicit concurrent mark sweep GC freed 4323(165KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 798us total 27.036ms
,E/BaseAppContext( 2077): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,I/GCM     ( 1857): GCM config loaded
,V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1016): Process com.sec.android.app.sysscope (pid 2628)(adj 0) has died(34,1134)
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,W/dex2oat ( 4144): Verification of void android.support.v4.app.o$a.a(java.lang.String, java.io.PrintWriter) took 139.901ms
,I/Gmail   ( 3835): getAccountsCursor
,I/SA      ( 4296): [SSP] onCreated
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 4180): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 4180): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_DM  ( 3174): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,I/DBG_DM  ( 3174): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3174): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4180): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 4180): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 4180): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4180): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 4180): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 4180): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.651509ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb86b6dc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86b7060 counterpartCT=4 counterpartW=96 counterparth=96
,I/AuthZen ( 2077): Fetching signing key...
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{33281c2c u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 41331(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 26MB/40MB, paused 2.916ms total 172.402ms
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/GCoreFlp( 1857): No location to return for getLastLocation()
,W/dex2oat ( 4144): Verification of boolean com.google.android.gms.ads.internal.formats.k.onTouch(android.view.View, android.view.MotionEvent) took 173.221ms
,W/FusedLocationProvider( 1857): location=null
,V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
,I/ActivityManager( 1016): Killing 3469:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,I/AuthZen ( 2077): Signing key fetched successfully!
,I/SA      ( 4296): [TPM] There is no property file
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 4296): [SCU] isHaveSA() - false
,I/AMMetaDataParserService( 3955): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/SA      ( 4296): [TPM] getModelProperty : null
,I/SA      ( 4296): [TPM] getCSCProperty : null
,I/DBG_POLICYDM( 4180): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/SA      ( 4296): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4296): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4296): [DM] TFT FEATURE: false
I/DBG_POLICYDM( 4180): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/SA      ( 4296): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,I/SA      ( 4296): [DM] init START
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,W/GCoreFlp( 1857): No location to return for getLastLocation()
,W/FusedLocationProvider( 1857): location=null
,W/libprocessgroup( 1016): failed to open /acct/uid_10060/pid_3469/cgroup.procs: No such file or directory
,W/Auth    ( 1857): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/SA      ( 4296): [DM] This device is not a Vodafone
,W/art     ( 3955): Suspending all threads took: 61.644ms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/BaseAppContext( 2077): Using Auth Proxy for data requests.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GCoreUlr( 1857): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/DBG_POLICYDM( 4180): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,W/dex2oat ( 4144): Verification of void com.google.android.gms.ads.internal.purchase.c.b() took 143.925ms
,W/ResourceType( 4296): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4296): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/dex2oat ( 4144): Verification of java.lang.Object[] com.google.android.gms.ads.internal.purchase.a.newArray(int) took 152.696ms
,W/ResourceType( 4296): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4296): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4296): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4296): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4296): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4296): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4296): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4296): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4296): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4296): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ResourceType( 4296): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4296): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4296): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4296): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4296): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4296): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4296): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,I/DBG_POLICYDM( 4180): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/14/08:50:08
W/ResourceType( 4296): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4296): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
I/DBG_POLICYDM( 4180): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,W/ResourceType( 4296): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4296): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4296): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
I/DBG_POLICYDM( 4180): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
W/ResourceType( 4296): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 4296): [SCU] isHaveSA() - false
I/SA      ( 4296): support phone number id : false
I/SA      ( 4296): [DM] Supports Ref Jpn : true
,I/SA      ( 4296): [DM] init END
,W/dex2oat ( 4144): Verification of void com.google.android.gms.ads.internal.request.AdRequestInfoParcel.<init>(android.os.Bundle, com.google.android.gms.ads.internal.client.AdRequestParcel, com.google.android.gms.ads.internal.client.AdSizeParcel, java.lang.String, android.content.pm.ApplicationInfo, android.content.pm.PackageInfo, java.lang.String, java.lang.String, java.lang.String, com.google.android.gms.ads.internal.util.client.VersionInfoParcel, android.os.Bundle, int, java.util.List, java.util.List, android.os.Bundle, boolean, android.os.Messenger, int, int, float, java.lang.String, long, java.lang.String, java.util.List, java.lang.String, com.google.android.gms.ads.internal.formats.NativeAdOptionsParcel, long, com.google.android.gms.ads.internal.request.CapabilityParcel, java.lang.String, float, int, int) took 170.460ms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/SA      ( 4296): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4296): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,I/GAV2    ( 3835): Thread[GAThread,5,main]: No campaign data found.
,D/ActivityManager( 1016): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SA      ( 4296): [OR] onReceive END
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/a       ( 2077): Opening database auth.proximity.permit_store...,
I/SA      ( 4296): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4296): [ODM] queryOpenData(key= GEO_IP )
D/AuthZenTransactionCache( 2077): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2077): Clearing transaction cache
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2,
I/DBG_DM  ( 3174): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
I/ActivityManager( 1016): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4353 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4353): MountEmulatedStorage()
I/SA      ( 4296): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4296): [LBE] REF_JPN : true
I/SA      ( 4296): [BDC] create
E/Zygote  ( 4353): v2
I/libpersona( 4353): KNOX_SDCARD checking this for 10042
I/libpersona( 4353): KNOX_SDCARD not a persona
I/art     ( 3955): WaitForGcToComplete blocked for 5.471ms for cause DisableMovingGc
,I/SELinux ( 4353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4353): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3955): took 0.604480ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb86b6dc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86b54c8 counterpartCT=4 counterpartW=96 counterparth=96
D/PersistentNotificationBroadcastReceiver( 1857): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/DBG_POLICYDM( 4180): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3174): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,D/PowerManagerService( 1016): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  ( 1016): lcd : 36 +
,I/AMMetaDataParserService( 3955): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255))),
,D/lights  ( 1016): lcd : 36 -
,D/lights  ( 1016): lcd : 19 +
,D/TimaKeyStoreProvider( 4353): TimaSignature is unavailable
,D/ActivityThread( 4353): Added TimaKeyStore provider
,D/lights  ( 1016): lcd : 19 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/DBG_DM  ( 3174): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
I/DBG_DM  ( 3174): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
W/ContextImpl( 3955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955): Resource data:2131099648
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4353): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 3955): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
I/SA      ( 4296): [DBMV2] getEmailID
,I/SA      ( 4296): [DBMV2] getDataV02ForItems
I/SA      ( 4296): [SSP] query invoked
,E/SQLiteLog( 4051): (284) automatic index on conversation_participants_view(conversation_id)
W/ResourcesManager( 3955): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3955): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.699480ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb834c810 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8342688 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3174): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,W/dex2oat ( 4144): Verification of java.lang.Object com.google.android.gms.common.stats.a.createFromParcel(android.os.Parcel) took 151.325ms
,I/AMMetaDataParserService( 3955): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/DBG_DM  ( 3174): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/SA      ( 4296): [SCU] get signed id from samsung account2.0 DB.
,I/DBG_DM  ( 3174): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 3174): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/SA      ( 4296): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4296): [BDC] destroy
,I/ActivityManager( 1016): Killing 3509:com.fmm.ds/1000 (adj 15): empty #31
,I/DBG_DM  ( 3174): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,I/DBG_DM  ( 3174): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,E/SQLiteLog( 4051): (284) automatic index on conversation_participants_view(conversation_id)
,W/dex2oat ( 4144): Verification of com.google.android.gms.location.internal.LocationRequestInternal com.google.android.gms.location.internal.l.a(android.os.Parcel) took 141.127ms
,E/SQLiteLog( 4051): (284) automatic index on conversation_participants_view(conversation_id)
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/art     ( 4051): WaitForGcToComplete blocked for 15.846ms for cause HomogeneousSpaceCompact
,I/GFX construct_block_size_descriptor_2d second part( 3955): took 2.749895ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3955): took 8.714948ms for 0*0 texture 0
,I/GFX raster( 3955): took 12.442397ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8347d60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8347e08 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.651719ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8857ee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8857f90 counterpartCT=4 counterpartW=96 counterparth=96
,I/CalendarProvider2( 4353): CalendarProvider2.onCreate() called
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,I/AMMetaDataParserService( 3955): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.653178ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8859448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88594f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.649427ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb885c1e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb885c288 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/AMMetaDataParserService( 3955): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.743072ms for 96*96 texture 0
I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8859400 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,I/AMMetaDataParserService( 3955): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/DBG_DM  ( 3174): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3955): Resource data:2131099648
,I/AMMetaDataParserService( 3955): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 4180): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,D/SamsungIME( 1827): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/GFX raster( 3955): took 0.812395ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb834c810 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity,
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,I/DBG_POLICYDM( 4180): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/DBG_DM  ( 3174): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,E/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.660885ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8347d60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,E/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@34b8954
,I/AMMetaDataParserService( 3955): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.637291ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8857ee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3174): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,W/ContextImpl( 3174): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,E/SQLiteLog( 4051): (284) automatic index on conversation_participants_view(conversation_id)
,D/SettingsProvider( 1016): name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,I/GCoreUlr( 1857): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,I/AMMetaDataParserService( 3955): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/DBG_DM  ( 3174): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.643281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8859448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1016): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/AMMetaDataParserService( 3955): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/SQLiteLog( 4051): (284) automatic index on conversation_participants_view(conversation_id)
,W/ResourcesManager( 1181): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,I/ActivityManager( 1016): Killing 3529:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1016): mCursor = null
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.626927ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb885c1e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityYOffset
,I/AMMetaDataParserService( 3955): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/SecContentProvider2( 1016): mCursor = null
,I/DBG_DM  ( 3174): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.953751ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8859400 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/KnoxNotification( 1181): ----- inflateViews : modified publicViewLocal -----
,I/AMMetaDataParserService( 3955): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/SecContentProvider2( 1016): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1016): mCursor = null
,D/KnoxNotification( 1181): ----- inflateViews : modified KnoxViewLocal -----
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955): Resource data:2131099648
,D/PersonaManager( 1181): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/AMMetaDataParserService( 3955): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.682604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb834c810 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/AMMetaDataParserService( 3955): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3509/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10062/pid_3529/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3174): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 3174): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.642396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8347d60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Killing 3570:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,D/StrictMode( 4278): StrictMode policy violation; ~duration=1734 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4278): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4278): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4278): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4278): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4278): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4278): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4278): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4278): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4278): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4278): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4278): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4278): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4278): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4278): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4278): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4278): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4278): StrictMode policy violation; ~duration=1717 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4278): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4278): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4278): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4278): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4278): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4278): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4278): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4278): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4278): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4278): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4278): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4278): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4278): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4278): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4278),: 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4278): StrictMode policy violation; ~duration=1597 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4278): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4278): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4278): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4278): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4278): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4278): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4278): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4278): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4278): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4278): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4278): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4278): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4278): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4278): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4278): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4278): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4278): StrictMode policy violation; ~duration=1596 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4278): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4278): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4278): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4278): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4278): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4278): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4278): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4278): 	at android.app.Instrumentation.callApplicationOnCreate(Inst,rumentation.java:1020)
D/StrictMode( 4278): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4278): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4278): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4278): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4278): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4278): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4278): StrictMode policy violation; ~duration=1594 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4278): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4278): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4278): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4278): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4278): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4278): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4278): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4278): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4278): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4278): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4278): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4278): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4278): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4278): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4278): StrictMode policy violation; ~duration=1592 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4278): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4278): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4278): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4278): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4278): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4278): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4278): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4278): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4278): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4278): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4278): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4278): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4278): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4278): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4278): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4278): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4278): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4278): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4278): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4278): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4278): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4278): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4278): StrictMode policy violation; ~duration=1589 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4278): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4278): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4278): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4278): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4278): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4278): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4278): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4278): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4278): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4278): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4278): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4278): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4278): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4278): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4278): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4278): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4278): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4278): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4278): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4278): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4278): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4278): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4278): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4278): StrictMode policy violation; ~duration=1533 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4278): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4278): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4278): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4278): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4278): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4278): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4278): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4278): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4278): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4278): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4278): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4278): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4278): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4278): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4278): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4278): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
D/StrictMode( 4278): StrictMode policy violation; ~duration=1532 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4278): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4278): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4278): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4278): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4278): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4278): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4278): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4278): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4278): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4278): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4278): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4278): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4278): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4278): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4278): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/OpenGLRenderer( 3174): Render dirty regions requested: true
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4379 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 4379): MountEmulatedStorage()
E/Zygote  ( 4379): v2
I/libpersona( 4379): KNOX_SDCARD checking this for 1000
I/libpersona( 4379): KNOX_SDCARD not a persona
I/SELinux ( 4379): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4379): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4379): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
I/ActivityManager( 1016): Killing 3344:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=4, Uoast
D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 60 -> 60
D/DisplayPowerController( 1016): animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
D/SRIB_DCS( 3174): log_dcs ThreadedRenderer::initialize entered! 
I/Adreno-EGL( 3174): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3174): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3174): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3174): Local Branch: 
I/Adreno-EGL( 3174): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3174): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3174):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/OpenGLRenderer( 3174): Initialized EGL, version 1.4
D/lights  ( 1016): lcd : 46 +
D/TimaKeyStoreProvider( 4379): TimaSignature is unavailable
D/ActivityThread( 4379): Added TimaKeyStore provider
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 60 -> 60
,D/DisplayPowerController( 1016): animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1016): lcd : 46 -
D/lights  ( 1016): lcd : 60 +
,D/OpenGLRenderer( 3174): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3174): Enabling debug mode 0
,D/lights  ( 1016): lcd : 60 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 60 -> 60
,D/DisplayPowerController( 1016): animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusChecker( 4379): onReceive : android.intent.action.BOOT_COMPLETED
,I/StatusChecker( 4379): onReceive : net.mt.init : DONE
,I/AMMetaDataParserService( 3955): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4398): MountEmulatedStorage()
E/Zygote  ( 4398): v2
I/libpersona( 4398): KNOX_SDCARD checking this for 10116
I/libpersona( 4398): KNOX_SDCARD not a persona
,I/SELinux ( 4398): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4398): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4398 uid=10116 gids={50116, 9997} abi=armeabi-v7a
E/SELinux ( 4398): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 3594:com.sec.esdk.elm/u0a94 (adj 15): empty #31
D/ActivityManager( 1016): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/TimaKeyStoreProvider( 4398): TimaSignature is unavailable
,D/ActivityThread( 4398): Added TimaKeyStore provider
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.627709ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8857ee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/libprocessgroup( 1016): failed to open /acct/uid_10009/pid_3344/cgroup.procs: No such file or directory
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.647500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8859448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/PageBuddyNotiSvc( 4398): Intent received : action=android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3955): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ContextImpl( 4398): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.628906ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb885c1e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,I/PageBuddyNotiSvc( 4398): onCreate mCpBitFlag=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3955): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520,
,E/Zygote  ( 4414): MountEmulatedStorage(),
E/Zygote  ( 4414): v2
I/libpersona( 4414): KNOX_SDCARD checking this for 10125
,I/libpersona( 4414): KNOX_SDCARD not a persona
,I/SELinux ( 4414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4414): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4414 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4414): TimaSignature is unavailable
,D/ActivityThread( 4414): Added TimaKeyStore provider
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.721302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8859400 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3570/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10094/pid_3594/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955): Resource data:2131099648
,I/AMMetaDataParserService( 3955): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.682500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb834c810 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.638385ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8347d60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4414): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4414): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4414): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     ( 1857): Explicit concurrent mark sweep GC freed 28371(2MB) AllocSpace objects, 43(688KB) LOS objects, 40% free, 12MB/20MB, paused 2.608ms total 676.005ms
,I/GCoreUlr( 1857): Unbound from all location providers
I/GCoreUlr( 1857): Place inference reporting - stopped
,I/AMMetaDataParserService( 3955): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.628282ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8857ee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3955): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/QuickConnect( 4414): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 4414): Util.setSCRunningSetting - [value]0
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SettingsProvider( 1016): name = scon_is_running
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10125
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/QuickConnect( 4414): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,I/GCoreUlr( 1857): DispatchingService.onDestroy()
I/GCoreUlr( 1857): Stopping handler for UlrDispSvcFast
,I/QuickConnect( 4414): PeriphStartReceiver.onReceive - no need to start
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.636771ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8859448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3955): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/Zygote  ( 4430): MountEmulatedStorage(),
E/Zygote  ( 4430): v2
I/libpersona( 4430): KNOX_SDCARD checking this for 10131
,I/libpersona( 4430): KNOX_SDCARD not a persona
I/SELinux ( 4430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4430 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,E/SELinux ( 4430): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GCoreUlr( 1857): Unbound from all location providers
I/GCoreUlr( 1857): Place inference reporting - stopped
,D/TimaKeyStoreProvider( 4430): TimaSignature is unavailable
,D/ActivityThread( 4430): Added TimaKeyStore provider
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.640625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb885c1e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb885cc68 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4430): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4430): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4430): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4430): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3955): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.758803ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8859400 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb885c1a0 counterpartCT=4 counterpartW=96 counterparth=96
,E/Watchdog( 1016): !@Sync 1
,D/SBrowserFeatureFlag( 4430): initialized in static block : loadCscFeatureValue() succeed! 
,D/SensorService( 1016): [SO] 0.134 0.402 10.113
,D/SettingsProvider( 1016): name = audio_safe_volume_state
,I/AMMetaDataParserService( 3955): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955): Resource data:2131099648
,I/AMMetaDataParserService( 3955): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.772656ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb834c810 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8340050 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ManifestProvider( 4430): onCreate()
,W/com.google.a.a.b.d.a( 4278): Application name is not set. Call Builder#setApplicationName.
,I/GFX raster( 3955): took 0.860782ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8347d60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8340050 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.674740ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8857ee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8340050 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/NetworkSettingsReceiver( 4430): onReceive: android.intent.action.BOOT_COMPLETED
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.641511ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8859448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8340050 counterpartCT=4 counterpartW=96 counterparth=96
,E/SBrowserFeatureFlag( 4430): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@51ee239
,D/SBrowserFeatureFlag( 4430): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4430): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/AMMetaDataParserService( 3955): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/SMD     (  286): DCD OFF,
,E/Zygote  ( 4449): MountEmulatedStorage()
,E/Zygote  ( 4449): v2
I/libpersona( 4449): KNOX_SDCARD checking this for 10135
I/libpersona( 4449): KNOX_SDCARD not a persona
,I/SELinux ( 4449): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4449): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4449): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4449 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3602:com.wssnps/1000 (adj 15): empty #31
,I/art     (  303): Explicit concurrent mark sweep GC freed 8745(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 899us total 33.250ms,
,D/TimaKeyStoreProvider( 4449): TimaSignature is unavailable
D/ActivityThread( 4449): Added TimaKeyStore provider
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3955): took 0.651355ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb885c1e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8340050 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520,
,W/ResourcesManager( 4449): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4449): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4449): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 19.024ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.753749ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8859400 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8340050 counterpartCT=4 counterpartW=96 counterparth=96
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 20.723ms
,I/AMMetaDataParserService( 3955): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955): Resource data:2131099648
,I/AMMetaDataParserService( 3955): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.745364ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb834c810 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8340050 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.656771ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8347d60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8340050 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3602/cgroup.procs: No such file or directory
,I/GFX raster( 3955): took 0.686406ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8857ee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8340050 counterpartCT=4 counterpartW=96 counterparth=96
,D/daemonapp( 1342): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3955): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/art     ( 3893): Suspending all threads took: 22.834ms
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.649427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8859448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8340050 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.783542ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb885c1e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8340050 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4469): MountEmulatedStorage()
E/Zygote  ( 4469): v2
I/libpersona( 4469): KNOX_SDCARD checking this for 10139
I/libpersona( 4469): KNOX_SDCARD not a persona
,I/SELinux ( 4469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4469 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
E/SELinux ( 4469): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.720625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8859400 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8340050 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/TimaKeyStoreProvider( 4469): TimaSignature is unavailable
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
D/ActivityThread( 4469): Added TimaKeyStore provider
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3955): Resource data:Loop for running a,ctivitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
W/ContextImpl( 3955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.default_searchable
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
I/CalendarProvider2( 4353): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955): Resource data:2131165197
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ResourcesManager( 3955): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3955): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3955): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,W/ResourcesManager( 4469): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3955): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3955): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/ActivityManager( 1016): Killing 2813:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,I/AMMetaDataParserService( 3955): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3955): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4489): MountEmulatedStorage(),
E/Zygote  ( 4489): v2
I/libpersona( 4489): KNOX_SDCARD checking this for 10145
I/libpersona( 4489): KNOX_SDCARD not a persona,
,I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4489 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 4489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Killing 3637:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,E/SELinux ( 4489): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955): Resource data:2131165197
,I/AMMetaDataParserService( 3955): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,I/AMMetaDataParserService( 3955): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/ActivityManager( 1016): Killing 3368:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4489): TimaSignature is unavailable
,D/ActivityThread( 4489): Added TimaKeyStore provider
,W/ResourcesManager( 4489): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4489): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4489): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4489): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4489): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3955): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3955): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3955): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955): Resource data:2131165197
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3955): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,I/AMMetaDataParserService( 3955): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/libprocessgroup( 1016): failed to open /acct/uid_10120/pid_2813/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10014/pid_3637/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_3368/cgroup.procs: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3955): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3955): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3955): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 3955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955): Resource data:2131099648
,W/ResourcesManager( 3955): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3955): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,I/AMMetaDataParserService( 3955): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,E/Zygote  ( 4511): MountEmulatedStorage()
E/Zygote  ( 4511): v2
I/libpersona( 4511): KNOX_SDCARD checking this for 10072
I/libpersona( 4511): KNOX_SDCARD not a persona
,I/SELinux ( 4511): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId,
,I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4511 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1016): startService callerProcessName:com.android.email, calleePkgName: com.android.email
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
I/SELinux ( 4511): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4511): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4511): TimaSignature is unavailable
,D/ActivityThread( 4511): Added TimaKeyStore provider
,I/dex2oat ( 4144): dex2oat took 5.921s (threads: 4)
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4532 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/DexOptUtils( 2077): Odex created at:/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex
D/DexOptUtils( 2077): Set odex to world readable.
,E/Zygote  ( 4532): MountEmulatedStorage()
E/Zygote  ( 4532): v2
I/libpersona( 4532): KNOX_SDCARD checking this for 10146
D/DexOptUtils( 2077): Renamed odex to /data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.odex
I/libpersona( 4532): KNOX_SDCARD not a persona
,I/SELinux ( 4532): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4532): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Killing 3726:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 3709:com.sec.factory.camera/1000 (adj 15): empty #32
,E/SELinux ( 4532): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 3755:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3955): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,D/TimaKeyStoreProvider( 4532): TimaSignature is unavailable
,D/ActivityThread( 4532): Added TimaKeyStore provider
,D/BadgeProvider( 4511): onCreate
,D/BadgeProvider( 4511): DatabaseHelper
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 27916(1516KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 26MB/40MB, paused 2.580ms total 149.649ms
,W/libprocessgroup( 1016): failed to open /acct/uid_10022/pid_3726/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3709/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3755/cgroup.procs: No such file or directory
,W/ResourcesManager( 4532): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/BadgeProvider( 4511): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 1506): reloadBadges entered.
,D/BadgeProvider( 4511): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4511): sendNotify, [notify] : null
D/BadgeProvider( 4511): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4511): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4511): update, [UpdateCount] : 1
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,I/Process ( 4489): Sending signal. PID: 4489 SIG: 9
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:assistant
I/AMMetaDataParserService( 3955): Resource data:2131165220
,D/ActivityManager( 1016): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,W/ResourcesManager( 3955): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3955): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3955): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3955): getResourceTypeNamexml
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
I/GFX raster( 3955): took 0.715156ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8a6bad8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6b808 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3955): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,E/Zygote  ( 4553): MountEmulatedStorage()
E/Zygote  ( 4553): v2
I/libpersona( 4553): KNOX_SDCARD checking this for 1000
I/libpersona( 4553): KNOX_SDCARD not a persona
,I/SELinux ( 4553): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4553): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4553): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4553 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/lowmemorykiller(  254): Error writing /proc/4489/oom_score_adj; errno=22
,I/ActivityManager( 1016): Killing 3770:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,E/        ( 3955): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3955): took 0.601928ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3955): Bitmap=0xb8a6b928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7e3b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3955): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,D/TimaKeyStoreProvider( 4553): TimaSignature is unavailable
,D/ActivityThread( 4553): Added TimaKeyStore provider
,I/ActivityManager( 1016): Process com.android.email (pid 4489)(adj 11) has died(55,1099)
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.exchange, calleePkgName: com.android.email
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog,
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getRe,sourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity,
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/libpersona( 4569): KNOX_SDCARD checking this for 10145
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/libpersona( 4569): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/ActivityManager( 1016): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4569 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
W/ContextImpl( 3955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.AppPicker
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/ActivityManager( 1016): Killing 3782:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
W/ResourcesManager( 4569): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
W/ResourcesManager( 4569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
W/ResourcesManager( 4569): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,W/ResourcesManager( 4569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/ResourcesManager( 4569): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning,
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
E/Zygote  ( 4569): MountEmulatedStorage()
E/Zygote  ( 4569): v2
I/SELinux ( 4569): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4569): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4569): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
D/TimaKeyStoreProvider( 4569): TimaSignature is unavailable
D/ActivityThread( 4569): Added TimaKeyStore provider
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
,I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3955): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3955): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3955): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
,W/libprocessgroup( 1016): failed to open /acct/uid_10100/pid_3782/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3770/cgroup.procs: No such file or directory
,E/Zygote  ( 4585): MountEmulatedStorage()
,E/Zygote  ( 4585): v2
I/libpersona( 4585): KNOX_SDCARD checking this for 1000
I/libpersona( 4585): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4585 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3817:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,I/SELinux ( 4585): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4585): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4585): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 4585): TimaSignature is unavailable
,D/ActivityThread( 4585): Added TimaKeyStore provider
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 4585): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4585): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 4585): StateMachine : Current State = 1
D/SecurityLogAgent( 4585): BootReceiver : completed task. Failed to return wakelock . 
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1016): Killing 3487:com.sec.pcw.device/1000 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{3dbfcfab u0 com.samsung.android.providers.context/.ContextService}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BadgeProvider( 4511): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/BadgeProvider( 4511): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4511): sendNotify, [notify] : null
D/BadgeProvider( 4511): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4511): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4511): update, [UpdateCount] : 1
,D/Launcher.Model( 1506): reloadBadges entered.
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1016): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Process ( 4532): Sending signal. PID: 4532 SIG: 9
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Process com.android.exchange (pid 4532)(adj 13) has died(54,1100)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1857): callingUid 10012, callindPid: 1857
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2077): Restart initialization of location
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{293736dd u0 com.android.settings/.wifi.WifiCredService}
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1477): query,matched:0, calling pid = 2077
,D/TP/SmsProvider( 1477): match 0:Elapsed time : 3.033 ms
,D/TP/MmsProvider( 1477): Query uri=content://mms, match=0, calling pid = 2077
,D/TP/SmsProvider( 1477): query,matched:0, calling pid = 2077
,D/TP/SmsProvider( 1477): match 0:Elapsed time : 1.712 ms
,D/TP/MmsProvider( 1477): Query uri=content://mms, match=0, calling pid = 2077
,I/DBG_POLICYDM( 4180): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/PackageManager( 1016): [MSG] WRITE_PACKAGE_RESTRICTIONS
,W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_3817/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3487/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 2077): getNumBytesRead when not calculated.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,D/AuthorizationBluetoothService( 1857): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1857): [235] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/a       ( 1857): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1857): No location to return for getLastLocation()
,W/FusedLocationProvider( 1857): location=null
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1857): [250] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2077): Restart initialization of location
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1857): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1857): No location to return for getLastLocation()
,W/FusedLocationProvider( 1857): location=null
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2590): Starting #3
,I/Hs20UtilService( 2590): Message received 5011
E/WifiStateMachine( 1016): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,D/WifiNative-wlan0( 1016): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1016): invaild command id : 215
,D/SecurityLogAgent( 4585): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4585): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4585): StateMachine : Current State = 1
,D/SecurityLogAgent( 4585): StateMachine : Changed Current State = 1
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.example.hello, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.example.hello for broadcast com.example.hello/io.jxcore.node.ConnectivityChangeListener: pid=4637 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,E/Zygote  ( 4637): MountEmulatedStorage(),
,E/Zygote  ( 4637): v2
,I/libpersona( 4637): KNOX_SDCARD checking this for 10174,
I/libpersona( 4637): KNOX_SDCARD not a persona
,I/SELinux ( 4637): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4637): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4637): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 4637): TimaSignature is unavailable
,D/ActivityThread( 4637): Added TimaKeyStore provider
,D/jxcore_app_log( 4637): JniHelper::setJavaVM(0xb7f7f450), pthread_self() = -1224986936
E/JX-Cordova( 4637): JXcore wasn't initialized yet
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: CONNECTED,
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4653): MountEmulatedStorage(),
I/libpersona( 4653): KNOX_SDCARD checking this for 10068
E/Zygote  ( 4653): v2,
I/libpersona( 4653): KNOX_SDCARD not a persona
I/SELinux ( 4653): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=4653 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4653): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4653): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4653): TimaSignature is unavailable
D/ActivityThread( 4653): Added TimaKeyStore provider
,W/ResourcesManager( 4653): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/FileShare-Client( 4653): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 4653): ClientBroadcastReceiver.onReceive - disconnected
,D/FileShare-Client( 4653): Outbound.stopDelayTimer - 
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4668): MountEmulatedStorage(),
,E/Zygote  ( 4668): v2
,I/libpersona( 4668): KNOX_SDCARD checking this for 10069
I/libpersona( 4668): KNOX_SDCARD not a persona
,I/SELinux ( 4668): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4668 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3656:com.samsung.android.sm/1000 (adj 15): empty #31
,I/SELinux ( 4668): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4668): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4668): TimaSignature is unavailable
,D/ActivityThread( 4668): Added TimaKeyStore provider
,D/FileShare-Server( 4668): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1016): Killing 3301:com.google.android.youtube/u0a166 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2590): Starting #4
,I/Hs20UtilService( 2590): Message received 5007
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 2590): Starting #5
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 2590): Message received 5007
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2590): Starting #6
,I/Hs20UtilService( 2590): Message received 5007
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2590): Starting #7
,D/PowerManagerService( 1016): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1016) eventTime = 52333
,D/PowerManagerService( 1016): [s] UserActivityState : 2 -> 1
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016 (0x0)
D/PowerManagerService( 1016): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{1000}) (elapsedTime=3403)
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 2590): Message received 5007
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1016): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1016): mCursor = null
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3656/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10166/pid_3301/cgroup.procs: No such file or directory
,E/Zygote  ( 4683): MountEmulatedStorage()
,E/Zygote  ( 4683): v2
I/libpersona( 4683): KNOX_SDCARD checking this for 1000
I/libpersona( 4683): KNOX_SDCARD not a persona
,I/SELinux ( 4683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4683 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=4, Uoast
,I/SELinux ( 4683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4683): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,D/SRIB_DCS( 1181): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/art     (  303): Explicit concurrent mark sweep GC freed 8731(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 26.317ms
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider( 4683): TimaSignature is unavailable
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 17.410ms
,D/ActivityThread( 4683): Added TimaKeyStore provider,
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 18.583ms
,I/PCWCLIENTTRACE_LOG( 4683): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 4683): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 4683): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 4683): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 4683): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4683): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4683): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1016): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=10, mSplitNum[1]=17, mSplitNum[2]=26, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=34
,I/splitIntent( 1016): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4701): MountEmulatedStorage()
E/Zygote  ( 4701): v2
I/libpersona( 4701): KNOX_SDCARD checking this for 10111
I/libpersona( 4701): KNOX_SDCARD not a persona
,I/SELinux ( 4701): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4701 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4701): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4701): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3687): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 14 08:50:13 GMT+01:00 2016
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/SecurityLogAgent( 4585): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4585): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4585): StateMachine : Current State = 1
D/accuweather( 1745): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SecurityLogAgent( 4585): StateMachine : Changed Current State = 1
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4701): TimaSignature is unavailable
,D/ActivityThread( 4701): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3687): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3687): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3687): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.183: ( 3687): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 4717): MountEmulatedStorage()
I/libpersona( 4717): KNOX_SDCARD checking this for 10159
E/Zygote  ( 4717): v2
I/libpersona( 4717): KNOX_SDCARD not a persona
I/KLMS-2.5.183: ( 3687): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/SELinux ( 4717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/KLMS-2.5.183: ( 3687): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/SELinux ( 4717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4717): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3687): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3687): StateImplV2(): networkChangeListener().START
I/ActivityManager( 1016): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4717 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/KLMS-2.5.183: ( 3687): NetworkChangeOperations(): uploadRequestLog().START 
,D/daemonapp( 1342): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,I/KLMS-2.5.183: ( 3687): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3687): StateImplV2(): networkChangeListener().END
,D/accuweather( 1745): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1745): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1745): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,I/KLMS-2.5.183: ( 3687): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 4717): TimaSignature is unavailable
,D/ActivityThread( 4717): Added TimaKeyStore provider
,D/accuweather( 1745): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1745): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1745): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 4180): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4180): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 4180): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,E/Zygote  ( 4733): MountEmulatedStorage()
,E/Zygote  ( 4733): v2
,I/libpersona( 4733): KNOX_SDCARD checking this for 10081
I/SELinux ( 4733): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4733): KNOX_SDCARD not a persona,
,I/SELinux ( 4733): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1016): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4733 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4733): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4733): TimaSignature is unavailable
,D/ActivityThread( 4733): Added TimaKeyStore provider
,E/SPPClientService( 4258): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 4296): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4296): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 4296): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/SMD     (  286): DCD OFF
,I/DBG_POLICYDM( 4180): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4180): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 4180): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,E/DBG_POLICYDM( 4180): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/DBG_POLICYDM( 4180): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 4296): [SLFUCHKMGR] constructor called
,I/SA      ( 4296): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4296): [OR] == isSIMCardReady false ==
,I/SurfaceFlinger(  257): id=12 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=12 Removed Uoast (-2/9)
,I/iu.SyncManager( 2077): SYNC; picasa accounts
,I/MusicStore( 4701): Database version: 108
,I/SA      ( 4296): [SCU] == networkStateCheck == true
,I/SA      ( 4296): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 4296): isChinaCountryCode : false
I/SA      ( 4296): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 4296): [OR] == networkStateCheck true ==
,D/NetworkLogImpl( 2077): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2077): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2077): num queued entries: 0
,I/iu.UploadsManager( 2077): num updated entries: 0
,I/iu.SyncManager( 2077): NEXT; no task
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4759): MountEmulatedStorage(),
I/ActivityManager( 1016): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4759 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Zygote  ( 4759): v2
I/libpersona( 4759): KNOX_SDCARD checking this for 10010
I/libpersona( 4759): KNOX_SDCARD not a persona
,I/SELinux ( 4759): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4759): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/SA      ( 4296): [OR] GetMyCountryZoneTask
,I/SA      ( 4296): [OR] onReceive END
E/SELinux ( 4759): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 3955:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 3893:com.vlingo.midas/u0a31 (adj 15): empty #32
,V/DownloadManager( 1237): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/TimaKeyStoreProvider( 4759): TimaSignature is unavailable
,D/ActivityThread( 4759): Added TimaKeyStore provider
,D/SecContentProvider2( 1016): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1016): mCursor = null
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4296): [SRS] prepareGetMyCountryZone
,E/Zygote  ( 4776): MountEmulatedStorage()
I/libpersona( 4776): KNOX_SDCARD checking this for 10113
E/Zygote  ( 4776): v2
I/libpersona( 4776): KNOX_SDCARD not a persona
I/SELinux ( 4776): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SA      ( 4296): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SELinux ( 4776): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/SA      ( 4296): [SSP] query invoked
,E/SELinux ( 4776): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4776 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3835:com.google.android.gm/u0a101 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4776): TimaSignature is unavailable
,D/ActivityThread( 4776): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3955/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10031/pid_3893/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10101/pid_3835/cgroup.procs: No such file or directory
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 27363(1715KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/40MB, paused 2.524ms total 151.795ms
,I/SA      ( 4296): [TPMU] GetMccFromDB : null
I/SA      ( 4296): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4296): [TPM] isNoProxy(default) : true
,E/File    ( 4296): fail readDirectory() errno=2
,D/WaitQueueForNetworkActivate( 4759): notifyNetworkActivated
,W/ResourcesManager( 4701): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4701): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/JNIHelp ( 4701): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ContextImpl( 4759): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityThread( 4701): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4701): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@184ac9c1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4701): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4701): GMSCore installation verified
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ConfigStore( 4701): Config Database version: 1
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4701): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4701): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4701): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,W/ContextImpl( 4776): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/hcjo    ( 4759): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4759): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 4759): exit::IDLE
D/InitializeManagerStateMachine( 4759): entry::NETWORK_CHECK
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/InitializeManagerStateMachine( 4759): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4759): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4759): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4759): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4759): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4759): entry::SUCCESS
D/hcjo    ( 4759): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/ContextImpl( 4776): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/hcjo    ( 4759): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 4759): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4759): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4759): exit::SUCCESS
D/InitializeManagerStateMachine( 4759): entry::IDLE
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,I/AudioService( 1016): getStreamVolume 3 index 0
,W/ContextImpl( 4776): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/MediaRouter( 4701): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4776): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,V/MusicLeanback( 4701): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 4701): type=WIFI subType= reason=null isConnected=true
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/NetworkMonitor( 4701): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4821): MountEmulatedStorage()
E/Zygote  ( 4821): v2
I/libpersona( 4821): KNOX_SDCARD checking this for 10002
I/libpersona( 4821): KNOX_SDCARD not a persona
,I/SELinux ( 4821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4821 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4821): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4821): TimaSignature is unavailable
,D/ActivityThread( 4821): Added TimaKeyStore provider
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/GoogleHttpClient( 4701): Failed to load SSLCertificateSocketFactory from package
I/GoogleHttpClient( 4701): Falling back to old SSLCertificateSocketFactory
,I/GHttpClientFactory( 4701): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/AlarmManager( 1016): waitForAlarm result :4
,I/ActivityManager( 1016): Killing 3999:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 4776): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/LibraryLoader( 4776): Time to load native libraries: 2 ms (timestamps 3946-3948)
I/LibraryLoader( 4776): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4776): Binding Chromium to main looper Looper (main, tid 1) {3ffeaeec}
,I/LibraryLoader( 4776): Expected native library version number "",actual native library version number ""
,I/chromium( 4776): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3999/cgroup.procs: No such file or directory
,I/BrowserStartupController( 4776): Initializing chromium process, singleProcess=true
,W/art     ( 4776): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 4776): ApplicationContext is null in ApplicationStatus,
,E/Zygote  ( 4844): MountEmulatedStorage(),
E/Zygote  ( 4844): v2
I/libpersona( 4844): KNOX_SDCARD checking this for 1000,
I/SELinux ( 4844): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4844): KNOX_SDCARD not a persona,
,I/SELinux ( 4844): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4844): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4844 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,D/TimaKeyStoreProvider( 4844): TimaSignature is unavailable
,D/ActivityThread( 4844): Added TimaKeyStore provider
,W/chromium( 4776): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 4776): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,I/chromium( 4776): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,I/Adreno-EGL( 4776): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4776): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4776): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4776): Local Branch: 
I/Adreno-EGL( 4776): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4776): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4776):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/DIAGMON_AGENT( 4844): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/NSApplication( 4776): Starting up...
,W/AudioManagerAndroid( 4776): Requires BLUETOOTH permission
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4875 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4875): MountEmulatedStorage()
E/Zygote  ( 4875): v2
I/libpersona( 4875): KNOX_SDCARD checking this for 10120
I/libpersona( 4875): KNOX_SDCARD not a persona
,I/SELinux ( 4875): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Killing 4197:com.samsung.helphub/1000 (adj 15): empty #31,
I/ActivityManager( 1016): Killing 3929:com.android.vending/u0a28 (adj 15): empty #32
,I/SELinux ( 4875): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4875): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4875): TimaSignature is unavailable
,D/ActivityThread( 4875): Added TimaKeyStore provider
,W/ResourcesManager( 4875): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/DIAGMON_AGENT( 4844): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 4844): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 4844): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 4844): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 4844): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 4844): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4197/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10028/pid_3929/cgroup.procs: No such file or directory
,I/SA      ( 4296): [RC New] Execute method=[GET] start
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4296): [RC New] Security=[true]
,I/System.out( 4296): Thread-641(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4296): Thread-641(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4296): Thread-641(ApacheHTTPLog):isShipBuild true
I/System.out( 4296): Thread-641(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4296): Thread-641(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  274): uids 10041
D/EnterpriseController(  274): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  274): getNetworkForDns: using netid 502 for uid 10041
,E/Zygote  ( 4895): MountEmulatedStorage()
I/libpersona( 4895): KNOX_SDCARD checking this for 10009
E/Zygote  ( 4895): v2
I/libpersona( 4895): KNOX_SDCARD not a persona
,I/SELinux ( 4895): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1016): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4895 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4895): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4895): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4895): TimaSignature is unavailable
,D/ActivityThread( 4895): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 4243:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
I/ActivityManager( 1016): Killing 4222:com.sec.knox.foldercontainer/1000 (adj 15): empty #32
,I/FOTA_Client( 4895): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 4895): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 4895): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 4895): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/ActivityManager( 1016): Killing 4278:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,D/QuickConnect( 4414): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 4414): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 4414): PeriphStartReceiver.onReceive - no need to start
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4222/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4243/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10107/pid_4278/cgroup.procs: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1016): Killing 4379:com.sec.android.app.mt/1000 (adj 15): empty #31
,I/splitIntent( 1016): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=24
,I/splitIntent( 1016): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SSRM:n  ( 1016): SIOP:: AP = 370
,E/Zygote  ( 4916): MountEmulatedStorage(),
E/Zygote  ( 4916): v2
I/libpersona( 4916): KNOX_SDCARD checking this for 10062
I/libpersona( 4916): KNOX_SDCARD not a persona
,I/SELinux ( 4916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1016): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4916 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4916): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/FOTA_Client( 4895): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1342): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1342): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1342): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1342): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1342): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/TimaKeyStoreProvider( 4916): TimaSignature is unavailable
,D/ActivityThread( 4916): Added TimaKeyStore provider
,I/FOTA_Client( 4895): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/daemonapp( 1342): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1342): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1342): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1342): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1342): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1342): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1342): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1342): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/SecurityLogAgent( 4585): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4585): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4585): StateMachine : Current State = 1
,I/KLMS-2.5.183: ( 3687): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Mon Mar 14 08:50:15 GMT+01:00 2016
,D/daemonapp( 1342): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1342): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1342): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1342): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1342): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3687): KLMSAbstractReciever(): onReceive().END.
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4379/cgroup.procs: No such file or directory
,I/KLMS-2.5.183: ( 3687): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3687): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 4935): MountEmulatedStorage(),
E/Zygote  ( 4935): v2
I/libpersona( 4935): KNOX_SDCARD checking this for 10157
I/libpersona( 4935): KNOX_SDCARD not a persona
I/SELinux ( 4935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/KLMS-2.5.183: ( 3687): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/SELinux ( 4935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4935 uid=10157 gids={50157, 9997} abi=armeabi-v7a
E/SELinux ( 4935): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3687): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService },
,D/TimaKeyStoreProvider( 4935): TimaSignature is unavailable,
D/ActivityThread( 4935): Added TimaKeyStore provider
,I/SA      ( 4296): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.,
,D/comdaemonstockapp( 1342): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET,
D/comdaemonstockapp( 1342): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0,
,I/art     (  303): Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 643us total 32.774ms,
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3687): KLMSIntentService(): TIME_CHANGED
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 760us total 17.150ms
,I/ExternalOEMControlProvider( 4916): onCreate
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 17.604ms
,W/ResourcesManager( 4935): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KLMS-2.5.183: ( 3687): StateImplV2(): dateTimeChanged().START : Mon Mar 14 08:50:15 GMT+01:00 2016
,E/Zygote  ( 4951): MountEmulatedStorage()
E/Zygote  ( 4951): v2
I/libpersona( 4951): KNOX_SDCARD checking this for 10046
I/libpersona( 4951): KNOX_SDCARD not a persona
I/SELinux ( 4951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4951 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/SELinux ( 4951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/KLMS-2.5.183: ( 3687): StateImplV2(): dateTimeChanged().END
,E/SELinux ( 4951): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4963): MountEmulatedStorage(),
E/Zygote  ( 4963): v2
I/libpersona( 4963): KNOX_SDCARD checking this for 1000
I/libpersona( 4963): KNOX_SDCARD not a persona,
I/SELinux ( 4963): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4963): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4963): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=4963 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4951): TimaSignature is unavailable
,D/ActivityThread( 4951): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3687): KLMSIntentService(): onDestroy()
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4963): TimaSignature is unavailable
,D/ActivityThread( 4963): Added TimaKeyStore provider,
,E/Zygote  ( 4980): MountEmulatedStorage()
I/libpersona( 4980): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4980): v2
I/libpersona( 4980): KNOX_SDCARD not a persona
,I/SELinux ( 4980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4980 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 4980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4980): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ Time Manager ( 4916): Time Difference not stored. TIME_DIFFERENCE
,W/ResourcesManager( 4963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4951): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4951): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4951): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4951): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4980): TimaSignature is unavailable
,D/ActivityThread( 4980): Added TimaKeyStore provider
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimeService( 4980): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457941816000,
D/        ( 4980): TimeServiceNative: User Time to be set is 1457941816000,
D/QC-time-services( 4980): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4980): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4980): Lib:time_genoff_operation: pargs->ts_val = 1457941816000
,D/QC-time-services( 4980): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  316): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  316): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457941816000
D/QC-time-services(  316): Daemon:genoff_opr: Base = 2, val = 1457941816000, operation = 0
,D/QC-time-services(  316): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/13/70 5:55:32
,D/QC-time-services(  316): Daemon:Value read from RTC seconds = 22053332000,
D/QC-time-services(  316): Daemon:new time 1457941816000 
D/QC-time-services(  316): Daemon: delta 1435888484000 genoff 1435888484000 
,D/QC-time-services(  316): Daemon:genoff_persistent_update: Writing genoff = 1435888484000 to memory
D/QC-time-services(  316): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  316): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/Mms/MmsApp( 4951): [start]    onCreate() consume time = 0.0
,I/ActivityManager( 1016): Killing 4430:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,D/accuweather( 1745): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1745): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/QC-time-services(  316): Updating the TOD offset,
D/QC-time-services(  316): Daemon:genoff_persistent_update: Writing genoff = 1435888484000 to memory
D/QC-time-services(  316): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  316): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  316): Daemon:Update to modem bit set
D/QC-time-services(  316): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  316): Daemon: Base = 2, Value being sent to MODEM = 1119923684000
E/QC-time-services( 4980): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  316): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  316): Daemon: Time-services: Waiting to acceptconnection
,E/Zygote  ( 4998): MountEmulatedStorage()
E/Zygote  ( 4998): v2
I/libpersona( 4998): KNOX_SDCARD checking this for 10085
I/libpersona( 4998): KNOX_SDCARD not a persona
I/SELinux ( 4998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4998 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4998): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 4469:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 4511:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4998): TimaSignature is unavailable
,D/ActivityThread( 4998): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 4553:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,W/ResourcesManager( 4998): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4998): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4998): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4998): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4998): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4998): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/SA      ( 4296): [RC New] [v2liruge] api execute + 801
I/SA      ( 4296): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4296): AsyncTask #1 calls detatch()
,D/SettingsProvider( 1016): name = next_alarm_formatted
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10085
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/SA      ( 4296): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 4296): [OCP] update openData : PL
,I/SA      ( 4296): [TPMU] getNetworkMcc : 
,I/SA      ( 4296): [SCU] saveMccToPreferece Start
,I/SA      ( 4296): [SCU] RegionMCC : 260
I/SA      ( 4296): [SSP] query invoked
,I/SA      ( 4296): [TPMU] GetMccFromDB : null
,I/SA      ( 4296): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4296): [SCU] saveMccToPreferece End
,I/SA      ( 4296): [RC New] executeRequest [v2liruge] end. 883
,I/SA      ( 4296): [RC New] Execute end
,W/libprocessgroup( 1016): failed to open /acct/uid_10139/pid_4469/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_4511/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10131/pid_4430/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4553/cgroup.procs: No such file or directory
,I/SA      ( 4296): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 4296): [OR] GetMyCountryZoneTask Success
,W/art     ( 4951): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 133.643ms
,D/Mms/ArtClassLoader( 4951): init before art
,D/Mms/TelephonyPermission( 4951): start operation mode monitor
,W/ResourcesManager( 4951): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 4951): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 4951): isDefault true
,D/Mms/MmsApp( 4951): onCreate() com.android.mms
,W/art     ( 4998): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 119.045ms
,I/jxcore-log( 3806): INFO testUtils Toggling radios to: true
I/jxcore-log( 3806): 
,D/BluetoothAdapter( 3806): enable()
,D/BluetoothAdapter( 3806): enable(): BT is already enabled..!
,D/Mms/MmsApp( 4951): [start]    initCountryIso consume time = 310.160208
,D/CountryDetector( 1016): The first listener is added
,I/jxcore-log( 3806): Unit Test app is loaded
I/jxcore-log( 3806): 
,D/SecContentProvider( 1016): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1016): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1016): mCursor = null
,D/Mms/MmsApp( 4951): [end]    initCountryIso consume time = 13.975208
D/Mms/MmsConfig( 4951): [start]    MmsConfig.init() consume time = 0.11474
,D/WifiService( 1016): setWifiEnabled: true pid=3806, uid=10155
W/ActivityManager( 1016): Permission Denial: getCurrentUser() from pid=3806, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1016): Failed getting userId using ActivityManagerNative
W/WifiService( 1016): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=3806, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1016): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1016): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1016): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1016): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1016): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1016): name = wifi_on
,I/WifiService( 1016): disconnect: pid=3806, uid=10155
,I/wpa_supplicant( 1869): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/chromium( 3806): [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Mms/MmsConfig( 4951): before partial update
,D/Mms/MmsConfig( 4951): Load Resize quality : 80
,I/wpa_supplicant( 1869): CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1869): wlan0: State: COMPLETED -> DISCONNECTED
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1869): Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
D/Tethering( 1016): InitialState.processMessage what=4
I/wpa_supplicant( 1869): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
I/wpa_supplicant( 1869): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/wpa_supplicant( 1869): Cmd 35605 not handled
E/WifiStateMachine( 1016): WifiStateMachine: Leaving Connected state
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1869): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1869): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1869): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1869): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1869): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1869): First Scan Start
I/wpa_supplicant( 1869): Scan requested (ret=0) - scan timeout 30 seconds
E/Tethering( 1016): No numeric data
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/Tethering( 1016): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1016): clearTetheredNotification()
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,V/NetworkStats( 1016): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
D/HotspotTile( 1181): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1181): updateTetherState():false, false
,D/EasySignUpManager_1.0.1( 4951): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4951): isAuth is false
D/Mms/MmsConfig( 4951): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,V/NetworkStats( 1016): performPollLocked() took 8ms
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/TP/MmsSmsProvider( 1477): query,matched:2117, calling pid = 4951
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/CommandListener(  274): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NativeCrypto( 1857): Read error: ssl=0xb84d75b0: I/O error during system call, Connection timed out
,E/WifiStateMachine( 1016): Start Disconnecting Watchdog 1
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
I/wpa_supplicant( 1869): wlan0: Setting scan request: 0 sec 0 usec
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
E/ConnectivityService( 1016): updateNetworkInfo()
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ConnectivityService( 1016): updateNetworkInfo()
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,D/TP/MmsSmsProvider( 1477): match 2117:Elapsed time : 23.255 ms
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,D/CommandListener(  274): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1016): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,D/ConnectivityService( 1016): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1016): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityManager.CallbackHandler( 2077): CM callback handler got msg 524292
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,D/TelephonyNetworkFactory( 1477): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/CSLegacyTypeTracker( 1016): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1016): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1477): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/WifiNetworkAgent( 1016): NetworkAgent: NetworkAgent channel lost
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1016): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1016): MasterInitialState.processMessage what=3
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,V/NetworkStats( 1016): updateIfacesLocked()
,V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1181): EthernetConnected: false
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
,D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,V/NetworkStats( 1016): performPollLocked() took 7ms
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 29215(1645KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 26MB/40MB, paused 2.650ms total 164.473ms
,V/NativeCrypto( 1857): SSL shutdown failed: ssl=0xb84d75b0: I/O error during system call, Broken pipe
,D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
,E/GCM     ( 1857): Wifi connection closed with errorCode 20
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,D/ConnectivityService( 1016): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): doQuit - quitNow()
,D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/EasySignUpManager_1.0.1( 4951): isAuth is false
,D/EasySignUpManager_1.0.1( 4951): getServiceStatus : serviceId (1) is OFF
E/CscParser( 4951): mps_code.dat does not exist
E/CscParser( 4951): customer_path =/system/csc/customer.xml
E/CscParser( 4951): fileName + /system/csc/customer.xml
,E/Zygote  ( 5022): MountEmulatedStorage()
,I/libpersona( 5022): KNOX_SDCARD checking this for 10094
E/Zygote  ( 5022): v2
I/libpersona( 5022): KNOX_SDCARD not a persona
,I/SELinux ( 5022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/CscParser( 4951): mps_code.dat does not exist
E/CscParser( 4951): customer_path =/system/csc/customer.xml
E/CscParser( 4951): fileName + /system/csc/customer.xml
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5022 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4653:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
E/SELinux ( 5022): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/ArtClassLoader( 4951): init [DONE] art
,D/CscParser( 4951): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4951):  enable multiwindow = true
,E/Mms/MessageUtils( 4951): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4951): updateCountryIso : update country iso info 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4316, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/Mms/MmsConfig( 4951): [end]    init() consume time = 314.297291
,D/Mms/Contact( 4951): [start]    init() consume time = 0.813698
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1443): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1443): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/TimaKeyStoreProvider( 5022): TimaSignature is unavailable
,D/ActivityThread( 5022): Added TimaKeyStore provider
V/HeadsetService( 2663): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2663): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/TP/MmsSmsProvider( 1477): query,matched:13, calling pid = 4951
,D/TP/MmsSmsProvider( 1477): match 13:Elapsed time : 1.474 ms
,D/Mms/Contact( 4951): [end]    init consume time = 22.516042
,D/ActivityManager( 1016): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/Mms/DraftCache( 4951): [start]    rebuildCache consume time = 9.699167
,W/libprocessgroup( 1016): failed to open /acct/uid_10068/pid_4653/cgroup.procs: No such file or directory
,D/TP/MmsSmsProvider( 1477): query,matched:12, calling pid = 4951
,D/Mms/MethodReflector( 4951): getSubId is called
D/Mms/TelephonyUtils( 4951): getLongSubId from simSlot 0, return Value = -1
,D/TP/MmsSmsProvider( 1477): match 12:Elapsed time : 2.135 ms
,D/Mms/MethodReflector( 4951): getTelephonyProperty is called
D/Mms/DownloadManager( 4951): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4951): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4951): auto download without roaming -> true
D/Mms/DownloadManager( 4951): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 4951): getSubId is called
,D/Mms/MethodReflector( 4951): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4951): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4951): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 4951): getTelephonyProperty is called
D/Mms/DownloadManager( 4951): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4951): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4951): auto download without roaming -> true
D/Mms/DownloadManager( 4951): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4951): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4951): mAutoDownload ------> true
,D/elm:15183( 5022): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,E/SMD     (  286): DCD OFF
,D/elm:15183( 5022): ELMEngine.ELMEngine( context ).
,D/Mms/DraftCache( 4951): [end]    rebuildCache consume time = 23.756822
D/elm:15183( 5022): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1016): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 5022): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,D/elm:15183( 5022): ElmAgentService : onCreate()
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/elm:15183( 5022): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:15183( 5022): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15183( 5022): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:15183( 5022): ModuleBase.ModifySetAlarm()
,D/elm:15183( 5022): MDMBridge.getInstance()
D/elm:15183( 5022): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 5044): MountEmulatedStorage()
I/libpersona( 5044): KNOX_SDCARD checking this for 10134
E/Zygote  ( 5044): v2
I/libpersona( 5044): KNOX_SDCARD not a persona
,I/SELinux ( 5044): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5044): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ServiceManager(  313): Waiting for service AtCmdFwd...
I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5044 uid=10134 gids={50134, 9997} abi=armeabi-v7a
D/elm:15183( 5022): ElmAgentService : onDestroy().
,E/SELinux ( 5044): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/ComposerPerformance( 4951): 1457941816748 ms / [DONE] Composer constructor
,I/ActivityManager( 1016): Killing 4668:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,E/CII     ( 4951): CommonIMSInterface: VoLTE CSC feature disabled.
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/Mms/ReservationManager( 4951): ReservationManager()
,I/Mms/ReservationManager( 4951): resetAfterConnected()
,D/Mms/Conversation( 4951): [start]    init() consume time = 54.671459
,D/TP/MmsSmsProvider( 1477): query,matched:7, calling pid = 4951
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/TP/MmsSmsProvider( 1477): deleteConversation threadId: 9223372036854775807
D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/TP/MmsSmsProvider( 1477): match 7:Elapsed time : 2.792 ms
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/TP/MmsSmsProvider( 1477): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1477): updateThread(), thread_id = 9223372036854775807
I/Mms/ReservationManager( 4951): getReservedSendMessageCount(): retMessageCount=0
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3,
D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
V/TP/MmsSmsDatabaseHelper( 1477): sUpgradeVersion = 0, db.getVersion() = 81
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3,
D/Mms/MmsApp( 4951): [end]    onCreate() consume time = 16.165937
D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,E/SQLiteLog( 1477): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1477): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1477): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1477): (284) automatic index on im_threads(normal_thread_id)
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
E/SQLiteLog( 1477): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1477): (284) automatic index on im_threads(normal_thread_id)
D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/TimaKeyStoreProvider( 5044): TimaSignature is unavailable
,D/ActivityThread( 5044): Added TimaKeyStore provider
,D/Mms/DownloadManager( 4951): Service state changed: Bundle[mParcelledData.dataSize=744]
I/ActivityManager( 1016): Killing 4683:com.sec.pcw.device/1000 (adj 15): empty #31
D/Mms/DownloadManager( 4951): roaming ------> false, mSimSlot = 0
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/Mms/MethodReflector( 4951): getSubId is called
D/Mms/TelephonyUtils( 4951): getLongSubId from simSlot 0, return Value = -1
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/TP/MmsSmsProvider( 1477): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1477): need read changed broadcast:false
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/Mms/MethodReflector( 4951): getTelephonyProperty is called
D/Mms/DownloadManager( 4951): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4951): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4951): auto download without roaming -> true
D/Mms/DownloadManager( 4951): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 4951): mAutoDownload ------> true
,D/Mms/Conversation( 4951): [end]    init consume time = 18.774584
D/Mms/MessagingNotification( 4951): [start]    init() consume time = 0.511562
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/Mms/MessagingNotification( 4951): [end]    init consume time = 3.074948
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/TP/MmsSmsProvider( 1477): query,matched:0, calling pid = 4951
V/TP/MmsSmsProvider( 1477): getSimpleConversations entered.
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/TP/MmsSmsProvider( 1477): match 0:Elapsed time : 1.101 ms
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/Mms/SpamFilter( 4951): [start]    SpamFilter fill() begin consume time = 8.639375
D/Mms/Synchronizer( 4951): [start]    doSync consume time = 0.110573
,W/ResourcesManager( 5044): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5044): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/TP/MmsSmsProvider( 1477): query,matched:400, calling pid = 4951
,D/TP/MmsSmsProvider( 1477): update, matched:300, calling pid = 4951
V/TP/MmsSmsProvider( 1477): syncDBData start
,V/TP/MmsSmsProvider( 1477): syncDBData sms end
,V/TP/MmsSmsProvider( 1477): syncDBData mms end
,V/TP/MmsSmsProvider( 1477): syncDBData end
D/Mms/Synchronizer( 4951): [end]    doSync consume time = 8.130052
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/PowerManagerService( 1016): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1016) eventTime = 55884,
D/PowerManagerService( 1016): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016 (0x0)
D/PowerManagerService( 1016): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{10054}) (elapsedTime=3485)
,E/Zygote  ( 5077): MountEmulatedStorage()
,E/Zygote  ( 5077): v2
I/libpersona( 5077): KNOX_SDCARD checking this for 10072
I/libpersona( 5077): KNOX_SDCARD not a persona
,I/SELinux ( 5077): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5077 uid=10072 gids={50072, 9997} abi=armeabi-v7a,
D/Mms/SpamFilter( 4951): [end]    SpamFilter fill() finished consume time = 23.954792
,I/SELinux ( 5077): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5077): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/splitIntent( 1016): Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1016): Killing 3971:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/TimaKeyStoreProvider( 5077): TimaSignature is unavailable
,D/ActivityThread( 5077): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 4156:com.sec.android.soagent/u0a34 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_4668/cgroup.procs: No such file or directory
,D/BadgeProvider( 5077): onCreate
,D/BadgeProvider( 5077): DatabaseHelper
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5093): MountEmulatedStorage()
,E/Zygote  ( 5093): v2
I/libpersona( 5093): KNOX_SDCARD checking this for 1000
I/SELinux ( 5093): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5093): KNOX_SDCARD not a persona
,I/SELinux ( 5093): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5093 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5093): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4683/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_3971/cgroup.procs: No such file or directory
,D/Mms/MessagingNotification( 4951): checkBadgeCount unreadCount=0 badgeCount=0
,W/libprocessgroup( 1016): failed to open /acct/uid_10034/pid_4156/cgroup.procs: No such file or directory
,D/TP/SmsProvider( 1477): query,matched:26, calling pid = 4951
,D/TP/SmsProvider( 1477): match 26:Elapsed time : 0.993 ms
,D/TimaKeyStoreProvider( 5093): TimaSignature is unavailable
,D/ActivityThread( 5093): Added TimaKeyStore provider
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PackageManager( 1016): [MSG] SEND_PENDING_BROADCAST
,D/TP/MmsSmsProvider( 1477): query,matched:6, calling pid = 4951
,D/TP/MmsSmsProvider( 1477): match 6:Elapsed time : 1.296 ms
,I/ApplicationPolicy( 1016): updateDataUsageMap
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,E/MTPRx   ( 5093): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,I/PageBuddyNotiSvc( 4398): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/RegisteredComponentCache( 1465): Collect Tech packages for Knox
,D/PersonaManager( 1465): isKioskContainerExistOnDevice
,D/PersonaManager( 1465): isKioskContainerExistOnDevice
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1016): mCursor = null
,D/RegisteredServicesCache( 1465): empty dynamic service
,V/MTPRx   ( 5093): sealedState: false
V/MTPRx   ( 5093): sealedUsbMassStorageState: false
E/MTPRx   ( 5093): check value of boot_completed is1
E/MTPRx   ( 5093): check booting is completed_sys.boot_completed
,E/MTPRx   ( 5093): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 5093): Status for mount/Unmount :removed
E/MTPRx   ( 5093): SDcard is not available
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/MTPRx   ( 5093): value of connected istrue
W/MTPRx   ( 5093): value of configured istrue
W/MTPRx   ( 5093): value of mtpEnabled istrue
W/MTPRx   ( 5093): value of ptpEnabled isfalse
,E/MTPRx   ( 5093): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 5093): mFirstTime: false
,D/        ( 5093): MTP: reading debug level property
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/MTPJNIInterface( 5093): Getting CryptionKey from JAVA,
I/libpersona( 5109): KNOX_SDCARD checking this for 10025
E/MTPRx   ( 5093): currentUserId is 0
I/libpersona( 5109): KNOX_SDCARD not a persona,
E/Zygote  ( 5109): MountEmulatedStorage()
E/Zygote  ( 5109): v2
I/SELinux ( 5109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5109): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5109 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5109): TimaSignature is unavailable
,D/ActivityThread( 5109): Added TimaKeyStore provider
,E/MTPRx   ( 5093): Start observing USB_STATE_MATCH 
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1016): Killing 4717:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,E/MTPRx   ( 5093): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 5093): is_Privatemode is NOT 1
,D/SettingsProvider( 1016): name = boot_time_connected
,E/MTPRx   ( 5093): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 5093): noti = 17
D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,W/ResourcesManager( 5109): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/SecContentProvider( 1016): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 5093): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/Mms/Contact( 4951): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 4951): performUpdate:widgetCount=0
,D/Mms/ContactsCache( 4951): [start]    invalidate() consume time = 364.336927
,D/Mms/ContactsCache( 4951): [end]    invalidate() consume time = 0.510156
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,E/MTPRx   ( 5093): else part ... so first time!!!
,E/MTPPlaObsrvr( 5093): inside setContext()
E/MTPPlaObsrvr( 5093):  inside createplafiles
,I/OMACP   ( 5109): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,E/MTPPlaObsrvr( 5093): playlist count is0
E/MTPPlaObsrvr( 5093):  inside try branch createplafiles
,E/MTPPlaObsrvr( 5093):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 5093): Inside registerContentObserver
,E/MtpAdbObserver( 5093): inside setContext()
E/MtpAdbObserver( 5093): Inside registerContentObserver
W/Settings( 5093): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,V/MtpMediaDBManager( 5093): inside deleteAllDB
,E/MtpService( 5093): onCreate.
,D/Mms/Omacp( 4951): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,E/MtpService( 5093): < MTP > Registering BroadCast receiver :::::
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 5093): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,I/OMACP   ( 5109): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 5109): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,V/MtpMediaDBManager( 5093): inside Thread updateDB
,I/OMACP   ( 5109): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,D/MtpService( 1237): updating state; isCurrentUser=true, mMtpLocked=false
,I/OMACP   ( 5109): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 5109): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 5109): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,E/MtpService( 5093): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,I/OMACP   ( 5109): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 5109): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 5109): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
I/OMACP   ( 5109): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,I/OMACP   ( 5109): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 5109): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,E/MtpService( 5093): onStartCommand.
,I/OMACP   ( 5109): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,W/MTPRx   ( 5093): calling native method
E/MTPJNIInterface( 5093): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 5093): handleMessage. msg= { when=-2ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 5093): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 5093): noti = 10
,E/MtpService( 5093): onStartCommand.
W/MTPRx   ( 5093): calling native method
E/MTPRx   ( 5093): Checking the driver time out
E/MTPJNIInterface( 5093): noti = 2
D/        ( 5093): deleting sockets before message queue initialization
D/        ( 5093): event handler thread is created, so set the flag
,E/MtpMediaDBManager( 5093): count : 27
,E/MTPRx   ( 5093): called native method
E/MTPJNIInterface( 5093): setting Media scanner status0
E/MTPJNIInterface( 5093): After setting Media scanner status0
,W/MTPRx   ( 5093): notification from stack 1,
E/        ( 5093): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 5093): Getting media scanner status0
,E/MTPJNIInterface( 5093): DeviceName is A5-1
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MtpService( 5093): handleMessage. msg= { when=-26ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
W/MtpMediaDBManager( 5093): sending db update complete noti to stack
E/MTPJNIInterface( 5093): noti = 29
,V/UserPresentBroadcastReceiver( 1857): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  257): id=13 Removed Uoast (8/8)
,I/SurfaceFlinger(  257): id=13 Removed Uoast (-2/8)
,E/MTPJNIInterface( 5093): Status for mount/Unmount :removed
,E/MTPJNIInterface( 5093): SDcard is not available
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/        ( 5093): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,D/BluetoothNotiBroadcastReceiver( 1320): onReceive
,E/        ( 5093): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/BluetoothStatusReceiver( 1181): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1181): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,E/MTPJNIInterface( 5093): Status for mount/Unmount :removed
E/MTPJNIInterface( 5093): SDcard is not available
E/SQLiteLog( 5093): (21) API call with NULL database connection pointer
E/SQLiteLog( 5093): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5093): (21) API call with NULL database connection pointer
E/SQLiteLog( 5093): (21) misuse at line 100726 of [9491ba7d73]
,E/SQLiteLog( 5093): (21) API call with NULL database connection pointer
E/SQLiteLog( 5093): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5093): (21) API call with NULL database connection pointer
E/SQLiteLog( 5093): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 5093): notification from stack 2
,D/        ( 5093): [mtp_init_device] Library open with 32 bits.
D/        ( 5093): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,E/        ( 5093): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 5093): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 5093):  [sua_support_present:1287] returning false 
D/        ( 5093): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5133): MountEmulatedStorage()
E/Zygote  ( 5133): v2
I/libpersona( 5133): KNOX_SDCARD checking this for 10003
I/libpersona( 5133): KNOX_SDCARD not a persona
,I/SELinux ( 5133): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5133 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a

```
