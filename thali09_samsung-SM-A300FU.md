#### Test 79751015cf21110_thali09_samsung-SM-A300FU Logs


```
--------- beginning of main
08-09 07:50:45.901  5648  5668 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-09 07:50:46.031  1017  1529 D LocationManagerService: getProviders()=[passive]
08-09 07:50:46.071  5416  5416 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
--------- beginning of system
08-09 07:50:46.211  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-09 07:50:46.211  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:46.211  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-09 07:50:46.211  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
08-09 07:50:46.241  1017  1529 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-09 07:50:46.241  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.241  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.241  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.241  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.251  5693  5693 E Zygote  : MountEmulatedStorage()
08-09 07:50:46.251  5693  5693 E Zygote  : v2
08-09 07:50:46.251  5693  5693 I libpersona: KNOX_SDCARD checking this for 1000
08-09 07:50:46.251  5693  5693 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:46.261  5693  5693 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-09 07:50:46.261  1017  1529 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5693 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-09 07:50:46.261  5685  5685 D AndroidRuntime: 
08-09 07:50:46.261  5685  5685 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-09 07:50:46.261  5693  5693 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:46.261  5693  5693 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-09 07:50:46.261  5685  5685 D AndroidRuntime: CheckJNI is OFF
08-09 07:50:46.261  5685  5685 D AndroidRuntime: readGMSProperty: start
08-09 07:50:46.261  5685  5685 D AndroidRuntime: readGMSProperty: already setted!!
08-09 07:50:46.261  5685  5685 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-09 07:50:46.261  1017  1529 I ActivityManager: Killing 4566:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
08-09 07:50:46.261  5685  5685 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-09 07:50:46.261  5685  5685 D AndroidRuntime: readGMSProperty: end
08-09 07:50:46.261  5685  5685 D AndroidRuntime: addProductProperty: start
08-09 07:50:46.281  1017  1460 D ActivityManager: startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
08-09 07:50:46.281  1017  1460 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
08-09 07:50:46.281  1017  1460 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:46.281  1017  1460 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-09 07:50:46.281  1017  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
08-09 07:50:46.291  5416  5416 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-09 07:50:46.301  5693  5693 D TimaKeyStoreProvider: TimaSignature is unavailable
08-09 07:50:46.301  5693  5693 D ActivityThread: Added TimaKeyStore provider
08-09 07:50:46.301  1017  1529 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-09 07:50:46.301  1017  1529 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
08-09 07:50:46.311  1930  1930 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-09 07:50:46.311  1017  1528 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-09 07:50:46.311  1017  1528 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
08-09 07:50:46.311  1017  1528 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:46.311  1017  1528 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-09 07:50:46.311  1017  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-09 07:50:46.341  5693  5693 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-09 07:50:46.341  5693  5693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-09 07:50:46.341  1017  1476 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-09 07:50:46.341  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-09 07:50:46.341  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:46.341  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:46.341  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-09 07:50:46.351  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
08-09 07:50:46.351  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.351  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.351  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.351  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.351  5693  5693 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-09 07:50:46.371  5416  5698 W AccountFeatureHelper: Write apps_features disabled false
08-09 07:50:46.371  5720  5720 I libpersona: KNOX_SDCARD checking this for 10098
08-09 07:50:46.371  5693  5719 E FilterInstaller: installFilters
08-09 07:50:46.371  5720  5720 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:46.371  5720  5720 E Zygote  : MountEmulatedStorage()
08-09 07:50:46.371  5720  5720 E Zygote  : v2
08-09 07:50:46.371  5693  5719 E FilterInstaller: There is no requred permission
08-09 07:50:46.371  5720  5720 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-09 07:50:46.381  5720  5720 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:46.381  5720  5720 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-09 07:50:46.381  1017  1029 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5720 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-09 07:50:46.391  5648  5668 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 309 ms] updated apps [took 309 ms] 
08-09 07:50:46.391  1017  1030 I ActivityManager: Killing 5160:com.samsung.android.sm/1000 (adj 15): empty #21
08-09 07:50:46.401   314   314 I art     : Explicit concurrent mark sweep GC freed 8681(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 640us total 26.855ms
08-09 07:50:46.411  5685  5685 E AffinityControl: AffinityControl: registerfunction enter
08-09 07:50:46.411  5720  5720 D TimaKeyStoreProvider: TimaSignature is unavailable
08-09 07:50:46.411  5720  5720 D ActivityThread: Added TimaKeyStore provider
08-09 07:50:46.421   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.858ms
08-09 07:50:46.441  5685  5685 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-09 07:50:46.441   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 16.828ms
08-09 07:50:46.451  5720  5720 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
08-09 07:50:46.451  5720  5720 D PackageIntentReceiver: Not GearManger package! 
08-09 07:50:46.451  1017  1475 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
08-09 07:50:46.451  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.451  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.451  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.451  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.461  5546  5564 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-09 07:50:46.471  5738  5738 E Zygote  : MountEmulatedStorage()
08-09 07:50:46.471  5738  5738 E Zygote  : v2
08-09 07:50:46.471  5738  5738 I libpersona: KNOX_SDCARD checking this for 1000
08-09 07:50:46.471  5738  5738 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:46.471  5738  5738 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-09 07:50:46.471  1017  1475 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5738 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-09 07:50:46.471  1017  1492 E PersonaManagerService: inState():  stateMachine is null !!
08-09 07:50:46.471  1017  1492 I PersonaManagerService: PersonaId don't exist
08-09 07:50:46.471  1017  1492 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-09 07:50:46.471  1017  1475 I ActivityManager: Killing 5177:com.google.android.apps.plus/u0a117 (adj 15): empty #21
08-09 07:50:46.481  5738  5738 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:46.481  1017  1492 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-09 07:50:46.481  5738  5738 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-09 07:50:46.491  1017  1492 W ActivityManager: mDVFSHelper.acquire()
08-09 07:50:46.501  5546  5564 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-09 07:50:46.501  1017  1492 D FocusedStackFrame: Set to : 0
08-09 07:50:46.501  5546  5564 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 07:50:46.501  5546  5564 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-09 07:50:46.501  5738  5738 D TimaKeyStoreProvider: TimaSignature is unavailable
08-09 07:50:46.501  5738  5738 D ActivityThread: Added TimaKeyStore provider
08-09 07:50:46.501  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.501  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.501  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.501  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.511  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-09 07:50:46.511  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-09 07:50:46.521  5755  5755 E Zygote  : MountEmulatedStorage()
08-09 07:50:46.521  5755  5755 E Zygote  : v2
08-09 07:50:46.521  5755  5755 I libpersona: KNOX_SDCARD checking this for 10170
08-09 07:50:46.521  5755  5755 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:46.531  5755  5755 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-09 07:50:46.531  1017  1492 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5755 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-09 07:50:46.531  1017  1492 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-09 07:50:46.531  1017  1492 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-09 07:50:46.531  1017  1492 D InputDispatcher: Focused application set to: xxxx
08-09 07:50:46.531  1017  1492 D InputDispatcher: Focus left window: 1477
08-09 07:50:46.531  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-09 07:50:46.531  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-09 07:50:46.531  5685  5685 D AndroidRuntime: Shutting down VM
08-09 07:50:46.531   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
08-09 07:50:46.531  5755  5755 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:46.531  5755  5755 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-09 07:50:46.551  5755  5755 D TimaKeyStoreProvider: TimaSignature is unavailable
08-09 07:50:46.551  5755  5755 D ActivityThread: Added TimaKeyStore provider
08-09 07:50:46.561  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-09 07:50:46.561  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-09 07:50:46.571  1017  1529 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-09 07:50:46.571  1017  1017 V ActivityManager: Display changed displayId=0
08-09 07:50:46.571  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-09 07:50:46.611  1017  1529 D PersonaManager: isKioskContainerExistOnDevice
08-09 07:50:46.621  5416  5416 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
08-09 07:50:46.621  1017  1528 I ActivityManager: Killing 5070:com.google.android.partnersetup/u0a14 (adj 15): empty #21
08-09 07:50:46.631  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-09 07:50:46.741  5685  5685 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-09 07:50:46.761  1017  1503 I art     : Explicit concurrent mark sweep GC freed 170382(9MB) AllocSpace objects, 3(2MB) LOS objects, 33% free, 23MB/34MB, paused 2.394ms total 176.462ms
08-09 07:50:46.761   258  1892 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
,08-09 07:50:46.771  1017  1503 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,08-09 07:50:46.771  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.771  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.771  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:46.771  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:46.781  1477  1477 V ActivityThread: updateVisibility : ActivityRecord{be94e75 token=android.os.BinderProxy@15169c51 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,08-09 07:50:46.781  1477  1477 D Launcher: onTrimMemory. Level: 20
,08-09 07:50:46.791  5773  5773 E Zygote  : MountEmulatedStorage()
08-09 07:50:46.791  5773  5773 E Zygote  : v2
08-09 07:50:46.791  5773  5773 I libpersona: KNOX_SDCARD checking this for 1000
08-09 07:50:46.791  5773  5773 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:46.791  5773  5773 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-09 07:50:46.791  5773  5773 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-09 07:50:46.791  5773  5773 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-09 07:50:46.801  1017  1503 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5773 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-09 07:50:46.801  1017  1503 I ActivityManager: Killing 5400:com.sec.pcw.device/1000 (adj 15): empty #21
,08-09 07:50:46.821  5773  5773 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-09 07:50:46.821  5773  5773 D ActivityThread: Added TimaKeyStore provider
,08-09 07:50:46.831  3936  4331 I Icing   : Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,08-09 07:50:46.851  5773  5788 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
,08-09 07:50:46.851  1017  1136 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-09 07:50:46.851  1017  1136 I ActivityManager: Killing 5382:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-09 07:50:46.861  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-09 07:50:46.861  1017  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-09 07:50:46.861  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-09 07:50:46.861  5773  5788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,08-09 07:50:46.861  1017  1529 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-09 07:50:46.861  1017  1529 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
08-09 07:50:46.861  1017  1529 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:46.861  1017  1529 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:46.861  1017  1529 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,08-09 07:50:46.871  5773  5773 D AcmsService: Enter Oncreate
,08-09 07:50:46.871  5773  5773 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-09 07:50:46.871  5773  5773 D AcmsService: creating AcmsCore
,08-09 07:50:46.871  5773  5773 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-09 07:50:46.871  5773  5773 D AcmsCore: AcmsCore
,08-09 07:50:46.871  5773  5773 D AcmsCore: init
08-09 07:50:46.871  5773  5773 D AcmsCore: Looper handler is not null
08-09 07:50:46.871  5773  5773 D AcmsCore: Post to AcmsCoreHandler
08-09 07:50:46.871  5773  5773 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-09 07:50:46.871  5773  5773 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-09 07:50:46.871  5773  5773 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
,08-09 07:50:46.871  5773  5773 D AcmsService: onStartCommand
08-09 07:50:46.871  5773  5773 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
08-09 07:50:46.871  5773  5773 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-09 07:50:46.871  5773  5773 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-09 07:50:46.871  5773  5773 D AcmsService: Incremented Counter Value : onStartCommand
,08-09 07:50:46.881  1017  1217 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,08-09 07:50:46.881  5773  5773 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,08-09 07:50:46.881  5773  5789 D AcmsCertificateMngr: AcmsCertificateMngr
,08-09 07:50:46.891  5773  5789 D AcmsRevocationMngr: AcmsRevocationMngr
,08-09 07:50:46.901  5755  5755 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-09 07:50:46.901  3936  4331 I Icing   : Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
,08-09 07:50:46.911  5773  5773 D AcmsService: Inside handle Intent
08-09 07:50:46.911  5773  5773 D AcmsService: App added - package name: com.test.thalitest
08-09 07:50:46.911  5773  5773 D AcmsCore: Post to AcmsCoreHandler
08-09 07:50:46.911  5773  5773 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-09 07:50:46.911  5773  5773 D AcmsServiceMonitor: Incrementing - Counter value: 3
08-09 07:50:46.911  5773  5773 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
08-09 07:50:46.911  5773  5773 D AcmsService: Decremented Counter Value : handleStartIntent
08-09 07:50:46.911  5773  5773 D AcmsServiceMonitor: Decrementing - Counter value: 2
,08-09 07:50:46.941  5755  5755 I LibraryLoader: Time to load native libraries: 25 ms (timestamps 7713-7738)
,08-09 07:50:46.941  5755  5755 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-09 07:50:46.971  5755  5755 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {40259d9}
,08-09 07:50:46.971  5755  5755 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-09 07:50:46.971  5755  5755 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-09 07:50:47.001  5755  5755 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-09 07:50:47.001  5755  5755 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-09 07:50:47.001  5755  5755 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-09 07:50:47.021  5755  5792 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,08-09 07:50:47.031  5755  5755 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-09 07:50:47.031  5755  5755 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,08-09 07:50:47.031  5755  5755 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-09 07:50:47.031  5755  5755 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-09 07:50:47.031  5755  5755 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-09 07:50:47.031  5755  5755 I Adreno-EGL: Build Date: 04/06/15 Mon
08-09 07:50:47.031  5755  5755 I Adreno-EGL: Local Branch: 
08-09 07:50:47.031  5755  5755 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-09 07:50:47.031  5755  5755 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-09 07:50:47.031  5755  5755 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-09 07:50:47.101  5755  5803 D BluetoothAdapter: 536348586: getState() :  mService = null. Returning STATE_OFF
,08-09 07:50:47.121  1017  1043 W ActivityManager: Activity pause timeout for ActivityRecord{454188f u0 com.test.thalitest/.MainActivity t50}
,08-09 07:50:47.161  5755  5801 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-09 07:50:47.181  5363  5363 I Mms/MmsApp:  start initViewCache mms
,08-09 07:50:47.191  5363  5363 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1927.824583
08-09 07:50:47.191  5363  5363 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-09 07:50:47.211  5755  5755 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-09 07:50:47.221  5755  5755 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-09 07:50:47.231  5755  5755 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-09 07:50:47.231  5755  5755 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-09 07:50:47.241  5755  5755 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-09 07:50:47.241  5755  5755 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-09 07:50:47.241  5755  5755 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-09 07:50:47.291  5755  5814 D OpenGLRenderer: Render dirty regions requested: true
,08-09 07:50:47.301  1017  1492 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-09 07:50:47.301  1017  1492 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-09 07:50:47.301  1017  1492 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-09 07:50:47.301  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-09 07:50:47.301  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-09 07:50:47.311  5755  5755 V ActivityThread: updateVisibility : ActivityRecord{1c453a81 token=android.os.BinderProxy@1859458b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-09 07:50:47.311  5755  5755 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-09 07:50:47.311  5755  5755 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-09 07:50:47.311  5363  5363 D AbsListView: Get MotionRecognitionManager
,08-09 07:50:47.311  1017  1030 D MotionRecognitionService:  ssp status : false
,08-09 07:50:47.321   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,08-09 07:50:47.321  5363  5363 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 134.348593
,08-09 07:50:47.331  1017  1529 D InputDispatcher: Focus entered window: 5755
,08-09 07:50:47.341  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-09 07:50:47.341  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-09 07:50:47.341  5755  5755 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-09 07:50:47.341  5755  5814 I OpenGLRenderer: Initialized EGL, version 1.4
,08-09 07:50:47.341  5755  5814 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-09 07:50:47.351  5755  5814 D OpenGLRenderer: Enabling debug mode 0
,08-09 07:50:47.371  1017  1475 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-09 07:50:47.381  1173  1173 I StatusBar: Icon Only,
08-09 07:50:47.381  1173  1173 D PanelView: There is/are notification(s) 
,08-09 07:50:47.381  1017  5818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-09 07:50:47.391  3936  4331 I Icing   : Indexing D2B2F813CD55909B17D100D9886DFA4C4B449F6E from com.google.android.googlequicksearchbox
,08-09 07:50:47.391  5755  5755 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-09 07:50:47.391  5755  5755 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1859458b time:88187
,08-09 07:50:47.401  1017  1048 I ActivityManager: Displayed Component not be shown by security: +784ms (total +899ms)
,08-09 07:50:47.401  1017  1048 W ActivityManager: mDVFSHelper.release()
08-09 07:50:47.401  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{454188f u0 com.test.thalitest/.MainActivity t50} time:88197
,08-09 07:50:47.411  5363  5363 D Mms/BubbleViewCache: fillCache bubble = 1
,08-09 07:50:47.411  1771  1771 I SamsungIME: getCurrentCandidateView
,08-09 07:50:47.421   258  1892 I SurfaceFlinger: id=11 Removed uhalitest (7/9)
,08-09 07:50:47.421   258   455 I SurfaceFlinger: id=11 Removed uhalitest (-2/9)
,08-09 07:50:47.481  5755  5755 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5755
,08-09 07:50:47.521  3936  4331 I Icing   : Indexing done D2B2F813CD55909B17D100D9886DFA4C4B449F6E
,08-09 07:50:47.541  1771  1771 D SamsungIME: Dismiss ExpandCandiate
,08-09 07:50:47.561  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-09 07:50:47.561  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-09 07:50:47.561  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-09 07:50:47.561  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-09 07:50:47.611  5755  5755 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-09 07:50:47.701  1771  1771 I SamsungIME: getDebugLevel  : 0x4f4c
,08-09 07:50:47.721  5755  5820 D jxcore_app_log: JniHelper::setJavaVM(0xb7f6b2f0), pthread_self() = -1202954664
,08-09 07:50:47.731  5755  5820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-09 07:50:47.731  5755  5820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-09 07:50:47.731  5755  5820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-09 07:50:47.731  5755  5820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-09 07:50:47.731  5755  5820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-09 07:50:47.731  5755  5820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bd0c5f1 added. We now have 1 listener(s)
,08-09 07:50:47.731  1771  1771 I SamsungIME: getDebugLevel  : 0x4f4c
,08-09 07:50:47.751  1771  1771 I SamsungIME: KeybaordView init() : load resources
,08-09 07:50:47.751  5755  5820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
08-09 07:50:47.751  5755  5820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-09 07:50:47.751  5755  5820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 07:50:47.751  5755  5820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-09 07:50:47.761  5755  5820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9aa1744 added. We now have 1 listener(s)
08-09 07:50:47.761  5755  5820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 07:50:47.771  5755  5820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-09 07:50:47.771  5755  5820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-09 07:50:47.771  5755  5820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-09 07:50:47.771  5755  5820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-09 07:50:47.771  5755  5820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-09 07:50:47.771  5755  5820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 07:50:47.771  5755  5820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-09 07:50:47.771  5755  5820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:50:47.771  5755  5820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 07:50:47.771  5755  5820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:50:47.771  5755  5820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 07:50:47.771  5755  5820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 07:50:47.771  5755  5820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:50:47.771  5755  5820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:50:47.771  5755  5820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:50:47.771  5755  5820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 07:50:47.771  5755  5820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-09 07:50:47.771  5755  5820 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-09 07:50:47.781  5755  5820 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-09 07:50:47.791  1771  1771 I SamsungIME: getCurrentKeyboard
08-09 07:50:47.791  1771  1771 I SamsungIME: getTextKeyboard
,08-09 07:50:47.811  1771  1771 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-09 07:50:47.821  5755  5755 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-09 07:50:47.921   294   294 E SMD     : DCD OFF
,08-09 07:50:48.411  5773  5789 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,08-09 07:50:48.431  5773  5789 I AcmsKeyStoreHelper: Key Store exist
08-09 07:50:48.431  5773  5789 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-09 07:50:48.531  5755  5826 W jxcore-log: Initializing JXcore engine
08-09 07:50:48.531  5755  5826 W jxcore-log: JXcore engine is ready
08-09 07:50:48.541  5773  5789 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-09 07:50:48.541  5773  5789 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-09 07:50:48.541  5773  5789 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-09 07:50:48.541  5773  5789 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-09 07:50:48.541  5773  5789 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-09 07:50:48.541  5773  5789 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-09 07:50:48.541  5773  5789 D AcmsCore: This is NOT a valid MirrorLink app
08-09 07:50:48.541  5773  5789 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-09 07:50:48.541  5773  5789 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-09 07:50:48.541  5773  5789 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-09 07:50:48.541  5773  5789 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
08-09 07:50:48.541  5773  5773 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-09 07:50:48.541  5773  5773 D AcmsService: Enter onDestroy
08-09 07:50:48.541  5773  5773 I AcmsService: cleanUp(): inside service clean up
08-09 07:50:48.541  5773  5773 D AcmsCore: AcmsCore: inside DeInit
08-09 07:50:48.541  5773  5773 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-09 07:50:48.541  5773  5773 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-09 07:50:48.541  5773  5773 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-09 07:50:48.541  5773  5773 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-09 07:50:48.541  5773  5773 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
08-09 07:50:48.541  5773  5773 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-09 07:50:48.541  5773  5773 D AcmsService: killing acms process
08-09 07:50:48.541  5773  5773 I Process : Sending signal. PID: 5773 SIG: 9
08-09 07:50:48.581  1900  1900 E audit   : type=1400 msg=audit(1470721848.581:203): avc:  denied  { ioctl } for  pid=5826 comm="Thread-1028" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-09 07:50:48.581  1900  1900 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:48.581  1900  1900 E audit   : type=1300 msg=audit(1470721848.581:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e6008f8 items=0 ppid=314 ppcomm=main pid=5826 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1028" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-09 07:50:48.581  1900  1900 E audit   : type=1320 msg=audit(1470721848.581:203): 
08-09 07:50:48.601  5755  5826 W jxcore-log: Starting JXcore engine
08-09 07:50:48.631  1017  1029 I ActivityManager: Process ACMS.Process (pid 5773)(adj 0) has died(24,798)
08-09 07:50:48.701  5755  5826 W jxcore-log: Platform android
08-09 07:50:48.701  5755  5826 W jxcore-log: 
08-09 07:50:48.701  5755  5826 W jxcore-log: Process ARCH arm
08-09 07:50:48.701  5755  5826 W jxcore-log: 
08-09 07:50:48.941  5755  5826 I jxcore-log: JXcore Cordova bridge is ready!
08-09 07:50:48.941  5755  5826 I jxcore-log: 
08-09 07:50:48.941  5755  5826 W jxcore-log: JXcore engine is started
08-09 07:50:48.941  5755  5820 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-09 07:50:48.941  5755  5755 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-09 07:50:48.951  5755  5826 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
08-09 07:50:48.951  5755  5826 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
08-09 07:50:48.961  5755  5755 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
08-09 07:50:48.971  5755  5755 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
08-09 07:50:48.971  1017  1503 D FocusedStackFrame: Set to : 0
08-09 07:50:48.971  1017  1503 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-09 07:50:48.971  1017  1503 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-09 07:50:48.971  1017  1503 D InputDispatcher: Focused application set to: xxxx
08-09 07:50:48.971  1017  1503 D InputDispatcher: Focus left window: 5755
08-09 07:50:48.981  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-09 07:50:48.981  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-09 07:50:48.991  5755  5755 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-09 07:50:48.991  5755  5820 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
08-09 07:50:48.991  5755  5755 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-09 07:50:48.991  5755  5755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:50:48.991  5755  5755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:50:48.991  5755  5755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:50:48.991  5755  5755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 07:50:48.991  5755  5755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bd0c5f1 removed from the list
08-09 07:50:48.991  5755  5755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:50:48.991  5755  5755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9aa1744 removed from the list
08-09 07:50:48.991  5755  5755 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:50:48.991  5755  5755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-09 07:50:48.991  5755  5755 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-09 07:50:49.001   258   448 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
08-09 07:50:49.001   258  1892 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
08-09 07:50:49.011  1017  1029 W ActivityManager: mDVFSHelper.acquire()
08-09 07:50:49.021  1017  1029 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-09 07:50:49.041  1477  1477 D Launcher: onRestart, Launcher: 506837653
08-09 07:50:49.041  1477  1477 D Launcher: onStart, Launcher: 506837653
08-09 07:50:49.041  1477  1477 D Launcher.HomeView: onStart
08-09 07:50:49.041  1477  1477 D Launcher: onResume, Launcher: 506837653
08-09 07:50:49.041  1017  1475 D SettingsProvider: name = kids_home_mode
08-09 07:50:49.041  1017  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-09 07:50:49.041  1017  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-09 07:50:49.041  1017  1475 D SettingsProvider: selectionArgs: false
08-09 07:50:49.041  1017  1475 D SettingsProvider: selectionArgs: 10006
08-09 07:50:49.041  1017  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-09 07:50:49.041  1017  1475 D SettingsProvider: ret = -1
08-09 07:50:49.041  1477  1477 D Launcher.HomeView: onResume
08-09 07:50:49.051  1477  1477 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-09 07:50:49.051  1477  1477 D MenuAppsGridFragment: onResume
08-09 07:50:49.051  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:49.051  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:49.051  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
08-09 07:50:49.051  1477  1477 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-09 07:50:49.061  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:49.061  1017  1529 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
08-09 07:50:49.061  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:49.061  1017  1529 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
08-09 07:50:49.061  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
08-09 07:50:49.061  1477  1477 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-09 07:50:49.061  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:49.061  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:49.061  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
08-09 07:50:49.061  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
08-09 07:50:49.071  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.071  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.071  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.071  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.081  5828  5828 E Zygote  : MountEmulatedStorage()
08-09 07:50:49.081  5828  5828 E Zygote  : v2
08-09 07:50:49.081  5828  5828 I libpersona: KNOX_SDCARD checking this for 10089
08-09 07:50:49.081  5828  5828 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:49.081  5828  5828 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-09 07:50:49.081  1017  1043 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=5828 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
08-09 07:50:49.091  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:49.091  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:49.091  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
08-09 07:50:49.091  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
08-09 07:50:49.091  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.091  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.091  5828  5828 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:49.091  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.091  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.091  5828  5828 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-09 07:50:49.101  5839  5839 E Zygote  : MountEmulatedStorage()
08-09 07:50:49.101  5839  5839 E Zygote  : v2
08-09 07:50:49.101  5839  5839 I libpersona: KNOX_SDCARD checking this for 10139
08-09 07:50:49.101  1017  1476 D ActivityManager: handle home activity for 0
08-09 07:50:49.101  5839  5839 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:49.101  1017  1476 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-09 07:50:49.101  1017  1043 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5839 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
08-09 07:50:49.101  1017  1476 D KnoxTimeoutHandler: post home show event for user 0
08-09 07:50:49.111  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-09 07:50:49.101  1017  1476 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-09 07:50:49.101  1017  1476 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-09 07:50:49.111  1017  1529 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
08-09 07:50:49.101  1017  1476 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-09 07:50:49.111  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.111  1477  1477 D Launcher.HomeView: onPause
08-09 07:50:49.111  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.111  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-09 07:50:49.111  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.111  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-09 07:50:49.111  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.111  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-09 07:50:49.111  5839  5839 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-09 07:50:49.111  1477  1477 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-09 07:50:49.111  1017  1529 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:49.111  1017  1529 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:49.111  1017  1529 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
08-09 07:50:49.111  5839  5839 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:49.111  5839  5839 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-09 07:50:49.131  5828  5828 D TimaKeyStoreProvider: TimaSignature is unavailable
08-09 07:50:49.131  5828  5828 D ActivityThread: Added TimaKeyStore provider
08-09 07:50:49.131  1017  1529 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=5856 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-09 07:50:49.131  5856  5856 E Zygote  : MountEmulatedStorage()
08-09 07:50:49.131  5856  5856 E Zygote  : v2
08-09 07:50:49.131  5856  5856 I libpersona: KNOX_SDCARD checking this for 10039
08-09 07:50:49.131  5856  5856 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:49.131  5856  5856 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-09 07:50:49.141  5839  5839 D TimaKeyStoreProvider: TimaSignature is unavailable
08-09 07:50:49.141  5856  5856 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:49.141  5839  5839 D ActivityThread: Added TimaKeyStore provider
08-09 07:50:49.141  5856  5856 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-09 07:50:49.141  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:49.141  1017  1029 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1477, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
08-09 07:50:49.141  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:49.141  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
08-09 07:50:49.151   258   258 I SurfaceFlinger: id=13 createSurf (540x960),1 flag=4, Mauncher
08-09 07:50:49.151  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-09 07:50:49.151  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:49.151  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:49.151  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
08-09 07:50:49.151  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-09 07:50:49.151  5828  5828 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-09 07:50:49.151  5828  5828 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
08-09 07:50:49.151  2509  2509 D Recents_RecreateReceiver: onReceive by home
08-09 07:50:49.161  1017  1503 D InputDispatcher: Focus entered window: 1477
08-09 07:50:49.161  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-09 07:50:49.161  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-09 07:50:49.161  1477  1477 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-09 07:50:49.161  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:49.161  1017  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:49.161  1017  1492 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
08-09 07:50:49.161  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
08-09 07:50:49.171  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.171  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.171  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.171  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.171  5856  5856 D TimaKeyStoreProvider: TimaSignature is unavailable
08-09 07:50:49.171  5856  5856 D ActivityThread: Added TimaKeyStore provider
08-09 07:50:49.171  1477  1477 D Launcher.HomeView: onStop
08-09 07:50:49.171  1477  1477 V ActivityThread: updateVisibility : ActivityRecord{be94e75 token=android.os.BinderProxy@15169c51 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-09 07:50:49.181  1017  1528 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-09 07:50:49.181  5839  5839 V TaskCloserActivity: TaskCloserActivity enter()
08-09 07:50:49.181  5876  5876 E Zygote  : MountEmulatedStorage()
08-09 07:50:49.181  1017  5875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-09 07:50:49.181  5876  5876 E Zygote  : v2
08-09 07:50:49.181  5876  5876 I libpersona: KNOX_SDCARD checking this for 10084
08-09 07:50:49.181  5876  5876 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:49.181  5839  5839 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
08-09 07:50:49.181  5876  5876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-09 07:50:49.181  1771  1771 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
08-09 07:50:49.191  5755  5755 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-09 07:50:49.191  5876  5876 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:49.191  1017  1492 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=5876 uid=10084 gids={50084, 9997} abi=armeabi-v7a
08-09 07:50:49.191  5876  5876 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-09 07:50:49.191  1173  1173 I StatusBar: Icon Only
08-09 07:50:49.191  1173  1173 D PanelView: There is/are notification(s) 
08-09 07:50:49.201  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:49.201  1017  1492 I ActivityManager: Killing 5426:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
08-09 07:50:49.201  1017  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:49.201  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
08-09 07:50:49.221  1477  1477 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@15169c51 time:90010
08-09 07:50:49.221  5876  5876 D TimaKeyStoreProvider: TimaSignature is unavailable
08-09 07:50:49.221  5876  5876 D ActivityThread: Added TimaKeyStore provider
08-09 07:50:49.221  5856  5856 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-09 07:50:49.221  5856  5856 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 07:50:49.221  5856  5856 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-09 07:50:49.221  5856  5856 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-09 07:50:49.231  5856  5856 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-09 07:50:49.231  5856  5856 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-09 07:50:49.231  5856  5856 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-09 07:50:49.241  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:49.241  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:49.241  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
08-09 07:50:49.241  1017  1503 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
08-09 07:50:49.241  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.241  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.241  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.241  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:49.241  5876  5876 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-09 07:50:49.271  5894  5894 E Zygote  : MountEmulatedStorage()
08-09 07:50:49.281  5894  5894 E Zygote  : v2
08-09 07:50:49.281  5894  5894 I libpersona: KNOX_SDCARD checking this for 10135
08-09 07:50:49.281  5894  5894 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:49.281  5894  5894 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-09 07:50:49.281  5894  5894 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:49.281  1017  1503 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5894 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
08-09 07:50:49.281  5894  5894 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-09 07:50:49.281  1017  1503 I ActivityManager: Killing 5093:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-09 07:50:49.281  1017  1043 W ProcessCpuTracker: Skipping unknown process pid 5426
08-09 07:50:49.291  1017  1460 D PersonaManager: isKioskContainerExistOnDevice
,08-09 07:50:49.301  1017  1048 W ActivityManager: mDVFSHelper.release()
08-09 07:50:49.301  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{35b545c3 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t49} time:90093
08-09 07:50:49.301  1017  1217 I ActivityManager: Killing 5447:com.sec.spp.push/u0a32 (adj 15): empty #21
08-09 07:50:49.311  5894  5894 D TimaKeyStoreProvider: TimaSignature is unavailable
08-09 07:50:49.311  5894  5894 D ActivityThread: Added TimaKeyStore provider
,08-09 07:50:49.321  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-09 07:50:49.331  5894  5894 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,08-09 07:50:49.331  5894  5894 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-09 07:50:49.331  5894  5894 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-09 07:50:49.331  5894  5894 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
08-09 07:50:49.331  5894  5894 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
,08-09 07:50:49.371  1017  1460 I ActivityManager: Killing 5462:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-09 07:50:49.391  5856  5856 D NearbySource: Nearby Source Create!
,08-09 07:50:49.401  5856  5856 D NearbyContext: Nearby Context Create!
,08-09 07:50:49.431   257   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-09 07:50:49.431   257   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-09 07:50:49.431  5856  5856 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-09 07:50:49.431  5856  5856 D SLinkSource: Samsung link source created
,08-09 07:50:49.481  5856  5913 D ContactProvider: getAllContactInfoList Start
,08-09 07:50:49.481  1017  1136 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-09 07:50:49.491  1017  1217 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-09 07:50:49.491  5856  5856 D GalleryCacheReady: Receive : home resume
,08-09 07:50:49.491  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-09 07:50:49.491  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:49.491  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,08-09 07:50:49.501  5363  5363 D Mms/UIEventReceiver: ui event
,08-09 07:50:49.501  1017  1476 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.,
,08-09 07:50:49.501  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:49.501  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:49.501  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-09 07:50:49.511  5839  5839 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,08-09 07:50:49.511  1017  1492 I ActivityManager: Killing 5483:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-09 07:50:49.521  5856  5913 D ContactProvider: getAllContactInfoList End
,08-09 07:50:49.521  5856  5913 I syncContacts: thread: 1028, sync time = 53
,08-09 07:50:49.531  1017  2718 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-09 07:50:49.561  5911  5911 D AndroidRuntime: 
08-09 07:50:49.561  5911  5911 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-09 07:50:49.561  5911  5911 D AndroidRuntime: CheckJNI is OFF
,08-09 07:50:49.561  5911  5911 D AndroidRuntime: readGMSProperty: start
08-09 07:50:49.561  5911  5911 D AndroidRuntime: readGMSProperty: already setted!!
08-09 07:50:49.561  5911  5911 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-09 07:50:49.561  5911  5911 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-09 07:50:49.561  5911  5911 D AndroidRuntime: readGMSProperty: end
08-09 07:50:49.561  5911  5911 D AndroidRuntime: addProductProperty: start
,08-09 07:50:49.681  5911  5911 E AffinityControl: AffinityControl: registerfunction enter,
,08-09 07:50:49.711  5911  5911 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-09 07:50:49.721  1017  1136 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-09 07:50:49.721  1017  1136 D PackageManager: START PACKAGE DELETE: observer{1005642029}
08-09 07:50:49.721  1017  1136 D PackageManager: pkg{<packageName>}
08-09 07:50:49.721  1017  1136 D PackageManager: user{0}
08-09 07:50:49.721  1017  1136 D PackageManager: caller{2000}
08-09 07:50:49.721  1017  1136 D PackageManager: flags{2}
,08-09 07:50:49.721  1017  1136 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-09 07:50:49.721  1017  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER,
08-09 07:50:49.721  1017  1136 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-09 07:50:49.721  1017  1136 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-09 07:50:49.721  1017  1136 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-09 07:50:49.721  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
08-09 07:50:49.721  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-09 07:50:49.721  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
08-09 07:50:49.721  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-09 07:50:49.721  1017  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg,
,08-09 07:50:49.721  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-09 07:50:49.721  1017  1043 I ActivityManager: Killing 5755:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,08-09 07:50:49.811  1017  1058 W PackageSettings: Skipping PackageSetting{c579947 com.example.hello/10168} due to missing metadata
,08-09 07:50:49.851  1017  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-09 07:50:49.861  1017  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-09 07:50:49.911  5546  5546 I art     : Explicit concurrent mark sweep GC freed 17309(954KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 869us total 47.807ms
,08-09 07:50:49.921  5648  5648 I art     : Explicit concurrent mark sweep GC freed 24797(1549KB) AllocSpace objects, 1(22KB) LOS objects, 26% free, 5MB/7MB, paused 1.700ms total 65.510ms
,08-09 07:50:49.931  1771  1771 E SamsungIME: mOCRHelper is null
,08-09 07:50:49.941  5693  5693 I art     : Explicit concurrent mark sweep GC freed 9275(431KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 3MB/5MB, paused 976us total 85.169ms
,08-09 07:50:49.941  1930  2102 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-09 07:50:49.951  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-09 07:50:49.961  3633  3633 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 09 07:50:49 GMT+02:00 2016
,08-09 07:50:49.961  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,08-09 07:50:49.981  1017  1123 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-09 07:50:49.981  1017  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-09 07:50:49.981  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-09 07:50:49.991  1017  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
08-09 07:50:49.991  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-09 07:50:49.991  1017  1042 W TextServicesManagerService: no available spell checker services found
08-09 07:50:49.991  1017  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-09 07:50:49.991  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-09 07:50:49.991  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-09 07:50:49.991  1017  1492 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-09 07:50:50.001  1017  1123 V NetworkStats: performPollLocked() took 17ms
08-09 07:50:50.001  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-09 07:50:50.001  1438  1438 D RegisteredServicesCache: empty dynamic service
,08-09 07:50:50.001  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-09 07:50:50.001  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-09 07:50:50.001  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-09 07:50:50.001  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-09 07:50:50.001  1017  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:50.001  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-09 07:50:50.001  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-09 07:50:50.011  3633  3633 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-09 07:50:50.011  1017  1529 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
08-09 07:50:50.011  1017  1529 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-09 07:50:50.011  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-09 07:50:50.021  1017  1529 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-09 07:50:50.021  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.021  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.021  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.021  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.021  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-09 07:50:50.031  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-09 07:50:50.041  1017  1029 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-09 07:50:50.041  1017  1029 D SecContentProvider2: mCursor = null
08-09 07:50:50.041  5924  5924 E Zygote  : MountEmulatedStorage()
08-09 07:50:50.041  5924  5924 I libpersona: KNOX_SDCARD checking this for 10090
08-09 07:50:50.041  5924  5924 E Zygote  : v2
08-09 07:50:50.041  5924  5924 I libpersona: KNOX_SDCARD not a persona
,08-09 07:50:50.041  5924  5924 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-09 07:50:50.041  5924  5924 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-09 07:50:50.041  5924  5924 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-09 07:50:50.041  1017  1529 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5924 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-09 07:50:50.051  3633  3633 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-09 07:50:50.051  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
,08-09 07:50:50.061  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,08-09 07:50:50.071  3633  3633 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-09 07:50:50.071  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-09 07:50:50.081  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-09 07:50:50.091  3633  3633 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-09 07:50:50.091  1017  1124 D NtpTrustedTime: forceRefresh() from cache miss
,08-09 07:50:50.091   281  1001 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-09 07:50:50.091   281  1001 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-09 07:50:50.091  5363  5363 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,08-09 07:50:50.091  1017  1492 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-09 07:50:50.091  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,08-09 07:50:50.091   281  1001 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-09 07:50:50.091   281  1001 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-09 07:50:50.101  1017  1124 D NtpTrustedTime: forceRefresh Fail.
,08-09 07:50:50.101  5924  5924 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-09 07:50:50.101  3633  5923 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-09 07:50:50.101  5924  5924 D ActivityThread: Added TimaKeyStore provider
,08-09 07:50:50.111  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-09 07:50:50.111  1017  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:50.111  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-09 07:50:50.111  3633  5923 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-09 07:50:50.121  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-09 07:50:50.121  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.121  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.121  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.121  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.121  3633  5923 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-09 07:50:50.131  3633  5923 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-09 07:50:50.131  5363  5941 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,08-09 07:50:50.131  5363  5941 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,08-09 07:50:50.141  5942  5942 E Zygote  : MountEmulatedStorage(),
,08-09 07:50:50.141  5942  5942 E Zygote  : v2
08-09 07:50:50.141  5942  5942 I libpersona: KNOX_SDCARD checking this for 1000
08-09 07:50:50.141  5942  5942 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:50.141  5942  5942 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-09 07:50:50.141  5942  5942 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:50.141  5942  5942 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-09 07:50:50.151  1017  1043 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=5942 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-09 07:50:50.161  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-09 07:50:50.161  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.161  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.161  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.161  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.181  5951  5951 E Zygote  : MountEmulatedStorage()
,08-09 07:50:50.181  5951  5951 E Zygote  : v2
08-09 07:50:50.181  5951  5951 I libpersona: KNOX_SDCARD checking this for 1000
08-09 07:50:50.181  5951  5951 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:50.181  5951  5951 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-09 07:50:50.181  1017  1043 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5951 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-09 07:50:50.181  5951  5951 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-09 07:50:50.181  5951  5951 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-09 07:50:50.191  1017  1476 I TactileAssist: enable value -1
08-09 07:50:50.191  1017  1476 I TactileAssist: internal enable value -1
08-09 07:50:50.191  1017  1476 I TactileAssist: intensity value -1
08-09 07:50:50.191  1017  1476 I TactileAssist: saveAppList value true
,08-09 07:50:50.201  1017  1476 I TactileAssist: List of disabled apps :
,08-09 07:50:50.211   314   314 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 26.107ms
,08-09 07:50:50.211  5951  5951 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-09 07:50:50.211  5942  5942 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-09 07:50:50.211  5951  5951 D ActivityThread: Added TimaKeyStore provider
08-09 07:50:50.211  5942  5942 D ActivityThread: Added TimaKeyStore provider
,08-09 07:50:50.221   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 17.085ms
,08-09 07:50:50.231  1017  1058 I art     : Explicit concurrent mark sweep GC freed 38410(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 4.389ms total 274.366ms
,08-09 07:50:50.241  5630  5630 D Compatibility: onReceive() it will make start service
,08-09 07:50:50.241  1017  1217 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,08-09 07:50:50.241  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-09 07:50:50.241   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 17.110ms
,08-09 07:50:50.251  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:50.251  1017  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:50.251  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-09 07:50:50.261  5924  5924 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-09 07:50:50.261  1017  1217 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-09 07:50:50.261  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-09 07:50:50.261  5924  5924 D elm:15121: ELMEngine.ELMEngine( context ).
,08-09 07:50:50.261  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:50.261  1017  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-09 07:50:50.261  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-09 07:50:50.261  3633  5923 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-09 07:50:50.261  5924  5924 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-09 07:50:50.261  1017  1476 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-09 07:50:50.261  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-09 07:50:50.271  5630  5972 D Compatibility: onHandleIntent()
,08-09 07:50:50.271  5630  5972 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10170, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
08-09 07:50:50.271  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:50.271  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:50.271  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-09 07:50:50.271  5924  5924 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-09 07:50:50.271  5951  5951 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-09 07:50:50.271  5630  5972 D Compatibility: found: 2
,08-09 07:50:50.271  5630  5972 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-09 07:50:50.271  5630  5972 D Compatibility: skipping ResolveInfo{159e0a4c com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-09 07:50:50.271  5630  5972 D Compatibility: considering ResolveInfo{1e35ba95 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-09 07:50:50.271  5630  5972 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-09 07:50:50.281  5924  5924 D elm:15121: ElmAgentService : onCreate()
,08-09 07:50:50.281  5924  5974 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-09 07:50:50.281  5924  5974 D elm:15121: MainReceiver.listeningToPackageRemoved()
,08-09 07:50:50.281  5648  5973 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-09 07:50:50.281  3633  5923 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-09 07:50:50.281  1017  1528 D SecContentProvider2: uri = -1 selection = getSealedState
08-09 07:50:50.281  1017  1528 D SecContentProvider2: mCursor = null
,08-09 07:50:50.281  5630  5972 D Compatibility: enabling receiver ResolveInfo{1ff807aa com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-09 07:50:50.281  3273  3273 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
08-09 07:50:50.281  5951  5951 I PopupuiReceiver_KNOX: getSealedState : true
,08-09 07:50:50.281  3273  3273 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-09 07:50:50.281  1017  1460 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-09 07:50:50.281  1017  1460 D SecContentProvider2: mCursor = null
08-09 07:50:50.281  3273  3273 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-09 07:50:50.281  3273  3273 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-09 07:50:50.281  3273  3273 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-09 07:50:50.281  3273  3273 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-09 07:50:50.281  3273  3273 W System.err: ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-09 07:50:50.281  3273  3273 W System.err: ,	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:50.281  3273  3273 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,08-09 07:50:50.281  3273  3273 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-09 07:50:50.281  3273  3273 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-09 07:50:50.281  3273  3273 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:50.281  3273  3273 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
,08-09 07:50:50.281  3273  3273 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-09 07:50:50.291  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-09 07:50:50.281  3633  5923 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-09 07:50:50.291  5951  5951 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-09 07:50:50.291  1017  1528 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-09 07:50:50.291  1017  1528 D SecContentProvider2: mCursor = null
,08-09 07:50:50.291  5951  5951 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-09 07:50:50.291  5951  5951 D PopupuiReceiver: Action package removed
,08-09 07:50:50.291  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.291  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.291  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.291  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.301  5630  5972 D Compatibility: enabling receiver ResolveInfo{66d3f9b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-09 07:50:50.301  3633  3633 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-09 07:50:50.301  5942  5942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-09 07:50:50.301  5630  5972 D Compatibility: enabling receiver ResolveInfo{12c77f38 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-09 07:50:50.311  5975  5975 E Zygote  : MountEmulatedStorage()
,08-09 07:50:50.311  5975  5975 E Zygote  : v2,
08-09 07:50:50.311  5975  5975 I libpersona: KNOX_SDCARD checking this for 10055
08-09 07:50:50.311  5975  5975 I libpersona: KNOX_SDCARD not a persona
,08-09 07:50:50.311  5975  5975 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-09 07:50:50.321  1017  1030 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5975 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-09 07:50:50.321  5975  5975 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-09 07:50:50.321  5975  5975 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-09 07:50:50.321  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-09 07:50:50.331  5924  5974 D elm:15121: MDMBridge.getInstance()
08-09 07:50:50.331  5924  5974 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-09 07:50:50.331  5630  5972 D Compatibility: enabling receiver ResolveInfo{25046b11 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-09 07:50:50.341  5924  5974 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK(),
,08-09 07:50:50.341  1017  1503 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-09 07:50:50.341  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-09 07:50:50.351  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:50.351  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:50.351  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-09 07:50:50.351  5630  5972 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
08-09 07:50:50.351  1017  1460 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-09 07:50:50.351  1017  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.351  1017  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.351  1017  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.351  1017  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.361  5993  5993 E Zygote  : MountEmulatedStorage()
,08-09 07:50:50.361  5993  5993 E Zygote  : v2
08-09 07:50:50.361  5993  5993 I libpersona: KNOX_SDCARD checking this for 10145
08-09 07:50:50.361  5993  5993 I libpersona: KNOX_SDCARD not a persona
,08-09 07:50:50.371  5993  5993 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-09 07:50:50.371  1017  1460 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5993 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-09 07:50:50.371  5993  5993 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-09 07:50:50.371  5924  5924 D elm:15121: ElmAgentService : onDestroy().
08-09 07:50:50.371  5993  5993 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-09 07:50:50.381  1017  1058 D PackageManager: delete codoeFile: 
,08-09 07:50:50.391  5975  5975 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-09 07:50:50.391  5975  5975 D ActivityThread: Added TimaKeyStore provider
,08-09 07:50:50.391  1017  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-09 07:50:50.391  1017  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-09 07:50:50.401  1017  1058 D PackageManager: result of delete: 1{1005642029}
,08-09 07:50:50.401  1017  1460 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-09 07:50:50.401  1017  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.401  1017  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.401  1017  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.401  1017  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.401  5911  5911 D AndroidRuntime: Shutting down VM
,08-09 07:50:50.411  1017  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-09 07:50:50.411  1017  1058 D PackageManager: userId{-1}
08-09 07:50:50.411  1017  1058 D PackageManager: andCode{true}
,08-09 07:50:50.411  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-09 07:50:50.411  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-09 07:50:50.411  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-09 07:50:50.411  1017  1017 V EnterpriseBillingPolicy: uID is 10170
08-09 07:50:50.411  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-09 07:50:50.411  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-09 07:50:50.411  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-09 07:50:50.411  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-09 07:50:50.411  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-09 07:50:50.411  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-09 07:50:50.411  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-09 07:50:50.411  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-09 07:50:50.421  6009  6009 E Zygote  : MountEmulatedStorage()
08-09 07:50:50.421  6009  6009 I libpersona: KNOX_SDCARD checking this for 1000
08-09 07:50:50.421  6009  6009 E Zygote  : v2
08-09 07:50:50.421  6009  6009 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:50.421  6009  6009 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-09 07:50:50.421  5993  5993 D TimaKeyStoreProvider: TimaSignature is unavailable
08-09 07:50:50.421  5993  5993 D ActivityThread: Added TimaKeyStore provider
08-09 07:50:50.421  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-09 07:50:50.421  6009  6009 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:50.421  6009  6009 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-09 07:50:50.431  1017  1460 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6009 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-09 07:50:50.431  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-09 07:50:50.431  1017  1528 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-09 07:50:50.431  1017  1528 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-09 07:50:50.441  1017  1528 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:50.441  1017  1528 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-09 07:50:50.441  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-09 07:50:50.441  1017  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-09 07:50:50.441  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 07:50:50.441  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-09 07:50:50.441  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-09 07:50:50.441  1017  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-09 07:50:50.441  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-09 07:50:50.441  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-09 07:50:50.441  1017  1017 V EnterpriseBillingPolicy: uID is 10170
08-09 07:50:50.441  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-09 07:50:50.441  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-09 07:50:50.441  1017  2705 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-09 07:50:50.451  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-09 07:50:50.451  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-09 07:50:50.451  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-09 07:50:50.451  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-09 07:50:50.451  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-09 07:50:50.451  1017  1017 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-09 07:50:50.461  1017  1161 D TaskPersister: removeObsoleteFile: deleting file=50_task.xml
,08-09 07:50:50.461  1017  1460 I ActivityManager: Killing 5199:com.android.vending/u0a26 (adj 15): empty #21
,08-09 07:50:50.471  6009  6009 D TimaKeyStoreProvider: TimaSignature is unavailable
08-09 07:50:50.471  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-09 07:50:50.471  6009  6009 D ActivityThread: Added TimaKeyStore provider
08-09 07:50:50.471  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-09 07:50:50.481  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-09 07:50:50.481  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-09 07:50:50.481  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-09 07:50:50.491  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-09 07:50:50.491  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-09 07:50:50.491  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-09 07:50:50.491  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-09 07:50:50.491  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-09 07:50:50.491  1017  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-09 07:50:50.491  1017  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-09 07:50:50.501  1017  1529 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-09 07:50:50.501  1017  1529 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,08-09 07:50:50.511  1017  1529 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:50.511  1017  1529 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-09 07:50:50.511  1017  1529 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-09 07:50:50.521  5975  5975 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-09 07:50:50.521  6009  6009 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-09 07:50:50.521  5648  5973 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 243 ms] updated apps [took 243 ms] 
,08-09 07:50:50.531  1017  1476 I ActivityManager: Killing 5496:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-09 07:50:50.531  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-09 07:50:50.531  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.531  6009  6009 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
08-09 07:50:50.531  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.531  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.531  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.531  1017  1476 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-09 07:50:50.531  1017  1476 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-09 07:50:50.531  5993  5993 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-09 07:50:50.531  5993  5993 D ThemeInfoUtil: isCurrentFestival = false
,08-09 07:50:50.551  6025  6025 E Zygote  : MountEmulatedStorage()
08-09 07:50:50.551  6025  6025 E Zygote  : v2
,08-09 07:50:50.551  6025  6025 I libpersona: KNOX_SDCARD checking this for 1000
08-09 07:50:50.551  6025  6025 I libpersona: KNOX_SDCARD not a persona
,08-09 07:50:50.551  6025  6025 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-09 07:50:50.561  6025  6025 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-09 07:50:50.561  6025  6025 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-09 07:50:50.561  5975  5975 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-09 07:50:50.561  1017  1017 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6025 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-09 07:50:50.561  5975  5975 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-09 07:50:50.561  5975  5975 D UserAnalysis: Create SecureDbHelper
,08-09 07:50:50.571  5975  5975 D IntelligenceServiceApplication: onCreate()
,08-09 07:50:50.571  1017  1503 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-09 07:50:50.571  5975  5975 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-09 07:50:50.571  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.571  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.571  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.571  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.581  5975  5975 D IntelligenceServiceApplication: no applications having user consent for prediction,
,08-09 07:50:50.591  6040  6040 E Zygote  : MountEmulatedStorage()
08-09 07:50:50.591  6040  6040 I libpersona: KNOX_SDCARD checking this for 10148
08-09 07:50:50.591  6040  6040 E Zygote  : v2
08-09 07:50:50.591  6040  6040 I libpersona: KNOX_SDCARD not a persona
,08-09 07:50:50.591  6040  6040 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-09 07:50:50.591  6025  6025 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-09 07:50:50.591  6040  6040 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:50.591  6025  6025 D ActivityThread: Added TimaKeyStore provider
,08-09 07:50:50.601  6040  6040 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-09 07:50:50.601  1017  1503 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6040 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-09 07:50:50.601  1017  1503 I ActivityManager: Killing 5520:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-09 07:50:50.601  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-09 07:50:50.611  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-09 07:50:50.611  5693  5693 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
08-09 07:50:50.611  5693  5693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-09 07:50:50.611  5911  5911 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-09 07:50:50.611  1017  1528 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-09 07:50:50.611  1017  1528 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-09 07:50:50.621  1017  1528 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:50.621  1017  1528 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:50.621  1017  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,08-09 07:50:50.621  1017  1503 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,08-09 07:50:50.621  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.621  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.621  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.621  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.631  5693  5693 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
,08-09 07:50:50.631  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-09 07:50:50.631  6040  6040 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-09 07:50:50.631  5693  6053 I FilterInstaller: FilterPackageService : ACTION_REMOVED
,08-09 07:50:50.631  5693  6053 D FilterUnInstaller: before removeFromFS
,08-09 07:50:50.641  6040  6040 D ActivityThread: Added TimaKeyStore provider
,08-09 07:50:50.641  6025  6025 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-09 07:50:50.641  6025  6025 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-09 07:50:50.641  6025  6025 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-09 07:50:50.641  6057  6057 E Zygote  : MountEmulatedStorage(),
08-09 07:50:50.641  6057  6057 E Zygote  : v2
08-09 07:50:50.641  6057  6057 I libpersona: KNOX_SDCARD checking this for 1000
08-09 07:50:50.641  6057  6057 I libpersona: KNOX_SDCARD not a persona
,08-09 07:50:50.641  6057  6057 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-09 07:50:50.651  1017  1503 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6057 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-09 07:50:50.651  6057  6057 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-09 07:50:50.651  1017  1503 I ActivityManager: Killing 5567:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-09 07:50:50.651  6057  6057 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-09 07:50:50.651  1017  1492 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.provider.filterprovider
08-09 07:50:50.651  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.651  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.651  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.651  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.,
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.,
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-09 07:50:50.671  6071  6071 I libpersona: KNOX_SDCARD checking this for 10095
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
08-09 07:50:50.671  6071  6071 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:50.671  6071  6071 E Zygote  : MountEmulatedStorage()
,08-09 07:50:50.671  6071  6071 E Zygote  : v2
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-09 07:50:50.671  6071  6071 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-09 07:50:50.671  1017  1492 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6071 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
08-09 07:50:50.671  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,08-09 07:50:50.681  6071  6071 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-09 07:50:50.681  6071  6071 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-09 07:50:50.691  6057  6057 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-09 07:50:50.691  6057  6057 D ActivityThread: Added TimaKeyStore provider
,08-09 07:50:50.691  5975  5975 D BluetoothAdapter: 420566756: getState() :  mService = null. Returning STATE_OFF
,08-09 07:50:50.691  5975  5975 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
08-09 07:50:50.691  6025  6025 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-09 07:50:50.691  6025  6025 I PCWCLIENTTRACE_PushUtil: sales region : global
08-09 07:50:50.691  6025  6025 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-09 07:50:50.691  6025  6025 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-09 07:50:50.701  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-09 07:50:50.701  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-09 07:50:50.701  5975  5975 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-09 07:50:50.701  1017  1476 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
08-09 07:50:50.701  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.701  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.701  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.701  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.711  6071  6071 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-09 07:50:50.711  6071  6071 D ActivityThread: Added TimaKeyStore provider
,08-09 07:50:50.721  6057  6057 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-09 07:50:50.721  6040  6040 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-09 07:50:50.731  6089  6089 E Zygote  : MountEmulatedStorage(),
08-09 07:50:50.731  6089  6089 I libpersona: KNOX_SDCARD checking this for 10029
,08-09 07:50:50.731  6089  6089 E Zygote  : v2
08-09 07:50:50.731  6089  6089 I libpersona: KNOX_SDCARD not a persona,
08-09 07:50:50.731  6089  6089 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-09 07:50:50.741  6089  6089 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:50.741  1017  1476 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6089 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,08-09 07:50:50.741  6089  6089 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-09 07:50:50.751  1017  1476 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-09 07:50:50.761  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.761  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.761  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.761  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.771  6103  6103 E Zygote  : MountEmulatedStorage(),
08-09 07:50:50.771  6103  6103 I libpersona: KNOX_SDCARD checking this for 1000
08-09 07:50:50.771  6103  6103 E Zygote  : v2
08-09 07:50:50.771  6103  6103 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:50.771  6103  6103 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-09 07:50:50.771  6103  6103 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-09 07:50:50.771  6103  6103 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-09 07:50:50.781  6089  6089 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-09 07:50:50.781  6089  6089 D ActivityThread: Added TimaKeyStore provider
,08-09 07:50:50.781  1017  1476 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6103 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-09 07:50:50.781  1017  1476 I ActivityManager: Killing 5589:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-09 07:50:50.781  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider,
08-09 07:50:50.781  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
08-09 07:50:50.781  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:50.781  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-09 07:50:50.781  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-09 07:50:50.791  6071  6071 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,08-09 07:50:50.791  1017  1503 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-09 07:50:50.801  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.801  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.801  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.801  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.811  6071  6071 W FileUtils: Failed to chmod(/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-09 07:50:50.811  6071  6071 E SQLiteLog: (284) automatic index on titles(filter_id)
,08-09 07:50:50.811  6103  6103 D TimaKeyStoreProvider: TimaSignature is unavailable
08-09 07:50:50.811  6103  6103 D ActivityThread: Added TimaKeyStore provider
,08-09 07:50:50.821  6121  6121 E Zygote  : MountEmulatedStorage()
08-09 07:50:50.821  6121  6121 E Zygote  : v2
08-09 07:50:50.821  6121  6121 I libpersona: KNOX_SDCARD checking this for 10152
08-09 07:50:50.821  6121  6121 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:50.821  6121  6121 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-09 07:50:50.821  1017  1503 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6121 uid=10152 gids={50152, 9997} abi=armeabi-v7a,
08-09 07:50:50.821  6121  6121 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-09 07:50:50.821  6121  6121 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-09 07:50:50.841  6057  6057 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
,08-09 07:50:50.841  1017  1503 I ActivityManager: Killing 5613:com.wsomacp/u0a23 (adj 15): empty #21,
,08-09 07:50:50.851  6121  6121 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-09 07:50:50.851  6121  6121 D ActivityThread: Added TimaKeyStore provider
,08-09 07:50:50.851  6071  6081 E SQLiteLog: (284) automatic index on titles(filter_id)
,08-09 07:50:50.861  6089  6136 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-09 07:50:50.861  1017  1503 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-09 07:50:50.861  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.861  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.861  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-09 07:50:50.861  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-09 07:50:50.871  6057  6057 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-09 07:50:50.871  6057  6057 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-09 07:50:50.871  6057  6057 D AndroidRuntime: Shutting down VM
,08-09 07:50:50.871  6103  6103 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
08-09 07:50:50.871  6057  6057 E AndroidRuntime: FATAL EXCEPTION: main
08-09 07:50:50.871  6057  6057 E AndroidRuntime: Process: com.samsung.android.sm, PID: 6057
08-09 07:50:50.871  6057  6057 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-09 07:50:50.871  6057  6057 E AndroidRuntime: 	... 9 more
08-09 07:50:50.881  6057  6115 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
08-09 07:50:50.881  6138  6138 E Zygote  : MountEmulatedStorage()
08-09 07:50:50.881  6138  6138 E Zygote  : v2
08-09 07:50:50.881  6138  6138 I libpersona: KNOX_SDCARD checking this for 10032
08-09 07:50:50.881  6138  6138 I libpersona: KNOX_SDCARD not a persona
08-09 07:50:50.881  6138  6138 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-09 07:50:50.881  1017  1503 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=6138 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-09 07:50:50.881  1017  1503 I ActivityManager: Killing 3540:com.google.process.gapps/u0a11 (adj 15): empty #21
08-09 07:50:50.881  6138  6138 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-09 07:50:50.881  1017  1030 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
08-09 07:50:50.881  6138  6138 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-09 07:50:50.881  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
08-09 07:50:50.891  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-09 07:50:50.891  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-09 07:50:50.891  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
08-09 07:50:50.891  6121  6121 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-09 07:50:50.891  6121  6121 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10

```
